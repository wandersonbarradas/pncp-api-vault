---
section_id: "6.5.22"
source_type: "manual"
group: "Serviços de Contrato/Empenho"
title: "Consultar Empenhos"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos"
page_start: 334
page_end: 338
status: "normalizado"
reconciliation_status: "openapi-missing"
reconciliation_verified_at: "2026-05-02"
reconciliation_verified_against: "https://pncp.gov.br/pncp-api/v3/api-docs"
---

# Consultar Empenhos

## Resumo
Serviço que permite consultar empenhos pertencentes a um contrato/empenho.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos`

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
curl -k -X GET "${BASE_URL}/v1/orgaos/10000000000003/contratos/2025/1/empenhos" \
-H "Accept: */*"
```

## Notas de normalização
- Operação preservada a partir do manual segmentado local; não foi localizada operação equivalente na OpenAPI capturada.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-5-22-consultar-empenhos.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
