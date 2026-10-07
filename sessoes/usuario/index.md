# Usuário

Índice compacto da sessão.

| Método | Endpoint | Operação | Fonte | Reconciliação | Arquivo |
| --- | --- | --- | --- | --- | --- |
| `DELETE` | `/v1/usuarios/{id}` | Excluir usuário | `openapi` | `openapi-confirmed` | [excluir-usuario.md](./excluir-usuario.md) |
| `DELETE` | `/v1/usuarios/{id}/orgaos` | Excluir Entes Autorizados de um Usuário | `manual+openapi` | `openapi-confirmed` | [excluir-entes-autorizados-de-um-usuario.md](./excluir-entes-autorizados-de-um-usuario.md) |
| `GET` | `/v1/usuarios` | Consultar usuário por login ou por CPF/CNPJ | `manual+openapi` | `openapi-confirmed` | [consultar-usuario-por-login-ou-por-cpf-cnpj.md](./consultar-usuario-por-login-ou-por-cpf-cnpj.md) |
| `GET` | `/v1/usuarios/permissoes` | Consultar permissões | `openapi` | `openapi-confirmed` | [consultar-permissoes.md](./consultar-permissoes.md) |
| `GET` | `/v1/usuarios/{id}` | Consultar usuário por ID | `manual+openapi` | `openapi-confirmed` | [consultar-usuario-por-id.md](./consultar-usuario-por-id.md) |
| `PATCH` | `/v1/usuarios/{id}/permissoes` | Alterar permissões do usuário | `openapi` | `openapi-confirmed` | [alterar-permissoes-do-usuario.md](./alterar-permissoes-do-usuario.md) |
| `POST` | `/v1/usuarios` | Inserir usuário | `openapi` | `openapi-confirmed` | [inserir-usuario.md](./inserir-usuario.md) |
| `POST` | `/v1/usuarios/login` | Autenticação/login no sistema | `manual+openapi` | `openapi-confirmed` | [autenticacao-login-no-sistema.md](./autenticacao-login-no-sistema.md) |
| `POST` | `/v1/usuarios/{id}/orgaos` | Inserir Entes Autorizados para um Usuário | `manual+openapi` | `openapi-confirmed` | [inserir-entes-autorizados-para-um-usuario.md](./inserir-entes-autorizados-para-um-usuario.md) |
| `PUT` | `/v1/usuarios/{id}` | Atualizar usuário | `manual+openapi` | `openapi-confirmed` | [atualizar-usuario.md](./atualizar-usuario.md) |
