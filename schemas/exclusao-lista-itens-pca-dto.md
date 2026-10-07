---
title: "ExclusaoListaItensPcaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# ExclusaoListaItensPcaDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| justificativa | string | não |  |  |
| listaNumerosItens | array[integer (int32)] | não |  |  |

## Usado como Corpo de Requisição

- [DELETE /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens](../sessoes/plano-de-contratacao/excluir-itens-de-plano-de-contratacao.md) - Excluir Itens de Plano de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
