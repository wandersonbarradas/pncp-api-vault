---
section_id: "6.7.7"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Consultar Valores de um Plano de Contratação por Categoria"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/valorescategoriaitem"
page_start: 373
page_end: 374
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Valores de um Plano de Contratação por Categoria

## Resumo
Serviço que permite consultar a quantidade de itens e o valor total dos itens por.

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/valorescategoriaitem`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `categoriaItem` | query | integer | não |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: `array`

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
- `sections/6-7-7-consultar-valores-de-um-plano-de-contratacao-por-categoria.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
