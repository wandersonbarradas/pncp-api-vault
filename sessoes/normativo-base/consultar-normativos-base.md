---
section_id: null
source_type: "openapi"
group: "Normativo Base"
title: "Consultar normativos base"
method: "GET"
endpoint: "/v1/normativo-base"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar normativos base

## Resumo
Operação `GET /v1/normativo-base`.

## Endpoint
`GET /v1/normativo-base`

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
- Endpoint presente na OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
