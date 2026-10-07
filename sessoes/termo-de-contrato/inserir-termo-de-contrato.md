---
section_id: "6.6.1"
source_type: "manual+openapi"
group: "Serviço de Termo de Contrato"
title: "Inserir Termo de Contrato"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos"
page_start: 338
page_end: 341
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Termo de Contrato

## Resumo
Serviço que permite inserir um termo de contrato a um contrato. O termo pode ser um.

## Endpoint
`POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`IncluirTermoContratoDTO`](../../schemas/incluir-termo-contrato-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `tipoTermoContratoId` | integer (int64) | sim |
| `numeroTermoContrato` | string | não |
| `objetoTermoContrato` | string | sim |
| `qualificacaoAcrescimoSupressao` | boolean | sim |
| `qualificacaoVigencia` | boolean | sim |
| `qualificacaoFornecedor` | boolean | sim |
| `qualificacaoInformativo` | boolean | sim |
| `qualificacaoReajuste` | boolean | sim |
| `dataAssinatura` | string | sim |
| `niFornecedor` | string | não |
| `tipoPessoaFornecedor` | string | não |
| `nomeRazaoSocialFornecedor` | string | não |
| `niFornecedorSubContratado` | string | não |
| `tipoPessoaFornecedorSubContratado` | string | não |
| `nomeRazaoSocialFornecedorSubContratado` | string | não |
| `informativoObservacao` | string | não |
| `fundamentoLegal` | string | não |
| `valorAcrescido` | number | não |
| `numeroParcelas` | integer (int32) | não |
| `valorParcela` | number | não |
| `valorGlobal` | number | não |
| `prazoAditadoDias` | integer (int32) | não |
| `dataVigenciaInicio` | string (date) | não |
| `dataVigenciaFim` | string (date) | não |

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
- `sections/6-6-1-inserir-termo-de-contrato.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
