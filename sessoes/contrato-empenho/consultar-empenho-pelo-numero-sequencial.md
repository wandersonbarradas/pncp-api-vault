---
section_id: "14.4"
source_type: "manual+openapi"
group: "Empenho"
title: "Consultar Empenho pelo Número Sequencial"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos/{sequencialEmpenho}"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Empenho pelo Número Sequencial

## Resumo
Serviço que permite consultar um empenho específico pertencente a um contra-.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos/{sequencialEmpenho}`

## Parâmetros de entrada
Não há parâmetros documentados na OpenAPI para esta operação.

## Corpo da requisição
Não se aplica.

## Resposta
Retorna `cnpj`, `ano`, `sequencialContrato`, `sequencialEmpenho`, `numeroEmpenho`, `situacaoEmpenhoId`, `situacaoEmpenhoNome`, `dataSituacaoEmpenho`, `tipoPessoa`, `niCredorFornecedor`, `nomeCredorFornecedor`, `numeroPlanoInterno`, `codigoNaturezaDespesa`, `dataEmissaoEmpenho`, `valorTotal`, `valorSubItem`, `codigoEmenda`, `fonteEmenda`, `statusResponseEmenda`, `jsonResponseEmenda`, `dataConsultaEmenda`, `dataInclusao`, `dataAtualizacao` e o objeto `emendaParlamentar`.

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
curl -k -X GET "${BASE_URL}/v1/orgaos/10000000000003/contratos/2025/1/empenhos/1" \
-H "Accept: */*"
```

## Notas de normalização
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Endpoint reclassificado de `openapi-missing` para `openapi-confirmed` após a versão 2.6 do manual.

## Fontes
- Manual de Integração do PNCP v2.6, seção 14.4.
- `raw/datasets/pncp-openapi.json`
