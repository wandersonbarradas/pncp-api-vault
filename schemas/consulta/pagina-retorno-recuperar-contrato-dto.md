---
title: "PaginaRetornoRecuperarContratoDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# PaginaRetornoRecuperarContratoDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| data | array[[RecuperarContratoDTO](./recuperar-contrato-dto.md)] | não |  |  |
| empty | boolean | não |  |  |
| numeroPagina | integer (int64) | não |  |  |
| paginasRestantes | integer (int64) | não |  |  |
| totalPaginas | integer (int64) | não |  |  |
| totalRegistros | integer (int64) | não |  |  |

## Schemas Relacionados

- [RecuperarContratoDTO](./recuperar-contrato-dto.md)

## Usado em Respostas

- `200`: [GET /v1/contratos](../../consulta/contrato-empenho/consultar-contratos-por-data-de-publica-o.md) - Consultar Contratos por Data de Publicação
- `200`: [GET /v1/contratos/atualizacao](../../consulta/contrato-empenho/consultar-contratos-empenhos-por-data-de-atualiza-o-global.md) - Consultar Contratos/Empenhos por Data de Atualização Global

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
