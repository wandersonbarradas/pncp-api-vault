---
title: "RecuperarCompraItemSigiloDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RecuperarCompraItemSigiloDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 2 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| aplicabilidadeMargemPreferenciaAdicional | boolean | não |  |  |
| aplicabilidadeMargemPreferenciaNormal | boolean | não |  |  |
| catalogo | [CatalogoDTO](./catalogo-dto.md) | não |  |  |
| catalogoCodigoItem | string | não |  |  |
| categoriaItemCatalogo | [DominioGenericoDTO](./dominio-generico-dto.md) | não |  |  |
| codigoRegistroImobiliario | string | não |  |  |
| criterioJulgamentoId | integer (int64) | não |  |  |
| criterioJulgamentoNome | string | não |  |  |
| dataAtualizacao | string (date-time) | não |  |  |
| dataInclusao | string (date-time) | não |  |  |
| descricao | string | não |  |  |
| exigenciaConteudoNacional | boolean | não |  |  |
| imagem | integer (int32) | não |  |  |
| incentivoProdutivoBasico | boolean | não |  |  |
| informacaoComplementar | string | não |  |  |
| itemCategoriaId | integer (int64) | não |  |  |
| itemCategoriaNome | string | não |  |  |
| materialOuServico | string | não |  | M, S |
| materialOuServicoNome | string | não |  |  |
| ncmNbsCodigo | string | não |  |  |
| ncmNbsDescricao | string | não |  |  |
| numeroItem | integer (int32) | não |  |  |
| orcamentoSigiloso | boolean | não |  |  |
| patrimonio | string | não |  |  |
| percentualMargemPreferenciaAdicional | number | não |  |  |
| percentualMargemPreferenciaNormal | number | não |  |  |
| quantidade | number | não |  |  |
| situacaoCompraItem | string | não |  | 1, 2, 3, 4, 5 |
| situacaoCompraItemNome | string | não |  |  |
| temResultado | boolean | não |  |  |
| tipoBeneficio | string | não |  | 1, 2, 3, 4, 5 |
| tipoBeneficioNome | string | não |  |  |
| tipoMargemPreferencia | [TipoMargemPreferenciaDTO](./tipo-margem-preferencia-dto.md) | não |  |  |
| unidadeMedida | string | não |  |  |
| valorTotal | number | não |  |  |
| valorUnitarioEstimado | number | não |  |  |

## Schemas Relacionados

- [CatalogoDTO](./catalogo-dto.md)
- [DominioGenericoDTO](./dominio-generico-dto.md)
- [TipoMargemPreferenciaDTO](./tipo-margem-preferencia-dto.md)

## Usado em Respostas

- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens](../sessoes/contratacao/consultar-todos-os-itens-de-contratacao.md) - Consultar Todos os Itens de Contratação
- `200`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/contratacao/consultar-item-de-contratacao.md) - Consultar Item de Contratação

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
