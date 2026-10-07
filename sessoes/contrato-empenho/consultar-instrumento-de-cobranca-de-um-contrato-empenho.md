---
section_id: "6.5.14"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Consultar Instrumento de Cobrança de um Contrato/Empenho"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}"
page_start: 303
page_end: 307
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Instrumento de Cobrança de um Contrato/Empenho

## Resumo
Serviço que permite consultar um instrumento de cobrança específico pertencente a.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencialContrato` | path | integer | sim |
| `sequencialInstrumentoCobranca` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`ConsultarInstrumentoCobrancaDTO`](../../schemas/consultar-instrumento-cobranca-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `cnpj` | string | não |
| `ano` | integer (int32) | não |
| `sequencialContrato` | integer (int32) | não |
| `sequencialInstrumentoCobranca` | integer (int32) | não |
| `tipoInstrumentoCobranca` | TipoInstrumentoCobrancaDTO | não |
| `numeroInstrumentoCobranca` | string | não |
| `dataEmissaoDocumento` | string (date) | não |
| `observacao` | string | não |
| `chaveNFe` | string | não |
| `fonteNFe` | integer (int64) | não |
| `dataConsultaNFe` | string (date-time) | não |
| `statusResponseNFe` | string | não |
| `jsonResponseNFe` | string | não |
| `notaFiscalEletronica` | NotaFiscalEletronicaConsultaDTO | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |

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
- `sections/6-5-14-consultar-instrumento-de-cobranca-de-um-contrato-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
