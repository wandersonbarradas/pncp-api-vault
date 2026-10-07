---
title: "RetificarInstrumentoCobrancaContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RetificarInstrumentoCobrancaContratoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| chaveNFe | string | não |  |  |
| dataEmissaoDocumento | string | não |  |  |
| justificativa | string | não |  |  |
| numeroInstrumentoCobranca | string | não |  |  |
| observacao | string | não |  |  |
| tipoInstrumentoCobrancaId | integer (int64) | não |  |  |

## Usado como Corpo de Requisição

- [PATCH /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}](../sessoes/contrato-empenho/retificar-parcialmente-instrumento-de-cobranca-de-contrato-empenho.md) - Retificar Parcialmente Instrumento de Cobrança de Contrato/Empenho

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
