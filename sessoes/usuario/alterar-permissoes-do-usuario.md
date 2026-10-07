---
section_id: null
source_type: "openapi"
group: "Usuário"
title: "Alterar permissões do usuário"
method: "PATCH"
endpoint: "/v1/usuarios/{id}/permissoes"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Alterar permissões do usuário

## Resumo
Operação `PATCH /v1/usuarios/{id}/permissoes`.

## Endpoint
`PATCH /v1/usuarios/{id}/permissoes`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`AlterarParcialPermissaoUsuarioDTO`](../../schemas/alterar-parcial-permissao-usuario-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `administrador` | boolean | não |
| `gestaoEnteAutorizado` | boolean | não |
| `statusBloqueado` | boolean | não |
| `incluirPermissoes` | array | não |
| `removerPermissoes` | array | não |

## Resposta
A OpenAPI capturada não descreve um schema de resposta de negócio específico para `200`, ou a operação está disponível apenas no manual local.

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
- Endpoint presente na OpenAPI atual, sem seção correspondente no manual segmentado local.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
