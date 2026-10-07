---
title: "PaginaRetornoPlanoContratacaoComItensDoUsuarioDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# PaginaRetornoPlanoContratacaoComItensDoUsuarioDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 3 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| data | array[[PlanoContratacaoComItensDoUsuarioDTO](./plano-contratacao-com-itens-do-usuario-dto.md)] | não |  |  |
| empty | boolean | não |  |  |
| numeroPagina | integer (int64) | não |  |  |
| paginasRestantes | integer (int64) | não |  |  |
| totalPaginas | integer (int64) | não |  |  |
| totalRegistros | integer (int64) | não |  |  |

## Schemas Relacionados

- [PlanoContratacaoComItensDoUsuarioDTO](./plano-contratacao-com-itens-do-usuario-dto.md)

## Usado em Respostas

- `200`: [GET /v1/pca/](../../consulta/plano-de-contratacao/consultar-itens-de-pca-por-ano-do-pca-e-c-digo-de-classifica-o-superior.md) - Consultar Itens de PCA por Ano do PCA e Código de Classificação Superior
- `200`: [GET /v1/pca/atualizacao](../../consulta/plano-de-contratacao/consultar-pca-por-data-de-atualiza-o-global.md) - Consultar PCA por Data de Atualização Global
- `200`: [GET /v1/pca/usuario](../../consulta/plano-de-contratacao/consultar-itens-de-pca-por-ano-do-pca-id-usuario-e-c-digo-de-classifica-o-superior.md) - Consultar Itens de PCA por Ano do PCA, IdUsuario e Código de Classificação Superior

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
