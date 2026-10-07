---
section_id: "6.3.6"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Inserir Documento de Contratação"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos"
page_start: 165
page_end: 169
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Documento de Contratação

## Resumo
Serviço que permite inserir/anexar um documento/arquivo a uma Contratação. O.

## Endpoint
`POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `Titulo-Documento` | header | string | sim |
| `Tipo-Documento-Id` | header | integer | sim |

## Corpo da requisição
Schema OpenAPI: `object`

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
- `sections/6-3-6-inserir-documento-a-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
