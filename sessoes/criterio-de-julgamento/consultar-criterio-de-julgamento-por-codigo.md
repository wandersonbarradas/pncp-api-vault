---
section_id: "5.4.1"
source_type: "manual+openapi"
group: "Critério de Julgamento"
title: "Consultar critério de julgamento por código"
method: "GET"
endpoint: "/v1/criterios-julgamentos/{id}"
page_start: 53
page_end: 54
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar critério de julgamento por código

## Resumo
Serviço que permite consultar um critério de julgamento pelo seu código.

## Endpoint
`GET /v1/criterios-julgamentos/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`DominioGenericoDTO`](../../schemas/dominio-generico-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `nome` | string | não |
| `descricao` | string | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `statusAtivo` | boolean | não |

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
- `sections/5-4-1-consultar-criterio-de-julgamento-por-codigo.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
