---
section_id: null
source_type: "openapi"
group: "Plano de Contratação"
title: "Consultar Plano de Contratação com Itens"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/plano"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Plano de Contratação com Itens

## Resumo
Operação `GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/plano`.

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/plano`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`PlanoContratacaoComItensDTO`](../../schemas/plano-contratacao-com-itens-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `itens` | array | não |
| `uasg` | string | não |
| `unidadeResponsavel` | string | não |

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
- Endpoint presente na OpenAPI atual, sem seção correspondente no manual segmentado local.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
