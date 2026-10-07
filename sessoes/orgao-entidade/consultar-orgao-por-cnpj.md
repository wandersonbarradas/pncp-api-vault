---
section_id: "6.2.3"
source_type: "manual+openapi"
group: "Serviços de Órgão/Entidade"
title: "Consultar Órgão por CNPJ"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}"
page_start: 126
page_end: 127
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Órgão por CNPJ

## Resumo
Serviço que permite consultar um órgão pelo seu CNPJ.

## Endpoint
`GET /v1/orgaos/{cnpj}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |

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
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-2-3-consultar-orgao-por-cnpj.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
