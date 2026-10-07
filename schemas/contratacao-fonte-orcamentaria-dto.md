---
title: "ContratacaoFonteOrcamentariaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# ContratacaoFonteOrcamentariaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataInclusao | string (date-time) | não |  |  |
| fonteOrcamentaria | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |
| numeroControlePNCPCompra | string | não |  |  |

## Schemas Relacionados

- [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria](../sessoes/contratacao/consultar-todas-as-fontes-orcamentarias-da-contratacao.md) - Consultar Todas as Fontes Orçamentárias da Contratação
- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria/{fonteOrcamentariaId}](../sessoes/contratacao/consultar-fonte-orcamentaria-da-contratacao.md) - Consultar Fonte Orçamentária da Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
