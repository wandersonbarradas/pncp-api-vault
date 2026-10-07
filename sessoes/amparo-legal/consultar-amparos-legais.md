---
section_id: "5.15.2"
source_type: "manual+openapi"
group: "Amparo Legal"
title: "Consultar amparos legais"
method: "GET"
endpoint: "/v1/amparos-legais"
page_start: 68
page_end: 69
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar amparos legais

## Resumo
Serviço que permite consultar os amparos legais cadastrados no PNCP.

## Endpoint
`GET /v1/amparos-legais`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `tipoAmparoLegalId` | query | integer | não |
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
- `sections/5-15-2-consultar-amparos-legais.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
