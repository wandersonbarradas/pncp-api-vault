---
section_id: "6.5.1"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Inserir Contrato"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/contratos"
page_start: 268
page_end: 273
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Contrato

## Resumo
Serviço que permite incluir um contrato/empenho. Este serviço será acionado por.

## Endpoint
`POST /v1/orgaos/{cnpj}/contratos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |

## Corpo da requisição
Schema OpenAPI: [`IncluirContratoDTO`](../../schemas/incluir-contrato-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `cnpjCompra` | string | sim |
| `anoCompra` | integer (int32) | não |
| `sequencialCompra` | integer (int32) | sim |
| `tipoContratoId` | integer (int64) | sim |
| `numeroContratoEmpenho` | string | sim |
| `anoContrato` | integer (int32) | não |
| `processo` | string | sim |
| `categoriaProcessoId` | integer (int64) | sim |
| `niFornecedor` | string | sim |
| `tipoPessoaFornecedor` | string | sim |
| `nomeRazaoSocialFornecedor` | string | sim |
| `receita` | boolean | sim |
| `codigoUnidade` | string | sim |
| `objetoContrato` | string | sim |
| `valorInicial` | number | sim |
| `numeroParcelas` | integer (int32) | sim |
| `valorParcela` | number | sim |
| `valorGlobal` | number | sim |
| `dataAssinatura` | string (date) | sim |
| `dataVigenciaInicio` | string (date) | sim |
| `dataVigenciaFim` | string (date) | sim |
| `valorAcumulado` | number | não |
| `niFornecedorSubContratado` | string | não |
| `tipoPessoaFornecedorSubContratado` | string | não |
| `nomeRazaoSocialFornecedorSubContratado` | string | não |
| `informacaoComplementar` | string | não |
| `urlCipi` | string | não |
| `identificadorCipi` | string | não |

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
- `sections/6-5-1-inserir-contrato-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
