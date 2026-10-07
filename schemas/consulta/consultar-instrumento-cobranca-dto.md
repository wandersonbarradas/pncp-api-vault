---
title: "ConsultarInstrumentoCobrancaDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# ConsultarInstrumentoCobrancaDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 0 endpoint(s)

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
| recuperarContratoDTO | [RecuperarContratoDTO](./recuperar-contrato-dto.md) | não |  |  |
| sequencialContrato | integer (int32) | não |  |  |
| sequencialInstrumentoCobranca | integer (int32) | não |  |  |
| statusResponseNFe | string | não |  |  |
| tipoInstrumentoCobranca | [TipoInstrumentoCobrancaDTO](./tipo-instrumento-cobranca-dto.md) | não |  |  |

## Schemas Relacionados

- [NotaFiscalEletronicaConsultaDTO](./nota-fiscal-eletronica-consulta-dto.md)
- [RecuperarContratoDTO](./recuperar-contrato-dto.md)
- [TipoInstrumentoCobrancaDTO](./tipo-instrumento-cobranca-dto.md)

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
