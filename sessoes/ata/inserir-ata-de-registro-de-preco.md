---
section_id: "6.4.1"
source_type: "manual+openapi"
group: "Serviços de Ata"
title: "Inserir Ata de Registro de Preço"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas"
page_start: 233
page_end: 235
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Ata de Registro de Preço

## Resumo
Serviço que permite inserir uma ata de Registro de Preço no PNCP referente a uma.

## Endpoint
`POST /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `anoCompra` | path | integer | sim |
| `sequencialCompra` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AtaRegistroPrecoInclusaoDTO`](../../schemas/ata-registro-preco-inclusao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `numeroAtaRegistroPreco` | string | não |
| `anoAta` | integer (int32) | sim |
| `dataAssinatura` | string (date) | não |
| `dataVigenciaInicio` | string (date) | não |
| `dataVigenciaFim` | string (date) | não |

## Resposta
Schema OpenAPI: [`AtaRegistroPreco`](../../schemas/ata-registro-preco.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `compra` | Compra | não |
| `numeroAtaRegistroPreco` | string | sim |
| `anoAta` | integer (int32) | sim |
| `dataPublicacaoPncp` | string (date-time) | não |
| `dataAssinatura` | string (date) | não |
| `cancelado` | boolean | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `dataAtualizacaoGlobal` | string (date-time) | não |
| `dataVigenciaInicio` | string (date) | não |
| `dataVigenciaFim` | string (date) | não |
| `sequencialAta` | integer (int32) | não |
| `dataCancelamento` | string (date-time) | não |
| `excluido` | boolean | não |
| `atributoControle` | integer (int64) | não |
| `numeroControlePNCP` | string | não |

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
- `sections/6-4-1-inserir-ata-de-registro-de-preco.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
