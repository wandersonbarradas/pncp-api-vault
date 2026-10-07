---
section_id: "5.3.1"
source_type: "manual+openapi"
group: "Modo de Disputa"
title: "Consultar modo de disputa por código"
method: "GET"
endpoint: "/v1/modos-disputas/{id}"
page_start: 50
page_end: 51
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar modo de disputa por código

## Resumo
Serviço que permite consultar um modo de disputa pelo seu código.

## Endpoint
`GET /v1/modos-disputas/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`DominioGenericoDTO`](../../schemas/dominio-generico-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `nome` | string | não |
| `descricao` | string | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `statusAtivo` | boolean | não |

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
- `sections/5-3-1-consultar-modo-de-disputa-por-codigo.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
