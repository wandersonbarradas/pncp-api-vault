---
section_id: null
source_type: "openapi"
group: "Usuário"
title: "Excluir usuário"
method: "DELETE"
endpoint: "/v1/usuarios/{id}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir usuário

## Resumo
Operação `DELETE /v1/usuarios/{id}`.

## Endpoint
`DELETE /v1/usuarios/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
A OpenAPI capturada não descreve um schema de resposta de negócio específico para `200`, ou a operação está disponível apenas no manual local.

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
