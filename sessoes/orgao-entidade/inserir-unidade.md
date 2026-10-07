---
section_id: "6.2.4"
source_type: "manual+openapi"
group: "Serviços de Órgão/Entidade"
title: "Inserir Unidade"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/unidades"
page_start: 127
page_end: 130
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Unidade

## Resumo
Serviço que permite inserir uma unidade em um órgão/entidade.

## Endpoint
`POST /v1/orgaos/{cnpj}/unidades`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |

## Corpo da requisição
Schema OpenAPI: [`IncluirUnidadeOrgaoDTO`](../../schemas/incluir-unidade-orgao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `codigoIBGE` | string | não |
| `codigoUnidade` | string | não |
| `nomeUnidade` | string | não |

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
- `sections/6-2-4-incluir-unidade.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
