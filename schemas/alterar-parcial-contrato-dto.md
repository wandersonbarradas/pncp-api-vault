---
title: "AlterarParcialContratoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-10-07"
---

# AlterarParcialContratoDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| cnpjCompra | string | não |  |  |
| anoCompra | integer (int32) | não |  |  |
| sequencialCompra | integer (int32) | não |  |  |
| sequencialAta | integer (int32) | não |  |  |
| frutoAdesao | boolean | não |  |  |
| temRemanejamento | boolean | não |  |  |
| emendaParlamentar | boolean | não |  |  |
| tipoContratoId | integer (int64) | não |  |  |
| numeroContratoEmpenho | string | não |  |  |
| processo | string | não |  |  |
| categoriaProcessoId | integer (int64) | não |  |  |
| niFornecedor | string | não |  |  |
| tipoPessoaFornecedor | string | não |  |  |
| nomeRazaoSocialFornecedor | string | não |  |  |
| receita | boolean | não |  |  |
| codigoUnidade | string | não |  |  |
| objetoContrato | string | não |  |  |
| valorInicial | number | não |  |  |
| numeroParcelas | integer (int32) | não |  |  |
| valorParcela | number | não |  |  |
| valorGlobal | number | não |  |  |
| dataAssinatura | string (date) | não |  |  |
| dataVigenciaInicio | string (date) | não |  |  |
| dataVigenciaFim | string (date) | não |  |  |
| valorAcumulado | number | não |  |  |
| niFornecedorSubContratado | string | não |  |  |
| tipoPessoaFornecedorSubContratado | string | não |  |  |
| nomeRazaoSocialFornecedorSubContratado | string | não |  |  |
| informacaoComplementar | string | não |  |  |
| urlCipi | string | não |  |  |
| identificadorCipi | string | não |  |  |
| cnpjOrgaoSubRogado | string | não |  |  |
| codigoUnidadeSubRogada | string | não |  |  |
| tipoParteEnvolvidaId | integer (int64) | não |  |  |
| cnpjOrgaoParteEnvolvida | string | não |  |  |
| codigoUnidadeParteEnvolvida | string | não |  |  |
| justificativa | string | não |  |  |

## Usado em Requisições

- `PATCH /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}` em [retificar-parcialmente-contrato.md](../sessoes/contrato-empenho/retificar-parcialmente-contrato.md) - Retificar Parcialmente Contrato

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
