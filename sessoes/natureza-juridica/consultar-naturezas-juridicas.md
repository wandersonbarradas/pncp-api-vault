---
section_id: null
source_type: "openapi"
group: "Natureza Jurídica"
title: "Consultar naturezas jurídicas"
method: "GET"
endpoint: "/v1/naturezas-juridicas"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar naturezas jurídicas

## Resumo
Operação `GET /v1/naturezas-juridicas`.

## Endpoint
`GET /v1/naturezas-juridicas`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `identificadores` | query | array | não |

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
- Endpoint presente na OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
