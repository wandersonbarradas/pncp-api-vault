---
section_id: "6.7.10"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Retificar Parcialmente item de Plano de Contratação"
method: "PATCH"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/{numeroItem}"
page_start: 383
page_end: 387
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Parcialmente item de Plano de Contratação

## Resumo
Serviço que permite retificar um item específico de um plano de contratação no PNCP.

## Endpoint
`PATCH /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/{numeroItem}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `numeroItem` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`RetificarParcialPlanoContratacaoItemDTO`](../../schemas/retificar-parcial-plano-contratacao-item-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `categoriaItemPca` | integer (int64) | não |
| `catalogo` | integer (int64) | não |
| `classificacaoSuperiorCodigo` | string | não |
| `classificacaoSuperiorNome` | string | não |
| `pdmCodigo` | string | não |
| `pdmDescricao` | string | não |
| `classificacaoCatalogo` | string | não |
| `codigoItem` | string | não |
| `descricao` | string | não |
| `unidadeFornecimento` | string | não |
| `quantidade` | number | não |
| `valorUnitario` | number | não |
| `valorTotal` | number | não |
| `valorOrcamentoExercicio` | number | não |
| `unidadeRequisitante` | string | não |
| `dataDesejada` | string (date) | não |
| `grupoContratacaoCodigo` | string | não |
| `grupoContratacaoNome` | string | não |
| `justificativa` | string | não |
| `numeroItem` | integer (int32) | não |

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
- `sections/6-7-10-retificar-parcialmente-item-de-plano-de-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
