---
title: "AlterarCompraParcialDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarCompraParcialDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| amparoLegalId | integer (int64) | não |  |  |
| cnpjOrgaoSubRogado | string | não |  |  |
| codigoUnidadeCompradora | string | não |  |  |
| codigoUnidadeSubRogada | string | não |  |  |
| dataAberturaProposta | string (date-time) | não |  |  |
| dataEncerramentoProposta | string (date-time) | não |  |  |
| informacaoComplementar | string | não |  |  |
| justificativa | string | não |  |  |
| justificativaPresencial | string | não |  |  |
| linkProcessoEletronico | string | não |  |  |
| linkSistemaOrigem | string | não |  |  |
| modalidadeId | integer (int64) | não |  |  |
| modoDisputaId | integer (int64) | não |  |  |
| numeroCompra | string | não |  |  |
| numeroProcesso | string | não |  |  |
| objetoCompra | string | não |  |  |
| situacaoCompraId | string | não |  | 1, 2, 3, 4 |
| srp | boolean | não |  |  |
| tipoInstrumentoConvocatorioId | integer (int64) | não |  |  |

## Usado como Corpo de Requisição

- [PATCH /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}](../sessoes/contratacao/retificar-parcialmente-uma-contratacao.md) - Retificar parcialmente uma Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
