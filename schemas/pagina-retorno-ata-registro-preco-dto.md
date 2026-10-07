---
title: "PaginaRetornoAtaRegistroPrecoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# PaginaRetornoAtaRegistroPrecoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| data | array[[AtaRegistroPrecoDTO](./ata-registro-preco-dto.md)] | não |  |  |
| empty | boolean | não |  |  |
| numeroPagina | integer (int64) | não |  |  |
| paginasRestantes | integer (int64) | não |  |  |
| totalPaginas | integer (int64) | não |  |  |
| totalRegistros | integer (int64) | não |  |  |

## Schemas Relacionados

- [AtaRegistroPrecoDTO](./ata-registro-preco-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas](../sessoes/ata/consultar-atas-de-registro-de-preco-por-compra.md) - Consultar Atas de Registro de Preço por Compra

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
