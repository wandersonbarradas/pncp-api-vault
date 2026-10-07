---
title: "RecuperarHistoricoContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarHistoricoContratoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| categoriaLogManutencao | string | não |  | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15 |
| categoriaLogManutencaoNome | string | não |  |  |
| contratoAno | integer (int32) | não |  |  |
| contratoOrgaoCnpj | string | não |  |  |
| contratoSequencial | integer (int32) | não |  |  |
| justificativa | string | não |  |  |
| logManutencaoDataInclusao | string (date-time) | não |  |  |
| numeroTermoContrato | string | não |  |  |
| sequencialDocumentoContrato | integer (int32) | não |  |  |
| sequencialDocumentoTermoContrato | integer (int32) | não |  |  |
| sequencialInstrumentoCobranca | integer (int32) | não |  |  |
| sequencialTermoContrato | integer (int32) | não |  |  |
| tipoLogManutencao | string | não |  | 0, 1, 2 |
| tipoLogManutencaoNome | string | não |  |  |
| tituloDocumentoContrato | string | não |  |  |
| tituloDocumentoTermoContrato | string | não |  |  |
| usuarioNome | string | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/historico](../sessoes/contrato-empenho/consultar-historico-de-contrato.md) - Consultar Histórico de Contrato

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
