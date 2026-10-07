---
title: "IncluirInstrumentoCobrancaContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IncluirInstrumentoCobrancaContratoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| chaveNFe | string | não |  |  |
| dataEmissaoDocumento | string | não |  |  |
| numeroInstrumentoCobranca | string | não |  |  |
| observacao | string | não |  |  |
| tipoInstrumentoCobrancaId | integer (int64) | sim |  |  |

## Usado como Corpo de Requisição

- [POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca](../sessoes/contrato-empenho/inserir-instrumento-de-cobranca-de-um-contrato-empenho.md) - Inserir Instrumento de Cobrança de um Contrato/Empenho

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
