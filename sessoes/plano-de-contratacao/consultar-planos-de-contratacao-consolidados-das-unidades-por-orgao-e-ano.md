---
section_id: "6.7.4"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Consultar Planos de Contratação Consolidados das Unidades por Órgão e Ano"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/consolidado/unidades"
page_start: 367
page_end: 369
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Planos de Contratação Consolidados das Unidades por Órgão e Ano

## Resumo
Serviço que permite consultar os dados dos planos de contratações das unidades de.

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{ano}/consolidado/unidades`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `pagina` | query | integer | não |
| `tamanhoPagina` | query | integer | não |

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
- `sections/6-7-4-consultar-plano-das-unidades-por-orgao-e-ano.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
