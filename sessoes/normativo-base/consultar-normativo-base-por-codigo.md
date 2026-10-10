---
section_id: null
source_type: "openapi"
group: "Normativo Base"
title: "Consultar normativo base por código"
method: "GET"
endpoint: "/v1/normativo-base/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar normativo base por código

## Resumo
Operação `GET /v1/normativo-base/{id}`.

## Endpoint
`GET /v1/normativo-base/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer (int64) | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`NormativoBaseDTO`](../../schemas/normativo-base-dto.md)

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
