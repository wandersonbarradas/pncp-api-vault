---
section_id: null
source_type: "openapi"
group: "Conformidade Modalidade e Critério de Julgamento"
title: "Excluir conformidade entre modalidade de contratação e critério de julgamento"
method: "DELETE"
endpoint: "/v1/modalidade-criterio-julgamento/{modalidadeId}/{criterioJulgamentoId}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir conformidade entre modalidade de contratação e critério de julgamento

## Resumo
Operação `DELETE /v1/modalidade-criterio-julgamento/{modalidadeId}/{criterioJulgamentoId}`.

## Endpoint
`DELETE /v1/modalidade-criterio-julgamento/{modalidadeId}/{criterioJulgamentoId}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `modalidadeId` | path | integer | sim |
| `criterioJulgamentoId` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`ExcluirDominioGenericoDTO`](../../schemas/excluir-dominio-generico-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `justificativaAtualizacao` | string | não |

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
- Endpoint presente na OpenAPI atual, sem seção correspondente no manual segmentado local.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
