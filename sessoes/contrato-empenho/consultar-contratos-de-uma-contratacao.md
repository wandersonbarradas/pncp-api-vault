---
section_id: "6.5.9"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Consultar Contratos de uma Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/contratacao/{anoContratacao}/{sequencialContratacao}"
page_start: 292
page_end: 296
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Contratos de uma Contratação

## Resumo
Serviço que permite recuperar os contratos/empenhos de uma contratação.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/contratacao/{anoContratacao}/{sequencialContratacao}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `anoContratacao` | path | integer | sim |
| `sequencialContratacao` | path | integer | sim |
| `pagina` | query | integer | sim |
| `tamanhoPagina` | query | integer | não |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`PaginaRetornoRecuperarContratoDTO`](../../schemas/pagina-retorno-recuperar-contrato-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `data` | array | não |
| `totalRegistros` | integer (int64) | não |
| `totalPaginas` | integer (int64) | não |
| `numeroPagina` | integer (int64) | não |
| `paginasRestantes` | integer (int64) | não |
| `empty` | boolean | não |

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
- `sections/6-5-9-consultar-contratos-empenhos-de-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
