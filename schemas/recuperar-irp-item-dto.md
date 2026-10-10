---
title: "RecuperarIrpItemDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# RecuperarIrpItemDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| numeroItem | integer (int32) | não |  |  |
| materialOuServico | string | não |  | M, S |
| categoriaItemId | integer (int64) | não |  |  |
| categoriaItemNome | string | não |  |  |
| criterioJulgamentoId | integer (int64) | não |  |  |
| criterioJulgamentoNome | string | não |  |  |
| aplicabilidadeMargemPreferencia | boolean | não |  |  |
| exigenciaConteudoNacional | boolean | não |  |  |
| descricao | string | não |  |  |
| informacaoComplementar | string | não |  |  |
| unidadeFornecimento | string | não |  |  |
| valorUnitarioEstimado | number | não |  |  |
| indicadorValorSigiloso | boolean | não |  |  |
| codigoGtin | string | não |  |  |
| codigoNcmNbs | string | não |  |  |
| descricaoNcmNbs | string | não |  |  |
| catalogoId | integer (int64) | não |  |  |
| catalogoNome | string | não |  |  |
| catalogoUrl | string | não |  |  |
| codigoItemCatalogo | string | não |  |  |
| dataInclusao | string (date-time) | não |  |  |

## Usado em Respostas

- `GET /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens` em [consultar-todos-os-itens-da-intencao-de-registro-de-preco.md](../sessoes/irp/consultar-todos-os-itens-da-intencao-de-registro-de-preco.md) - Consultar Todos os Itens da Intenção de Registro de Preço
- `GET /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens/{numeroItem}` em [consultar-item-da-intencao-de-registro-de-preco.md](../sessoes/irp/consultar-item-da-intencao-de-registro-de-preco.md) - Consultar Item da Intenção de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
