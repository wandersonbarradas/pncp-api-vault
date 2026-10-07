---
section_id: "6.3.2"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Retificar Contratação"
method: "PUT"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}"
page_start: 152
page_end: 156
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Contratação

## Resumo
Serviço que permite retificar os dados de uma contratação. Este serviço será acionado.

## Endpoint
`PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarCompraDTO`](../../schemas/alterar-compra-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `tipoInstrumentoConvocatorioId` | integer (int64) | sim |
| `modalidadeId` | integer (int64) | sim |
| `modoDisputaId` | integer (int64) | sim |
| `numeroCompra` | string | sim |
| `numeroProcesso` | string | sim |
| `situacaoCompraId` | string | sim |
| `objetoCompra` | string | sim |
| `informacaoComplementar` | string | não |
| `amparoLegalId` | integer (int64) | sim |
| `cnpjOrgaoSubRogado` | string | não |
| `codigoUnidadeSubRogada` | string | não |
| `srp` | boolean | sim |
| `dataAberturaProposta` | string (date-time) | não |
| `dataEncerramentoProposta` | string (date-time) | não |
| `codigoUnidadeCompradora` | string | sim |
| `linkSistemaOrigem` | string | não |
| `linkProcessoEletronico` | string | não |
| `justificativa` | string | não |
| `justificativaPresencial` | string | não |

## Resposta
A OpenAPI capturada não descreve um schema de resposta de negócio específico para `200`, ou a operação está disponível apenas no manual local.

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
- `sections/6-3-2-retificar-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
