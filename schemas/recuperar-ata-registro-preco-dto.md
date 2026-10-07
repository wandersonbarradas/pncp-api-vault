---
title: "RecuperarAtaRegistroPrecoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarAtaRegistroPrecoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 1 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoAta | integer (int32) | não |  |  |
| cancelado | boolean | não |  |  |
| dataAssinatura | string (date) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataAtualizacaoGlobal | string (date-time) | não |  |  |
| dataCancelamento | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| dataVigenciaFim | string (date) | não |  |  |
| dataVigenciaInicio | string (date) | não |  |  |
| informacaoComplementarCompra | string | não |  |  |
| modalidadeNome | string | não |  |  |
| numeroAtaRegistroPreco | string | não |  |  |
| numeroControlePNCP | string | não |  |  |
| numeroControlePncpCompra | string | não |  |  |
| objetoCompra | string | não |  |  |
| orgaoEntidade | [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md) | não |  |  |
| orgaoSubRogado | [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md) | não |  |  |
| sequencialAta | integer (int32) | não |  |  |
| unidadeOrgao | [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md) | não |  |  |
| unidadeSubRogada | [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md) | não |  |  |
| usuarioNome | string | não |  |  |

## Schemas Relacionados

- [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md)
- [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}](../sessoes/ata/consultar-ata-de-registro-de-preco.md) - Consultar Ata de Registro de Preço

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
