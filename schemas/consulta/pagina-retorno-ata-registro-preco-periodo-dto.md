---
title: "PaginaRetornoAtaRegistroPrecoPeriodoDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# PaginaRetornoAtaRegistroPrecoPeriodoDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| data | array[[AtaRegistroPrecoPeriodoDTO](./ata-registro-preco-periodo-dto.md)] | não |  |  |
| empty | boolean | não |  |  |
| numeroPagina | integer (int64) | não |  |  |
| paginasRestantes | integer (int64) | não |  |  |
| totalPaginas | integer (int64) | não |  |  |
| totalRegistros | integer (int64) | não |  |  |

## Schemas Relacionados

- [AtaRegistroPrecoPeriodoDTO](./ata-registro-preco-periodo-dto.md)

## Usado em Respostas

- `200`: [GET /v1/atas](../../consulta/ata/consultar-ata-de-registro-de-pre-o-por-per-odo-de-vig-ncia.md) - Consultar Ata de Registro de Preço por Período de Vigência
- `200`: [GET /v1/atas/atualizacao](../../consulta/ata/consultar-atas-de-registro-de-pre-o-por-data-de-atualiza-o-global.md) - Consultar Atas de Registro de Preço por Data de Atualização Global

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
