---
title: "AlterarParcialTipoDocumentoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# AlterarParcialTipoDocumentoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| nome | string | não |  |  |
| descricao | string | não |  |  |
| tipoInformacaoId | integer (int64) | não |  |  |
| statusAtivo | boolean | não |  |  |
| justificativaAtualizacao | string | não |  |  |

## Usado em Requisições

- `PATCH /v1/tipos-documentos/{id}` em [alterar-tipo-de-documento.md](../sessoes/tipo-de-documento/alterar-tipo-de-documento.md) - Alterar Tipo de Documento

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
