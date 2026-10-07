---
title: "IncluirTipoInstrumentoConvocatorioDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IncluirTipoInstrumentoConvocatorioDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| descricao | string | não |  |  |
| id | integer (int64) | não |  |  |
| nome | string | não |  |  |
| obrigatoriedadeDataAberturaPropostaId | integer (int64) | não |  |  |
| obrigatoriedadeDataEncerramentoPropostaId | integer (int64) | não |  |  |

## Usado como Corpo de Requisição

- [POST /v1/tipos-instrumentos-convocatorios](../sessoes/instrumento-convocatorio/inserir-instrumento-convocatorio.md) - Inserir instrumento convocatório

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
