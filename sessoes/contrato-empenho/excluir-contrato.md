---
section_id: "6.5.3"
source_type: "manual+openapi"
group: "Serviços de Contrato/Empenho"
title: "Excluir Contrato"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}"
page_start: 281
page_end: 282
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir Contrato

## Resumo
Serviço que permite remover um contrato/empenho. Este serviço será acionado por.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: [`ExclusaoDTO`](../../schemas/exclusao-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `justificativa` | string | sim |

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
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `sections/6-5-3-excluir-contrato-empenho.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
