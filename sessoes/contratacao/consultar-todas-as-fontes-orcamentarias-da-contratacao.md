---
section_id: "6.3.27"
source_type: "manual"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Consultar Todas as Fontes Orçamentárias da Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria"
page_start: 231
page_end: 233
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Todas as Fontes Orçamentárias da Contratação

## Resumo
Serviço que permite consultar a lista de fontes orçamentárias de uma contratação.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Não se aplica.

## Resposta
A OpenAPI capturada não descreve um schema de resposta de negócio específico para `200`, ou a operação está disponível apenas no manual local.

## Códigos de retorno
Não estruturado na OpenAPI capturada.

## Exemplo cURL
```bash
curl -k -X GET "${BASE_URL}/v1/orgaos/10000000000003/compras/2025/2/fonte-orcamentaria" \
-H "Accept: */*"
```

## Notas de normalização
- Operação preservada a partir do manual segmentado local; não foi localizada operação equivalente na OpenAPI capturada.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-3-27-consultar-todas-as-fontes-orcamentarias-da-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
