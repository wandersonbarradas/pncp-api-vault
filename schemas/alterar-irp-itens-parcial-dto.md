---
title: "AlterarIrpItensParcialDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# AlterarIrpItensParcialDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| numeroItem | integer (int32) | não |  |  |
| materialOuServico | string | não | Tipo do item: 'M' (Material) ou 'S' (Serviço). | M, S |
| categoriaItemId | integer (int64) | não |  |  |
| criterioJulgamentoId | integer (int64) | não |  |  |
| aplicabilidadeMargemPreferencia | boolean | não |  |  |
| exigenciaConteudoNacional | boolean | não |  |  |
| descricao | string | não |  |  |
| informacaoComplementar | string | não |  |  |
| unidadeFornecimento | string | não |  |  |
| valorUnitarioEstimado | number | não |  |  |
| indicadorValorSigiloso | boolean | não |  |  |
| codigoGtin | string | não |  |  |
| codigoNcmNbs | string | não |  |  |
| descricaoNcmNbs | string | não |  |  |
| catalogoId | integer (int64) | não |  |  |
| codigoItemCatalogo | string | não |  |  |

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
