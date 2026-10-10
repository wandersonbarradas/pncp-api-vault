---
section_id: "14.5"
source_type: "manual+openapi"
group: "Empenho"
title: "Consultar Empenhos"
method: "GET"
endpoint: "/v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar Empenhos

## Resumo
Serviço que permite consultar empenhos pertencentes a um contrato/empenho.

## Endpoint
`GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/empenhos`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `ano` | path | integer | sim |
| `sequencialContrato` | path | integer | sim |
| `pagina` | query | integer | não |
| `tamanhoPagina` | query | integer | não |

## Corpo da requisição
Não se aplica.

## Resposta
Retorna `data` (lista de empenhos) com `cnpj`, `ano`, `sequencialContrato`, `sequencialEmpenho`, `numeroEmpenho`, `situacaoEmpenhoId`, `situacaoEmpenhoNome`, `dataSituacaoEmpenho`, `tipoPessoa`, `niCredorFornecedor`, `nomeCredorFornecedor`, `numeroPlanoInterno`, `codigoNaturezaDespesa`, `dataEmissaoEmpenho`, `valorTotal`, `valorSubItem`, `codigoEmenda`, `fonteEmenda`, `statusResponseEmenda`, `jsonResponseEmenda`, `dataConsultaEmenda`, `dataInclusao`, `dataAtualizacao` e `emendaParlamentar`. Também retorna `totalRegistros`, `totalPaginas`, `numeroPagina`, `paginasRestantes` e `empty`.

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
curl -k -X GET "${BASE_URL}/v1/orgaos/10000000000003/contratos/2025/1/empenhos" \
-H "Accept: */*"
```

## Notas de normalização
- Conteúdo consolidado a partir da seção do manual e da OpenAPI atual.
- Endpoint reclassificado de `openapi-missing` para `openapi-confirmed` após a versão 2.6 do manual.

## Fontes
- Manual de Integração do PNCP v2.6, seção 14.5.
- `raw/datasets/pncp-openapi.json`
