---
title: "RecuperarHistoricoAtaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarHistoricoAtaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| ataSequencial | integer (int32) | não |  |  |
| categoriaLogManutencao | string | não |  | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15 |
| categoriaLogManutencaoNome | string | não |  |  |
| compraAno | integer (int32) | não |  |  |
| compraOrgaoCnpj | string | não |  |  |
| compraSequencial | integer (int32) | não |  |  |
| documentoAtaSequencial | integer (int32) | não |  |  |
| documentoAtaTipo | string | não |  |  |
| documentoAtaTitulo | string | não |  |  |
| justificativa | string | não |  |  |
| logManutencaoDataInclusao | string (date-time) | não |  |  |
| tipoLogManutencao | string | não |  | 0, 1, 2 |
| tipoLogManutencaoNome | string | não |  |  |
| usuarioNome | string | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/atas/{sequencialAta}/historico](../sessoes/ata/consultar-historico-de-ata.md) - Consultar Histórico de Ata

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
