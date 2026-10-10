---
section_id: "14.3"
source_type: "manual+openapi"
group: "Empenho"
title: "Excluir Empenho"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/empenhos/{sequencialEmpenho}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir Empenho

## Resumo
Serviço que permite remover um empenho. Este serviço será acionado por qualquer plataforma digital credenciada.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/empenhos/{sequencialEmpenho}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `sequencialEmpenho` | path | integer | sim |

## Corpo da requisição

| Campo | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- |
| `justificativa` | string (255) | sim | Motivo/justificativa da exclusão do empenho |

## Resposta
Schema OpenAPI: `object`

## Códigos de retorno

| HTTP |
| --- |
| `200` |
| `400` |
| `401` |
| `422` |
| `500` |

## Exemplo cURL
Exemplo não disponível na fonte consolidada atual.

## Notas de normalização
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Endpoint reclassificado de `openapi-missing` para `openapi-confirmed` após a versão 2.6 do manual.

## Fontes
- Manual de Integração do PNCP v2.6, seção 14.3.
- `raw/datasets/pncp-openapi.json`
