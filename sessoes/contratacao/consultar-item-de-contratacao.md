---
section_id: "6.3.14"
source_type: "manual+openapi"
group: "Serviços de Contratação (Editais, Avisos e Atos)"
title: "Consultar Item de Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}"
page_start: 192
page_end: 196
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Item de Contratação

## Resumo
Serviço para consultar um item específico de uma contratação.

## Endpoint
`GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `numeroItem` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`RecuperarCompraItemSigiloDTO`](../../schemas/recuperar-compra-item-sigilo-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `numeroItem` | integer (int32) | não |
| `descricao` | string | não |
| `materialOuServico` | string | não |
| `materialOuServicoNome` | string | não |
| `valorUnitarioEstimado` | number | não |
| `valorTotal` | number | não |
| `quantidade` | number | não |
| `unidadeMedida` | string | não |
| `orcamentoSigiloso` | boolean | não |
| `itemCategoriaId` | integer (int64) | não |
| `itemCategoriaNome` | string | não |
| `patrimonio` | string | não |
| `codigoRegistroImobiliario` | string | não |
| `criterioJulgamentoId` | integer (int64) | não |
| `criterioJulgamentoNome` | string | não |
| `situacaoCompraItem` | string | não |
| `situacaoCompraItemNome` | string | não |
| `tipoBeneficio` | string | não |
| `tipoBeneficioNome` | string | não |
| `incentivoProdutivoBasico` | boolean | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `temResultado` | boolean | não |
| `imagem` | integer (int32) | não |
| `aplicabilidadeMargemPreferenciaNormal` | boolean | não |
| `aplicabilidadeMargemPreferenciaAdicional` | boolean | não |
| `percentualMargemPreferenciaNormal` | number | não |
| `percentualMargemPreferenciaAdicional` | number | não |
| `ncmNbsCodigo` | string | não |
| `ncmNbsDescricao` | string | não |
| `catalogo` | CatalogoDTO | não |
| `categoriaItemCatalogo` | DominioGenericoDTO | não |
| `catalogoCodigoItem` | string | não |
| `informacaoComplementar` | string | não |
| `tipoMargemPreferencia` | TipoMargemPreferenciaDTO | não |
| `exigenciaConteudoNacional` | boolean | não |

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
- `sections/6-3-14-consultar-item-de-uma-contratacao.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
