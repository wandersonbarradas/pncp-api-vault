---
section_id: "6.7.8"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Inserir itens de Plano de Contratação"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens"
page_start: 374
page_end: 378
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir itens de Plano de Contratação

## Resumo
Serviço que permite inserir itens em um plano de contratação de um ano de uma.

## Endpoint
`POST /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: `array`

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
- `sections/6-7-8-inserir-itens-de-plano-de-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
