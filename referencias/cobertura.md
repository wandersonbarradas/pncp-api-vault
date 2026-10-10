# Cobertura

Resumo da origem do material presente no vault.

## Origem

- `manual`: 25 arquivos
- `manual+openapi`: 103 arquivos
- `openapi`: 101 arquivos

## Métodos HTTP

- `DELETE`: 29 arquivos
- `GET`: 122 arquivos
- `PATCH`: 24 arquivos
- `POST`: 45 arquivos
- `PUT`: 9 arquivos

## Observações

- `manual+openapi`: sessão do manual reconciliada com operação do Swagger.
- `manual`: operação preservada do manual local sem equivalente claramente exposto na OpenAPI capturada.
- `openapi`: operação presente no Swagger atual sem seção correspondente no manual local.
- `openapi-consulta`: operação presente no Swagger da API pública de Consulta.

## API de Consulta

- Fonte capturada: `referencias/openapi-consulta.json`.
- Swagger/API docs: <https://pncp.gov.br/api/consulta/v3/api-docs>.
- Endpoints normalizados: 12 arquivos em `consulta/`.
- Grupos: `ata` com 2 endpoints; `contratacao` com 4 endpoints; `contrato-empenho` com 2 endpoints; `instrumento-cobranca` com 1 endpoint; `plano-de-contratacao` com 3 endpoints.

## Reconciliação Seletiva

- `amparo-legal`: openapi-confirmed: 4 endpoints
- `ata`: openapi-confirmed: 16 endpoints; openapi-missing: 6 endpoints
- `catalogo`: openapi-confirmed: 4 endpoints
- `categoria-de-item`: openapi-confirmed: 4 endpoints
- `conformidade-instrumento-convocatorio-modalidade-amparo-legal`: openapi-confirmed: 6 endpoints
- `conformidade-instrumento-convocatorio-modo-de-disputa`: openapi-confirmed: 4 endpoints
- `conformidade-modalidade-criterio-de-julgamento`: openapi-confirmed: 4 endpoints
- `conformidade-modalidade-fonte-orcamentaria`: openapi-confirmed: 4 endpoints
- `contratacao`: openapi-confirmed: 31 endpoints; openapi-missing: 1 endpoints
- `contrato-empenho`: openapi-confirmed: 26 endpoints
- `criterio-de-julgamento`: openapi-confirmed: 4 endpoints
- `fonte-orcamentaria`: openapi-confirmed: 4 endpoints
- `fonte-orcamentaria-da-contratacao`: openapi-confirmed: 4 endpoints
- `instrumento-convocatorio`: openapi-confirmed: 4 endpoints
- `irp`: openapi-confirmed: 17 endpoints
- `modalidade-de-contratacao`: openapi-confirmed: 4 endpoints
- `modo-de-disputa`: openapi-confirmed: 4 endpoints
- `natureza-juridica`: openapi-confirmed: 1 endpoints
- `normativo-base`: openapi-confirmed: 4 endpoints
- `orgao-entidade`: openapi-confirmed: 9 endpoints
- `pais`: openapi-confirmed: 1 endpoints
- `plano-de-contratacao`: openapi-confirmed: 21 endpoints
- `porte-de-empresa`: openapi-confirmed: 4 endpoints
- `situacao-resultado-item`: openapi-confirmed: 1 endpoints
- `termo-de-contrato`: openapi-confirmed: 13 endpoints
- `tipo-de-contrato`: openapi-confirmed: 2 endpoints; openapi-missing: 2 endpoints
- `tipo-de-documento`: openapi-confirmed: 2 endpoints; openapi-missing: 2 endpoints
- `tipo-de-instrumento-de-cobranca`: openapi-confirmed: 4 endpoints
- `tipo-parte-envolvida`: openapi-confirmed: 2 endpoints
- `usuario`: openapi-confirmed: 10 endpoints

## Fontes Complementares

- `referencias/tabelas-de-dominio-pncp.md`: Markdown enxuto extraído da página pública de tabelas de domínio do PNCP.
- `schemas/`: schemas normalizados a partir de `components.schemas` da OpenAPI pública do PNCP.
- `consulta/`: endpoints públicos normalizados da API de Consulta.
- `schemas/consulta/`: schemas normalizados da API de Consulta.
- `referencias/superficies-da-api.md`: guia de escolha entre `api/consulta` e `api/pncp`.
