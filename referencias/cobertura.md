# Cobertura

Resumo da origem do material presente no vault.

## Origem

- `manual`: 31 arquivos
- `manual+openapi`: 98 arquivos
- `openapi`: 66 arquivos

## Métodos HTTP

- `DELETE`: 26 arquivos
- `GET`: 104 arquivos
- `PATCH`: 16 arquivos
- `POST`: 38 arquivos
- `PUT`: 11 arquivos

## Observações

- `manual+openapi`: sessão do manual reconciliada com operação do Swagger.
- `manual`: operação preservada do manual local sem equivalente claramente exposto na OpenAPI capturada.
- `openapi`: operação presente no Swagger atual sem seção correspondente no manual local.
- `openapi-consulta`: operação presente no Swagger da API pública de Consulta.

## API de Consulta

- Fonte capturada: `referencias/openapi-consulta.json`.
- Swagger/API docs: <https://pncp.gov.br/api/consulta/v3/api-docs>.
- Endpoints normalizados: 12 arquivos em `consulta/`.
- Schemas normalizados: 23 arquivos em `schemas/consulta/`.
- Grupos: `ata` com 2 endpoints; `contratacao` com 4 endpoints; `contrato-empenho` com 2 endpoints; `instrumento-cobranca` com 1 endpoint; `plano-de-contratacao` com 3 endpoints.
- Status: endpoints marcados como `consulta-openapi-confirmed` foram extraídos diretamente da OpenAPI de Consulta capturada em 2026-05-03.

## Reconciliação Seletiva

- `contratacao`: 31 endpoints `openapi-confirmed`; 1 endpoints `openapi-missing`.
- `ata`: 16 endpoints `openapi-confirmed`; 6 endpoints `openapi-missing`.
- `contrato-empenho`: 20 endpoints `openapi-confirmed`; 6 endpoints `openapi-missing`.
- `plano-de-contratacao`: 21 endpoints `openapi-confirmed`.
- `termo-de-contrato`: 13 endpoints `openapi-confirmed`.
- `orgao-entidade`: 9 endpoints `openapi-confirmed`.
- `amparo-legal`: 4 endpoints `openapi-confirmed`.
- `catalogo`: 4 endpoints `openapi-confirmed`.
- `categoria-de-item`: 4 endpoints `openapi-confirmed`.
- `conformidade-instrumento-convocatorio-modalidade-amparo-legal`: 6 endpoints `openapi-confirmed`.
- `conformidade-instrumento-convocatorio-modo-de-disputa`: 4 endpoints `openapi-confirmed`.
- `conformidade-modalidade-criterio-de-julgamento`: 4 endpoints `openapi-confirmed`.
- `conformidade-modalidade-fonte-orcamentaria`: 4 endpoints `openapi-confirmed`.
- `criterio-de-julgamento`: 4 endpoints `openapi-confirmed`.
- `fonte-orcamentaria`: 4 endpoints `openapi-confirmed`.
- `fonte-orcamentaria-da-contratacao`: 4 endpoints `openapi-confirmed`.
- `instrumento-convocatorio`: 4 endpoints `openapi-confirmed`.
- `modalidade-de-contratacao`: 4 endpoints `openapi-confirmed`.
- `modo-de-disputa`: 4 endpoints `openapi-confirmed`.
- `tipo-de-contrato`: 2 endpoints `openapi-missing`.
- `tipo-de-documento`: 2 endpoints `openapi-missing`.
- `tipo-de-instrumento-de-cobranca`: 4 endpoints `openapi-confirmed`.
- `usuario`: 10 endpoints `openapi-confirmed`.
- Todos os blocos foram reconciliados seletivamente contra a OpenAPI pública/local disponível em 2026-05-02.
### Verificação pública do Swagger

Em 2026-05-02, os 6 endpoints `openapi-missing` de `ata` foram verificados contra a especificação pública carregada pelo Swagger em <https://pncp.gov.br/pncp-api/v3/api-docs>. Eles não aparecem na especificação pública atual; permanecem preservados por constarem no manual normalizado.

### Ausentes Verificados na Especificação Pública

- `contrato-empenho`: 20 endpoints `openapi-confirmed`; 6 endpoints `openapi-missing`.
### Avisos de Qualidade

Alguns endpoints preservados do manual normalizado têm `quality_status: needs-review` porque o path ou a seção parecem truncados/incompletos. Eles continuam no vault para rastreabilidade, mas não devem ser usados como referência confiável sem revisão contra fonte oficial original.

## Fontes Complementares

- `referencias/tabelas-de-dominio-pncp.md`: Markdown enxuto extraído do MHTML local da página pública de tabelas de domínio do PNCP, capturada em 2026-05-02.
- `schemas/`: 114 schemas normalizados a partir de `components.schemas` da OpenAPI pública do PNCP.
- `consulta/`: endpoints públicos normalizados da API de Consulta.
- `schemas/consulta/`: schemas normalizados da API de Consulta.
- `referencias/superficies-da-api.md`: guia de escolha entre `api/consulta` e `api/pncp`.
