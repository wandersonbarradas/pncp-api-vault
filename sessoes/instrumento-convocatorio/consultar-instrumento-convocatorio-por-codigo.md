---
section_id: "5.1.1"
source_type: "manual+openapi"
group: "Instrumento Convocatório"
title: "Consultar instrumento convocatório por código"
method: "GET"
endpoint: "/v1/tipos-instrumentos-convocatorios/{id}"
page_start: 41
page_end: 44
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar instrumento convocatório por código

## Resumo
Serviço que permite consultar um instrumento convocatório pelo seu código.

## Endpoint
`GET /v1/tipos-instrumentos-convocatorios/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`TipoInstrumentoConvocatorioDTO`](../../schemas/tipo-instrumento-convocatorio-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `nome` | string | não |
| `descricao` | string | não |
| `obrigatoriedadeDataAberturaPropostaNome` | string | não |
| `obrigatoriedadeDataEncerramentoPropostaNome` | string | não |
| `dataInclusao` | string (date-time) | não |
| `dataAtualizacao` | string (date-time) | não |
| `statusAtivo` | boolean | não |

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
- `sections/5-1-1-consultar-instrumento-convocatorio-por-codigo.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
