---
section_id: "6.7.13"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Excluir Itens de Plano de Contratação"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens"
page_start: 393
page_end: 394
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir Itens de Plano de Contratação

## Resumo
Serviço que permite excluir itens de um plano de contratação no PNCP. Este serviço.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`ExclusaoListaItensPcaDTO`](../../schemas/exclusao-lista-itens-pca-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `justificativa` | string | não |
| `listaNumerosItens` | array | não |

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
- `sections/6-7-13-excluir-itens-de-um-plano-de-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
