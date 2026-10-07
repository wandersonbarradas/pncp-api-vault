# Como Consultar Informações no PNCP

Guia curto para perguntas operacionais frequentes. Use este arquivo antes de abrir endpoints detalhados.

## Consultar uma licitação ou contratação

Para leitura pública de contratação publicada, use primeiro a superfície `api/consulta`.

- Operação principal pública: `GET /api/consulta/v1/orgaos/{cnpj}/compras/{ano}/{sequencial}` em [consultar-contrata-o.md](../consulta/contratacao/consultar-contrata-o.md).
- Exemplo de `numeroControlePNCP`: `06553895000178-1-000013/2026` normalmente aponta para `cnpj=06553895000178`, `ano=2026`, `sequencial=13`.
- Para listas por publicação, atualização global ou recebimento de propostas, consulte [consulta/contratacao/index.md](../consulta/contratacao/index.md).
- A rota antiga `GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}` em [consultar-uma-contratacao.md](../sessoes/contratacao/consultar-uma-contratacao.md) está preservada do manual com `openapi-missing`; prefira a rota de `api/consulta` para leitura pública principal.
- Para documentos da contratação em `api/pncp`: `GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos` em [consultar-documentos-de-contratacao.md](../sessoes/contratacao/consultar-documentos-de-contratacao.md).
- Para itens em `api/pncp`: `GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens` em [consultar-todos-os-itens-de-contratacao.md](../sessoes/contratacao/consultar-todos-os-itens-de-contratacao.md).
- Para histórico em `api/pncp`: `GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/historico` em [consultar-historico-de-contratacao.md](../sessoes/contratacao/consultar-historico-de-contratacao.md).

## Consultar atas de registro de preço

Use a sessão `ata`.

- Listar atas de uma compra: `GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas` em [consultar-atas-de-registro-de-preco-por-compra.md](../sessoes/ata/consultar-atas-de-registro-de-preco-por-compra.md).
- Consultar uma ata: `GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}` em [consultar-ata-de-registro-de-preco.md](../sessoes/ata/consultar-ata-de-registro-de-preco.md).
- Documentos da ata: `GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos` em [consultar-dados-de-todos-os-documentos-de-uma-ata-de-registro-de-preco.md](../sessoes/ata/consultar-dados-de-todos-os-documentos-de-uma-ata-de-registro-de-preco.md).
- Histórico da ata: `GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/atas/{sequencialAta}/historico` em [consultar-historico-de-ata.md](../sessoes/ata/consultar-historico-de-ata.md).

## Consultar contratos e empenhos

Use a sessão `contrato-empenho`.

- Contratos de uma contratação: `GET /v1/orgaos/{cnpj}/contratos/contratacao/{anoContratacao}/{sequencialContratacao}` em [consultar-contratos-de-uma-contratacao.md](../sessoes/contrato-empenho/consultar-contratos-de-uma-contratacao.md).
- Consultar contrato: `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}` em [consultar-contrato.md](../sessoes/contrato-empenho/consultar-contrato.md).
- Documentos do contrato/empenho: `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos` em [consultar-todos-os-documentos-de-um-contrato-empenho.md](../sessoes/contrato-empenho/consultar-todos-os-documentos-de-um-contrato-empenho.md).
- Instrumentos de cobrança: `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca` em [consultar-instrumentos-de-cobranca-de-um-contrato-empenho.md](../sessoes/contrato-empenho/consultar-instrumentos-de-cobranca-de-um-contrato-empenho.md).
- Endpoints específicos de empenho marcados como `openapi-missing` têm baixa confiança quando o path parece truncado; confirme antes de usar em integração.

## Consultar termos de contrato

Use a sessão `termo-de-contrato`.

- Listar termos: `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos` em [consultar-termos-de-contrato.md](../sessoes/termo-de-contrato/consultar-termos-de-contrato.md).
- Consultar termo: `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}` em [consultar-termo-de-contrato.md](../sessoes/termo-de-contrato/consultar-termo-de-contrato.md).
- Documentos do termo: `GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos` em [consultar-documentos-de-termo-de-contrato.md](../sessoes/termo-de-contrato/consultar-documentos-de-termo-de-contrato.md).

## Consultar plano de contratação anual

Use a sessão `plano-de-contratacao`.

- Plano consolidado por órgão e ano: `GET /v1/orgaos/{cnpj}/pca/{ano}/consolidado` em [consultar-planos-de-contratacao-consolidados-por-orgao-e-ano.md](../sessoes/plano-de-contratacao/consultar-planos-de-contratacao-consolidados-por-orgao-e-ano.md).
- Plano específico com itens: `GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/consolidado` em [consultar-plano-de-contratacao-com-itens.md](../sessoes/plano-de-contratacao/consultar-plano-de-contratacao-com-itens.md).
- Itens do plano: `GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/plano` em [consultar-itens-do-plano-de-contratacao.md](../sessoes/plano-de-contratacao/consultar-itens-do-plano-de-contratacao.md).
- CSV por órgão e ano: `GET /v1/orgaos/{cnpj}/pca/{ano}/csv` em [baixar-csv-dos-planos-de-contratacao-por-orgao-e-ano.md](../sessoes/plano-de-contratacao/baixar-csv-dos-planos-de-contratacao-por-orgao-e-ano.md).

## Consultar órgão, entidade ou unidade

Use a sessão `orgao-entidade`.

- Órgão por CNPJ: `GET /v1/orgaos/{cnpj}` em [consultar-orgao-por-cnpj.md](../sessoes/orgao-entidade/consultar-orgao-por-cnpj.md).
- Órgão por filtro: `GET /v1/orgaos/` em [consultar-orgao-por-filtro.md](../sessoes/orgao-entidade/consultar-orgao-por-filtro.md).
- Unidades do órgão: `GET /v1/orgaos/{cnpj}/unidades` em [consultar-unidades.md](../sessoes/orgao-entidade/consultar-unidades.md).
- Unidade específica: `GET /v1/orgaos/{cnpj}/unidades/{codigoUnidade}` em [consultar-unidade.md](../sessoes/orgao-entidade/consultar-unidade.md).

## Regra de uso por LLM

- Primeiro localize o caso neste arquivo.
- Para consulta pública de dados publicados, prefira `api/consulta`.
- Para registro, retificação, exclusão e sub-recursos não expostos na consulta pública, use `api/pncp`.
- Depois abra apenas o endpoint detalhado citado.
- Se o endpoint tiver `openapi-missing` ou `quality_status: needs-review`, informe a limitação na resposta.
