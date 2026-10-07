---
section_id: null
source_type: "openapi"
group: "Tipo de Instrumento de Cobrança"
title: "Consultar Tipo de Instrumento de Cobrança por Código"
method: "GET"
endpoint: "/v1/tipos-instrumentos-cobranca/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Tipo de Instrumento de Cobrança por Código

## Resumo
Operação `GET /v1/tipos-instrumentos-cobranca/{id}`.

## Endpoint
`GET /v1/tipos-instrumentos-cobranca/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`TipoInstrumentoCobrancaDTO`](../../schemas/tipo-instrumento-cobranca-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `nome` | string | não |
| `descricao` | string | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `statusAtivo` | boolean | não |

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
