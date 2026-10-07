---
section_id: "6.4.14"
source_type: "manual"
group: "Serviços de Ata"
title: "Excluir Parte Envolvida em Ata de Registro de Preço"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/partesenvolvidas/{cnpjOrgao}/{codUnidade}/{tipoParteEnvolvida}"
page_start: 262
page_end: 263
status: "normalizado"
reconciliation_status: "openapi-missing"
reconciliation_verified_at: "2026-05-02"
reconciliation_verified_against: "https://pncp.gov.br/pncp-api/v3/api-docs"
---

# Excluir Parte Envolvida em Ata de Registro de Preço

## Resumo
Serviço que recupera os dados de uma parte envolvida específica de uma ata de registro.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/partesenvolvidas/{cnpjOrgao}/{codUnidade}/{tipoParteEnvolvida}`

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
- `sections/6-4-14-excluir-parte-envolvida-em-ata-de-registro-de-preco.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
