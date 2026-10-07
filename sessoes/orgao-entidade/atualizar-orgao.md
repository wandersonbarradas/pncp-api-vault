---
section_id: "6.2.2"
source_type: "manual+openapi"
group: "Serviços de Órgão/Entidade"
title: "Atualizar Órgão"
method: "PUT"
endpoint: "/v1/orgaos"
page_start: 125
page_end: 126
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Atualizar Órgão

## Resumo
Serviço destinado exclusivamente aos administradores do PNCP que permite atualizar.

## Endpoint
`PUT /v1/orgaos`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Schema OpenAPI: [`IncluirOrgaoDTO`](../../schemas/incluir-orgao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `cnpj` | string | sim |

## Resposta
Schema OpenAPI: `object`

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
- `sections/6-2-2-atualizar-orgao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
