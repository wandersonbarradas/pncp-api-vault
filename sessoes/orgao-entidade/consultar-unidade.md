---
section_id: "6.2.6"
source_type: "manual+openapi"
group: "Serviços de Órgão/Entidade"
title: "Consultar Unidade"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/unidades/{codigoUnidade}"
page_start: 132
page_end: 134
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Unidade

## Resumo
Serviço que permite consultar uma unidade pertencente a um órgão/entidade a partir.

## Endpoint
`GET /v1/orgaos/{cnpj}/unidades/{codigoUnidade}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `codigoUnidade` | path | string | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`UnidadeOrgaoDTO`](../../schemas/unidade-orgao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `orgao` | OrgaoEntidadeDTO | não |
| `codigoUnidade` | string | não |
| `nomeUnidade` | string | não |
| `municipio` | Municipio | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `statusAtivo` | boolean | não |
| `justificativaAtualizacao` | string | não |

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
- `sections/6-2-6-consultar-unidade.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
