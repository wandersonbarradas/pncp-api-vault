---
title: "RecuperarDadosDocumentoCompraDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarDadosDocumentoCompraDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoCompra | integer (int32) | não |  |  |
| cnpj | string | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| sequencialCompra | integer (int32) | não |  |  |
| sequencialDocumento | integer (int32) | não |  |  |
| statusAtivo | boolean | não |  |  |
| tipoDocumentoDescricao | string | não |  |  |
| tipoDocumentoId | integer (int64) | não |  |  |
| tipoDocumentoNome | string | não |  |  |
| titulo | string | não |  |  |
| uri | string (uri) | não |  |  |
| url | string | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos](../sessoes/contratacao/consultar-documentos-de-contratacao.md) - Consultar Documentos de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
