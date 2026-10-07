---
title: "AlterarCompraItemDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# AlterarCompraItemDTO

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
| justificativa | string | não |  |  |
| materialOuServico | string | sim |  | M, S |
| ncmNbsCodigo | string | não |  |  |
| ncmNbsDescricao | string | não |  |  |
| numeroItem | integer (int32) | sim |  |  |
| orcamentoSigiloso | boolean | sim |  |  |
| patrimonio | string | não | Código de patrimônio |  |
| percentualMargemPreferenciaAdicional | number | não |  |  |
| percentualMargemPreferenciaNormal | number | não |  |  |
| quantidade | number | sim |  |  |
| situacaoCompraItemId | string | sim |  | 1, 2, 3, 4, 5 |
| tipoBeneficioId | string | sim |  | 1, 2, 3, 4, 5 |
| unidadeMedida | string | sim |  |  |
| valorTotal | number | sim |  |  |
| valorUnitarioEstimado | number | sim |  |  |

## Usado como Corpo de Requisição

- [PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/contratacao/retificar-item-de-contratacao.md) - Retificar Item de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
