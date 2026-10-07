---
section_id: null
source_type: "openapi"
group: "Órgão"
title: "Consultar Órgão por ID"
method: "GET"
endpoint: "/v1/orgaos/id/{orgaoId}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Órgão por ID

## Resumo
Operação `GET /v1/orgaos/id/{orgaoId}`.

## Endpoint
`GET /v1/orgaos/id/{orgaoId}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `orgaoId` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`OrgaoConsultaDTO`](../../schemas/orgao-consulta-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `cnpj` | string | não |
| `razaoSocial` | string | não |
| `nomeFantasia` | string | não |
| `codigoNaturezaJuridica` | string | não |
| `situacaoCadastral` | string | não |
| `motivoSituacaoCadastral` | string | não |
| `dataSituacaoCadastral` | string (date) | não |
| `poderId` | string | não |
| `esferaId` | string | não |
| `dataValidacao` | string (date-time) | não |
| `validado` | boolean | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `descricaoNaturezaJuridica` | string | não |
| `statusAtivo` | boolean | não |
| `justificativaAtualizacao` | string | não |

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
