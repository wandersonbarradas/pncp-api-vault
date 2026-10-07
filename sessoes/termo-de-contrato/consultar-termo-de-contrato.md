---
section_id: "6.6.4"
source_type: "manual+openapi"
group: "Serviço de Termo de Contrato"
title: "Consultar Termo de Contrato"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}"
page_start: 348
page_end: 350
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Termo de Contrato

## Resumo
Serviço que permite recuperar um termo de contrato.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `sequencialTermoContrato` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`RecuperarTermoContratoDTO`](../../schemas/recuperar-termo-contrato-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `tipoTermoContratoNome` | string | não |
| `unidade` | RecuperarUnidadeOrgaoDTO | não |
| `dataAssinatura` | string (date) | não |
| `dataVigenciaInicio` | string (date) | não |
| `dataVigenciaFim` | string (date) | não |
| `dataAtualizacao` | string (date-time) | não |
| `fornecedor` | RecuperarFornecedorDTO | não |
| `niFornecedor` | string | não |
| `tipoPessoa` | string | não |
| `fornecedorSubContratado` | RecuperarFornecedorDTO | não |
| `orgaoEntidade` | RecuperarOrgaoEntidadeDTO | não |
| `dataInclusao` | string (date-time) | não |
| `dataPublicacaoPncp` | string (date-time) | não |
| `informacaoComplementar` | string | não |
| `processo` | string | não |
| `nomeRazaoSocialFornecedor` | string | não |
| `sequencialTermoContrato` | integer (int32) | não |
| `numeroTermoContrato` | string | não |
| `unidadeSubrogada` | RecuperarUnidadeOrgaoDTO | não |
| `tipoPessoaSubContratada` | string | não |
| `valorParcela` | number | não |
| `valorGlobal` | number | não |
| `informativoObservacao` | string | não |
| `orgaoSubrogado` | RecuperarOrgaoEntidadeDTO | não |
| `valorAcrescido` | number | não |
| `fundamentoLegal` | string | não |
| `objetoTermoContrato` | string | não |
| `qualificacaoReajuste` | boolean | não |
| `prazoAditadoDias` | integer (int32) | não |
| `numeroParcelas` | integer (int32) | não |
| `niFornecedorSubContratado` | string | não |
| `nomeFornecedorSubContratado` | string | não |
| `qualificacaoFornecedor` | boolean | não |
| `qualificacaoVigencia` | boolean | não |
| `qualificacaoAcrescimoSupressao` | boolean | não |

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
- `sections/6-6-4-consultar-um-termo-de-contrato.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
