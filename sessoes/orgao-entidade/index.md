# Serviços de Órgão/Entidade

Índice compacto da sessão.

| Método | Endpoint | Operação | Fonte | Reconciliação | Arquivo |
| --- | --- | --- | --- | --- | --- |
| `GET` | `/v1/orgaos/` | Consultar Órgão por Filtro | `openapi` | `openapi-confirmed` | [consultar-orgao-por-filtro.md](./consultar-orgao-por-filtro.md) |
| `GET` | `/v1/orgaos/id/{orgaoId}` | Consultar Órgão por ID | `openapi` | `openapi-confirmed` | [consultar-orgao-por-id.md](./consultar-orgao-por-id.md) |
| `GET` | `/v1/orgaos/{cnpj}` | Consultar Órgão por CNPJ | `manual+openapi` | `openapi-confirmed` | [consultar-orgao-por-cnpj.md](./consultar-orgao-por-cnpj.md) |
| `GET` | `/v1/orgaos/{cnpj}/unidades` | Consultar Unidades | `manual+openapi` | `openapi-confirmed` | [consultar-unidades.md](./consultar-unidades.md) |
| `GET` | `/v1/orgaos/{cnpj}/unidades/{codigoUnidade}` | Consultar Unidade | `manual+openapi` | `openapi-confirmed` | [consultar-unidade.md](./consultar-unidade.md) |
| `POST` | `/v1/orgaos` | Inserir Órgão | `manual+openapi` | `openapi-confirmed` | [inserir-orgao.md](./inserir-orgao.md) |
| `POST` | `/v1/orgaos/{cnpj}/unidades` | Inserir Unidade | `manual+openapi` | `openapi-confirmed` | [inserir-unidade.md](./inserir-unidade.md) |
| `PUT` | `/v1/orgaos` | Atualizar Órgão | `manual+openapi` | `openapi-confirmed` | [atualizar-orgao.md](./atualizar-orgao.md) |
| `PUT` | `/v1/orgaos/{cnpj}/unidades` | Atualizar Unidade | `manual+openapi` | `openapi-confirmed` | [atualizar-unidade.md](./atualizar-unidade.md) |
