---
section_id: "6.2.5"
source_type: "manual+openapi"
group: "Serviços de Órgão/Entidade"
title: "Atualizar Unidade"
method: "PUT"
endpoint: "/v1/orgaos/{cnpj}/unidades"
page_start: 130
page_end: 132
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Atualizar Unidade

## Resumo
Serviço que permite atualizar os dados (nome da unidade e código IBGE do município).

## Endpoint
`PUT /v1/orgaos/{cnpj}/unidades`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarUnidadeOrgaoDTO`](../../schemas/alterar-unidade-orgao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `codigoUnidade` | string | não |
| `nomeUnidade` | string | não |
| `codigoIBGE` | string | não |

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
- `sections/6-2-5-atualizar-unidade.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
