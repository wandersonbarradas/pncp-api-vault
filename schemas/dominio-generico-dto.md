---
title: "DominioGenericoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# DominioGenericoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 4 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataAtualizacao | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| descricao | string | não |  |  |
| id | integer (int64) | não |  |  |
| nome | string | não |  |  |
| statusAtivo | boolean | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/categoriaItemPcas/{id}](../sessoes/categoria-de-item/consultar-categoria-de-item-por-codigo.md) - Consultar categoria de item por código
- `200`: [GET /v1/criterios-julgamentos/{id}](../sessoes/criterio-de-julgamento/consultar-criterio-de-julgamento-por-codigo.md) - Consultar critério de julgamento por código
- `200`: [GET /v1/modalidades/{id}](../sessoes/modalidade-de-contratacao/consultar-modalidade-de-contratacao-por-codigo.md) - Consultar modalidade de contratação por código
- `200`: [GET /v1/modos-disputas/{id}](../sessoes/modo-de-disputa/consultar-modo-de-disputa-por-codigo.md) - Consultar modo de disputa por código

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
