---
section_id: "6.3.4"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Excluir Contratação"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}"
page_start: 159
page_end: 161
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir Contratação

## Resumo
Serviço que permite excluir uma contratação. Este serviço será acionado por qualquer.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`ExclusaoDTO`](../../schemas/exclusao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `justificativa` | string | sim |

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
- `sections/6-3-4-excluir-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
