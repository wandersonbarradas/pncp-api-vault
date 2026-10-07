---
title: "RecuperarCompraItemResultadoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarCompraItemResultadoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| amparoLegalCriterioDesempate | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |
| amparoLegalMargemPreferencia | [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md) | não |  |  |
| aplicacaoBeneficioMeEpp | boolean | não |  |  |
| aplicacaoCriterioDesempate | boolean | não |  |  |
| aplicacaoMargemPreferencia | boolean | não |  |  |
| codigoPais | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataCancelamento | string (date-time) | não |  |  |
| dataCotacaoMoedaEstrangeira | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataResultado | string (date) | não |  |  |
| indicadorSubcontratacao | boolean | não |  |  |
| moedaEstrangeira | [MoedaResumidoDTO](./moeda-resumido-dto.md) | não |  |  |
| motivoCancelamento | string | não |  |  |
| naturezaJuridicaId | string | não |  |  |
| naturezaJuridicaNome | string | não |  |  |
| niFornecedor | string | não |  |  |
| nomeRazaoSocialFornecedor | string | não |  |  |
| numeroControlePNCPCompra | string | não |  |  |
| numeroItem | integer (int32) | não |  |  |
| ordemClassificacaoSrp | integer (int32) | não |  |  |
| paisOrigemProdutoServico | [PaisResumidoDTO](./pais-resumido-dto.md) | não |  |  |
| percentualDesconto | number | não |  |  |
| porteFornecedorId | string | não |  | 1, 2, 3, 4, 5 |
| porteFornecedorNome | string | não |  |  |
| quantidadeHomologada | number | não |  |  |
| sequencialResultado | integer (int32) | não |  |  |
| situacaoCompraItemResultadoId | string | não |  | 1, 2 |
| situacaoCompraItemResultadoNome | string | não |  |  |
| timezoneCotacaoMoedaEstrangeira | string | não |  |  |
| tipoPessoa | string | não |  | PJ, PF, PE |
| valorNominalMoedaEstrangeira | number | não |  |  |
| valorTotalHomologado | number | não |  |  |
| valorUnitarioHomologado | number | não |  |  |

## Schemas Relacionados

- [DominioGenericoResumidoDTO](./dominio-generico-resumido-dto.md)
- [MoedaResumidoDTO](./moeda-resumido-dto.md)
- [PaisResumidoDTO](./pais-resumido-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados](../sessoes/contratacao/consultar-resultados-de-item-de-contratacao.md) - Consultar Resultados de Item de Contratação
- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados/{sequencialResultado}](../sessoes/contratacao/consultar-resultado-de-item-de-contratacao.md) - Consultar Resultado de Item de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
