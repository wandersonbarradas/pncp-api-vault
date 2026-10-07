---
section_id: "6.4.2"
source_type: "manual+openapi"
group: "Serviços de Ata"
title: "Retificar Ata de Registro de Preço"
method: "PUT"
endpoint: "/v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}"
page_start: 236
page_end: 240
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Ata de Registro de Preço

## Resumo
Serviço que permite retificar os dados de uma ata de Registro de Preço.

## Endpoint
`PUT /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `anoCompra` | path | integer | sim |
| `sequencialCompra` | path | integer | sim |
| `sequencialAta` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AtaRegistroPrecoAlteracaoDTO`](../../schemas/ata-registro-preco-alteracao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `numeroAtaRegistroPreco` | string | sim |
| `anoAta` | integer (int32) | sim |
| `dataAssinatura` | string (date) | sim |
| `dataVigenciaInicio` | string (date) | sim |
| `dataVigenciaFim` | string (date) | sim |
| `cancelado` | boolean | sim |
| `dataCancelamento` | string (date-time) | não |
| `justificativa` | string | sim |

## Resposta
Schema OpenAPI: [`AtaRegistroPrecoDTO`](../../schemas/ata-registro-preco-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `numeroAtaRegistroPreco` | string | não |
| `anoAta` | integer (int32) | não |
| `dataAssinatura` | string (date) | não |
| `dataVigenciaInicio` | string (date) | não |
| `dataVigenciaFim` | string (date) | não |
| `dataCancelamento` | string (date-time) | não |
| `cancelado` | boolean | não |
| `dataPublicacaoPncp` | string (date-time) | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `dataAtualizacaoGlobal` | string (date-time) | não |
| `sequencialAta` | integer (int32) | não |
| `numeroControlePNCP` | string | não |
| `orgaoEntidade` | RecuperarOrgaoEntidadeDTO | não |
| `orgaoSubRogado` | RecuperarOrgaoEntidadeDTO | não |
| `unidadeOrgao` | RecuperarUnidadeOrgaoDTO | não |
| `unidadeSubRogada` | RecuperarUnidadeOrgaoDTO | não |
| `modalidadeNome` | string | não |
| `objetoCompra` | string | não |
| `informacaoComplementarCompra` | string | não |
| `usuarioNome` | string | não |

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
- `sections/6-4-2-retificar-ata-de-registro-de-preco.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
