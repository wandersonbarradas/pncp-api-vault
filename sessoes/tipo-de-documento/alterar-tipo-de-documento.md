---
section_id: null
source_type: "openapi"
group: "Tipo de Documento"
title: "Alterar Tipo de Documento"
method: "PATCH"
endpoint: "/v1/tipos-documentos/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Alterar Tipo de Documento

## Resumo
Operação `PATCH /v1/tipos-documentos/{id}`.

## Endpoint
`PATCH /v1/tipos-documentos/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer (int64) | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarParcialTipoDocumentoDTO`](../../schemas/alterar-parcial-tipo-documento-dto.md)

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
- Endpoint presente na OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
