---
section_id: null
source_type: "openapi"
group: "Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal"
title: "Consultar Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal"
method: "GET"
endpoint: "/v1/instrumento-convocatorio-modalidade-amparo-legal"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal

## Resumo
Operação `GET /v1/instrumento-convocatorio-modalidade-amparo-legal`.

## Endpoint
`GET /v1/instrumento-convocatorio-modalidade-amparo-legal`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `amparoLegalId` | query | integer | não |
| `modalidadeId` | query | integer | não |
| `tipoInstrumentoConvocatorioId` | query | integer | não |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: `array`

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
