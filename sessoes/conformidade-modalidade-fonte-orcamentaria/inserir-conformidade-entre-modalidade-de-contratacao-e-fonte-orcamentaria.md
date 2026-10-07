---
section_id: null
source_type: "openapi"
group: "Conformidade Modalidade e Fonte Orçamentaria"
title: "Inserir conformidade entre modalidade de contratação e Fonte Orçamentaria"
method: "POST"
endpoint: "/v1/modalidade-fonte-orcamentaria"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir conformidade entre modalidade de contratação e Fonte Orçamentaria

## Resumo
Operação `POST /v1/modalidade-fonte-orcamentaria`.

## Endpoint
`POST /v1/modalidade-fonte-orcamentaria`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Schema OpenAPI: [`ModalidadeFonteOrcamentariaDTO`](../../schemas/modalidade-fonte-orcamentaria-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `modalidadeId` | integer (int64) | não |
| `fonteOrcamentariaId` | integer (int64) | não |

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
- Endpoint presente na OpenAPI atual, sem seção correspondente no manual segmentado local.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
