---
title: "RecuperarDadosDocumentoContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarDadosDocumentoContratoDTO

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
| tipoDocumentoNome | string | não |  |  |
| titulo | string | não |  |  |
| uri | string (uri) | não |  |  |
| url | string | não |  |  |

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos](../sessoes/contrato-empenho/consultar-documentos-de-contrato.md) - Consultar Documentos de Contrato

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
