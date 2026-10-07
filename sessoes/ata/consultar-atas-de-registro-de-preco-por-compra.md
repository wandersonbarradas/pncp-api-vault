---
section_id: "6.4.5"
source_type: "manual+openapi"
group: "Serviços de Ata"
title: "Consultar Atas de Registro de Preço por Compra"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas"
page_start: 244
page_end: 246
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Atas de Registro de Preço por Compra

## Resumo
Serviço que permite recuperar as atas de Registro de Preço de uma contratação.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `anoCompra` | path | integer | sim |
| `sequencialCompra` | path | integer | sim |
| `pagina` | query | integer | não |
| `tamanhoPagina` | query | integer | não |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`PaginaRetornoAtaRegistroPrecoDTO`](../../schemas/pagina-retorno-ata-registro-preco-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `data` | array | não |
| `totalRegistros` | integer (int64) | não |
| `totalPaginas` | integer (int64) | não |
| `numeroPagina` | integer (int64) | não |
| `paginasRestantes` | integer (int64) | não |
| `empty` | boolean | não |

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
- `sections/6-4-5-consultar-atas-de-registro-de-preco-por-compra.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
