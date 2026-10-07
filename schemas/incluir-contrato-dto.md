---
title: "IncluirContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IncluirContratoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| anoCompra | integer (int32) | não |  |  |
| anoContrato | integer (int32) | não |  |  |
| categoriaProcessoId | integer (int64) | sim |  |  |
| cnpjCompra | string | sim |  |  |
| codigoUnidade | string | sim |  |  |
| dataAssinatura | string (date) | sim |  |  |
| dataVigenciaFim | string (date) | sim |  |  |
| dataVigenciaInicio | string (date) | sim |  |  |
| identificadorCipi | string | não |  |  |
| informacaoComplementar | string | não |  |  |
| niFornecedor | string | sim |  |  |
| niFornecedorSubContratado | string | não |  |  |
| nomeRazaoSocialFornecedor | string | sim |  |  |
| nomeRazaoSocialFornecedorSubContratado | string | não |  |  |
| numeroContratoEmpenho | string | sim |  |  |
| numeroParcelas | integer (int32) | sim |  |  |
| objetoContrato | string | sim |  |  |
| processo | string | sim |  |  |
| receita | boolean | sim |  |  |
| sequencialCompra | integer (int32) | sim |  |  |
| tipoContratoId | integer (int64) | sim |  |  |
| tipoPessoaFornecedor | string | sim |  |  |
| tipoPessoaFornecedorSubContratado | string | não |  |  |
| urlCipi | string | não |  |  |
| valorAcumulado | number | não |  |  |
| valorGlobal | number | sim |  |  |
| valorInicial | number | sim |  |  |
| valorParcela | number | sim |  |  |

## Usado como Corpo de Requisição

- [POST /v1/orgaos/{cnpj}/contratos](../sessoes/contrato-empenho/inserir-contrato.md) - Inserir Contrato

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
