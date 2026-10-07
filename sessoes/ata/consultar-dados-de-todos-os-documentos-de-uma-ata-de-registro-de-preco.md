---
section_id: "6.4.9"
source_type: "manual+openapi"
group: "Serviços de Ata"
title: "Consultar Dados de Todos os Documentos de uma Ata de Registro de Preço"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos"
page_start: 251
page_end: 253
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Dados de Todos os Documentos de uma Ata de Registro de Preço

## Resumo
Serviço que permite consultar a lista de documentos pertencentes a uma ata específica.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `anoCompra` | path | integer | sim |
| `sequencialCompra` | path | integer | sim |
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
- `sections/6-4-9-consultar-todos-os-documentos-de-uma-ata.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
