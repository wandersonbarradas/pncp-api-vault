---
title: "AmparoLegalDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AmparoLegalDTO

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
| statusAtivo | boolean | não |  |  |
| tipoAmparoLegal | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |

## Schemas Relacionados

- [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md)

## Usado em Respostas

- `200`: [GET /v1/amparos-legais/{id}](../sessoes/amparo-legal/consultar-amparo-legal-por-codigo.md) - Consultar amparo legal por código

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
