---
title: "ConsultarModalidadeCriterioJulgamentoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# ConsultarModalidadeCriterioJulgamentoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| criterioJulgamento | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| modalidadeContratacao | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |

## Schemas Relacionados

- [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md)

## Usado em Respostas

- `200`: [GET /v1/modalidade-criterio-julgamento/{modalidadeId}/{criterioJulgamentoId}](../sessoes/conformidade-modalidade-criterio-de-julgamento/consultar-conformidade-entre-modalidade-de-contratacao-e-criterio-de-julgamento-por-codigo.md) - Consultar conformidade entre modalidade de contratação e critério de julgamento por código

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
