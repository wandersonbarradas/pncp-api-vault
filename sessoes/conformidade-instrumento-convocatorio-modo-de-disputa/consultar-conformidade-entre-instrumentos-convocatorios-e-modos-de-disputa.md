---
section_id: "5.19.2"
source_type: "manual+openapi"
group: "Regra de conformidade entre Instrumento Convocatório e Modo de"
title: "Consultar conformidade entre instrumentos convocatórios e modos de disputa"
method: "GET"
endpoint: "/v1/tipo-instrumento-convocatorio-modo-disputa"
page_start: 87
page_end: 90
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar conformidade entre instrumentos convocatórios e modos de disputa

## Resumo
Modos de Disputa.

## Endpoint
`GET /v1/tipo-instrumento-convocatorio-modo-disputa`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `tipoInstrumentoConvocatorioId` | query | integer | não |
| `modoDisputaId` | query | integer | não |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: `object`

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
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/5-19-2-consultar-conformidade-entre-instrumentos-convocatorios-e.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
