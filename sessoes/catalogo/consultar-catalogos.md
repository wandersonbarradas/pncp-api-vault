---
section_id: "5.23.2"
source_type: "manual+openapi"
group: "Catálogos (Itens de Plano de Contratações e Contratações)"
title: "Consultar catálogos"
method: "GET"
endpoint: "/v1/catalogos"
page_start: 98
page_end: 107
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar catálogos

## Resumo
Serviço que permite consultar os catálogos cadastrados no PNCP.

## Endpoint
`GET /v1/catalogos`

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
- `sections/5-23-2-consultar-catalogos.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
