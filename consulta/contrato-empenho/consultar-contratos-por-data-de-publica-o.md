---
title: "Consultar Contratos por Data de Publicação"
surface: "consulta"
base_path: "/api/consulta/v1"
group: "Contrato/Empenho"
method: "GET"
endpoint: "/v1/contratos"
source_type: "openapi-consulta"
reconciliation_status: "consulta-openapi-confirmed"
updated: "2026-05-03"
---

# Consultar Contratos por Data de Publicação

Operação pública de consulta: `GET /api/consulta/v1/contratos`.

## Endpoint

`GET /api/consulta/v1/contratos`

## Parâmetros

| Nome | Local | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- | --- |
| `dataInicial` | query | string | sim |  |
| `dataFinal` | query | string | sim |  |
| `cnpjOrgao` | query | string | não |  |
| `codigoUnidadeAdministrativa` | query | string | não |  |
| `usuarioId` | query | integer (int64) | não |  |
| `pagina` | query | integer (int32) | sim |  |
| `tamanhoPagina` | query | integer (int32) | não |  |

## Corpo da Requisição

Não se aplica.

## Respostas

| HTTP | Descrição | Schema |
| --- | --- | --- |
| `200` | OK | [PaginaRetornoRecuperarContratoDTO](../../schemas/consulta/pagina-retorno-recuperar-contrato-dto.md) |
| `204` | No Content | `object` |
| `400` | Bad Request | `oneOf: object, [RespostaErroValidacaoDTO](../../schemas/consulta/resposta-erro-validacao-dto.md)` |
| `401` | Unauthorized | `string` |
| `422` | Unprocessable Entity | `object` |
| `500` | Internal Server Error | `string` |

## Exemplo

```bash
curl -X GET 'https://pncp.gov.br/api/consulta/v1/contratos'
```

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
