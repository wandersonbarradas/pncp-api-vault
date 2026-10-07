---
section_id: "5.1.2"
source_type: "manual+openapi"
group: "Instrumento Convocatório"
title: "Consultar instrumentos convocatórios"
method: "GET"
endpoint: "/v1/tipos-instrumentos-convocatorios"
page_start: 44
page_end: 47
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar instrumentos convocatórios

## Resumo
Serviço que permite consultar os instrumentos convocatórios cadastrados no PNCP.

## Endpoint
`GET /v1/tipos-instrumentos-convocatorios`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `statusAtivo` | query | boolean | não |

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
- `sections/5-1-2-consultar-instrumentos-convocatorios.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
