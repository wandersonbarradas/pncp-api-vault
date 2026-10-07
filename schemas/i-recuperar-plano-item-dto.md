---
title: "IRecuperarPlanoItemDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IRecuperarPlanoItemDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoPca | integer (int32) | não |  |  |
| catalogoId | integer (int32) | não |  |  |
| categoriaItemPcaNome | string | não |  |  |
| categoriaItemPcaid | integer (int32) | não |  |  |
| classificacaoCatalogoId | integer (int32) | não |  |  |
| classificacaoSuperiorCodigo | string | não |  |  |
| classificacaoSuperiorNome | string | não |  |  |
| cnpj | string | não |  |  |
| codigoItem | string | não |  |  |
| codigoUnidade | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataDesejada | string (date) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| descricao | string | não |  |  |
| grupoContratacaoCodigo | string | não |  |  |
| grupoContratacaoNome | string | não |  |  |
| nomeCatalogo | string | não |  |  |
| nomeClassificacao | string | não |  |  |
| nomeUnidade | string | não |  |  |
| numeroItem | integer (int32) | não |  |  |
| pdmCodigo | string | não |  |  |
| pdmDescricao | string | não |  |  |
| quantidade | number | não |  |  |
| sequencialPca | integer (int32) | não |  |  |
| unidadeFornecimento | string | não |  |  |
| unidadeRequisitante | string | não |  |  |
| valorOrcamentoExercicio | number | não |  |  |
| valorTotal | number | não |  |  |
| valorUnitario | number | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens](../sessoes/plano-de-contratacao/consultar-itens-do-plano-de-contratacao.md) - Consultar Itens do Plano de Contratação
- `200`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/contratacao](../sessoes/plano-de-contratacao/retornar-itens-de-plano-de-contratacao-por-numero-da-contratacao.md) - Retornar Itens de Plano de Contratação por número da Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
