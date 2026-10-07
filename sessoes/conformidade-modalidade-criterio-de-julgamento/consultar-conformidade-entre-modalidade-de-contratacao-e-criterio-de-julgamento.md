---
section_id: "5.22.2"
source_type: "manual+openapi"
group: "Regra de conformidade entre Modalidade de Contratação e"
title: "Consultar conformidade entre modalidade de contratação e critério de julgamento"
method: "GET"
endpoint: "/v1/modalidade-criterio-julgamento"
page_start: 93
page_end: 96
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar conformidade entre modalidade de contratação e critério de julgamento

## Resumo
Critério de Julgamento.

## Endpoint
`GET /v1/modalidade-criterio-julgamento`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `modalidadeId` | query | integer | não |
| `criterioJulgamentoId` | query | integer | não |

## Corpo da requisição
Não se aplica.

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
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/5-22-2-consultar-conformidade-entre-modalidade-de-contratacao-e.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
