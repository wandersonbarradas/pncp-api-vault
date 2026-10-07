---
title: "AlterarUsuarioDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarUsuarioDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| email | string | não |  |  |
| entesAutorizados | array[string] | não |  |  |
| nome | string | não |  |  |
| senha | string | não |  |  |

## Usado como Corpo de Requisição

- [PUT /v1/usuarios/{id}](../sessoes/usuario/atualizar-usuario.md) - Atualizar usuário

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
