---
title: "TipoInstrumentoConvocatorioModoDisputaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# TipoInstrumentoConvocatorioModoDisputaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataInclusao | string (date-time) | não |  |  |
| modoDisputa | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |
| tipoInstrumentoConvocatorio | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |

## Schemas Relacionados

- [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md)

## Usado em Respostas

- `200`: [GET /v1/tipo-instrumento-convocatorio-modo-disputa/{tipoInstrumentoConvocatorioId}/{modoDisputaId}](../sessoes/conformidade-instrumento-convocatorio-modo-de-disputa/consultar-conformidade-entre-instrumentos-convocatorios-e-modos-de-disputa-por-codigo.md) - Consultar conformidade entre instrumentos convocatórios e modos de disputa por código

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
