---
title: "RecuperarHistoricoIrpDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# RecuperarHistoricoIrpDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| justificativa | string | não |  |  |
| tipoLogManutencao | string | não |  | 0, 1, 2 |
| categoriaLogManutencao | string | não |  | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20 |
| logManutencaoDataInclusao | string (date-time) | não |  |  |
| categoriaLogManutencaoNome | string | não |  |  |
| usuarioNome | string | não |  |  |
| irpOrgaoCnpj | string | não |  |  |
| irpSequencial | integer (int32) | não |  |  |
| itemNumero | integer (int32) | não |  |  |
| documentoTipo | string | não |  |  |
| documentoTitulo | string | não |  |  |
| documentoSequencial | integer (int32) | não |  |  |
| tipoLogManutencaoNome | string | não |  |  |
| irpAno | integer (int32) | não |  |  |

## Usado em Respostas

- `GET /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/historico` em [consultar-historico-de-intencao-de-registro-de-preco.md](../sessoes/irp/consultar-historico-de-intencao-de-registro-de-preco.md) - Consultar Histórico de Intenção de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
