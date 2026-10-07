---
section_id: "5.19.1"
source_type: "manual+openapi"
group: "Regra de conformidade entre Instrumento Convocatório e Modo de"
title: "Consultar conformidade entre instrumentos convocatórios e modos de disputa por código"
method: "GET"
endpoint: "/v1/tipo-instrumento-convocatorio-modo-disputa/{tipoInstrumentoConvocatorioId}/{modoDisputaId}"
page_start: 83
page_end: 87
status: "normalizado"
reconciliation_status: "openapi-confirmed"
---

# Consultar conformidade entre instrumentos convocatórios e modos de disputa por código

## Resumo
Modos de Disputa por Código.

## Endpoint
`GET /v1/tipo-instrumento-convocatorio-modo-disputa/{tipoInstrumentoConvocatorioId}/{modoDisputaId}`

## Parâmetros de entrada

| Nome | Local | Tipo | Obrigatório |
| --- | --- | --- | --- |
| `tipoInstrumentoConvocatorioId` | path | integer | sim |
| `modoDisputaId` | path | integer | sim |

## Corpo da requisição
Não se aplica.

## Resposta
Schema OpenAPI: [`TipoInstrumentoConvocatorioModoDisputaDTO`](../../schemas/tipo-instrumento-convocatorio-modo-disputa-dto.md)

| Campo | Tipo | Obrigatório |
| --- | --- | --- |
| `tipoInstrumentoConvocatorio` | DominioGenericoResumidoDTO | não |
| `modoDisputa` | DominioGenericoResumidoDTO | não |
| `dataInclusao` | string (date-time) | não |

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
- `sections/5-19-1-consultar-conformidade-entre-instrumentos-convocatorios-e.md`
- `endpoints.json`
- `raw/datasets/pncp-openapi.json`
