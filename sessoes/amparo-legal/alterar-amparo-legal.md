---
section_id: null
source_type: "openapi"
group: "Amparo legal"
title: "Alterar amparo legal"
method: "PATCH"
endpoint: "/v1/amparos-legais/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Alterar amparo legal

## Resumo
Operação `PATCH /v1/amparos-legais/{id}`.

## Endpoint
`PATCH /v1/amparos-legais/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarParcialAmparoLegalDTO`](../../schemas/alterar-parcial-amparo-legal-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `nome` | string | não |
| `descricao` | string | não |
| `tipoAmparoLegalId` | integer (int64) | não |
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
