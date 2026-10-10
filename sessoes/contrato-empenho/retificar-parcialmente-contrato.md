---
section_id: null
source_type: "openapi"
group: "Contrato/Empenho"
title: "Retificar Parcialmente Contrato"
method: "PATCH"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Parcialmente Contrato

## Resumo
Operação `PATCH /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}`.

## Endpoint
`PATCH /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer (int32) | sim |
| `sequencial` | path | integer (int32) | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarParcialContratoDTO`](../../schemas/alterar-parcial-contrato-dto.md)

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
