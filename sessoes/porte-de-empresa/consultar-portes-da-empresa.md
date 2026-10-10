---
section_id: null
source_type: "openapi"
group: "Porte de Empresa"
title: "Consultar Portes da Empresa"
method: "GET"
endpoint: "/v1/portes-empresa"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Portes da Empresa

## Resumo
Operação `GET /v1/portes-empresa`.

## Endpoint
`GET /v1/portes-empresa`

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
