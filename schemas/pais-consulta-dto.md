---
title: "PaisConsultaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# PaisConsultaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| id | string | não |  |  |
| nome | string | não |  |  |
| codigoPaisBcb | integer (int64) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| statusAtivo | boolean | não |  |  |

## Usado em Respostas

- `GET /v1/paises` em [consultar-paises.md](../sessoes/pais/consultar-paises.md) - Consultar países

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
