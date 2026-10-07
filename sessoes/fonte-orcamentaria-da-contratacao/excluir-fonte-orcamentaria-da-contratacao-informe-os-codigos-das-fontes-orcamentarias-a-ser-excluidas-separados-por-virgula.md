---
section_id: null
source_type: "openapi"
group: "Fonte orçamentária da contratação"
title: "Excluir fonte orçamentária da contratação - Informe os códigos das fontes orçamentárias a ser excluídas, separados por vírgula"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir fonte orçamentária da contratação - Informe os códigos das fontes orçamentárias a ser excluídas, separados por vírgula

## Resumo
Operação `DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria`.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`ExcluirContratacaoFonteOrcamentariaDTO`](../../schemas/excluir-contratacao-fonte-orcamentaria-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `listaFonteOrcamentariaId` | array | não |
| `justificativaAtualizacao` | string | não |

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
