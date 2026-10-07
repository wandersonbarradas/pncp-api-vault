---
section_id: "6.3.19"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Consultar Histórico de Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/historico"
page_start: 218
page_end: 221
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Histórico de Contratação

## Resumo
Serviço que permite consultar todos os eventos de uma contratação específica, dos.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/historico`

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
- `sections/6-3-19-consultar-historico-da-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
