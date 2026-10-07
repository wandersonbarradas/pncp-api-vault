---
section_id: "6.3.20"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Inserir Item de Contratação"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens"
page_start: 221
page_end: 222
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Item de Contratação

## Resumo
Serviço que permite inserir uma imagem de um item de Contratação. O sistema permite.

## Endpoint
`POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: `array`

## Resposta
Schema OpenAPI: `array`

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
- `sections/6-3-20-inserir-imagem-de-um-item-de-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
