---
title: "AlterarParcialTipoContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# AlterarParcialTipoContratoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| nome | string | não |  |  |
| descricao | string | não |  |  |
| statusAtivo | boolean | não |  |  |
| justificativaAtualizacao | string | não |  |  |

## Usado em Requisições

- `PATCH /v1/tipos-contratos/{id}` em [alterar-tipo-de-contrato.md](../sessoes/tipo-de-contrato/alterar-tipo-de-contrato.md) - Alterar Tipo de Contrato

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
