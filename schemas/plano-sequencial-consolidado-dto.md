---
title: "PlanoSequencialConsolidadoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# PlanoSequencialConsolidadoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoPca | integer (int32) | não |  |  |
| cnpj | string | não |  |  |
| codigoUnidade | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataAtualizacaoGlobalPCA | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| municipio | string | não |  |  |
| nomeUnidade | string | não |  |  |
| numeroControlePNCP | string | não |  |  |
| quantidade | number | não |  |  |
| razaoSocial | string | não |  |  |
| sequencialPca | integer (int32) | não |  |  |
| uf | string | não |  |  |
| usuario | string | não |  |  |
| valorTotal | number | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/consolidado](../sessoes/plano-de-contratacao/consultar-plano-de-contratacao-consolidado.md) - Consultar Plano de Contratação Consolidado

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
