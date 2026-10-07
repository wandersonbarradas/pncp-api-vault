---
title: "AlterarCompraItemResultadoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarCompraItemResultadoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| amparoLegalCriterioDesempateId | integer (int64) | não |  |  |
| amparoLegalMargemPreferenciaId | integer (int64) | não |  |  |
| aplicacaoBeneficioMeEpp | boolean | não |  |  |
| aplicacaoCriterioDesempate | boolean | não |  |  |
| aplicacaoMargemPreferencia | boolean | não |  |  |
| codigoPais | string | não |  |  |
| dataCancelamento | string | não |  |  |
| dataCotacaoMoedaEstrangeira | string (date-time) | não |  |  |
| dataResultado | string (date) | não |  |  |
| indicadorSubcontratacao | boolean | não |  |  |
| justificativa | string | não |  |  |
| motivoCancelamento | string | não |  |  |
| naturezaJuridicaId | string | não |  |  |
| niFornecedor | string | não |  |  |
| nomeRazaoSocialFornecedor | string | não |  |  |
| ordemClassificacaoSrp | integer (int32) | não |  |  |
| paisOrigemProdutoServicoId | string | não |  |  |
| percentualDesconto | number | não |  |  |
| porteFornecedorId | string | não |  | 1, 2, 3, 4, 5 |
| quantidadeHomologada | number | não |  |  |
| simboloMoedaEstrangeira | string | não |  |  |
| situacaoCompraItemResultadoId | integer (int64) | não |  |  |
| timezoneCotacaoMoedaEstrangeira | string | não |  |  |
| tipoPessoaId | string | não |  |  |
| valorNominalMoedaEstrangeira | number | não |  |  |
| valorTotalHomologado | number | não |  |  |
| valorUnitarioHomologado | number | não |  |  |

## Usado como Corpo de Requisição

- [PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados/{sequencialResultado}](../sessoes/contratacao/retificar-resultado-de-item-de-contratacao.md) - Retificar Resultado de Item de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
