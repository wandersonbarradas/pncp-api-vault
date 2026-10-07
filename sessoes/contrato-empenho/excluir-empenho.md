---
section_id: "6.5.20"
source_type: "manual"
group: "Serviços de Contrato/Empenho"
title: "Excluir Empenho"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/contratos"
page_start: 330
page_end: 331
status: "normalizado"
reconciliation_status: "openapi-missing"
reconciliation_verified_at: "2026-05-02"
reconciliation_verified_against: "https://pncp.gov.br/pncp-api/v3/api-docs"
quality_status: "needs-review"
normalization_warning: "endpoint_possivelmente_incompleto_no_manual_normalizado"
---

# Excluir Empenho

## Resumo
Serviço que permite remover um empenho. Este serviço será acionado por qualquer.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/contratos`

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


## Aviso de qualidade
Este endpoint foi preservado porque consta no manual normalizado, mas não aparece na especificação pública do Swagger verificada em 2026-05-02. O path ou a seção parecem truncados/incompletos no material normalizado; trate como referência de baixa confiança até revisão contra a fonte oficial original.

## Notas de normalização
- Operação preservada a partir do manual segmentado local; não foi localizada operação equivalente na OpenAPI capturada.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-5-20-excluir-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
