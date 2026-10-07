---
title: "InserirUsuarioDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# InserirUsuarioDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| administrador | boolean | não |  |  |
| cpfCnpj | string | não |  |  |
| email | string | não |  |  |
| entesAutorizados | array[string] | não |  |  |
| nome | string | não |  |  |

## Usado como Corpo de Requisição

- [POST /v1/usuarios](../sessoes/usuario/inserir-usuario.md) - Inserir usuário

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
