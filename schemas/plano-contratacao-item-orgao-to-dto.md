---
title: "PlanoContratacaoItemOrgaoToDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# PlanoContratacaoItemOrgaoToDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoPca | integer (int32) | não |  |  |
| cnpj | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| esfera | string | não |  |  |
| poder | string | não |  |  |
| quantidade | number | não |  |  |
| razaoSocial | string | não |  |  |
| valorTotal | number | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/pca/{ano}/consolidado](../sessoes/plano-de-contratacao/consultar-planos-de-contratacao-consolidados-por-orgao-e-ano.md) - Consultar Planos de Contratação Consolidados por Órgão e Ano

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
