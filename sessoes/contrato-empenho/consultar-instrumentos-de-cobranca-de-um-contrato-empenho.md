---
section_id: "6.5.15"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Consultar Instrumentos de Cobrança de um Contrato/Empenho"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca"
page_start: 307
page_end: 310
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Instrumentos de Cobrança de um Contrato/Empenho

## Resumo
Serviço que permite consultar os instrumentos de cobrança vinculados a um contra-.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencialContrato` | path | integer | sim |

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
- `sections/6-5-15-consultar-instrumentos-de-cobranca-de-um-contrato-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
