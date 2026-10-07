---
section_id: null
source_type: "openapi"
group: "Conformidade Instrumento convocatório e Modo de disputa"
title: "Inserir conformidade entre instrumentos convocatórios e modos de disputa"
method: "POST"
endpoint: "/v1/tipo-instrumento-convocatorio-modo-disputa"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir conformidade entre instrumentos convocatórios e modos de disputa

## Resumo
Operação `POST /v1/tipo-instrumento-convocatorio-modo-disputa`.

## Endpoint
`POST /v1/tipo-instrumento-convocatorio-modo-disputa`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Schema OpenAPI: [`IncluirTipoInstrumentoConvocatorioModoDisputaDTO`](../../schemas/incluir-tipo-instrumento-convocatorio-modo-disputa-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `tipoInstrumentoConvocatorioId` | integer (int64) | não |
| `modoDisputaId` | integer (int64) | não |

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
