---
section_id: "6.3.3"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Retificar parcialmente uma Contratação"
method: "PATCH"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}"
page_start: 156
page_end: 159
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar parcialmente uma Contratação

## Resumo
Serviço que permite retificar parcialmente os dados de uma contratação. Este serviço.

## Endpoint
`PATCH /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarCompraParcialDTO`](../../schemas/alterar-compra-parcial-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `tipoInstrumentoConvocatorioId` | integer (int64) | não |
| `modalidadeId` | integer (int64) | não |
| `modoDisputaId` | integer (int64) | não |
| `numeroCompra` | string | não |
| `numeroProcesso` | string | não |
| `situacaoCompraId` | string | não |
| `objetoCompra` | string | não |
| `informacaoComplementar` | string | não |
| `amparoLegalId` | integer (int64) | não |
| `cnpjOrgaoSubRogado` | string | não |
| `codigoUnidadeSubRogada` | string | não |
| `srp` | boolean | não |
| `dataAberturaProposta` | string (date-time) | não |
| `dataEncerramentoProposta` | string (date-time) | não |
| `codigoUnidadeCompradora` | string | não |
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
- `sections/6-3-3-retificar-parcialmente-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
