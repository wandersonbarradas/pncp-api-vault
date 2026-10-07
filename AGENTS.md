# AGENTS.md

Este vault contém documentação normalizada da API PNCP. O objetivo principal é consulta rápida por humanos e por modelos de LLM, com baixo consumo de contexto.

## Regra Principal

Não leia muitos arquivos antes de localizar o alvo. Primeiro use os índices compactos; depois abra somente os endpoints relevantes.

## Ordem de Busca Recomendada

1. Leia `index.md` para escolher o macrogrupo quando o tema for amplo.
2. Leia `mapas/consulta.md` quando a pergunta for sobre consulta pública de dados publicados no PNCP.
3. Leia `mapas/como-consultar.md` para perguntas operacionais comuns como consultar licitação, ata, contrato, termo, PCA, órgão ou unidade.
4. Leia `mapas/indice-llm.md` quando precisar localizar uma operação por domínio, método ou título.
5. Use `mapas/rotas-consulta-compactas.md` quando a pergunta trouxer um path de `api/consulta`.
6. Use `mapas/rotas-compactas.md` quando a pergunta trouxer um path de `api/pncp`.
7. Use `mapas/schemas-consulta.md` para campos de resposta da API de Consulta.
8. Use `mapas/schemas.md` para campos, DTOs, corpo de requisição ou resposta da API `api/pncp`.
9. Abra `consulta/<grupo>/index.md` ou `sessoes/<sessao>/index.md` para reduzir a busca dentro de um grupo.
10. Abra apenas os arquivos de endpoint ou schema necessários para responder.

## Escolha da Superfície

- Use `api/consulta` para leitura pública de contratações, atas, contratos/empenhos, instrumentos de cobrança e PCA publicados.
- Use `api/pncp` para registro, manutenção, retificação, exclusão e sub-recursos preservados no manual normalizado.
- Se o usuário citar `numeroControlePNCP`, normalmente extraia CNPJ, ano e sequencial e comece pela API de Consulta.
- Não assuma que schemas de `schemas/consulta/` e `schemas/` são equivalentes; compare explicitamente quando necessário.
- Quando uma rota `api/pncp/v1` de consulta principal redirecionar ou corresponder à superfície pública, cite a rota `api/consulta/v1` como referência principal.

## Como Responder

- Cite o endpoint completo e o método HTTP.
- Quando existir `section_id`, mencione-o se a pergunta envolver rastreabilidade com o manual.
- Use `source_type` para qualificar a origem:
  - `manual+openapi`: manual e Swagger reconciliados.
  - `openapi`: endpoint presente no Swagger atual, sem seção manual equivalente.
  - `openapi-consulta`: endpoint presente no Swagger da API de Consulta.
  - `manual`: endpoint preservado do manual local, sem equivalente claro no Swagger capturado.
- Use `reconciliation_status` quando existir: `openapi-confirmed` significa que método e path foram encontrados na OpenAPI capturada; `openapi-missing` significa que o endpoint está no manual, mas não foi encontrado na OpenAPI capturada.
- Use `consulta-openapi-confirmed` para endpoints extraídos da OpenAPI pública de Consulta.
- Sempre diga qual superfície foi usada: `api/consulta` ou `api/pncp`.
- Se houver `quality_status: needs-review` ou `normalization_warning`, trate o endpoint como baixa confiança e mencione a limitação.
- Se houver divergência de fonte, diga isso explicitamente.
- Não invente campos, parâmetros ou códigos de retorno. Se o arquivo não documenta algo, diga que não está documentado no vault.

## Estrutura

- `sessoes/`: arquivos detalhados por endpoint.
- `sessoes/<sessao>/index.md`: índice compacto de uma sessão.
- `consulta/`: endpoints públicos normalizados da superfície `api/consulta`.
- `consulta/<grupo>/index.md`: índice compacto de um grupo da API de Consulta.
- `mapas/como-consultar.md`: guia rápido para perguntas operacionais recorrentes.
- `mapas/indice-llm.md`: índice geral para localização rápida.
- `mapas/consulta.md`: mapa da API de Consulta.
- `mapas/rotas-consulta-compactas.md`: lista enxuta de rotas públicas de consulta.
- `mapas/rotas-compactas.md`: lista enxuta para busca por path.
- `mapas/schemas-consulta.md`: índice compacto dos schemas da API de Consulta.
- `mapas/schemas.md`: índice compacto dos schemas OpenAPI.
- `schemas/`: documentação normalizada de DTOs e modelos.
- `schemas/consulta/`: DTOs e modelos da API de Consulta.
- `mapas/operacoes.md`: navegação humana por método HTTP.
- `referencias/`: convenções, cobertura e tabelas de domínio.
- `referencias/superficies-da-api.md`: quando usar `api/consulta` versus `api/pncp`.
- `referencias/tabelas-de-dominio-pncp.md`: fonte enxuta para códigos e regras de conformidade visíveis na página pública.

## Restrições de Manutenção

- Não edite os arquivos de endpoint manualmente sem motivo claro; eles são gerados a partir do material normalizado.
- Se precisar melhorar conteúdo, prefira corrigir a fonte normalizada e regenerar o vault.
- Mantenha os índices compactos atualizados sempre que arquivos forem adicionados, removidos ou renomeados.
- Evite criar notas analíticas soltas neste vault. Ele é uma referência técnica, não uma wiki de pesquisa.
