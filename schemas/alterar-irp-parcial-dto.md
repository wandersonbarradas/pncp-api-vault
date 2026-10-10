---
title: "AlterarIrpParcialDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# AlterarIrpParcialDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| codigoUnidadeGerenciadora | string | não |  |  |
| cnpjOrgaoSubRogado | string | não |  |  |
| codigoUnidadeSubRogada | string | não |  |  |
| numeroIrp | string | não |  |  |
| numeroProcesso | string | não |  |  |
| tipoInstrumentoConvocatorioId | integer (int64) | não |  |  |
| amparoLegalId | integer (int64) | não |  |  |
| modalidadeId | integer (int64) | não |  |  |
| modoDisputaId | integer (int64) | não |  |  |
| situacaoIrpId | integer (int64) | não |  |  |
| dataCancelamento | string (date-time) | não |  |  |
| motivoCancelamento | string | não |  |  |
| objetoIrp | string | não |  |  |
| informacaoComplementar | string | não |  |  |
| indicadorPossibilidadeAdesao | boolean | não |  |  |
| dataHoraFinalManifestacaoInteresse | string (date-time) | não |  |  |
| urlPlataformaOrigem | string | não |  |  |
| urlProcessoEletronico | string | não |  |  |
| justificativa | string | não |  |  |

## Usado em Requisições

- `PATCH /v1/orgaos/{cnpj}/irp/{ano}/{sequencial}` em [retificar-parcialmente-uma-intencao-de-registro-de-preco.md](../sessoes/irp/retificar-parcialmente-uma-intencao-de-registro-de-preco.md) - Retificar parcialmente uma Intenção de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
