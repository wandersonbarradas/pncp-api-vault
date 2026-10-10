---
section_id: null
source_type: "openapi"
group: "Intenção de Registro de Preços"
title: "Inserir Intenção de Registro de Preço"
method: "POST"
endpoint: "/v1/orgaos/{cnpj}/irp"
page_start: null
page_end: null
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Inserir Intenção de Registro de Preço

## Resumo
Operação `POST /v1/orgaos/{cnpj}/irp`.

## Endpoint
`POST /v1/orgaos/{cnpj}/irp`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `cnpj` | path | string | sim |
| `Titulo-Documento` | header | string | sim |
| `Tipo-Documento-Id` | header | integer (int64) | sim |

## Corpo da requisição
Content-Type: `multipart/form-data`

| Campo | Tipo | Obrigatório | Descrição |
| --- | --- | --- | --- |
| `irp` | string (binary) | sim | O arquivo com os dados da IRP deve utilizar o formato JSON, conforme o exemplo:  {   "codigoUnidadeGerenciadora": "string",   "tipoInstrumentoConvocatorioId"... |
| `documento` | string (binary) | sim |  |

Exemplo de `irp`:
```json
O arquivo com os dados da IRP deve utilizar o formato JSON, conforme o exemplo:

{
  "codigoUnidadeGerenciadora": "string",
  "tipoInstrumentoConvocatorioId": 0,
  "modalidadeId": 0,
  "amparoLegalId": 0,
  "modoDisputaId": 0,
  "numeroIrp": "string",
  "anoIrp": 0,
  "numeroProcesso": "string",
  "objetoIrp": "string",
  "informacaoComplementar": "string",
  "indicadorPossibilidadeAdesao": true,
  "dataHoraFinalManifestacaoInteresse": "2026-12-30T10:00:00",
  "urlPlataformaOrigem": "string",
  "urlProcessoEletronico": "string",
  "itensIrp": [
    {
      "numeroItem": 0,
      "materialOuServico": "M",
      "categoriaItemId": 0,
      "criterioJulgamentoId": 0,
      "aplicabilidadeMargemPreferencia": true,
      "exigenciaConteudoNacional": true,
      "descricao": "string",
      "informacaoComplementar": "string",
      "unidadeFornecimento": "string",
      "valorUnitarioEstimado": 0,
      "indicadorValorSigiloso": true,
      "codigoGtin": "string",
      "codigoNcmNbs": "string",
      "descricaoNcmNbs": "string",
      "catalogoId": 0,
      "codigoItemCatalogo": "string"
    }
  ]
}

```

## Resposta
Schema OpenAPI: `object`

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
- Endpoint presente na OpenAPI atual.
- Nome do arquivo segue a descrição do Swagger; `section_id` foi preservado apenas no frontmatter quando disponível.

## Fontes
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
