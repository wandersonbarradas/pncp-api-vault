---
title: "TipoInstrumentoConvocatorioDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# TipoInstrumentoConvocatorioDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataAtualizacao | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| descricao | string | não |  |  |
| id | integer (int64) | não |  |  |
| nome | string | não |  |  |
| obrigatoriedadeDataAberturaPropostaNome | string | não |  |  |
| obrigatoriedadeDataEncerramentoPropostaNome | string | não |  |  |
| statusAtivo | boolean | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/tipos-instrumentos-convocatorios/{id}](../sessoes/instrumento-convocatorio/consultar-instrumento-convocatorio-por-codigo.md) - Consultar instrumento convocatório por código

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
