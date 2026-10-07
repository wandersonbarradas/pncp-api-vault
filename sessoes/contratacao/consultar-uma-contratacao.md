---
section_id: "6.3.5"
source_type: "manual"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Consultar uma Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}"
page_start: 161
page_end: 165
status: "normalizado"
reconciliation_status: "openapi-missing"
---

# Consultar uma Contratação

## Resumo
Serviço que permite consultar uma contratação.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`

## Superfície pública recomendada

Para leitura pública da contratação publicada, prefira a operação da API de Consulta:

`GET /api/consulta/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`

Arquivo relacionado: [consultar-contrata-o.md](../../consulta/contratacao/consultar-contrata-o.md).

Esta rota de `api/pncp/v1` permanece preservada para rastreabilidade com o manual, mas está marcada como `openapi-missing` na OpenAPI principal capturada.

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Não se aplica.

## Resposta
A OpenAPI capturada não descreve um schema de resposta de negócio específico para `200`, ou a operação está disponível apenas no manual local.

## Códigos de retorno
Não estruturado na OpenAPI capturada.

## Exemplo cURL
Exemplo não disponível na fonte consolidada atual.

## Notas de normalização
- Operação preservada a partir do manual segmentado local; não foi localizada operação equivalente na OpenAPI capturada.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-3-5-consultar-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
