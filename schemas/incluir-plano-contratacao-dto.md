---
title: "IncluirPlanoContratacaoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IncluirPlanoContratacaoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoPca | integer (int32) | sim |  |  |
| codigoUnidade | string | sim |  |  |
| itensPlano | array[[IncluirPlanoContratacaoItemDTO](./incluir-plano-contratacao-item-dto.md)] | sim |  |  |

## Schemas Relacionados

- [IncluirPlanoContratacaoItemDTO](./incluir-plano-contratacao-item-dto.md)

## Usado como Corpo de Requisição

- [POST /v1/orgaos/{cnpj}/pca](../sessoes/plano-de-contratacao/inserir-plano-de-contratacao.md) - Inserir Plano de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
