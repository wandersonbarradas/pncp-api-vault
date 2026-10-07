---
section_id: "6.5.11"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Inserir Instrumento de Cobrança de um Contrato/Empenho"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca"
page_start: 298
page_end: 300
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Instrumento de Cobrança de um Contrato/Empenho

## Resumo
Serviço que permite incluir um instrumento de cobrança de um contrato/empenho. Este.

## Endpoint
`POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencialContrato` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`IncluirInstrumentoCobrancaContratoDTO`](../../schemas/incluir-instrumento-cobranca-contrato-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `tipoInstrumentoCobrancaId` | integer (int64) | sim |
| `numeroInstrumentoCobranca` | string | não |
| `chaveNFe` | string | não |
| `dataEmissaoDocumento` | string | não |
| `observacao` | string | não |

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
- `sections/6-5-11-inserir-instrumento-de-cobranca-de-um-contrato-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
