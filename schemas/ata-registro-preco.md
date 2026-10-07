---
title: "AtaRegistroPreco"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AtaRegistroPreco

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoAta | integer (int32) | sim |  |  |
| atributoControle | integer (int64) | não |  |  |
| cancelado | boolean | não |  |  |
| compra | [Compra](./compra.md) | não |  |  |
| dataAssinatura | string (date) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataAtualizacaoGlobal | string (date-time) | não |  |  |
| dataCancelamento | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| dataVigenciaFim | string (date) | não |  |  |
| dataVigenciaInicio | string (date) | não |  |  |
| excluido | boolean | não |  |  |
| id | integer (int64) | não |  |  |
| numeroAtaRegistroPreco | string | sim |  |  |
| numeroControlePNCP | string | não |  |  |
| sequencialAta | integer (int32) | não |  |  |

## Schemas Relacionados

- [Compra](./compra.md)

## Usado em Respostas

- `200`: [POST /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas](../sessoes/ata/inserir-ata-de-registro-de-preco.md) - Inserir Ata de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
