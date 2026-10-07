---
section_id: "6.7.11"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Retificar Parcialmente itens de Plano de Contratação"
method: "PATCH"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens"
page_start: 387
page_end: 392
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Parcialmente itens de Plano de Contratação

## Resumo
Serviço que permite retificar itens de um plano de contratação no PNCP. Este serviço.

## Endpoint
`PATCH /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`RetificarParcialPlanoContratacaoListaItensDTO`](../../schemas/retificar-parcial-plano-contratacao-lista-itens-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `lista` | array | não |
| `justificativa` | string | não |

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
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-7-11-retificar-parcialmente-itens-de-um-plano-de-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
