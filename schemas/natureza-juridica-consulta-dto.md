---
title: "NaturezaJuridicaConsultaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# NaturezaJuridicaConsultaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| id | string | não |  |  |
| nome | string | não |  |  |
| descricao | string | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| statusAtivo | boolean | não |  |  |

## Usado em Respostas

- `GET /v1/naturezas-juridicas` em [consultar-naturezas-juridicas.md](../sessoes/natureza-juridica/consultar-naturezas-juridicas.md) - Consultar naturezas jurídicas

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
