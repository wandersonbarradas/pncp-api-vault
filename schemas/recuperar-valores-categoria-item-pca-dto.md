---
title: "RecuperarValoresCategoriaItemPcaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarValoresCategoriaItemPcaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| categoriaItemId | integer (int64) | não |  |  |
| categoriaItemNome | string | não |  |  |
| quantidadeItens | integer (int64) | não |  |  |
| valorTotal | number | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/pca/{ano}/valorescategoriaitem](../sessoes/plano-de-contratacao/consultar-valores-de-planos-de-contratacao-de-um-orgao-por-categoria.md) - Consultar Valores de Planos de Contratação de um Órgão por Categoria
- `200`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/valorescategoriaitem](../sessoes/plano-de-contratacao/consultar-valores-de-um-plano-de-contratacao-por-categoria.md) - Consultar Valores de um Plano de Contratação por Categoria

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
