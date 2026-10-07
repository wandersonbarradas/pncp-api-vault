---
section_id: "6.7.14"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Retornar Itens de Plano de Contratação por número da Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/contratacao"
page_start: 394
page_end: 398
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retornar Itens de Plano de Contratação por número da Contratação

## Resumo
Contratação.

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/contratacao`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `numeroContratacao` | query | string | sim |
| `page` | query | integer | não |
| `size` | query | integer | não |

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
- `sections/6-7-14-recuperar-itens-de-plano-de-contratacao-por-numero-da.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
