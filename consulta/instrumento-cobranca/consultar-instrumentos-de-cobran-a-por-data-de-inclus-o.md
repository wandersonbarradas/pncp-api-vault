---
title: "Consultar Instrumentos de Cobrança por Data de Inclusão"
surface: "consulta"
base_path: "/api/consulta/v1"
group: "Instrumento de Cobrança"
method: "GET"
endpoint: "/v1/instrumentoscobranca/inclusao"
source_type: "openapi-consulta"
reconciliation_status: "consulta-openapi-confirmed"
updated: "2026-05-03"
---

# Consultar Instrumentos de Cobrança por Data de Inclusão

Operação pública de consulta: `GET /api/consulta/v1/instrumentoscobranca/inclusao`.

## Endpoint

`GET /api/consulta/v1/instrumentoscobranca/inclusao`

## Parâmetros

| Nome | Local | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- | --- |
| `dataInicial` | query | string | sim |  |
| `dataFinal` | query | string | sim |  |
| `tipoInstrumentoCobranca` | query | integer (int64) | não |  |
| `cnpjOrgao` | query | string | não |  |
| `pagina` | query | integer (int32) | sim |  |
| `tamanhoPagina` | query | integer (int32) | não |  |

## Corpo da Requisição

Não se aplica.

## Respostas

| HTTP | Descrição | Schema |
| --- | --- | --- |
| `200` | OK | [PaginaRetornoConsultarInstrumentoCobrancaDTO](../../schemas/consulta/pagina-retorno-consultar-instrumento-cobranca-dto.md) |
| `204` | No Content | `object` |
| `400` | Bad Request | `oneOf: object, [RespostaErroValidacaoDTO](../../schemas/consulta/resposta-erro-validacao-dto.md)` |
| `401` | Unauthorized | `string` |
| `422` | Unprocessable Entity | `object` |
| `500` | Internal Server Error | `string` |

## Exemplo

```bash
curl -X GET 'https://pncp.gov.br/api/consulta/v1/instrumentoscobranca/inclusao'
```

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
