---
title: "Consultar Atas de Registro de Preço por Data de Atualização Global"
surface: "consulta"
base_path: "/api/consulta/v1"
group: "Ata"
method: "GET"
endpoint: "/v1/atas/atualizacao"
source_type: "openapi-consulta"
reconciliation_status: "consulta-openapi-confirmed"
updated: "2026-05-03"
---

# Consultar Atas de Registro de Preço por Data de Atualização Global

Operação pública de consulta: `GET /api/consulta/v1/atas/atualizacao`.

## Endpoint

`GET /api/consulta/v1/atas/atualizacao`

## Parâmetros

| Nome | Local | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- | --- |
| `dataInicial` | query | string | sim |  |
| `dataFinal` | query | string | sim |  |
| `idUsuario` | query | integer (int64) | não |  |
| `cnpj` | query | string | não |  |
| `codigoUnidadeAdministrativa` | query | string | não |  |
| `pagina` | query | integer (int32) | sim |  |
| `tamanhoPagina` | query | integer (int32) | não |  |

## Corpo da Requisição

Não se aplica.

## Respostas

| HTTP | Descrição | Schema |
| --- | --- | --- |
| `200` | OK | [PaginaRetornoAtaRegistroPrecoPeriodoDTO](../../schemas/consulta/pagina-retorno-ata-registro-preco-periodo-dto.md) |
| `204` | No Content | `object` |
| `400` | Bad Request | `oneOf: object, [RespostaErroValidacaoDTO](../../schemas/consulta/resposta-erro-validacao-dto.md)` |
| `401` | Unauthorized | `string` |
| `422` | Unprocessable Entity | `object` |
| `500` | Internal Server Error | `string` |

## Exemplo

```bash
curl -X GET 'https://pncp.gov.br/api/consulta/v1/atas/atualizacao'
```

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
