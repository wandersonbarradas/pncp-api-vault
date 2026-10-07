---
title: "RecuperarContratoDTO"
type: "openapi-schema"
surface: "consulta"
source: "https://pncp.gov.br/api/consulta/v3/api-docs"
updated: "2026-05-03"
---

# RecuperarContratoDTO

- Superfície: `api/consulta`
- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoContrato | integer (int32) | não |  |  |
| categoriaProcesso | [Categoria](./categoria.md) | não |  |  |
| codigoPaisFornecedor | string | não |  |  |
| dataAssinatura | string (date) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataAtualizacaoGlobal | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| dataVigenciaFim | string (date) | não |  |  |
| dataVigenciaInicio | string (date) | não |  |  |
| identificadorCipi | string | não |  |  |
| informacaoComplementar | string | não |  |  |
| niFornecedor | string | não |  |  |
| niFornecedorSubContratado | string | não |  |  |
| nomeFornecedorSubContratado | string | não |  |  |
| nomeRazaoSocialFornecedor | string | não |  |  |
| numeroContratoEmpenho | string | não |  |  |
| numeroControlePNCP | string | não |  |  |
| numeroControlePncpCompra | string | não |  |  |
| numeroParcelas | integer (int32) | não |  |  |
| numeroRetificacao | integer (int32) | não |  |  |
| objetoContrato | string | não |  |  |
| orgaoEntidade | [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md) | não |  |  |
| orgaoSubRogado | [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md) | não |  |  |
| processo | string | não |  |  |
| receita | boolean | não |  |  |
| sequencialContrato | integer (int32) | não |  |  |
| tipoContrato | [TipoContrato](./tipo-contrato.md) | não |  |  |
| tipoPessoa | string | não |  | PJ, PF, PE |
| tipoPessoaSubContratada | string | não |  | PJ, PF, PE |
| unidadeOrgao | [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md) | não |  |  |
| unidadeSubRogada | [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md) | não |  |  |
| urlCipi | string | não |  |  |
| usuarioNome | string | não |  |  |
| valorAcumulado | number | não |  |  |
| valorGlobal | number | não |  |  |
| valorInicial | number | não |  |  |
| valorParcela | number | não |  |  |

## Schemas Relacionados

- [Categoria](./categoria.md)
- [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md)
- [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md)
- [TipoContrato](./tipo-contrato.md)

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
