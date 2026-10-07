---
title: "RetificarParcialPlanoContratacaoListaItensDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RetificarParcialPlanoContratacaoListaItensDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| justificativa | string | não |  |  |
| lista | array[[RetificarParcialPlanoContratacaoItemDTO](./retificar-parcial-plano-contratacao-item-dto.md)] | não |  |  |

## Schemas Relacionados

- [RetificarParcialPlanoContratacaoItemDTO](./retificar-parcial-plano-contratacao-item-dto.md)

## Usado como Corpo de Requisição

- [PATCH /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens](../sessoes/plano-de-contratacao/retificar-parcialmente-itens-de-plano-de-contratacao.md) - Retificar Parcialmente itens de Plano de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
