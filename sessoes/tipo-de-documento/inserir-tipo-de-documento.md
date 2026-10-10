---
section_id: null
source_type: "openapi"
group: "Tipo de Documento"
title: "Inserir Tipo de Documento"
method: "POST"
endpoint: "/v1/tipos-documentos"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Tipo de Documento

## Resumo
Operação `POST /v1/tipos-documentos`.

## Endpoint
`POST /v1/tipos-documentos`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Schema OpenAPI: [`IncluirTipoDocumentoDTO`](../../schemas/incluir-tipo-documento-dto.md)

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
