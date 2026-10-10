---
title: "ExcluirItensIrpDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# ExcluirItensIrpDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| numerosItens | array (integer (int32)) | sim |  |  |
| justificativa | string | sim |  |  |

## Usado em Requisições

- `DELETE /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/itens` em [excluir-itens-da-intencao-de-registro-de-preco.md](../sessoes/irp/excluir-itens-da-intencao-de-registro-de-preco.md) - Excluir Itens da Intenção de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
