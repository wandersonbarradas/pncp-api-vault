---
section_id: null
source_type: "openapi"
group: "Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal"
title: "Excluir Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal"
method: "DELETE"
endpoint: "/v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal

## Resumo
Operação `DELETE /v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}`.

## Endpoint
`DELETE /v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `amparoLegalId` | path | integer | sim |
| `modalidadeId` | path | integer | sim |
| `tipoInstrumentoConvocatorioId` | path | integer | sim |

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
