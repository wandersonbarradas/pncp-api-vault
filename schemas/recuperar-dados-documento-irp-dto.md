---
title: "RecuperarDadosDocumentoIrpDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# RecuperarDadosDocumentoIrpDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| urlDownload | string (uri) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| sequencialIrp | integer (int32) | não |  |  |
| sequencialDocumento | integer (int32) | não |  |  |
| titulo | string | não |  |  |
| numeroControleIrp | string | não |  |  |
| tipoDocumentoNome | string | não |  |  |
| tipoDocumentoDescricao | string | não |  |  |
| tipoDocumentoCodigo | integer (int64) | não |  |  |
| cnpjOrgaoGerenciadorIrp | string | não |  |  |

## Usado em Respostas

- `GET /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}/arquivos` em [consultar-dados-de-todos-os-documentos-de-uma-intencao-de-registro-de-preco.md](../sessoes/irp/consultar-dados-de-todos-os-documentos-de-uma-intencao-de-registro-de-preco.md) - Consultar Dados de Todos os Documentos de uma Intenção de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
