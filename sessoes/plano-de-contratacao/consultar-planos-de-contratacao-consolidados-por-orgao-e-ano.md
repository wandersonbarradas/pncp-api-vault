---
section_id: "6.7.3"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Consultar Planos de Contratação Consolidados por Órgão e Ano"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/consolidado"
page_start: 366
page_end: 367
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Planos de Contratação Consolidados por Órgão e Ano

## Resumo
Serviço que permite consultar o plano de contratações anual específico de um.

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{ano}/consolidado`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`PlanoContratacaoItemOrgaoToDTO`](../../schemas/plano-contratacao-item-orgao-to-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `dataAtualizacao` | string (date-time) | não |
| `cnpj` | string | não |
| `dataPublicacaoPncp` | string (date-time) | não |
| `anoPca` | integer (int32) | não |
| `valorTotal` | number | não |
| `quantidade` | number | não |
| `poder` | string | não |
| `esfera` | string | não |
| `razaoSocial` | string | não |

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
- `sections/6-7-3-consultar-plano-por-orgao-e-ano.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
