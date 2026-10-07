---
section_id: null
source_type: "openapi"
group: "Usuário"
title: "Inserir usuário"
method: "POST"
endpoint: "/v1/usuarios"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir usuário

## Resumo
Operação `POST /v1/usuarios`.

## Endpoint
`POST /v1/usuarios`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Schema OpenAPI: [`InserirUsuarioDTO`](../../schemas/inserir-usuario-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `nome` | string | não |
| `cpfCnpj` | string | não |
| `email` | string | não |
| `administrador` | boolean | não |
| `entesAutorizados` | array | não |

## Resposta
Schema OpenAPI: [`CredenciaisDTO`](../../schemas/credenciais-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `login` | string | não |
| `nome` | string | não |
| `cpfCnpj` | string | não |
| `email` | string | não |
| `administrador` | boolean | não |
| `gestaoEnteAutorizado` | boolean | não |
| `statusBloqueado` | boolean | não |
| `token` | string | não |
| `senha` | string | não |
| `telefone` | string | não |
| `cnpjVinculado` | string | não |
| `entesAutorizados` | array | não |
| `nivelGovBR` | string | não |
| `permissoes` | array | não |

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
- Endpoint presente na OpenAPI atual, sem seção correspondente no manual segmentado local.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
