---
title: "AlterarParcialTipoInstrumentoConvocatorioDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarParcialTipoInstrumentoConvocatorioDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| descricao | string | não |  |  |
| justificativaAtualizacao | string | não |  |  |
| nome | string | não |  |  |
| obrigatoriedadeDataAberturaPropostaId | integer (int64) | não |  |  |
| obrigatoriedadeDataEncerramentoPropostaId | integer (int64) | não |  |  |
| statusAtivo | boolean | não |  |  |

## Usado como Corpo de Requisição

- [PATCH /v1/tipos-instrumentos-convocatorios/{id}](../sessoes/instrumento-convocatorio/alterar-instrumento-convocatorio.md) - Alterar instrumento convocatório

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
