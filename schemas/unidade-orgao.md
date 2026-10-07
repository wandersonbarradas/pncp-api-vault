---
title: "UnidadeOrgao"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# UnidadeOrgao

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| codigoUnidade | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| id | integer (int64) | não |  |  |
| justificativaAtualizacao | string | não |  |  |
| municipio | [Municipio](./municipio.md) | não |  |  |
| nomeUnidade | string | não |  |  |
| orgao | [OrgaoEntidade](./orgao-entidade.md) | não |  |  |
| statusAtivo | boolean | não |  |  |

## Schemas Relacionados

- [Municipio](./municipio.md)
- [OrgaoEntidade](./orgao-entidade.md)

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
