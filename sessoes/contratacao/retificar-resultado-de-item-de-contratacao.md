---
section_id: "6.3.16"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Retificar Resultado de Item de Contratação"
method: "PUT"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados/{sequencialResultado}"
page_start: 203
page_end: 210
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Resultado de Item de Contratação

## Resumo
Serviço para retificar um resultado do item de uma contratação, ou para alterar a.

## Endpoint
`PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados/{sequencialResultado}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `numeroItem` | path | integer | sim |
| `sequencialResultado` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarCompraItemResultadoDTO`](../../schemas/alterar-compra-item-resultado-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `quantidadeHomologada` | number | não |
| `valorUnitarioHomologado` | number | não |
| `valorTotalHomologado` | number | não |
| `percentualDesconto` | number | não |
| `aplicacaoMargemPreferencia` | boolean | não |
| `amparoLegalMargemPreferenciaId` | integer (int64) | não |
| `aplicacaoBeneficioMeEpp` | boolean | não |
| `aplicacaoCriterioDesempate` | boolean | não |
| `amparoLegalCriterioDesempateId` | integer (int64) | não |
| `simboloMoedaEstrangeira` | string | não |
| `dataCotacaoMoedaEstrangeira` | string (date-time) | não |
| `timezoneCotacaoMoedaEstrangeira` | string | não |
| `valorNominalMoedaEstrangeira` | number | não |
| `paisOrigemProdutoServicoId` | string | não |
| `tipoPessoaId` | string | não |
| `niFornecedor` | string | não |
| `nomeRazaoSocialFornecedor` | string | não |
| `porteFornecedorId` | string | não |
| `codigoPais` | string | não |
| `indicadorSubcontratacao` | boolean | não |
| `ordemClassificacaoSrp` | integer (int32) | não |
| `dataResultado` | string (date) | não |
| `naturezaJuridicaId` | string | não |
| `situacaoCompraItemResultadoId` | integer (int64) | não |
| `justificativa` | string | não |
| `dataCancelamento` | string | não |
| `motivoCancelamento` | string | não |

## Resposta
Schema OpenAPI: `object`

## Códigos de retorno

| HTTP |
| --- |
| `400` |
| `422` |
| `204` |
| `500` |
| `401` |
| `200` |

## Exemplo cURL
Exemplo não disponível na fonte consolidada atual.

## Notas de normalização
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-3-16-retificar-resultado-do-item-de-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
