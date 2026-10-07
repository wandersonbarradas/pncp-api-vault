---
section_id: "6.3.11"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Retificar Item de Contratação"
method: "PUT"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}"
page_start: 178
page_end: 182
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Item de Contratação

## Resumo
Serviço para retificar um item de uma contratação. Ou utilizado para alterar a situação do.

## Endpoint
`PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `numeroItem` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarCompraItemDTO`](../../schemas/alterar-compra-item-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `numeroItem` | integer (int32) | sim |
| `materialOuServico` | string | sim |
| `tipoBeneficioId` | string | sim |
| `incentivoProdutivoBasico` | boolean | sim |
| `descricao` | string | sim |
| `quantidade` | number | sim |
| `unidadeMedida` | string | sim |
| `orcamentoSigiloso` | boolean | sim |
| `valorUnitarioEstimado` | number | sim |
| `valorTotal` | number | sim |
| `situacaoCompraItemId` | string | sim |
| `criterioJulgamentoId` | integer (int64) | sim |
| `justificativa` | string | não |
| `patrimonio` | string | não |
| `codigoRegistroImobiliario` | string | não |
| `itemCategoriaId` | integer (int64) | não |
| `aplicabilidadeMargemPreferenciaNormal` | boolean | não |
| `aplicabilidadeMargemPreferenciaAdicional` | boolean | não |
| `codigoTipoMargemPreferencia` | integer (int64) | não |
| `percentualMargemPreferenciaNormal` | number | não |
| `percentualMargemPreferenciaAdicional` | number | não |
| `inConteudoNacional` | boolean | não |
| `ncmNbsCodigo` | string | não |
| `ncmNbsDescricao` | string | não |
| `catalogoId` | integer (int64) | não |
| `categoriaItemCatalogoId` | integer (int64) | não |
| `catalogoCodigoItem` | string | não |
| `informacaoComplementar` | string | não |

## Resposta
Schema OpenAPI: `object`

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
- `sections/6-3-11-retificar-item-de-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
