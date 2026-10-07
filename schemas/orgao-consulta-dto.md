---
title: "OrgaoConsultaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# OrgaoConsultaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 3 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| cnpj | string | não |  |  |
| codigoNaturezaJuridica | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataSituacaoCadastral | string (date) | não |  |  |
| dataValidacao | string (date-time) | não |  |  |
| descricaoNaturezaJuridica | string | não |  |  |
| esferaId | string | não |  |  |
| justificativaAtualizacao | string | não |  |  |
| motivoSituacaoCadastral | string | não |  |  |
| nomeFantasia | string | não |  |  |
| poderId | string | não |  |  |
| razaoSocial | string | não |  |  |
| situacaoCadastral | string | não |  |  |
| statusAtivo | boolean | não |  |  |
| validado | boolean | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/](../sessoes/orgao-entidade/consultar-orgao-por-filtro.md) - Consultar Órgão por Filtro
- `200`: [GET /v1/orgaos/id/{orgaoId}](../sessoes/orgao-entidade/consultar-orgao-por-id.md) - Consultar Órgão por ID
- `200`: [GET /v1/orgaos/{cnpj}](../sessoes/orgao-entidade/consultar-orgao-por-cnpj.md) - Consultar Órgão por CNPJ

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
