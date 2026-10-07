---
section_id: "6.6.8"
source_type: "manual+openapi"
group: "Serviço de Termo de Contrato"
title: "Consultar Documentos de Termo de Contrato"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos"
page_start: 356
page_end: 358
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Documentos de Termo de Contrato

## Resumo
Serviço que permite consultar a lista de documentos pertencentes a um termo de.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `sequencialTermo` | path | integer | sim |
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
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-6-8-consultar-todos-os-documentos-de-um-termo-de-contrato.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
