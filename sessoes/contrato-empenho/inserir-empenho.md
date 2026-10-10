---
section_id: "14.1"
source_type: "manual+openapi"
group: "Empenho"
title: "Inserir Empenho"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Empenho

## Resumo
Serviço que permite incluir um empenho para um respectivo Contrato. Este serviço será acionado por qualquer plataforma digital credenciada.

## Endpoint
`POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencialContrato` | path | integer | sim |

## Corpo da requisição
Schema OpenAPI: lista `empenhos`.

| Campo | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- |
| `empenhos` | array | sim | Lista de metadados dos empenhos |
| `empenhos[].numeroEmpenho` | string (50) | sim | Número do empenho |
| `empenhos[].tipoPessoa` | string (2) | sim | PJ - Pessoa jurídica; PF - Pessoa física; PE - Pessoa estrangeira |
| `empenhos[].niCredorFornecedor` | string (30) | sim | CNPJ, CPF ou identificador estrangeiro do credor/fornecedor |
| `empenhos[].nomeCredorFornecedor` | string (250) | sim | Nome do credor/fornecedor |
| `empenhos[].numeroPlanoInterno` | string (50) | não | Número do Plano Interno |
| `empenhos[].codigoNaturezaDespesa` | string (10) | não | Código da natureza de despesa |
| `empenhos[].dataEmissaoEmpenho` | string (date-time) | sim | Data/Hora da emissão do empenho |
| `empenhos[].valorTotal` | number | sim | Valor total do empenho |
| `empenhos[].valorSubItem` | number | não | Valor do subelemento |
| `empenhos[].codigoEmenda` | string (50) | não | Código da Emenda Parlamentar |

## Resposta
Schema OpenAPI: `object`

| Campo | Tipo | Descrição |
| --- | --- | --- |
| `location` | string (255) | Endereço HTTP do recurso criado |

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
- Manual de Integração do PNCP v2.6, seção 14.1.
- `raw/datasets/pncp-openapi.json`
