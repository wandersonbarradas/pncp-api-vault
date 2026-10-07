---
title: "PlanoContratacaoComItensDoUsuarioDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# PlanoContratacaoComItensDoUsuarioDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoPca | integer (int32) | não |  |  |
| codigoUnidade | string | não |  |  |
| dataAtualizacaoGlobalPCA | string (date-time) | não |  |  |
| dataPublicacaoPNCP | string (date-time) | não |  |  |
| idPcaPncp | string | não |  |  |
| itens | array[[PlanoContratacaoItemDTO](./plano-contratacao-item-dto.md)] | não |  |  |
| nomeUnidade | string | não |  |  |
| orgaoEntidadeCnpj | string | não |  |  |
| orgaoEntidadeRazaoSocial | string | não |  |  |

## Schemas Relacionados

- [PlanoContratacaoItemDTO](./plano-contratacao-item-dto.md)

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
