---
title: "AlterarCompraDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarCompraDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| amparoLegalId | integer (int64) | sim |  |  |
| cnpjOrgaoSubRogado | string | não |  |  |
| codigoUnidadeCompradora | string | sim |  |  |
| codigoUnidadeSubRogada | string | não |  |  |
| dataAberturaProposta | string (date-time) | não |  |  |
| dataEncerramentoProposta | string (date-time) | não |  |  |
| informacaoComplementar | string | não |  |  |
| justificativa | string | não |  |  |
| justificativaPresencial | string | não |  |  |
| linkProcessoEletronico | string | não |  |  |
| linkSistemaOrigem | string | não |  |  |
| modalidadeId | integer (int64) | sim |  |  |
| modoDisputaId | integer (int64) | sim |  |  |
| numeroCompra | string | sim |  |  |
| numeroProcesso | string | sim |  |  |
| objetoCompra | string | sim |  |  |
| situacaoCompraId | string | sim |  | 1, 2, 3, 4 |
| srp | boolean | sim |  |  |
| tipoInstrumentoConvocatorioId | integer (int64) | sim |  |  |

## Usado como Corpo de Requisição

- [PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}](../sessoes/contratacao/retificar-contratacao.md) - Retificar Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
