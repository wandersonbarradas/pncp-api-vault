---
section_id: null
source_type: "openapi"
group: "Intenção de Registro de Preços"
title: "Inserir Documento em Intenção de Registro de Preço"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Documento em Intenção de Registro de Preço

## Resumo
Operação `POST /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos`.

## Endpoint
`POST /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer (int32) | sim |
| `sequencial` | path | integer (int32) | sim |
| `Titulo-Documento` | header | string | sim |
| `Tipo-Documento` | header | integer (int64) | sim |

## Corpo da requisição
Content-Type: `multipart/form-data`

| Campo | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- |
| `arquivo` | string (binary) | sim |  |

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
- Endpoint presente na OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
