---
title: "PaginaRetornoRecuperarCompraPublicacaoDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# PaginaRetornoRecuperarCompraPublicacaoDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 3 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| data | array[[RecuperarCompraPublicacaoDTO](./recuperar-compra-publicacao-dto.md)] | não |  |  |
| empty | boolean | não |  |  |
| numeroPagina | integer (int64) | não |  |  |
| paginasRestantes | integer (int64) | não |  |  |
| totalPaginas | integer (int64) | não |  |  |
| totalRegistros | integer (int64) | não |  |  |

## Schemas Relacionados

- [RecuperarCompraPublicacaoDTO](./recuperar-compra-publicacao-dto.md)

## Usado em Respostas

- `200`: [GET /v1/contratacoes/atualizacao](../../consulta/contratacao/consultar-contrata-es-por-data-de-atualiza-o-global.md) - Consultar Contratações por Data de Atualização Global
- `200`: [GET /v1/contratacoes/proposta](../../consulta/contratacao/consultar-contrata-es-com-recebimento-de-propostas-aberto.md) - Consultar Contratações com Recebimento de Propostas Aberto
- `200`: [GET /v1/contratacoes/publicacao](../../consulta/contratacao/consultar-contrata-es-por-data-de-publica-o.md) - Consultar Contratações por Data de Publicação

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
