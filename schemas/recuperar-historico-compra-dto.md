---
title: "RecuperarHistoricoCompraDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarHistoricoCompraDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| categoriaLogManutencao | string | não |  | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15 |
| categoriaLogManutencaoNome | string | não |  |  |
| compraAno | integer (int32) | não |  |  |
| compraOrgaoCnpj | string | não |  |  |
| compraSequencial | integer (int32) | não |  |  |
| documentoSequencial | integer (int32) | não |  |  |
| documentoTipo | string | não |  |  |
| documentoTitulo | string | não |  |  |
| itemNumero | integer (int32) | não |  |  |
| itemResultadoNumero | integer (int32) | não |  |  |
| itemResultadoSequencial | integer (int32) | não |  |  |
| justificativa | string | não |  |  |
| logManutencaoDataInclusao | string (date-time) | não |  |  |
| tipoLogManutencao | string | não |  | 0, 1, 2 |
| tipoLogManutencaoNome | string | não |  |  |
| usuarioNome | string | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/historico](../sessoes/contratacao/consultar-historico-de-contratacao.md) - Consultar Histórico de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
