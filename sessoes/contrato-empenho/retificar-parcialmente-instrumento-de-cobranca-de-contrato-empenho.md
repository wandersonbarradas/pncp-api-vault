---
section_id: "6.5.17"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Retificar Parcialmente Instrumento de Cobrança de Contrato/Empenho"
method: "PATCH"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}"
page_start: 320
page_end: 325
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Parcialmente Instrumento de Cobrança de Contrato/Empenho

## Resumo
Serviço que permite retificar parcialmente um contrato/empenho. Além da justificativa,.

## Endpoint
`PATCH /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencialContrato` | path | integer | sim |
| `sequencialInstrumentoCobranca` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`RetificarInstrumentoCobrancaContratoDTO`](../../schemas/retificar-instrumento-cobranca-contrato-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `numeroInstrumentoCobranca` | string | não |
| `dataEmissaoDocumento` | string | não |
| `observacao` | string | não |
| `justificativa` | string | não |
| `tipoInstrumentoCobrancaId` | integer (int64) | não |
| `chaveNFe` | string | não |

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
- `sections/6-5-17-retificar-parcialmente-um-contrato-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
