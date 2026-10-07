# Termo de Contrato

Índice compacto da sessão.

| Método | Endpoint | Operação | Fonte | Reconciliação | Arquivo |
| --- | --- | --- | --- | --- | --- |
| `DELETE` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}` | Excluir Termo de Contrato | `manual+openapi` | `openapi-confirmed` | [excluir-termo-de-contrato.md](./excluir-termo-de-contrato.md) |
| `DELETE` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/{sequencialDocumento}` | Excluir Arquivo/Documento de Termo de Contrato | `manual+openapi` | `openapi-confirmed` | [excluir-arquivo-documento-de-termo-de-contrato.md](./excluir-arquivo-documento-de-termo-de-contrato.md) |
| `GET` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos` | Consultar Termos de Contrato | `manual+openapi` | `openapi-confirmed` | [consultar-termos-de-contrato.md](./consultar-termos-de-contrato.md) |
| `GET` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/quantidade` | Consultar Quantidade de Termos de Contrato | `openapi` | `openapi-confirmed` | [consultar-quantidade-de-termos-de-contrato.md](./consultar-quantidade-de-termos-de-contrato.md) |
| `GET` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}` | Consultar Termo de Contrato | `manual+openapi` | `openapi-confirmed` | [consultar-termo-de-contrato.md](./consultar-termo-de-contrato.md) |
| `GET` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos` | Consultar Documentos de Termo de Contrato | `manual+openapi` | `openapi-confirmed` | [consultar-documentos-de-termo-de-contrato.md](./consultar-documentos-de-termo-de-contrato.md) |
| `GET` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/excluidos/{sequencialDocumento}` | Baixar Arquivo/Documento Excluído de Termo de Contrato | `openapi` | `openapi-confirmed` | [baixar-arquivo-documento-excluido-de-termo-de-contrato.md](./baixar-arquivo-documento-excluido-de-termo-de-contrato.md) |
| `GET` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/quantidade` | Consultar Quantidade de Documentos de Termo de Contrato | `openapi` | `openapi-confirmed` | [consultar-quantidade-de-documentos-de-termo-de-contrato.md](./consultar-quantidade-de-documentos-de-termo-de-contrato.md) |
| `GET` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/{sequencialDocumento}` | Baixar Arquivo/Documento de Termo de Contrato | `openapi` | `openapi-confirmed` | [baixar-arquivo-documento-de-termo-de-contrato.md](./baixar-arquivo-documento-de-termo-de-contrato.md) |
| `GET` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/{sequencialDocumento}` | Consultar Documento de um Termo de Contrato | `manual` | `openapi-confirmed` | [consultar-documento-de-um-termo-de-contrato.md](./consultar-documento-de-um-termo-de-contrato.md) |
| `POST` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos` | Inserir Termo de Contrato | `manual+openapi` | `openapi-confirmed` | [inserir-termo-de-contrato.md](./inserir-termo-de-contrato.md) |
| `POST` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos` | Inserir Documento de Termo de Contrato | `manual+openapi` | `openapi-confirmed` | [inserir-documento-de-termo-de-contrato.md](./inserir-documento-de-termo-de-contrato.md) |
| `PUT` | `/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}` | Retificar Termo de Contrato | `manual+openapi` | `openapi-confirmed` | [retificar-termo-de-contrato.md](./retificar-termo-de-contrato.md) |
