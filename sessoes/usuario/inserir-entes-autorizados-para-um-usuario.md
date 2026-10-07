---
section_id: "6.1.5"
source_type: "manual+openapi"
group: "Serviços de Usuário"
title: "Inserir Entes Autorizados para um Usuário"
method: "POST"
endpoint: "/v1/usuarios/{id}/orgaos"
page_start: 119
page_end: 120
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Entes Autorizados para um Usuário

## Resumo
Serviço que permite inserir um ou mais CNPJs de entes autorizados para um usuário.

## Endpoint
`POST /v1/usuarios/{id}/orgaos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`IncluirUsuarioOrgaoDTO`](../../schemas/incluir-usuario-orgao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `entesAutorizados` | array | sim |

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
- `sections/6-1-5-inserir-entes-autorizados-para-um-usuario.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
