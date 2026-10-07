---
title: "AlterarParcialPermissaoUsuarioDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarParcialPermissaoUsuarioDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| administrador | boolean | não |  |  |
| gestaoEnteAutorizado | boolean | não |  |  |
| incluirPermissoes | array[integer (int64)] | não |  |  |
| removerPermissoes | array[integer (int64)] | não |  |  |
| statusBloqueado | boolean | não |  |  |

## Usado como Corpo de Requisição

- [PATCH /v1/usuarios/{id}/permissoes](../sessoes/usuario/alterar-permissoes-do-usuario.md) - Alterar permissões do usuário

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
