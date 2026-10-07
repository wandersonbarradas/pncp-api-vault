---
title: "UnidadeOrgaoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# UnidadeOrgaoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 3 endpoint(s)

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
| orgao | [OrgaoEntidadeDTO](./orgao-entidade-dto.md) | não |  |  |
| statusAtivo | boolean | não |  |  |

## Schemas Relacionados

- [Municipio](./municipio.md)
- [OrgaoEntidadeDTO](./orgao-entidade-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/unidades](../sessoes/orgao-entidade/consultar-unidades.md) - Consultar Unidades
- `200`: [GET /v1/orgaos/{cnpj}/unidades/{codigoUnidade}](../sessoes/orgao-entidade/consultar-unidade.md) - Consultar Unidade
- `200`: [POST /v1/orgaos/{cnpj}/unidades](../sessoes/orgao-entidade/inserir-unidade.md) - Inserir Unidade

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
