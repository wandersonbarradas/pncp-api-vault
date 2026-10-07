---
title: "IncluirTermoContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IncluirTermoContratoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| dataAssinatura | string | sim |  |  |
| dataVigenciaFim | string (date) | não |  |  |
| dataVigenciaInicio | string (date) | não |  |  |
| fundamentoLegal | string | não |  |  |
| informativoObservacao | string | não |  |  |
| niFornecedor | string | não |  |  |
| niFornecedorSubContratado | string | não |  |  |
| nomeRazaoSocialFornecedor | string | não |  |  |
| nomeRazaoSocialFornecedorSubContratado | string | não |  |  |
| numeroParcelas | integer (int32) | não |  |  |
| numeroTermoContrato | string | não |  |  |
| objetoTermoContrato | string | sim |  |  |
| prazoAditadoDias | integer (int32) | não |  |  |
| qualificacaoAcrescimoSupressao | boolean | sim |  |  |
| qualificacaoFornecedor | boolean | sim |  |  |
| qualificacaoInformativo | boolean | sim |  |  |
| qualificacaoReajuste | boolean | sim |  |  |
| qualificacaoVigencia | boolean | sim |  |  |
| tipoPessoaFornecedor | string | não |  |  |
| tipoPessoaFornecedorSubContratado | string | não |  |  |
| tipoTermoContratoId | integer (int64) | sim |  |  |
| valorAcrescido | number | não |  |  |
| valorGlobal | number | não |  |  |
| valorParcela | number | não |  |  |

## Usado como Corpo de Requisição

- [POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos](../sessoes/termo-de-contrato/inserir-termo-de-contrato.md) - Inserir Termo de Contrato

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
