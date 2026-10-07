---
title: "PlanoContratacaoComItensDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# PlanoContratacaoComItensDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| itens | array[[IRecuperarPlanoItemDTO](./i-recuperar-plano-item-dto.md)] | não |  |  |
| uasg | string | não |  |  |
| unidadeResponsavel | string | não |  |  |

## Schemas Relacionados

- [IRecuperarPlanoItemDTO](./i-recuperar-plano-item-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/plano](../sessoes/plano-de-contratacao/consultar-plano-de-contratacao-com-itens.md) - Consultar Plano de Contratação com Itens

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
