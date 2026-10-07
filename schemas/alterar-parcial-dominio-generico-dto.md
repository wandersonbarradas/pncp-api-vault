---
title: "AlterarParcialDominioGenericoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarParcialDominioGenericoDTO

- Tipo: `object`
- Usado em requisições: 5 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| descricao | string | não |  |  |
| justificativaAtualizacao | string | não |  |  |
| nome | string | não |  |  |
| statusAtivo | boolean | não |  |  |

## Usado como Corpo de Requisição

- [PATCH /v1/categoriaItemPcas/{id}](../sessoes/categoria-de-item/alterar-categoria-de-item.md) - Alterar categoria de item
- [PATCH /v1/criterios-julgamentos/{id}](../sessoes/criterio-de-julgamento/alterar-criterio-de-julgamento.md) - Alterar critério de julgamento
- [PATCH /v1/fontes-orcamentarias/{id}](../sessoes/fonte-orcamentaria/alterar-fonte-orcamentaria.md) - Alterar fonte orçamentária
- [PATCH /v1/modalidades/{id}](../sessoes/modalidade-de-contratacao/alterar-modalidade-de-contratacao.md) - Alterar modalidade de contratação
- [PATCH /v1/modos-disputas/{id}](../sessoes/modo-de-disputa/alterar-modo-de-disputa.md) - Alterar modo de disputa

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
