---
section_id: "6.2.7"
source_type: "manual+openapi"
group: "Serviços de Órgão/Entidade"
title: "Consultar Unidades"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/unidades"
page_start: 135
page_end: 137
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Unidades

## Resumo
Serviço que permite consultar unidades pertencentes a um órgão/entidade.

## Endpoint
`GET /v1/orgaos/{cnpj}/unidades`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |

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
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-2-7-consultar-unidades-de-um-orgao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
