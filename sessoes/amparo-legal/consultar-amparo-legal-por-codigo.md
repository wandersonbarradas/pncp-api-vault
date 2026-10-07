---
section_id: "5.15.1"
source_type: "manual+openapi"
group: "Amparo Legal"
title: "Consultar amparo legal por código"
method: "GET"
endpoint: "/v1/amparos-legais/{id}"
page_start: 66
page_end: 67
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar amparo legal por código

## Resumo
Serviço que permite consultar um amparo legal pelo seu código.

## Endpoint
`GET /v1/amparos-legais/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`AmparoLegalDTO`](../../schemas/amparo-legal-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `nome` | string | não |
| `descricao` | string | não |
| `tipoAmparoLegal` | DominioGenericoResumidoDTO | não |
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
- `sections/5-15-1-consultar-amparo-legal-por-codigo.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
