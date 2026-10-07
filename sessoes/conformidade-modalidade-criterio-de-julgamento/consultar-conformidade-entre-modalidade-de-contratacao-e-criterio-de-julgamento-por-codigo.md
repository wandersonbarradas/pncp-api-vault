---
section_id: "5.22.1"
source_type: "manual+openapi"
group: "Regra de conformidade entre Modalidade de Contratação e"
title: "Consultar conformidade entre modalidade de contratação e critério de julgamento por código"
method: "GET"
endpoint: "/v1/modalidade-criterio-julgamento/{modalidadeId}/{criterioJulgamentoId}"
page_start: 90
page_end: 93
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar conformidade entre modalidade de contratação e critério de julgamento por código

## Resumo
Critério de Julgamento por Código.

## Endpoint
`GET /v1/modalidade-criterio-julgamento/{modalidadeId}/{criterioJulgamentoId}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `modalidadeId` | path | integer | sim |
| `criterioJulgamentoId` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`ConsultarModalidadeCriterioJulgamentoDTO`](../../schemas/consultar-modalidade-criterio-julgamento-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `modalidadeContratacao` | DominioGenericoResumidoDTO | não |
| `criterioJulgamento` | DominioGenericoResumidoDTO | não |
| `dataInclusao` | string (date-time) | não |

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
- `sections/5-22-1-consultar-conformidade-entre-modalidade-de-contratacao-e.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
