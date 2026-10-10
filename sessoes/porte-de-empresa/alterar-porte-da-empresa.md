---
section_id: null
source_type: "openapi"
group: "Porte de Empresa"
title: "Alterar Porte da Empresa"
method: "PATCH"
endpoint: "/v1/portes-empresa/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Alterar Porte da Empresa

## Resumo
Operação `PATCH /v1/portes-empresa/{id}`.

## Endpoint
`PATCH /v1/portes-empresa/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer (int64) | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarParcialDominioGenericoDTO`](../../schemas/alterar-parcial-dominio-generico-dto.md)

## Resposta
Schema OpenAPI: `string`

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
- Endpoint presente na OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
