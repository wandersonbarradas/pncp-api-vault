---
section_id: "6.5.21"
source_type: "manual"
group: "Serviços de Contrato/Empenho"
title: "Consultar Empenho pelo Número Sequencial"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos/{sequencialEmpenho}"
page_start: 331
page_end: 334
status: "normalizado"
reconciliation_status: "openapi-missing"
reconciliation_verified_at: "2026-05-02"
reconciliation_verified_against: "https://pncp.gov.br/pncp-api/v3/api-docs"
---

# Consultar Empenho pelo Número Sequencial

## Resumo
Serviço que permite consultar um empenho específico pertencente a um contra-.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos/{sequencialEmpenho}`

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
curl -k -X GET "${BASE_URL}/v1/orgaos/10000000000003/contratos/2025/1/empenhos/1" \
-H "Accept: */*"
```

## Notas de normalização
- Operação preservada a partir do manual segmentado local; não foi localizada operação equivalente na OpenAPI capturada.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-5-21-consultar-empenho-pelo-numero-sequencial.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
