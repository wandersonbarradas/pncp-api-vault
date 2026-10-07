---
section_id: null
source_type: "openapi"
group: "Contrato/Empenho"
title: "Consultar Documentos de Contrato"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Documentos de Contrato

## Resumo
Operação `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos`.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `pagina` | query | integer | não |
| `tamanhoPagina` | query | integer | não |

## Corpo da requisição
Não se aplica.

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
- Endpoint presente na OpenAPI atual, sem seção correspondente no manual segmentado local.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
