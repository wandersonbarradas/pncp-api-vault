---
section_id: "5.26.1"
source_type: "manual+openapi"
group: "Regra de conformidade entre Modalidade de Contratação e Fonte"
title: "Consultar conformidade entre modalidade de contratação e Fonte Orçamentaria por código"
method: "GET"
endpoint: "/v1/modalidade-fonte-orcamentaria/{modalidadeId}/{fonteOrcamentariaId}"
page_start: 107
page_end: 109
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar conformidade entre modalidade de contratação e Fonte Orçamentaria por código

## Resumo
Fonte Orçamentária por Código.

## Endpoint
`GET /v1/modalidade-fonte-orcamentaria/{modalidadeId}/{fonteOrcamentariaId}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `modalidadeId` | path | integer | sim |
| `fonteOrcamentariaId` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`ConsultarModalidadeFonteOrcamentariaDTO`](../../schemas/consultar-modalidade-fonte-orcamentaria-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `modalidadeContratacao` | DominioGenericoResumidoDTO | não |
| `fonteOrcamentaria` | DominioGenericoResumidoDTO | não |
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
- `sections/5-26-1-consultar-conformidade-entre-modalidade-de-contratacao-e.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
