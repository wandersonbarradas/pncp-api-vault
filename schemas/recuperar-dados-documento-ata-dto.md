---
title: "RecuperarDadosDocumentoAtaDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarDadosDocumentoAtaDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| sequencialDocumento | integer (int32) | não |  |  |
| tipoDocumentoId | integer (int64) | não |  |  |
| tipoDocumentoNome | string | não |  |  |
| titulo | string | não |  |  |
| url | string (uri) | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos](../sessoes/ata/consultar-dados-de-todos-os-documentos-de-uma-ata-de-registro-de-preco.md) - Consultar Dados de Todos os Documentos de uma Ata de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
