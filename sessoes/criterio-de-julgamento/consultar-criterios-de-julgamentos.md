---
section_id: "5.4.2"
source_type: "manual+openapi"
group: "Critério de Julgamento"
title: "Consultar critérios de julgamentos"
method: "GET"
endpoint: "/v1/criterios-julgamentos"
page_start: 55
page_end: 57
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar critérios de julgamentos

## Resumo
Serviço que permite consultar os critérios de julgamento cadastrados no PNCP.

## Endpoint
`GET /v1/criterios-julgamentos`

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
- `sections/5-4-2-consultar-criterios-de-julgamento.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
