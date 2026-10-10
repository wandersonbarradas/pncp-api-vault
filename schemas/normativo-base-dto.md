---
title: "NormativoBaseDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# NormativoBaseDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| id | integer (int64) | não |  |  |
| nome | string | não |  |  |
| descricao | string | não |  |  |
| statusAtivo | boolean | não |  |  |

## Usado em Respostas

- `GET /v1/normativo-base/{id}` em [consultar-normativo-base-por-codigo.md](../sessoes/normativo-base/consultar-normativo-base-por-codigo.md) - Consultar normativo base por código

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
