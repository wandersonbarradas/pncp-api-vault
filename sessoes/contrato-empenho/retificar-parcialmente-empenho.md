---
section_id: "14.2"
source_type: "manual+openapi"
group: "Empenho"
title: "Retificar Parcialmente Empenho"
method: "PATCH"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos/{sequencialEmpenho}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Retificar Parcialmente Empenho

## Resumo
Serviço que permite retificar um empenho. Além da justificativa, pelo menos um dos campos relacionados ao empenho deve ser enviado para retificação. Este serviço será acionado por qualquer plataforma digital credenciada.

## Endpoint
`PATCH /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos/{sequencialEmpenho}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencialContrato` | path | integer | sim |
| `sequencialEmpenho` | path | integer | sim |

## Corpo da requisição

| Campo | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- |
| `justificativa` | string (255) | sim | Motivo/justificativa para a retificação do empenho |
| `numeroEmpenho` | string (50) | não | Número do empenho |
| `tipoPessoa` | string (2) | não | PJ - Pessoa jurídica; PF - Pessoa física; PE - Pessoa estrangeira |
| `niCredorFornecedor` | string (30) | não | CNPJ, CPF ou identificador de empresa estrangeira |
| `nomeCredorFornecedor` | string (250) | não | Nome do credor/fornecedor |
| `numeroPlanoInterno` | string (50) | não | Número do Plano Interno |
| `codigoNaturezaDespesa` | string (10) | não | Código da natureza de despesa |
| `dataEmissaoEmpenho` | string (date-time) | não | Data/Hora da emissão do empenho |
| `valorTotal` | number | não | Valor total do empenho |
| `valorSubItem` | number | não | Valor do subelemento ou subitem |
| `codigoEmenda` | string (50) | não | Código da Emenda Parlamentar |
| `situacaoEmpenhoId` | integer | não | Identificador da situação do empenho (1 – Empenhado / 2 - Cancelado) |
| `dataSituacaoEmpenho` | string (date-time) | não | Data/Hora da situação do empenho |

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
```bash
curl -k -X PATCH "${BASE_URL}/v1/orgaos/10000000000003/contratos/2025/1/empenhos/1" \
-H "Authorization: Bearer access_token" \
-H "Content-Type: application/json" \
-H "Accept: */*" \
--data "@/home/objeto.json"
```

## Notas de normalização
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Método corrigido de `PUT` para `PATCH` conforme a versão 2.6 do manual.

## Fontes
- Manual de Integração do PNCP v2.6, seção 14.2.
- `raw/datasets/pncp-openapi.json`
