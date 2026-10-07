---
section_id: "6.3.18"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Consultar Resultado de Item de Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados/{sequencialResultado}"
page_start: 214
page_end: 218
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Resultado de Item de Contratação

## Resumo
Serviço para consultar os dados de um resultado específico de um item da contratação.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados/{sequencialResultado}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `numeroItem` | path | integer | sim |
| `sequencialResultado` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`RecuperarCompraItemResultadoDTO`](../../schemas/recuperar-compra-item-resultado-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `numeroControlePNCPCompra` | string | não |
| `dataAtualizacao` | string (date-time) | não |
| `niFornecedor` | string | não |
| `tipoPessoa` | string | não |
| `dataInclusao` | string (date-time) | não |
| `numeroItem` | integer (int32) | não |
| `valorTotalHomologado` | number | não |
| `timezoneCotacaoMoedaEstrangeira` | string | não |
| `moedaEstrangeira` | MoedaResumidoDTO | não |
| `valorNominalMoedaEstrangeira` | number | não |
| `dataCotacaoMoedaEstrangeira` | string (date-time) | não |
| `nomeRazaoSocialFornecedor` | string | não |
| `codigoPais` | string | não |
| `porteFornecedorId` | string | não |
| `quantidadeHomologada` | number | não |
| `valorUnitarioHomologado` | number | não |
| `percentualDesconto` | number | não |
| `amparoLegalMargemPreferencia` | DominioGenericoResumidoDTO | não |
| `amparoLegalCriterioDesempate` | DominioGenericoResumidoDTO | não |
| `paisOrigemProdutoServico` | PaisResumidoDTO | não |
| `indicadorSubcontratacao` | boolean | não |
| `ordemClassificacaoSrp` | integer (int32) | não |
| `dataResultado` | string (date) | não |
| `motivoCancelamento` | string | não |
| `dataCancelamento` | string (date-time) | não |
| `porteFornecedorNome` | string | não |
| `sequencialResultado` | integer (int32) | não |
| `naturezaJuridicaNome` | string | não |
| `situacaoCompraItemResultadoId` | string | não |
| `situacaoCompraItemResultadoNome` | string | não |
| `aplicacaoMargemPreferencia` | boolean | não |
| `aplicacaoBeneficioMeEpp` | boolean | não |
| `aplicacaoCriterioDesempate` | boolean | não |
| `naturezaJuridicaId` | string | não |

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
- `sections/6-3-18-consultar-um-resultado-especifico-de-item-de-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
