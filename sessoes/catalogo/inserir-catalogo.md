---
section_id: null
source_type: "openapi"
group: "Catálogo"
title: "Inserir catálogo"
method: "POST"
endpoint: "/v1/catalogos"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir catálogo

## Resumo
Operação `POST /v1/catalogos`.

## Endpoint
`POST /v1/catalogos`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Schema OpenAPI: [`IncluirCatalogoDTO`](../../schemas/incluir-catalogo-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `nome` | string | não |
| `descricao` | string | não |
| `url` | string | não |

## Resposta
Schema OpenAPI: `string`

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
