---
section_id: "6.1.4"
source_type: "manual+openapi"
group: "Serviços de Usuário"
title: "Autenticação/login no sistema"
method: "POST"
endpoint: "/v1/usuarios/login"
page_start: 117
page_end: 118
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Autenticação/login no sistema

## Resumo
Serviço que recebe os dados para autenticação de um usuário e retorna um token de.

## Endpoint
`POST /v1/usuarios/login`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Schema OpenAPI: [`CamposLoginDTO`](../../schemas/campos-login-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `login` | string | sim |
| `senha` | string | não |

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
- `sections/6-1-4-realizar-login-de-usuario.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
