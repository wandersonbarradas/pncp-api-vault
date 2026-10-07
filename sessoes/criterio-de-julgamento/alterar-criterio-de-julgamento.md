---
section_id: null
source_type: "openapi"
group: "Critério de julgamento"
title: "Alterar critério de julgamento"
method: "PATCH"
endpoint: "/v1/criterios-julgamentos/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Alterar critério de julgamento

## Resumo
Operação `PATCH /v1/criterios-julgamentos/{id}`.

## Endpoint
`PATCH /v1/criterios-julgamentos/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarParcialDominioGenericoDTO`](../../schemas/alterar-parcial-dominio-generico-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `nome` | string | não |
| `descricao` | string | não |
| `statusAtivo` | boolean | não |
| `justificativaAtualizacao` | string | não |

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
