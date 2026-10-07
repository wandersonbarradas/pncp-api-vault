# Mapa da API de Consulta PNCP

Use este mapa para localizar endpoints públicos de leitura em `api/consulta`.

## Regra de Uso

- Para dados publicados de uma contratação, comece em `GET /api/consulta/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}`.
- Para itens, documentos e histórico, confira se há endpoint em `api/consulta`; se não houver, use os sub-recursos já documentados em `api/pncp`.
- Para manutenção ou envio de dados, use `api/pncp`, não `api/consulta`.

## Sessões

- [Ata](../consulta/ata/index.md): 2 endpoint(s).
- [Contratação](../consulta/contratacao/index.md): 4 endpoint(s).
- [Contrato/Empenho](../consulta/contrato-empenho/index.md): 2 endpoint(s).
- [Instrumento de Cobrança](../consulta/instrumento-cobranca/index.md): 1 endpoint(s).
- [Plano de Contratação](../consulta/plano-de-contratacao/index.md): 3 endpoint(s).

## Endpoints

| Método | Endpoint | Operação | Arquivo |
| --- | --- | --- | --- |
| `GET` | `/api/consulta/v1/atas` | Consultar Ata de Registro de Preço por Período de Vigência | [consultar-ata-de-registro-de-pre-o-por-per-odo-de-vig-ncia.md](../consulta/ata/consultar-ata-de-registro-de-pre-o-por-per-odo-de-vig-ncia.md) |
| `GET` | `/api/consulta/v1/atas/atualizacao` | Consultar Atas de Registro de Preço por Data de Atualização Global | [consultar-atas-de-registro-de-pre-o-por-data-de-atualiza-o-global.md](../consulta/ata/consultar-atas-de-registro-de-pre-o-por-data-de-atualiza-o-global.md) |
| `GET` | `/api/consulta/v1/contratacoes/atualizacao` | Consultar Contratações por Data de Atualização Global | [consultar-contrata-es-por-data-de-atualiza-o-global.md](../consulta/contratacao/consultar-contrata-es-por-data-de-atualiza-o-global.md) |
| `GET` | `/api/consulta/v1/contratacoes/proposta` | Consultar Contratações com Recebimento de Propostas Aberto | [consultar-contrata-es-com-recebimento-de-propostas-aberto.md](../consulta/contratacao/consultar-contrata-es-com-recebimento-de-propostas-aberto.md) |
| `GET` | `/api/consulta/v1/contratacoes/publicacao` | Consultar Contratações por Data de Publicação | [consultar-contrata-es-por-data-de-publica-o.md](../consulta/contratacao/consultar-contrata-es-por-data-de-publica-o.md) |
| `GET` | `/api/consulta/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}` | Consultar Contratação | [consultar-contrata-o.md](../consulta/contratacao/consultar-contrata-o.md) |
| `GET` | `/api/consulta/v1/contratos` | Consultar Contratos por Data de Publicação | [consultar-contratos-por-data-de-publica-o.md](../consulta/contrato-empenho/consultar-contratos-por-data-de-publica-o.md) |
| `GET` | `/api/consulta/v1/contratos/atualizacao` | Consultar Contratos/Empenhos por Data de Atualização Global | [consultar-contratos-empenhos-por-data-de-atualiza-o-global.md](../consulta/contrato-empenho/consultar-contratos-empenhos-por-data-de-atualiza-o-global.md) |
| `GET` | `/api/consulta/v1/instrumentoscobranca/inclusao` | Consultar Instrumentos de Cobrança por Data de Inclusão | [consultar-instrumentos-de-cobran-a-por-data-de-inclus-o.md](../consulta/instrumento-cobranca/consultar-instrumentos-de-cobran-a-por-data-de-inclus-o.md) |
| `GET` | `/api/consulta/v1/pca/` | Consultar Itens de PCA por Ano do PCA e Código de Classificação Superior | [consultar-itens-de-pca-por-ano-do-pca-e-c-digo-de-classifica-o-superior.md](../consulta/plano-de-contratacao/consultar-itens-de-pca-por-ano-do-pca-e-c-digo-de-classifica-o-superior.md) |
| `GET` | `/api/consulta/v1/pca/atualizacao` | Consultar PCA por Data de Atualização Global | [consultar-pca-por-data-de-atualiza-o-global.md](../consulta/plano-de-contratacao/consultar-pca-por-data-de-atualiza-o-global.md) |
| `GET` | `/api/consulta/v1/pca/usuario` | Consultar Itens de PCA por Ano do PCA, IdUsuario e Código de Classificação Superior | [consultar-itens-de-pca-por-ano-do-pca-id-usuario-e-c-digo-de-classifica-o-superior.md](../consulta/plano-de-contratacao/consultar-itens-de-pca-por-ano-do-pca-id-usuario-e-c-digo-de-classifica-o-superior.md) |
