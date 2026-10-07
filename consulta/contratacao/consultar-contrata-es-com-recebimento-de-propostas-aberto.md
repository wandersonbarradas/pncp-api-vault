---
title: "Consultar Contratações com Recebimento de Propostas Aberto"
surface: "consulta"
base_path: "/api/consulta/v1"
group: "Contratação"
method: "GET"
endpoint: "/v1/contratacoes/proposta"
source_type: "openapi-consulta"
reconciliation_status: "consulta-openapi-confirmed"
updated: "2026-05-03"
---

# Consultar Contratações com Recebimento de Propostas Aberto

Operação pública de consulta: `GET /api/consulta/v1/contratacoes/proposta`.

## Endpoint

`GET /api/consulta/v1/contratacoes/proposta`

## Parâmetros

| Nome | Local | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- | --- |
| `dataFinal` | query | string | sim |  |
| `codigoModalidadeContratacao` | query | integer (int64) | não |  |
| `uf` | query | string | não |  |
| `codigoMunicipioIbge` | query | string | não |  |
| `cnpj` | query | string | não |  |
| `codigoUnidadeAdministrativa` | query | string | não |  |
| `idUsuario` | query | integer (int64) | não |  |
| `pagina` | query | integer (int32) | sim |  |
| `tamanhoPagina` | query | integer (int32) | não |  |

## Corpo da Requisição

Não se aplica.

## Respostas

| HTTP | Descrição | Schema |
| --- | --- | --- |
| `200` | OK | [PaginaRetornoRecuperarCompraPublicacaoDTO](../../schemas/consulta/pagina-retorno-recuperar-compra-publicacao-dto.md) |
| `204` | No Content | `object` |
| `400` | Bad Request | `oneOf: object, [RespostaErroValidacaoDTO](../../schemas/consulta/resposta-erro-validacao-dto.md)` |
| `401` | Unauthorized | `string` |
| `422` | Unprocessable Entity | `object` |
| `500` | Internal Server Error | `string` |

## Exemplo

```bash
curl -X GET 'https://pncp.gov.br/api/consulta/v1/contratacoes/proposta'
```

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
