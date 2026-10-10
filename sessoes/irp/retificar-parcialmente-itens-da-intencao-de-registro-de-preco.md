---
section_id: null
source_type: "openapi"
group: "Intenção de Registro de Preços"
title: "Retificar Parcialmente Itens da Intenção de Registro de Preço"
method: "PATCH"
endpoint: "/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Parcialmente Itens da Intenção de Registro de Preço

## Resumo
Operação `PATCH /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens`.

## Endpoint
`PATCH /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer (int32) | sim |
| `sequencial` | path | integer (int32) | sim |

## Corpo da requisição
Schema OpenAPI: [`RetificarParcialIrpListaItensDTO`](../../schemas/retificar-parcial-irp-lista-itens-dto.md)

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
- Endpoint presente na OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
