---
section_id: "6.3.26"
source_type: "manual"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Consultar Fonte Orçamentária da Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria/{fonteOrcamentariaId}"
page_start: 229
page_end: 231
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Fonte Orçamentária da Contratação

## Resumo
Serviço que permite consultar fonte orçamentária da contratação pelo seu código.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria/{fonteOrcamentariaId}`

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
curl -k -X GET "${BASE_URL}/v1/orgaos/10000000000003/compras/2021/1/fonte-orcamentaria/1" \
-H "Accept: */*"
```

## Notas de normalização
- Operação preservada a partir do manual segmentado local; não foi localizada operação equivalente na OpenAPI capturada.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-3-26-consultar-fonte-orcamentaria-da-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
