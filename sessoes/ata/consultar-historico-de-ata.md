---
section_id: "6.4.11"
source_type: "manual+openapi"
group: "Serviços de Ata"
title: "Consultar Histórico de Ata"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/atas/{sequencialAta}/historico"
page_start: 254
page_end: 257
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Histórico de Ata

## Resumo
Serviço que permite consultar todos os eventos de uma ata específica e de seus.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/atas/{sequencialAta}/historico`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `sequencialAta` | path | integer | sim |
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
- `sections/6-4-11-consultar-historico-da-ata.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
