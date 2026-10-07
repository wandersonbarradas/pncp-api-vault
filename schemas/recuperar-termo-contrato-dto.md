---
title: "RecuperarTermoContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarTermoContratoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataAssinatura | string (date) | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| dataPublicacaoPncp | string (date-time) | não |  |  |
| dataVigenciaFim | string (date) | não |  |  |
| dataVigenciaInicio | string (date) | não |  |  |
| fornecedor | [RecuperarFornecedorDTO](./recuperar-fornecedor-dto.md) | não |  |  |
| fornecedorSubContratado | [RecuperarFornecedorDTO](./recuperar-fornecedor-dto.md) | não |  |  |
| fundamentoLegal | string | não |  |  |
| informacaoComplementar | string | não |  |  |
| informativoObservacao | string | não |  |  |
| niFornecedor | string | não |  |  |
| niFornecedorSubContratado | string | não |  |  |
| nomeFornecedorSubContratado | string | não |  |  |
| nomeRazaoSocialFornecedor | string | não |  |  |
| numeroParcelas | integer (int32) | não |  |  |
| numeroTermoContrato | string | não |  |  |
| objetoTermoContrato | string | não |  |  |
| orgaoEntidade | [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md) | não |  |  |
| orgaoSubrogado | [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md) | não |  |  |
| prazoAditadoDias | integer (int32) | não |  |  |
| processo | string | não |  |  |
| qualificacaoAcrescimoSupressao | boolean | não |  |  |
| qualificacaoFornecedor | boolean | não |  |  |
| qualificacaoReajuste | boolean | não |  |  |
| qualificacaoVigencia | boolean | não |  |  |
| sequencialTermoContrato | integer (int32) | não |  |  |
| tipoPessoa | string | não |  | PJ, PF, PE |
| tipoPessoaSubContratada | string | não |  | PJ, PF, PE |
| tipoTermoContratoNome | string | não |  |  |
| unidade | [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md) | não |  |  |
| unidadeSubrogada | [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md) | não |  |  |
| valorAcrescido | number | não |  |  |
| valorGlobal | number | não |  |  |
| valorParcela | number | não |  |  |

## Schemas Relacionados

- [RecuperarFornecedorDTO](./recuperar-fornecedor-dto.md)
- [RecuperarOrgaoEntidadeDTO](./recuperar-orgao-entidade-dto.md)
- [RecuperarUnidadeOrgaoDTO](./recuperar-unidade-orgao-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos](../sessoes/termo-de-contrato/consultar-termos-de-contrato.md) - Consultar Termos de Contrato
- `200`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}](../sessoes/termo-de-contrato/consultar-termo-de-contrato.md) - Consultar Termo de Contrato

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
