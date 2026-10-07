---
title: "AmparoLegal"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AmparoLegal

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataAtualizacao | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| descricao | string | não |  |  |
| id | integer (int64) | não |  |  |
| justificativaAtualizacao | string | não |  |  |
| nome | string | não |  |  |
| statusAtivo | boolean | não |  |  |
| tipoAmparoLegal | [TipoAmparoLegal](./tipo-amparo-legal.md) | não |  |  |

## Schemas Relacionados

- [TipoAmparoLegal](./tipo-amparo-legal.md)

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
