---
section_id: null
source_type: "openapi"
group: "Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal"
title: "Inserir Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal"
method: "POST"
endpoint: "/v1/instrumento-convocatorio-modalidade-amparo-legal"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal

## Resumo
Operação `POST /v1/instrumento-convocatorio-modalidade-amparo-legal`.

## Endpoint
`POST /v1/instrumento-convocatorio-modalidade-amparo-legal`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Schema OpenAPI: [`AmparoLegalModalidadeInstrumentoConvocatorioCommand`](../../schemas/amparo-legal-modalidade-instrumento-convocatorio-command.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `amparoLegalId` | integer (int64) | não |
| `modalidadeId` | integer (int64) | não |
| `tipoInstrumentoConvocatorioId` | integer (int64) | não |

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
