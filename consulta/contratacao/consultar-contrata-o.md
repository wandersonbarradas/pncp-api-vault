---
title: "Consultar Contratação"
surface: "consulta"
base_path: "/api/consulta/v1"
group: "Contratação"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}"
source_type: "openapi-consulta"
reconciliation_status: "consulta-openapi-confirmed"
updated: "2026-05-03"
---

# Consultar Contratação

Operação pública de consulta: `GET /api/consulta/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`.

## Endpoint

`GET /api/consulta/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`

## Parâmetros

| Nome | Local | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- | --- |
| `cnpj` | path | string | sim |  |
| `ano` | path | integer (int32) | sim |  |
| `sequencial` | path | integer (int32) | sim |  |

## Corpo da Requisição

Não se aplica.

## Respostas

| HTTP | Descrição | Schema |
| --- | --- | --- |
| `200` | OK | [RecuperarCompraDTO](../../schemas/consulta/recuperar-compra-dto.md) |
| `204` | No Content | `object` |
| `400` | Bad Request | `oneOf: object, [RespostaErroValidacaoDTO](../../schemas/consulta/resposta-erro-validacao-dto.md)` |
| `401` | Unauthorized | `string` |
| `422` | Unprocessable Entity | `object` |
| `500` | Internal Server Error | `string` |

## Exemplo

```bash
curl -X GET 'https://pncp.gov.br/api/consulta/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}'
```

## Relação com api/pncp

A rota equivalente em `api/pncp/v1` retorna redirecionamento lógico para esta superfície de consulta quando usada para a contratação principal publicada.

Sub-recursos como itens, documentos e histórico permanecem documentados na superfície `api/pncp` no vault atual.

Links relacionados:

- [Consultar uma Contratação](../../sessoes/contratacao/consultar-uma-contratacao.md)
- [Consultar Todos os Itens de Contratação](../../sessoes/contratacao/consultar-todos-os-itens-de-contratacao.md)
- [Consultar Documentos de Contratação](../../sessoes/contratacao/consultar-documentos-de-contratacao.md)
- [Consultar Histórico de Contratação](../../sessoes/contratacao/consultar-historico-de-contratacao.md)

## Fonte

- OpenAPI Consulta PNCP: <https://pncp.gov.br/api/consulta/v3/api-docs>
