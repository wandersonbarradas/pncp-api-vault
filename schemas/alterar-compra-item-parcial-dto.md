---
title: "AlterarCompraItemParcialDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarCompraItemParcialDTO

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
| codigoRegistroImobiliario | string | não |  |  |
| codigoTipoMargemPreferencia | integer (int64) | não |  |  |
| criterioJulgamentoId | integer (int64) | não |  |  |
| descricao | string | não |  |  |
| inConteudoNacional | boolean | não |  |  |
| incentivoProdutivoBasico | boolean | não |  |  |
| informacaoComplementar | string | não |  |  |
| itemCategoriaId | integer (int64) | não |  |  |
| justificativa | string | não |  |  |
| materialOuServico | string | não |  | M, S |
| ncmNbsCodigo | string | não |  |  |
| ncmNbsDescricao | string | não |  |  |
| orcamentoSigiloso | boolean | não |  |  |
| patrimonio | string | não |  |  |
| percentualMargemPreferenciaAdicional | number | não |  |  |
| percentualMargemPreferenciaNormal | number | não |  |  |
| quantidade | number | não |  |  |
| situacaoCompraItemId | string | não |  | 1, 2, 3, 4, 5 |
| tipoBeneficioId | string | não |  | 1, 2, 3, 4, 5 |
| unidadeMedida | string | não |  |  |
| valorTotal | number | não |  |  |
| valorUnitarioEstimado | number | não |  |  |

## Usado como Corpo de Requisição

- [PATCH /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/contratacao/retificar-parcialmente-um-item-de-contratacao.md) - Retificar Parcialmente um Item de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
