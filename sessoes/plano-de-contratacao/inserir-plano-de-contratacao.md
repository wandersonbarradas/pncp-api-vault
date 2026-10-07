---
section_id: "6.7.1"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Inserir Plano de Contratação"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/pca"
page_start: 361
page_end: 364
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Plano de Contratação

## Resumo
Serviço que permite inserir um plano de contratações de um ano de uma respectiva.

## Endpoint
`POST /v1/orgaos/{cnpj}/pca`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |

## Corpo da requisição
Schema OpenAPI: [`IncluirPlanoContratacaoDTO`](../../schemas/incluir-plano-contratacao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `codigoUnidade` | string | sim |
| `anoPca` | integer (int32) | sim |
| `itensPlano` | array | sim |

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
- `sections/6-7-1-inserir-plano-de-contratacoes.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
