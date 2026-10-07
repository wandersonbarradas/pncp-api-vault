---
title: "IncluirUsuarioOrgaoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IncluirUsuarioOrgaoDTO

- Tipo: `object`
- Usado em requisições: 2 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| entesAutorizados | array[string] | sim |  |  |

## Usado como Corpo de Requisição

- [DELETE /v1/usuarios/{id}/orgaos](../sessoes/usuario/excluir-entes-autorizados-de-um-usuario.md) - Excluir Entes Autorizados de um Usuário
- [POST /v1/usuarios/{id}/orgaos](../sessoes/usuario/inserir-entes-autorizados-para-um-usuario.md) - Inserir Entes Autorizados para um Usuário

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
