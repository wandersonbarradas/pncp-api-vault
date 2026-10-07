---
title: "CredenciaisDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# CredenciaisDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 3 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| administrador | boolean | não |  |  |
| cnpjVinculado | string | não |  |  |
| cpfCnpj | string | não |  |  |
| email | string | não |  |  |
| entesAutorizados | array[[EnteCredenciaisDTO](./ente-credenciais-dto.md)] | não |  |  |
| gestaoEnteAutorizado | boolean | não |  |  |
| id | integer (int64) | não |  |  |
| login | string | não |  |  |
| nivelGovBR | string | não |  |  |
| nome | string | não |  |  |
| permissoes | array[[DominioGenericoMinimoDTO](./dominio-generico-minimo-dto.md)] | não |  |  |
| senha | string | não |  |  |
| statusBloqueado | boolean | não |  |  |
| telefone | string | não |  |  |
| token | string | não |  |  |

## Schemas Relacionados

- [DominioGenericoMinimoDTO](./dominio-generico-minimo-dto.md)
- [EnteCredenciaisDTO](./ente-credenciais-dto.md)

## Usado em Respostas

- `200`: [GET /v1/usuarios](../sessoes/usuario/consultar-usuario-por-login-ou-por-cpf-cnpj.md) - Consultar usuário por login ou por CPF/CNPJ
- `200`: [GET /v1/usuarios/{id}](../sessoes/usuario/consultar-usuario-por-id.md) - Consultar usuário por ID
- `200`: [POST /v1/usuarios](../sessoes/usuario/inserir-usuario.md) - Inserir usuário

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
