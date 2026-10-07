---
section_id: "6.1.2"
source_type: "manual+openapi"
group: "Serviços de Usuário"
title: "Consultar usuário por ID"
method: "GET"
endpoint: "/v1/usuarios/{id}"
page_start: 113
page_end: 114
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar usuário por ID

## Resumo
Serviço que permite consultar os dados de um usuário pelo id. Disponível para o próprio.

## Endpoint
`GET /v1/usuarios/{id}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `id` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`CredenciaisDTO`](../../schemas/credenciais-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `id` | integer (int64) | não |
| `login` | string | não |
| `nome` | string | não |
| `cpfCnpj` | string | não |
| `email` | string | não |
| `administrador` | boolean | não |
| `gestaoEnteAutorizado` | boolean | não |
| `statusBloqueado` | boolean | não |
| `token` | string | não |
| `senha` | string | não |
| `telefone` | string | não |
| `cnpjVinculado` | string | não |
| `entesAutorizados` | array | não |
| `nivelGovBR` | string | não |
| `permissoes` | array | não |

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
- `sections/6-1-2-consultar-usuario-por-id.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
