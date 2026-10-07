---
title: "AtaRegistroPrecoAlteracaoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AtaRegistroPrecoAlteracaoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoAta | integer (int32) | sim |  |  |
| cancelado | boolean | sim |  |  |
| dataAssinatura | string (date) | sim |  |  |
| dataCancelamento | string (date-time) | não |  |  |
| dataVigenciaFim | string (date) | sim |  |  |
| dataVigenciaInicio | string (date) | sim |  |  |
| justificativa | string | sim |  |  |
| numeroAtaRegistroPreco | string | sim |  |  |

## Usado como Corpo de Requisição

- [PUT /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}](../sessoes/ata/retificar-ata-de-registro-de-preco.md) - Retificar Ata de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
