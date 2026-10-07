---
title: "RecuperarImagemContratacaoItemDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarImagemContratacaoItemDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataPublicacaoPncp | string | não |  |  |
| idContratacaoPncp | string | não |  |  |
| legenda | string | não |  |  |
| numeroItem | integer (int32) | não |  |  |
| sequencialImagem | integer (int32) | não |  |  |
| textoAlternativo | string | não |  |  |
| titulo | string | não |  |  |
| url | string | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/imagem](../sessoes/contratacao/recuperar-imagens-de-um-item-de-uma-contratacao.md) - Recuperar Imagens de um Item de uma Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
