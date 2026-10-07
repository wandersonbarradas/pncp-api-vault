---
section_id: "6.5.13"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Excluir Instrumento de Cobrança de Contrato/Empenho"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}"
page_start: 302
page_end: 303
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir Instrumento de Cobrança de Contrato/Empenho

## Resumo
Serviço que permite remover um instrumento de cobrança de um contrato/empenho.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencialContrato` | path | integer | sim |
| `sequencialInstrumentoCobranca` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`ExcluirInstrumentoCobrancaContratoDTO`](../../schemas/excluir-instrumento-cobranca-contrato-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `justificativa` | string | não |

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
- `sections/6-5-13-excluir-instrumento-de-cobranca-de-contrato-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
