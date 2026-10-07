---
section_id: "5.23.1"
source_type: "manual+openapi"
group: "Catálogos (Itens de Plano de Contratações e Contratações)"
title: "Consultar catálogo por código"
method: "GET"
endpoint: "/v1/catalogos/{id}"
page_start: 96
page_end: 98
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar catálogo por código

## Resumo
Serviço que permite consultar um catálogo pelo seu código.

## Endpoint
`GET /v1/catalogos/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`CatalogoDTO`](../../schemas/catalogo-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `nome` | string | não |
| `descricao` | string | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `statusAtivo` | boolean | não |
| `url` | string | não |

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
- `sections/5-23-1-consultar-catalogo-por-codigo.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
