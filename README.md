# PNCP API

Vault de consulta da API do PNCP, preparado a partir do material normalizado.

## Estrutura

- `index.md`: ponto de entrada principal do vault.
- `sessoes/`: documentação por sessão funcional da API.
- `consulta/`: endpoints públicos da superfície `api/consulta`.
- `mapas/`: visões de navegação por domínio, operação, fluxo e schemas.
- `schemas/`: DTOs e modelos normalizados da OpenAPI.
- `schemas/consulta/`: DTOs e modelos da API de Consulta.
- `referencias/`: convenções, cobertura e tabelas de domínio do PNCP.
- `assets/`: espaço reservado para anexos visuais, se necessário.

## Uso

- Para leitura humana, comece por `index.md`.
- Para consulta pública de dados publicados, comece por `consulta/index.md` ou `mapas/consulta.md`.
- Para busca por endpoint ou operação, navegue por `sessoes/` ou use a busca do Obsidian.
- Para entendimento de escopo e origem, consulte `referencias/cobertura.md` e `referencias/convencoes.md`.
- Para decidir entre `api/consulta` e `api/pncp`, consulte `referencias/superficies-da-api.md`.
- Para códigos e regras de domínio, consulte `referencias/tabelas-de-dominio-pncp.md`.

## Consulta por LLM

- Use `AGENTS.md` como instrução operacional para modelos.
- Use `mapas/como-consultar.md` para perguntas operacionais comuns.
- Use `mapas/consulta.md` quando a pergunta for sobre leitura pública de contratação, ata, contrato/empenho, instrumento de cobrança ou PCA.
- Use `mapas/indice-llm.md` para localizar arquivos candidatos com pouco contexto.
- Use `mapas/rotas-consulta-compactas.md` quando souber parte de um endpoint de `api/consulta`.
- Use `mapas/rotas-compactas.md` quando souber parte do endpoint ou método HTTP.
- Use `mapas/schemas-consulta.md` quando a pergunta for sobre campos de resposta da API de Consulta.
- Use `mapas/schemas.md` quando a pergunta for sobre campos de DTOs, corpo de requisição ou resposta.
- Abra arquivos detalhados em `consulta/` ou `sessoes/` somente depois de restringir a busca.
