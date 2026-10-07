---
section_id: "6.7.16"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Baixar CSV dos Planos de Contratação por Órgão e Ano"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/csv"
page_start: 399
page_end: 402
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Baixar CSV dos Planos de Contratação por Órgão e Ano

## Resumo
Serviço que gera arquivo CSV contendo as informações de itens dos Planos de.

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{ano}/csv`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |

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
- `sections/6-7-16-gerar-arquivo-csv-de-itens-dos-planos-por-orgao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
