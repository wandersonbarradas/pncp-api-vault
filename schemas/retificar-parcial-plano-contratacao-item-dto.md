---
title: "RetificarParcialPlanoContratacaoItemDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RetificarParcialPlanoContratacaoItemDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| catalogo | integer (int64) | não |  |  |
| categoriaItemPca | integer (int64) | não |  |  |
| classificacaoCatalogo | string | não |  | 1, 2 |
| classificacaoSuperiorCodigo | string | não |  |  |
| classificacaoSuperiorNome | string | não |  |  |
| codigoItem | string | não |  |  |
| dataDesejada | string (date) | não |  |  |
| descricao | string | não |  |  |
| grupoContratacaoCodigo | string | não |  |  |
| grupoContratacaoNome | string | não |  |  |
| justificativa | string | não |  |  |
| numeroItem | integer (int32) | não |  |  |
| pdmCodigo | string | não |  |  |
| pdmDescricao | string | não |  |  |
| quantidade | number | não |  |  |
| unidadeFornecimento | string | não |  |  |
| unidadeRequisitante | string | não |  |  |
| valorOrcamentoExercicio | number | não |  |  |
| valorTotal | number | não |  |  |
| valorUnitario | number | não |  |  |

## Usado como Corpo de Requisição

- [PATCH /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/plano-de-contratacao/retificar-parcialmente-item-de-plano-de-contratacao.md) - Retificar Parcialmente item de Plano de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
