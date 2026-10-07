---
section_id: "6.7.9"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Consultar Itens do Plano de Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens"
page_start: 378
page_end: 382
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Itens do Plano de Contratação

## Resumo
Serviço que permite recuperar a lista de itens pertencentes a um determinado Plano de.

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `categoria` | query | integer | não |
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
- `sections/6-7-9-consultar-itens-do-plano-de-contratacoes-de-uma-unidade-e-ano.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
