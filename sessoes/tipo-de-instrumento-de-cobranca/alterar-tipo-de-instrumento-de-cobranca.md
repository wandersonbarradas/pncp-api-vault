---
section_id: null
source_type: "openapi"
group: "Tipo de Instrumento de Cobrança"
title: "Alterar Tipo de Instrumento de Cobrança"
method: "PATCH"
endpoint: "/v1/tipos-instrumentos-cobranca/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Alterar Tipo de Instrumento de Cobrança

## Resumo
Operação `PATCH /v1/tipos-instrumentos-cobranca/{id}`.

## Endpoint
`PATCH /v1/tipos-instrumentos-cobranca/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarParcialTipoInstrumentoConbrancaDTO`](../../schemas/alterar-parcial-tipo-instrumento-conbranca-dto.md)

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
