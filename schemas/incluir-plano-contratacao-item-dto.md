---
title: "IncluirPlanoContratacaoItemDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IncluirPlanoContratacaoItemDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| catalogo | integer (int64) | sim |  |  |
| categoriaItemPca | integer (int64) | sim |  |  |
| classificacaoCatalogo | string | sim |  | 1, 2 |
| classificacaoSuperiorCodigo | string | sim |  |  |
| classificacaoSuperiorNome | string | sim |  |  |
| codigoItem | string | não |  |  |
| dataDesejada | string (date) | sim |  |  |
| descricao | string | não |  |  |
| grupoContratacaoCodigo | string | não |  |  |
| grupoContratacaoNome | string | não |  |  |
| numeroItem | integer (int32) | sim |  |  |
| pdmCodigo | string | não |  |  |
| pdmDescricao | string | não |  |  |
| quantidade | number | sim |  |  |
| unidadeFornecimento | string | sim |  |  |
| unidadeRequisitante | string | não |  |  |
| valorOrcamentoExercicio | number | sim |  |  |
| valorTotal | number | sim |  |  |
| valorUnitario | number | sim |  |  |

## Usado como Corpo de Requisição

- [POST /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens](../sessoes/plano-de-contratacao/inserir-itens-de-plano-de-contratacao.md) - Inserir itens de Plano de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
