---
title: "ConsultarInstrumentoCobrancaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# ConsultarInstrumentoCobrancaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| ano | integer (int32) | não |  |  |
| chaveNFe | string | não |  |  |
| cnpj | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataConsultaNFe | string (date-time) | não |  |  |
| dataEmissaoDocumento | string (date) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| fonteNFe | integer (int64) | não |  |  |
| jsonResponseNFe | string | não |  |  |
| notaFiscalEletronica | [NotaFiscalEletronicaConsultaDTO](./nota-fiscal-eletronica-consulta-dto.md) | não |  |  |
| numeroInstrumentoCobranca | string | não |  |  |
| observacao | string | não |  |  |
| sequencialContrato | integer (int32) | não |  |  |
| sequencialInstrumentoCobranca | integer (int32) | não |  |  |
| statusResponseNFe | string | não |  |  |
| tipoInstrumentoCobranca | [TipoInstrumentoCobrancaDTO](./tipo-instrumento-cobranca-dto.md) | não |  |  |

## Schemas Relacionados

- [NotaFiscalEletronicaConsultaDTO](./nota-fiscal-eletronica-consulta-dto.md)
- [TipoInstrumentoCobrancaDTO](./tipo-instrumento-cobranca-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca](../sessoes/contrato-empenho/consultar-instrumentos-de-cobranca-de-um-contrato-empenho.md) - Consultar Instrumentos de Cobrança de um Contrato/Empenho
- `200`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}](../sessoes/contrato-empenho/consultar-instrumento-de-cobranca-de-um-contrato-empenho.md) - Consultar Instrumento de Cobrança de um Contrato/Empenho

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
