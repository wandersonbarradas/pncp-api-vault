---
section_id: null
source_type: "openapi"
group: "Plano de Contratação"
title: "GET /v1/orgaos/{cnpj}/pca/{uasg}/{ano}/sequenciaisplano"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{uasg}/{ano}/sequenciaisplano"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# GET /v1/orgaos/{cnpj}/pca/{uasg}/{ano}/sequenciaisplano

## Resumo
Operação `GET /v1/orgaos/{cnpj}/pca/{uasg}/{ano}/sequenciaisplano`.

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{uasg}/{ano}/sequenciaisplano`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `uasg` | path | string | sim |
| `ano` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`SequenciaisDTO`](../../schemas/sequenciais-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `sequencialPlano` | integer (int32) | não |
| `sequencialUltimoItemInserido` | integer (int32) | não |

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
- Endpoint presente na OpenAPI atual, sem seção correspondente no manual segmentado local.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
