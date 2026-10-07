# Superfícies da API PNCP

O PNCP expõe pelo menos duas superfícies oficiais relevantes para este vault.

## api/consulta

- Base pública: `https://pncp.gov.br/api/consulta/v1`
- Swagger: <https://pncp.gov.br/api/consulta/swagger-ui/index.html>
- OpenAPI: <https://pncp.gov.br/api/consulta/v3/api-docs>
- Uso principal: leitura pública de dados publicados no PNCP.

Use esta superfície para perguntas como:

- dados públicos de uma contratação;
- valores, datas, objeto e situação de uma licitação publicada;
- consultas públicas agregadas por publicação, proposta ou atualização.

## api/pncp

- Base pública: `https://pncp.gov.br/api/pncp/v1`
- Swagger: <https://pncp.gov.br/api/pncp/swagger-ui/index.html>
- OpenAPI: <https://pncp.gov.br/pncp-api/v3/api-docs>
- Uso principal: superfície ampla da API, incluindo manutenção, registros e vários sub-recursos.

Use esta superfície para:

- inserir, retificar ou excluir registros;
- consultar sub-recursos documentados nela, como itens, documentos e histórico;
- operar contratos, atas, PCA, órgãos, usuários, domínios e conformidades.

## Regra Prática

- Para consultar a contratação principal publicada, prefira `api/consulta/v1`.
- Para manutenção e registros, use `api/pncp/v1`.
- Para sub-recursos, use a superfície onde o endpoint estiver documentado e confirmado.
- Não assuma equivalência entre schemas `consulta` e `pncp`; compare o schema da superfície correta.

## Exemplo Verificado

Para `06553895000178-1-000013/2026`:

- `GET /api/consulta/v1/orgaos/06553895000178/compras/2026/13` retornou o payload principal da contratação.
- `GET /api/pncp/v1/orgaos/06553895000178/compras/2026/13` retornou redirecionamento lógico para `api/consulta`.
- Sub-recursos como itens, documentos e histórico responderam em `api/pncp/v1` no teste realizado.
