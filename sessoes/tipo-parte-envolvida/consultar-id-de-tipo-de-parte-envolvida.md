---
section_id: null
source_type: "openapi"
group: "Tipo de Parte Envolvida"
title: "Consultar id de Tipo de Parte Envolvida"
method: "GET"
endpoint: "/v1/tipos-parte-envolvida/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar id de Tipo de Parte Envolvida

## Resumo
Operação `GET /v1/tipos-parte-envolvida/{id}`.

## Endpoint
`GET /v1/tipos-parte-envolvida/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer (int64) | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`TipoParteEnvolvidaDTO`](../../schemas/tipo-parte-envolvida-dto.md)

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
