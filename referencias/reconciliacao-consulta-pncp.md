# Reconciliação entre api/consulta e api/pncp

Esta nota registra diferenças práticas entre as superfícies `api/consulta` e `api/pncp` observadas durante a validação do vault.

## Caso Testado

Contratação: `06553895000178-1-000013/2026`

| Recurso | api/consulta | api/pncp | Resultado observado |
| --- | --- | --- | --- |
| Contratação principal | `GET /api/consulta/v1/orgaos/06553895000178/compras/2026/13` -> `200` | `GET /api/pncp/v1/orgaos/06553895000178/compras/2026/13` -> `301` | `api/pncp` redireciona logicamente para `api/consulta` |
| Itens | `GET /api/consulta/v1/orgaos/06553895000178/compras/2026/13/itens` -> `404` | `GET /api/pncp/v1/orgaos/06553895000178/compras/2026/13/itens` -> `200` | Sub-recurso disponível em `api/pncp` |
| Documentos | `GET /api/consulta/v1/orgaos/06553895000178/compras/2026/13/arquivos` -> `404` | `GET /api/pncp/v1/orgaos/06553895000178/compras/2026/13/arquivos` -> `200` | Sub-recurso disponível em `api/pncp` |
| Histórico | `GET /api/consulta/v1/orgaos/06553895000178/compras/2026/13/historico` -> `404` | `GET /api/pncp/v1/orgaos/06553895000178/compras/2026/13/historico` -> `200` | Sub-recurso disponível em `api/pncp` |
| Fonte orçamentária | `GET /api/consulta/v1/orgaos/06553895000178/compras/2026/13/fonte-orcamentaria` -> `404` | `GET /api/pncp/v1/orgaos/06553895000178/compras/2026/13/fonte-orcamentaria` -> `200` | Sub-recurso disponível em `api/pncp`; retorno vazio no caso testado |

## Payload Principal

O payload de `api/consulta` para a contratação principal usa formato público próprio. Ele não é 1:1 com o schema `Compra` da superfície `api/pncp`.

Diferenças observadas:

- `numeroControlePNCP` em `api/consulta` vs `numeroControle` no schema `pncp`.
- `valorTotalEstimado` em `api/consulta` vs `valorTotal` no schema `pncp`.
- `orcamentoSigilosoCodigo` e `orcamentoSigilosoDescricao` em `api/consulta` vs `indicadorOrcamentoSigiloso` no schema `pncp`.
- campos achatados `modalidadeId/modalidadeNome`, `modoDisputaId/modoDisputaNome`, `situacaoCompraId/situacaoCompraNome` em vez de objetos de domínio.

## Implicação

Para responder perguntas sobre dados públicos publicados, use os endpoints e schemas da superfície `api/consulta`. Para sub-recursos e manutenção, use a superfície `api/pncp` conforme o endpoint documentado.
