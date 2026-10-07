---
title: "PaginaRetornoRecuperarContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# PaginaRetornoRecuperarContratoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| data | array[[RecuperarContratoDTO](./recuperar-contrato-dto.md)] | não |  |  |
| empty | boolean | não |  |  |
| numeroPagina | integer (int64) | não |  |  |
| paginasRestantes | integer (int64) | não |  |  |
| totalPaginas | integer (int64) | não |  |  |
| totalRegistros | integer (int64) | não |  |  |

## Schemas Relacionados

- [RecuperarContratoDTO](./recuperar-contrato-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/contratos/contratacao/{anoContratacao}/{sequencialContratacao}](../sessoes/contrato-empenho/consultar-contratos-de-uma-contratacao.md) - Consultar Contratos de uma Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
