---
section_id: "5.17.2"
source_type: "manual+openapi"
group: "Categoria de Item (Plano de Contratações e Contratações)"
title: "Consultar categorias de item"
method: "GET"
endpoint: "/v1/categoriaItemPcas"
page_start: 73
page_end: 74
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar categorias de item

## Resumo
Serviço que permite consultar as categorias de item cadastradas no PNCP.

## Endpoint
`GET /v1/categoriaItemPcas`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `statusAtivo` | query | boolean | não |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: `object`

## Códigos de retorno

| HTTP |
| --- |
| `400` |
| `422` |
| `204` |
| `500` |
| `401` |
| `200` |

## Exemplo cURL
Exemplo não disponível na fonte consolidada atual.

## Notas de normalização
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/5-17-2-consultar-categorias-de-item.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
