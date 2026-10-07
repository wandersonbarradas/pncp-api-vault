---
title: "RecuperarCompraDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# RecuperarCompraDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| amparoLegal | [RecuperarAmparoLegalDTO](./recuperar-amparo-legal-dto.md) | não |  |  |
| anoCompra | integer (int32) | não |  |  |
| dataAberturaProposta | string (date-time) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataAtualizacaoGlobal | string (date-time) | não |  |  |
| dataEncerramentoProposta | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| existeResultado | boolean | não |  |  |
| fontesOrcamentarias | array[[ContratacaoFonteOrcamentariaDTO](./contratacao-fonte-orcamentaria-dto.md)] | não |  |  |
| indicadorOrcamentoSigiloso | string | não |  | COMPRA_SEM_SIGILO, COMPRA_PARCIALMENTE_SIGILOSA, COMPRA_TOTALMENTE_SIGILOSA |
| informacaoComplementar | string | não |  |  |
| justificativaPresencial | string | não |  |  |
| linkProcessoEletronico | string | não |  |  |
| linkSistemaOrigem | string | não |  |  |
| modalidadeId | integer (int64) | não |  |  |
| modalidadeNome | string | não |  |  |
| modoDisputaId | integer (int64) | não |  |  |
| modoDisputaNome | string | não |  |  |
| numeroCompra | string | não |  |  |
| numeroControlePNCP | string | não |  |  |
| objetoCompra | string | não |  |  |
| orcamentoSigilosoCodigo | integer (int32) | não |  |  |
| orcamentoSigilosoDescricao | string | não |  |  |
| orgaoEntidade | [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md) | não |  |  |
| orgaoSubRogado | [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md) | não |  |  |
| processo | string | não |  |  |
| sequencialCompra | integer (int32) | não |  |  |
| situacaoCompraId | string | não |  | 1, 2, 3, 4 |
| situacaoCompraNome | string | não |  |  |
| srp | boolean | não |  |  |
| tipoInstrumentoConvocatorioCodigo | integer (int64) | não |  |  |
| tipoInstrumentoConvocatorioNome | string | não |  |  |
| unidadeOrgao | [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md) | não |  |  |
| unidadeSubRogada | [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md) | não |  |  |
| usuarioNome | string | não |  |  |
| valorTotalEstimado | number | não |  |  |
| valorTotalHomologado | number | não |  |  |

## Schemas Relacionados

- [ContratacaoFonteOrcamentariaDTO](./contratacao-fonte-orcamentaria-dto.md)
- [RecuperarAmparoLegalDTO](./recuperar-amparo-legal-dto.md)
- [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md)
- [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}](../../consulta/contratacao/consultar-contrata-o.md) - Consultar Contratação

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
