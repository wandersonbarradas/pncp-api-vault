# Rotas Consulta Compactas

Formato: `METHOD /api/consulta/path -> consulta/grupo/arquivo | título`.

- `GET /api/consulta/v1/atas` -> `consulta/ata/consultar-ata-de-registro-de-pre-o-por-per-odo-de-vig-ncia.md` | Consultar Ata de Registro de Preço por Período de Vigência
- `GET /api/consulta/v1/atas/atualizacao` -> `consulta/ata/consultar-atas-de-registro-de-pre-o-por-data-de-atualiza-o-global.md` | Consultar Atas de Registro de Preço por Data de Atualização Global
- `GET /api/consulta/v1/contratacoes/atualizacao` -> `consulta/contratacao/consultar-contrata-es-por-data-de-atualiza-o-global.md` | Consultar Contratações por Data de Atualização Global
- `GET /api/consulta/v1/contratacoes/proposta` -> `consulta/contratacao/consultar-contrata-es-com-recebimento-de-propostas-aberto.md` | Consultar Contratações com Recebimento de Propostas Aberto
- `GET /api/consulta/v1/contratacoes/publicacao` -> `consulta/contratacao/consultar-contrata-es-por-data-de-publica-o.md` | Consultar Contratações por Data de Publicação
- `GET /api/consulta/v1/contratos` -> `consulta/contrato-empenho/consultar-contratos-por-data-de-publica-o.md` | Consultar Contratos por Data de Publicação
- `GET /api/consulta/v1/contratos/atualizacao` -> `consulta/contrato-empenho/consultar-contratos-empenhos-por-data-de-atualiza-o-global.md` | Consultar Contratos/Empenhos por Data de Atualização Global
- `GET /api/consulta/v1/instrumentoscobranca/inclusao` -> `consulta/instrumento-cobranca/consultar-instrumentos-de-cobran-a-por-data-de-inclus-o.md` | Consultar Instrumentos de Cobrança por Data de Inclusão
- `GET /api/consulta/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}` -> `consulta/contratacao/consultar-contrata-o.md` | Consultar Contratação
- `GET /api/consulta/v1/pca/` -> `consulta/plano-de-contratacao/consultar-itens-de-pca-por-ano-do-pca-e-c-digo-de-classifica-o-superior.md` | Consultar Itens de PCA por Ano do PCA e Código de Classificação Superior
- `GET /api/consulta/v1/pca/atualizacao` -> `consulta/plano-de-contratacao/consultar-pca-por-data-de-atualiza-o-global.md` | Consultar PCA por Data de Atualização Global
- `GET /api/consulta/v1/pca/usuario` -> `consulta/plano-de-contratacao/consultar-itens-de-pca-por-ano-do-pca-id-usuario-e-c-digo-de-classifica-o-superior.md` | Consultar Itens de PCA por Ano do PCA, IdUsuario e Código de Classificação Superior
