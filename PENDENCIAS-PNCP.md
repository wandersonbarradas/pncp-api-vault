# Pendências do vault PNCP vs. Manual v2.6

Relatório de manutenção para reprocessar a ingestão normalizada.
Não faz parte do conjunto de referência do vault (`mapas/`, `sessoes/`, `referencias/`).

> **Status: aplicado em 2026-10-07.** Empenho corrigido, seção IRP criada, domínios faltantes e métodos ausentes adicionados, mapas e schemas regenerados. Resta apenas a revisão editorial do `consultar-uma-contratacao.md` (endpoint da superfície de consulta).

## Baseline

- **Vault atual**: construído em ~2026-05-02/03, numeração antiga (`section_id` 6.x), reconciliado contra o Swagger antigo em `2026-05-02`.
- **Manual oficial agora**: **v2.6**, data **31/08/2026**, capítulos renumerados de **1 a 16**.
- **Swagger `api/pncp`** (`https://pncp.gov.br/pncp-api/v3/api-docs`): **124 paths / 214 operações** (capturado em 2026-10-07).
- **Swagger `api/consulta`** (`https://pncp.gov.br/api/consulta/v3/api-docs`): **12 endpoints**, iguais aos do vault. Superfície pública **estável**.

Arquivos do vault com endpoint declarado: **195** (excluindo `index.md`).

---

## 1. Seção inteira ausente: IRP (Intenção de Registro de Preços)

Novo capítulo **10** do manual. **17 endpoints** ausentes no vault (não existe `sessoes/irp`).

| Método | Path | Descrição |
| --- | --- | --- |
| POST | `/v1/orgaos/{cnpj}/irp` | Inserir Intenção de Registro de Preço |
| PATCH | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}` | Retificar parcialmente uma Intenção de Registro de Preço |
| DELETE | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}` | Excluir Intenção de Registro de Preço |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}` | Consultar Intenção de Registro de Preço |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/historico` | Consultar Histórico de Intenção de Registro de Preço |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/historico/quantidade` | Consultar Quantidade Histórico de IRP |
| POST | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos` | Inserir Documento em Intenção de Registro de Preço |
| DELETE | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos/{sequencialDocumento}` | Excluir Arquivo/Documento de IRP |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos` | Consultar Dados de Todos os Documentos de uma IRP |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos/quantidade` | Consultar Quantidade de Documentos de IRP |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos/{sequencialDocumento}` | Baixar Arquivo/Documento de IRP |
| POST | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens` | Inserir Itens da Intenção de Registro de Preço |
| PATCH | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens` | Retificar Parcialmente Itens da IRP |
| DELETE | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens` | Excluir Itens da Intenção de Registro de Preço |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens` | Consultar Todos os Itens da IRP |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens/quantidade` | Consultar Quantidade de Itens da IRP |
| GET | `/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens/{numeroItem}` | Consultar Item da IRP |

Observação: IRP **não** aparece na API de Consulta pública (`api/consulta`); é apenas `api/pncp`.

---

## 2. Empenho — paths/métodos errados no vault

O manual promoveu Empenho ao **capítulo 14** (5 endpoints). O vault tem 3 arquivos com **path truncado** e `quality_status: needs-review`.

| Operação | Vault (incorreto) | Manual v2.6 / Swagger (correto) |
| --- | --- | --- |
| Inserir Empenho | `POST /v1/orgaos/{cnpj}/contrat` | `POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos` |
| Retificar Parcialmente Empenho | `PUT /v1/orgaos/{cnpj}/contr` | `PATCH /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos/{sequencialEmpenho}` |
| Excluir Empenho | `DELETE /v1/orgaos/{cnpj}/contratos` | `DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/empenhos/{sequencialEmpenho}` |
| Consultar Empenhos | (já correto) | `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/empenhos` |
| Consultar Empenho pelo Sequencial | (já correto) | `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/empenhos/{sequencialEmpenho}` |

Arquivos a corrigir:
- `sessoes/contrato-empenho/inserir-empenho.md`
- `sessoes/contrato-empenho/retificar-parcialmente-empenho.md`
- `sessoes/contrato-empenho/excluir-empenho.md`

### Payload de Inserir Empenho (cap. 14.1)
```json
{
  "empenhos": [
    {
      "numeroEmpenho": "string",
      "tipoPessoa": "PJ",
      "niCredorFornecedor": "string",
      "nomeCredorFornecedor": "string",
      "numeroPlanoInterno": "string",
      "codigoNaturezaDespesa": "string",
      "dataEmissaoEmpenho": "2026-01-01T12:00:00",
      "valorTotal": 1000.0,
      "valorSubItem": 1000.0,
      "codigoEmenda": "string"
    }
  ]
}
```

### Retificar Parcialmente Empenho (cap. 14.2)
Campos adicionais: `situacaoEmpenhoId` (1 = Empenhado, 2 = Cancelado), `dataSituacaoEmpenho`, `justificativa` (obrigatório).

### Retorno de consulta (14.4 / 14.5)
Inclui `situacaoEmpenhoId`, `situacaoEmpenhoNome`, `fonteEmenda`, `statusResponseEmenda`, `jsonResponseEmenda`, `dataConsultaEmenda` e o objeto `emendaParlamentar` com 17 subcampos (`codigoEmenda`, `ano`, `tipoEmenda`, `autor`, `nomeAutor`, `numeroEmenda`, `localidadeDoGasto`, `funcao`, `subFuncao`, `valorEmpenhado`, `valorLiquidado`, `valorPago`, `valorRestoInscrito`, `valorRestoCancelado`, `valorRestoPago`, `dataInclusao`, `dataAtualizacao`).

---

## 3. Endpoints de domínio ausentes no vault (presentes no Swagger)

| Método | Path | Descrição |
| --- | --- | --- |
| GET | `/v1/portes-empresa` | Consultar Portes da Empresa |
| GET | `/v1/portes-empresa/{id}` | Consultar Porte da Empresa por Código |
| POST | `/v1/portes-empresa` | Inserir Porte da Empresa |
| PATCH | `/v1/portes-empresa/{id}` | Alterar Porte da Empresa |
| GET | `/v1/naturezas-juridicas` | Consultar naturezas jurídicas |
| GET | `/v1/normativo-base` | Consultar normativos base |
| GET | `/v1/normativo-base/{id}` | Consultar normativo base por código |
| POST | `/v1/normativo-base` | Inserir normativo base |
| PATCH | `/v1/normativo-base/{id}` | Alterar normativo base |
| GET | `/v1/paises` | Consultar países |
| GET | `/v1/situacoes-compra-item-resultado` | Consultar situações do resultado do item |
| GET | `/v1/tipos-parte-envolvida` | Consultar Tipo de Parte Envolvida |
| GET | `/v1/tipos-parte-envolvida/{id}` | Consultar id de Tipo de Parte Envolvida |

`portes-empresa` e `situacoes-compra-item-resultado` são novos (v2.5). `tipos-parte-envolvida` acompanha o recurso de Partes Envolvidas em Ata (v2.3.10).

---

## 4. Métodos ausentes em recursos que já existem no vault

| Método | Path | Descrição | Situação no vault |
| --- | --- | --- | --- |
| PATCH | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}` | Retificar Parcialmente Contrato | só há `GET`/`PUT`/`DELETE`; falta o PATCH |
| POST | `/v1/tipos-contratos` | Inserir Tipo de Contrato | só há `GET` |
| PATCH | `/v1/tipos-contratos/{id}` | Alterar Tipo de Contrato | só há `GET` |
| POST | `/v1/tipos-documentos` | Inserir Tipo de Documento | só há `GET` |
| PATCH | `/v1/tipos-documentos/{id}` | Alterar Tipo de Documento | só há `GET` |

---

## 5. Arquivos obsoletos/truncados no vault (endpoint não existe no Swagger)

| Método | Endpoint no vault | Arquivo | Correto |
| --- | --- | --- | --- |
| POST | `/v1/orgaos/{cnpj}/contrat` | `sessoes/contrato-empenho/inserir-empenho.md` | ver seção 2 |
| PUT | `/v1/orgaos/{cnpj}/contr` | `sessoes/contrato-empenho/retificar-parcialmente-empenho.md` | ver seção 2 |
| DELETE | `/v1/orgaos/{cnpj}/contratos` | `sessoes/contrato-empenho/excluir-empenho.md` | ver seção 2 |
| PUT | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}` | `sessoes/contrato-empenho/retificar-parcialmente-instrumento-de-cobranca-de-contra.md` | duplicado/truncado; o correto é o `PATCH ...` em `retificar-parcialmente-instrumento-de-cobranca-de-contrato-empenho.md` |

Caso especial (não é erro): `sessoes/contratacao/consultar-uma-contratacao.md` usa `GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`, que **não** existe no Swagger `api/pncp`. Esse GET é da **API de Consulta** (`consulta/contratacao/consultar-contrata-o.md`). Confirmar se o arquivo deve apontar para a superfície de consulta.

---

## 6. Mudanças de campos/regras (v2.4 → v2.6)

### v2.5 — CNPJ Alfanumérico
- A partir de jul/2026 o CNPJ passa a ser **alfanumérico** para novas inscrições. O tipo do campo `cnpj` deixa de ser estritamente numérico.
- Novas informações de fornecedor: **localidade** e **Cadastro de Reserva/Remanescente**.
- Referência: https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/acoes-e-programas/programas-e-atividades/cnpj-alfanumerico

### v2.6 — Obrigatoriedade
- `sequencialAta`: de **"Não"** para **"Condicional"** — informar apenas quando o contrato estiver vinculado a uma contratação do tipo **SRP**; nos demais casos, suprimir. Afeta:
  - Inserir Contratos/Empenhos
  - Retificar Contrato/Empenho
  - Retificar Parcialmente um Contrato/Empenho
- `percentualDesconto`: de **"Não"** para **"Sim"** em **Inserir Resultado do Item de uma Contratação**.

### v2.4 — Emendas e tabelas
- Empenhos com **Emenda Parlamentar** (campo `emendaParlamentar`).
- Novas tabelas: **Tipo de Contrato** e **Tipo de Documento** (o vault já cobre a leitura; faltam POST/PATCH).
- Fluxos de contratos fruto de **Ata de Registro de Preços (ARP)**.

---

## 7. Numeração de seções

O vault usa `section_id` no formato **6.x**. O manual v2.6 reorganizou o conteúdo em **capítulos 1–16** (ex.: Contratação = cap. 11, Contratos/Empenhos = cap. 13, Empenho = cap. 14, IRP = cap. 10). Ao regenerar, os `section_id` precisam ser remapeados.

---

## 8. API de Consulta (`api/consulta`) — sem alterações relevantes

O Swagger `api/consulta/v3/api-docs` mantém os **12 endpoints** já presentes em `consulta/`:
`/v1/pca/usuario`, `/v1/pca/atualizacao`, `/v1/pca/`, `/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`, `/v1/instrumentoscobranca/inclusao`, `/v1/contratos`, `/v1/contratos/atualizacao`, `/v1/contratacoes/publicacao`, `/v1/contratacoes/proposta`, `/v1/contratacoes/atualizacao`, `/v1/atas`, `/v1/atas/atualizacao`.

---

## Prioridade sugerida de correção

1. **Alta**: Empenho (paths/métodos errados bloqueiam escrita) e criação da seção **IRP**.
2. **Alta**: campos v2.6 (`sequencialAta`, `percentualDesconto`).
3. **Média**: `portes-empresa`, `situacoes-compra-item-resultado`, CNPJ alfanumérico.
4. **Média**: `PATCH` Retificar Parcialmente Contrato; POST/PATCH de Tipo de Contrato/Documento.
5. **Baixa**: `normativo-base`, `naturezas-juridicas`, `paises`, `tipos-parte-envolvida`; remapeamento de `section_id`.
