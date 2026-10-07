---
section_id: "6.7.6"
source_type: "manual+openapi"
group: "Serviços de Plano de Contratações"
title: "Consultar Plano de Contratação Consolidado"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/consolidado"
page_start: 371
page_end: 373
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Plano de Contratação Consolidado

## Resumo
Contratações de uma Unidade e Ano).

## Endpoint
`GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/consolidado`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`PlanoSequencialConsolidadoDTO`](../../schemas/plano-sequencial-consolidado-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `valorTotal` | number | não |
| `quantidade` | number | não |
| `dataAtualizacao` | string (date-time) | não |
| `dataAtualizacaoGlobalPCA` | string (date-time) | não |
| `dataPublicacaoPncp` | string (date-time) | não |
| `codigoUnidade` | string | não |
| `nomeUnidade` | string | não |
| `anoPca` | integer (int32) | não |
| `cnpj` | string | não |
| `razaoSocial` | string | não |
| `numeroControlePNCP` | string | não |
| `usuario` | string | não |
| `sequencialPca` | integer (int32) | não |
| `municipio` | string | não |
| `uf` | string | não |

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
- `sections/6-7-6-consultar-plano-de-contratacao-consolidado-plano-de.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
