---
section_id: null
source_type: "openapi"
group: "Conformidade Instrumento convocatório e Modo de disputa"
title: "Excluir conformidade entre instrumento convocatório e modo de disputa"
method: "DELETE"
endpoint: "/v1/tipo-instrumento-convocatorio-modo-disputa/{tipoInstrumentoConvocatorioId}/{modoDisputaId}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir conformidade entre instrumento convocatório e modo de disputa

## Resumo
Operação `DELETE /v1/tipo-instrumento-convocatorio-modo-disputa/{tipoInstrumentoConvocatorioId}/{modoDisputaId}`.

## Endpoint
`DELETE /v1/tipo-instrumento-convocatorio-modo-disputa/{tipoInstrumentoConvocatorioId}/{modoDisputaId}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `tipoInstrumentoConvocatorioId` | path | integer | sim |
| `modoDisputaId` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`ExcluirDominioGenericoDTO`](../../schemas/excluir-dominio-generico-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
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
