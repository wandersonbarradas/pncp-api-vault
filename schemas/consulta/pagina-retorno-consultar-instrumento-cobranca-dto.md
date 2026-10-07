---
title: "PaginaRetornoConsultarInstrumentoCobrancaDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# PaginaRetornoConsultarInstrumentoCobrancaDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| data | array[[ConsultarInstrumentoCobrancaDTO](./consultar-instrumento-cobranca-dto.md)] | não |  |  |
| empty | boolean | não |  |  |
| numeroPagina | integer (int64) | não |  |  |
| paginasRestantes | integer (int64) | não |  |  |
| totalPaginas | integer (int64) | não |  |  |
| totalRegistros | integer (int64) | não |  |  |

## Schemas Relacionados

- [ConsultarInstrumentoCobrancaDTO](./consultar-instrumento-cobranca-dto.md)

## Usado em Respostas

- `200`: [GET /v1/instrumentoscobranca/inclusao](../../consulta/instrumento-cobranca/consultar-instrumentos-de-cobran-a-por-data-de-inclus-o.md) - Consultar Instrumentos de Cobrança por Data de Inclusão

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
