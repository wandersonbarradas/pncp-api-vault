---
title: "RecuperarIrpDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# RecuperarIrpDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| numeroControlePNCP | string | não |  |  |
| sequencialIrp | integer (int32) | não |  |  |
| numeroIrp | string | não |  |  |
| anoIrp | integer (int32) | não |  |  |
| processo | string | não |  |  |
| situacaoIrpId | integer (int64) | não |  |  |
| situacaoIrpNome | string | não |  |  |
| orgaoEntidade | [`RecuperarOrgaoEntidadeDTO`](./recuperar-orgao-entidade-dto.md) | não |  |  |
| unidadeOrgao | [`RecuperarUnidadeOrgaoDTO`](./recuperar-unidade-orgao-dto.md) | não |  |  |
| orgaoSubRogado | [`RecuperarOrgaoEntidadeDTO`](./recuperar-orgao-entidade-dto.md) | não |  |  |
| unidadeSubRogada | [`RecuperarUnidadeOrgaoDTO`](./recuperar-unidade-orgao-dto.md) | não |  |  |
| tipoInstrumentoConvocatorioCodigo | integer (int64) | não |  |  |
| tipoInstrumentoConvocatorioNome | string | não |  |  |
| amparoLegalId | integer (int64) | não |  |  |
| amparoLegalNome | string | não |  |  |
| modalidadeId | integer (int64) | não |  |  |
| modalidadeNome | string | não |  |  |
| modoDisputaId | integer (int64) | não |  |  |
| modoDisputaNome | string | não |  |  |
| objetoIrp | string | não |  |  |
| informacaoComplementar | string | não |  |  |
| indicadorPossibilidadeAdesao | boolean | não |  |  |
| dataHoraFinalManifestacaoInteresse | string (date-time) | não |  |  |
| urlPlataformaOrigem | string | não |  |  |
| urlProcessoEletronico | string | não |  |  |
| usuarioNome | string | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| dataCancelamento | string (date-time) | não |  |  |
| motivoCancelamento | string | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataAtualizacaoGlobal | string (date-time) | não |  |  |
| quantidadeItens | integer (int64) | não |  |  |

## Usado em Respostas

- `GET /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}` em [consultar-intencao-de-registro-de-preco.md](../sessoes/irp/consultar-intencao-de-registro-de-preco.md) - Consultar Intenção de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
