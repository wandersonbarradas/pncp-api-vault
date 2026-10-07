---
title: "IncluirCompraItemDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# IncluirCompraItemDTO

- Tipo: `object`
- Usado em requisições: 1 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| aplicabilidadeMargemPreferenciaAdicional | boolean | não |  |  |
| aplicabilidadeMargemPreferenciaNormal | boolean | não |  |  |
| catalogoCodigoItem | string | não |  |  |
| catalogoId | integer (int64) | não |  |  |
| categoriaItemCatalogoId | integer (int64) | não |  |  |
| codigoRegistroImobiliario | string | não | Código de registro imobiliário |  |
| codigoTipoMargemPreferencia | integer (int64) | não |  |  |
| criterioJulgamentoId | integer (int64) | sim |  |  |
| descricao | string | sim |  |  |
| inConteudoNacional | boolean | não |  |  |
| incentivoProdutivoBasico | boolean | sim |  |  |
| informacaoComplementar | string | não |  |  |
| itemCategoriaId | integer (int64) | não |  |  |
| materialOuServico | string | sim |  | M, S |
| ncmNbsCodigo | string | não |  |  |
| ncmNbsDescricao | string | não |  |  |
| numeroItem | integer (int32) | sim |  |  |
| orcamentoSigiloso | boolean | sim |  |  |
| patrimonio | string | não | Código de patrimônio |  |
| percentualMargemPreferenciaAdicional | number | não |  |  |
| percentualMargemPreferenciaNormal | number | não |  |  |
| quantidade | number | sim |  |  |
| tipoBeneficioId | string | sim |  | 1, 2, 3, 4, 5 |
| unidadeMedida | string | sim |  |  |
| valorTotal | number | sim |  |  |
| valorUnitarioEstimado | number | sim |  |  |

## Usado como Corpo de Requisição

- [POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens](../sessoes/contratacao/inserir-itens-a-uma-contratacao.md) - Inserir Itens a uma Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
