---
section_id: null
source_type: "openapi"
group: "Intenção de Registro de Preços"
title: "Consultar Item da Intenção de Registro de Preço"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens/{numeroItem}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Item da Intenção de Registro de Preço

## Resumo
Operação `GET /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens/{numeroItem}`.

## Endpoint
`GET /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens/{numeroItem}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer (int32) | sim |
| `sequencial` | path | integer (int32) | sim |
| `numeroItem` | path | integer (int32) | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`RecuperarIrpItemDTO`](../../schemas/recuperar-irp-item-dto.md)

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
