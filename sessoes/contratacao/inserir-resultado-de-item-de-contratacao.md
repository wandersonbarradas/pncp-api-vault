---
section_id: "6.3.15"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Inserir Resultado de Item de Contratação"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados"
page_start: 196
page_end: 203
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Resultado de Item de Contratação

## Resumo
Serviço para inserir o resultado do item de uma contratação. O resultado possui as.

## Endpoint
`POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `numeroItem` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`IncluirCompraItemResultadoDTO`](../../schemas/incluir-compra-item-resultado-dto.md)

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
- `sections/6-3-15-inserir-resultado-do-item-de-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
