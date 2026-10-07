---
section_id: "6.6.7"
source_type: "manual+openapi"
group: "Serviço de Termo de Contrato"
title: "Excluir Arquivo/Documento de Termo de Contrato"
method: "DELETE"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/{sequencialDocumento}"
page_start: 355
page_end: 356
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Excluir Arquivo/Documento de Termo de Contrato

## Resumo
Serviço que permite remover um documento/arquivo pertencente a um termo de.

## Endpoint
`DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/{sequencialDocumento}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencial` | path | integer | sim |
| `sequencialTermo` | path | integer | sim |
| `sequencialDocumento` | path | integer | sim |

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
- `sections/6-6-7-excluir-documento-de-um-termo-de-contrato.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
