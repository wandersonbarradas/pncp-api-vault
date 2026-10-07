---
title: "NotaFiscalEletronicaConsultaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# NotaFiscalEletronicaConsultaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| chave | string | não |  |  |
| codigoOrgaoDestinatario | string | não |  |  |
| codigoOrgaoSuperiorDestinatario | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataEmissao | string | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataTipoEventoMaisRecente | string | não |  |  |
| eventos | array[[EventoNotaFiscalConsultaDTO](./evento-nota-fiscal-consulta-dto.md)] | não |  |  |
| instrumentoCobrancaId | integer (int64) | não |  |  |
| itens | array[[ItemNotaFiscalConsultaDTO](./item-nota-fiscal-consulta-dto.md)] | não |  |  |
| nfTransparenciaID | integer (int64) | não |  |  |
| niEmitente | string | não |  |  |
| nomeEmitente | string | não |  |  |
| nomeMunicipioEmitente | string | não |  |  |
| nomeOrgaoDestinatario | string | não |  |  |
| nomeOrgaoSuperiorDestinatario | string | não |  |  |
| numero | integer (int64) | não |  |  |
| serie | integer (int32) | não |  |  |
| tipoEventoMaisRecente | string | não |  |  |
| valorNotaFiscal | string | não |  |  |

## Schemas Relacionados

- [EventoNotaFiscalConsultaDTO](./evento-nota-fiscal-consulta-dto.md)
- [ItemNotaFiscalConsultaDTO](./item-nota-fiscal-consulta-dto.md)

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
