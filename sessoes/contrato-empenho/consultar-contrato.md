---
section_id: "6.5.8"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Consultar Contrato"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}"
page_start: 288
page_end: 292
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Contrato

## Resumo
Serviço que permite consultar um contrato/empenho específico.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`RecuperarContratoDTO`](../../schemas/recuperar-contrato-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `numeroControlePNCP` | string | não |
| `anoContrato` | integer (int32) | não |
| `tipoContrato` | TipoContrato | não |
| `numeroContratoEmpenho` | string | não |
| `dataAssinatura` | string (date) | não |
| `dataVigenciaInicio` | string (date) | não |
| `dataVigenciaFim` | string (date) | não |
| `dataAtualizacao` | string (date-time) | não |
| `niFornecedor` | string | não |
| `tipoPessoa` | string | não |
| `orgaoEntidade` | RecuperarOrgaoEntidadeDTO | não |
| `categoriaProcesso` | Categoria | não |
| `dataPublicacaoPncp` | string (date-time) | não |
| `informacaoComplementar` | string | não |
| `sequencialContrato` | integer (int32) | não |
| `unidadeOrgao` | RecuperarUnidadeOrgaoDTO | não |
| `processo` | string | não |
| `unidadeSubRogada` | RecuperarUnidadeOrgaoDTO | não |
| `orgaoSubRogado` | RecuperarOrgaoEntidadeDTO | não |
| `nomeRazaoSocialFornecedor` | string | não |
| `tipoPessoaSubContratada` | string | não |
| `numeroRetificacao` | integer (int32) | não |
| `valorInicial` | number | não |
| `valorParcela` | number | não |
| `valorGlobal` | number | não |
| `valorAcumulado` | number | não |
| `dataAtualizacaoGlobal` | string (date-time) | não |
| `identificadorCipi` | string | não |
| `urlCipi` | string | não |
| `receita` | boolean | não |
| `numeroParcelas` | integer (int32) | não |
| `niFornecedorSubContratado` | string | não |
| `nomeFornecedorSubContratado` | string | não |
| `objetoContrato` | string | não |
| `codigoPaisFornecedor` | string | não |
| `usuarioNome` | string | não |
| `numeroControlePncpCompra` | string | não |

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
- `sections/6-5-8-consultar-contrato-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
