---
title: "RetificarParcialIrpListaItensDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# RetificarParcialIrpListaItensDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| itens | array ([`AlterarIrpItensParcialDTO`](./alterar-irp-itens-parcial-dto.md)) | sim |  |  |
| justificativa | string | sim |  |  |

## Usado em Requisições

- `PATCH /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens` em [retificar-parcialmente-itens-da-intencao-de-registro-de-preco.md](../sessoes/irp/retificar-parcialmente-itens-da-intencao-de-registro-de-preco.md) - Retificar Parcialmente Itens da Intenção de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
