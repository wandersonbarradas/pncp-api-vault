---
section_id: "6.3.12"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Retificar Parcialmente um Item de Contratação"
method: "PATCH"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}"
page_start: 182
page_end: 187
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Parcialmente um Item de Contratação

## Resumo
Serviço para retificar parcialmente um item de uma contratação. Pode ser utilizado para.

## Endpoint
`PATCH /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `numeroItem` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarCompraItemParcialDTO`](../../schemas/alterar-compra-item-parcial-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `materialOuServico` | string | não |
| `tipoBeneficioId` | string | não |
| `incentivoProdutivoBasico` | boolean | não |
| `descricao` | string | não |
| `quantidade` | number | não |
| `unidadeMedida` | string | não |
| `valorUnitarioEstimado` | number | não |
| `valorTotal` | number | não |
| `orcamentoSigiloso` | boolean | não |
| `situacaoCompraItemId` | string | não |
| `criterioJulgamentoId` | integer (int64) | não |
| `patrimonio` | string | não |
| `codigoRegistroImobiliario` | string | não |
| `itemCategoriaId` | integer (int64) | não |
| `justificativa` | string | não |
| `aplicabilidadeMargemPreferenciaNormal` | boolean | não |
| `aplicabilidadeMargemPreferenciaAdicional` | boolean | não |
| `codigoTipoMargemPreferencia` | integer (int64) | não |
| `percentualMargemPreferenciaNormal` | number | não |
| `percentualMargemPreferenciaAdicional` | number | não |
| `ncmNbsCodigo` | string | não |
| `ncmNbsDescricao` | string | não |
| `inConteudoNacional` | boolean | não |
| `catalogoId` | integer (int64) | não |
| `categoriaItemCatalogoId` | integer (int64) | não |
| `catalogoCodigoItem` | string | não |
| `informacaoComplementar` | string | não |

## Resposta
A OpenAPI capturada não descreve um schema de resposta de negócio específico para `200`, ou a operação está disponível apenas no manual local.

## Códigos de retorno

| HTTP |
| --- |
| `400` |
| `422` |
| `204` |
| `500` |
| `401` |
| `200` |

## Exemplo cURL
Exemplo não disponível na fonte consolidada atual.

## Notas de normalização
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-3-12-retificar-parcialmente-um-item-de-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
