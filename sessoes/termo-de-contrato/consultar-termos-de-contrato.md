---
section_id: "6.6.5"
source_type: "manual+openapi"
group: "Serviço de Termo de Contrato"
title: "Consultar Termos de Contrato"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos"
page_start: 350
page_end: 352
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Termos de Contrato

## Resumo
Serviço que permite recuperar a lista de termos de um contrato.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos`

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
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-6-5-consultar-todos-os-termos-de-um-contrato.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
