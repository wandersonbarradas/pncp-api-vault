---
title: "ConsultarModalidadeFonteOrcamentariaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# ConsultarModalidadeFonteOrcamentariaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataInclusao | string (date-time) | não |  |  |
| fonteOrcamentaria | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |
| modalidadeContratacao | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |

## Schemas Relacionados

- [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md)

## Usado em Respostas

- `200`: [GET /v1/modalidade-fonte-orcamentaria/{modalidadeId}/{fonteOrcamentariaId}](../sessoes/conformidade-modalidade-fonte-orcamentaria/consultar-conformidade-entre-modalidade-de-contratacao-e-fonte-orcamentaria-por-codigo.md) - Consultar conformidade entre modalidade de contratação e Fonte Orçamentaria por código

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
