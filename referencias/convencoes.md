# Convenções

## Estrutura dos arquivos

- Cada arquivo representa uma operação ou endpoint.
- O nome do arquivo segue a descrição do Swagger em `kebab-case`.
- Arquivos em `consulta/` representam a superfície pública `api/consulta`; arquivos em `sessoes/` representam a superfície `api/pncp` normalizada do manual e da OpenAPI principal.
- `section_id` é preservado no frontmatter quando existe correspondência com o manual segmentado.
- `source_type` indica a origem do conteúdo: `manual+openapi`, `manual`, `openapi` ou `openapi-consulta`.
- `surface`, quando presente, indica a superfície da API: `consulta` ou `pncp`.
- `base_path`, quando presente, registra o prefixo operacional usado para montar o endpoint completo.
- `reconciliation_status`, quando presente, indica o resultado da reconciliação seletiva com a OpenAPI.
- `consulta-openapi-confirmed` indica endpoint extraído da OpenAPI pública de Consulta.
- `reconciliation_verified_against`, quando presente, registra a especificação pública usada para confirmar um status `openapi-missing`.
- `reconciliation_verified_at`, quando presente, registra a data da verificação pública.

## Leitura

- `Resumo`: descrição curta da operação.
- `Endpoint`: método HTTP e path.
- `Parâmetros de entrada`: parâmetros de path, query ou header quando disponíveis.
- `Corpo da requisição` e `Resposta`: resumo estrutural baseado na OpenAPI quando disponível.
- `Notas de normalização`: informa o tipo de consolidação feito.
- Em `consulta/`, os endpoints já aparecem com prefixo completo `GET /api/consulta/v1/...`.
- Em `sessoes/`, os endpoints geralmente aparecem como `GET /v1/...`; considere o contexto `api/pncp`.

## Campos de Qualidade

- `quality_status: needs-review` indica que o endpoint deve ser tratado com cautela.
- `normalization_warning` descreve o problema identificado, como path truncado ou fragmento duplicado no manual normalizado.
