---
section_id: null
source_type: "openapi"
group: "Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal"
title: "Consultar Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal por código"
method: "GET"
endpoint: "/v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal por código

## Resumo
Operação `GET /v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}`.

## Endpoint
`GET /v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `amparoLegalId` | path | integer | sim |
| `modalidadeId` | path | integer | sim |
| `tipoInstrumentoConvocatorioId` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`ConsultarAmparoLegalModalidadeInstrumentoConvocatorioDTO`](../../schemas/consultar-amparo-legal-modalidade-instrumento-convocatorio-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `amparoLegal` | DominioGenericoResumidoDTO | não |
| `modalidade` | DominioGenericoResumidoDTO | não |
| `tipoInstrumentoConvocatorio` | DominioGenericoResumidoDTO | não |
| `dataInclusao` | string (date-time) | não |

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
