---
section_id: "6.4.6"
source_type: "manual+openapi"
group: "Serviços de Ata"
title: "Consultar Ata de Registro de Preço"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}"
page_start: 246
page_end: 247
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Ata de Registro de Preço

## Resumo
Serviço que permite recuperar uma ata específica.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `anoCompra` | path | integer | sim |
| `sequencialCompra` | path | integer | sim |
| `sequencialAta` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`RecuperarAtaRegistroPrecoDTO`](../../schemas/recuperar-ata-registro-preco-dto.md)

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
- `sections/6-4-6-consultar-ata-de-registro-de-preco.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
