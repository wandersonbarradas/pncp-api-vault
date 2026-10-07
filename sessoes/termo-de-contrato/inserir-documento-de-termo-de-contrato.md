---
section_id: "6.6.6"
source_type: "manual+openapi"
group: "Serviço de Termo de Contrato"
title: "Inserir Documento de Termo de Contrato"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos"
page_start: 352
page_end: 355
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Documento de Termo de Contrato

## Resumo
Serviço que permite inserir um documento/arquivo a um termo de contrato. O sistema.

## Endpoint
`POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `sequencialTermo` | path | integer | sim |
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
- `sections/6-6-6-inserir-documento-a-um-termo-de-contrato.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
