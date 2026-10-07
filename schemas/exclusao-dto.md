---
title: "ExclusaoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# ExclusaoDTO

- Tipo: `object`
- Usado em requisições: 10 endpoint(s)
- Usado em respostas: 0 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| justificativa | string | sim |  |  |

## Usado como Corpo de Requisição

- [DELETE /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}](../sessoes/ata/excluir-ata-de-registro-de-preco.md) - Excluir Ata de Registro de Preço
- [DELETE /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos/{sequencialDocumento}](../sessoes/ata/excluir-documento-de-uma-ata.md) - Excluir Documento de uma Ata
- [DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}](../sessoes/contratacao/excluir-contratacao.md) - Excluir Contratação
- [DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos/{sequencialDocumento}](../sessoes/contratacao/excluir-arquivo-documento-de-contratacao.md) - Excluir Arquivo/Documento de Contratação
- [DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/imagem/{sequencialImagem}](../sessoes/contratacao/remover-imagem-de-um-item-de-uma-contratacao.md) - Remover Imagem de um Item de uma Contratação
- [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}](../sessoes/contrato-empenho/excluir-contrato.md) - Excluir Contrato
- [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos/{sequencialDocumento}](../sessoes/contrato-empenho/excluir-arquivo-documento-de-contrato-empenho.md) - Excluir Arquivo/Documento de Contrato/Empenho
- [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}](../sessoes/termo-de-contrato/excluir-termo-de-contrato.md) - Excluir Termo de Contrato
- [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/{sequencialDocumento}](../sessoes/termo-de-contrato/excluir-arquivo-documento-de-termo-de-contrato.md) - Excluir Arquivo/Documento de Termo de Contrato
- [DELETE /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}](../sessoes/plano-de-contratacao/excluir-plano-de-contratacoes.md) - Excluir Plano de Contratações

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
