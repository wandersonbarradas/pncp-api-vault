---
section_id: "6.1.1"
source_type: "manual+openapi"
group: "Serviços de Usuário"
title: "Atualizar usuário"
method: "PUT"
endpoint: "/v1/usuarios/{id}"
page_start: 111
page_end: 113
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Atualizar usuário

## Resumo
Serviço que permite alterar/atualizar os dados de um usuário. Disponível para o próprio.

## Endpoint
`PUT /v1/usuarios/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarUsuarioDTO`](../../schemas/alterar-usuario-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `nome` | string | não |
| `email` | string | não |
| `senha` | string | não |
| `entesAutorizados` | array | não |

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
- `sections/6-1-1-atualizar-usuario.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
