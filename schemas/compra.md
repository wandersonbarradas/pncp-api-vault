---
title: "Compra"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# Compra

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| amparoLegal | [AmparoLegal](./amparo-legal.md) | não |  |  |
| anoCompra | integer (int32) | não |  |  |
| atributoControle | integer (int64) | não |  |  |
| dataAberturaProposta | string (date-time) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataAtualizacaoGlobal | string (date-time) | não |  |  |
| dataEncerramentoProposta | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| excluido | boolean | não |  |  |
| existeResultado | boolean | não |  |  |
| id | integer (int64) | não |  |  |
| indicadorOrcamentoSigiloso | string | não |  | IndicadorOrcamentoSigiloso.COMPRA_SEM_SIGILO(codigo=1, descricao=Compra sem sigilo), IndicadorOrcamentoSigiloso.COMPRA_PARCIALMENTE_SIGILOSA(codigo=2, descricao=Compra parcialmente sigilosa), IndicadorOrcamentoSigiloso.COMPRA_TOTALMENTE_SIGILOSA(codigo=3, descricao=Compra totalmente sigilosa) |
| informacaoComplementar | string | não |  |  |
| justificativaPresencial | string | não |  |  |
| linkProcessoEletronico | string | não |  |  |
| linkSistemaOrigem | string | não |  |  |
| listaItensDescricao | string | não |  |  |
| modalidade | [Modalidade](./modalidade.md) | não |  |  |
| modoDisputa | [ModoDisputa](./modo-disputa.md) | não |  |  |
| numeroCompra | string | não |  |  |
| numeroControle | string | não |  |  |
| objetoCompra | string | não |  |  |
| orgaoEntidade | [OrgaoEntidade](./orgao-entidade.md) | não |  |  |
| orgaoSubRogado | [OrgaoEntidade](./orgao-entidade.md) | não |  |  |
| processo | string | não |  |  |
| sequencialCompra | integer (int32) | não |  |  |
| situacaoCompra | string | não |  | 1, 2, 3, 4 |
| srp | boolean | não |  |  |
| tipoInstrumentoConvocatorio | [TipoInstrumentoConvocatorio](./tipo-instrumento-convocatorio.md) | não |  |  |
| unidadeOrgao | [UnidadeOrgao](./unidade-orgao.md) | não |  |  |
| unidadeSubRogada | [UnidadeOrgao](./unidade-orgao.md) | não |  |  |
| valorTotal | number | não |  |  |
| valorTotalHomologado | number | não |  |  |

## Schemas Relacionados

- [AmparoLegal](./amparo-legal.md)
- [Modalidade](./modalidade.md)
- [ModoDisputa](./modo-disputa.md)
- [OrgaoEntidade](./orgao-entidade.md)
- [TipoInstrumentoConvocatorio](./tipo-instrumento-convocatorio.md)
- [UnidadeOrgao](./unidade-orgao.md)

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
