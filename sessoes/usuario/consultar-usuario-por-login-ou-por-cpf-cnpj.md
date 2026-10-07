---
section_id: "6.1.3"
source_type: "manual+openapi"
group: "Serviços de Usuário"
title: "Consultar usuário por login ou por CPF/CNPJ"
method: "GET"
endpoint: "/v1/usuarios"
page_start: 115
page_end: 116
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar usuário por login ou por CPF/CNPJ

## Resumo
Serviço que permite consultar os dados de um usuário pelo Login ou por um CPF/CNPJ.

## Endpoint
`GET /v1/usuarios`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `login` | query | string | não |
| `cpfCnpj` | query | string | não |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: `array`

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
- `sections/6-1-3-consultar-usuario-por-login-ou-por-cpf-cnpj.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
