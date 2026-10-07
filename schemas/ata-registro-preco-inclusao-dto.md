---
title: "AtaRegistroPrecoInclusaoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AtaRegistroPrecoInclusaoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoAta | integer (int32) | sim |  |  |
| dataAssinatura | string (date) | não |  |  |
| dataVigenciaFim | string (date) | não |  |  |
| dataVigenciaInicio | string (date) | não |  |  |
| numeroAtaRegistroPreco | string | não |  |  |

## Usado como Corpo de Requisição

- [POST /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas](../sessoes/ata/inserir-ata-de-registro-de-preco.md) - Inserir Ata de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
