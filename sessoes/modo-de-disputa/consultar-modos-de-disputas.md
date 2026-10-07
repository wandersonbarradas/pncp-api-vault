---
section_id: "5.3.2"
source_type: "manual+openapi"
group: "Modo de Disputa"
title: "Consultar modos de disputas"
method: "GET"
endpoint: "/v1/modos-disputas"
page_start: 52
page_end: 53
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar modos de disputas

## Resumo
Serviço que permite consultar os modos de disputa cadastrados no PNCP.

## Endpoint
`GET /v1/modos-disputas`

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
- `sections/5-3-2-consultar-modos-de-disputa.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
