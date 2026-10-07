---
title: "ConsultarAmparoLegalModalidadeInstrumentoConvocatorioDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# ConsultarAmparoLegalModalidadeInstrumentoConvocatorioDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| amparoLegal | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| modalidade | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |
| tipoInstrumentoConvocatorio | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |

## Schemas Relacionados

- [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md)

## Usado em Respostas

- `200`: [GET /v1/instrumento-convocatorio-modalidade-amparo-legal](../sessoes/conformidade-instrumento-convocatorio-modalidade-amparo-legal/consultar-conformidade-instrumento-convocatorio-modalidade-de-contratacao-e-amparo-legal.md) - Consultar Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal
- `200`: [GET /v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}](../sessoes/conformidade-instrumento-convocatorio-modalidade-amparo-legal/consultar-conformidade-instrumento-convocatorio-modalidade-de-contratacao-e-amparo-legal-por-codigo.md) - Consultar Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal por código

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
