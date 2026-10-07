---
section_id: "6.4.4"
source_type: "manual+openapi"
group: "Serviços de Ata"
title: "Excluir Ata de Registro de Preço"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}"
page_start: 242
page_end: 244
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir Ata de Registro de Preço

## Resumo
Serviço que permite remover uma ata de registro de preço. Não será permitida a.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `anoCompra` | path | integer | sim |
| `sequencialCompra` | path | integer | sim |
| `sequencialAta` | path | integer | sim |

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
- `sections/6-4-4-excluir-ata-de-registro-de-preco.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
