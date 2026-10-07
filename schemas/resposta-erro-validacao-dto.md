---
title: "RespostaErroValidacaoDTO"
type: "openapi-schema"
source: "https://pncp.gov.br/pncp-api/v3/api-docs"
updated: "2026-05-02"
---

# RespostaErroValidacaoDTO

- Tipo: `object`
- Usado em requisições: 0 endpoint(s)
- Usado em respostas: 164 endpoint(s)

## Campos

| Campo | Tipo | Obrigatório | Descrição | Enum |
| --- | --- | --- | --- | --- |
| erros | array[[IErroValidacaoDTO](./i-erro-validacao-dto.md)] | não |  |  |

## Schemas Relacionados

- [IErroValidacaoDTO](./i-erro-validacao-dto.md)

## Usado em Respostas

- `400`: [DELETE /v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}](../sessoes/conformidade-instrumento-convocatorio-modalidade-amparo-legal/excluir-conformidade-instrumento-convocatorio-modalidade-de-contratacao-e-amparo-legal.md) - Excluir Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal
- `400`: [DELETE /v1/modalidade-criterio-julgamento/{modalidadeId}/{criterioJulgamentoId}](../sessoes/conformidade-modalidade-criterio-de-julgamento/excluir-conformidade-entre-modalidade-de-contratacao-e-criterio-de-julgamento.md) - Excluir conformidade entre modalidade de contratação e critério de julgamento
- `400`: [DELETE /v1/modalidade-fonte-orcamentaria/{modalidadeId}/{fonteOrcamentariaId}](../sessoes/conformidade-modalidade-fonte-orcamentaria/excluir-conformidade-entre-modalidade-de-contratacao-e-fonte-orcamentaria.md) - Excluir conformidade entre modalidade de contratação e Fonte Orçamentaria
- `400`: [DELETE /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}](../sessoes/ata/excluir-ata-de-registro-de-preco.md) - Excluir Ata de Registro de Preço
- `400`: [DELETE /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos/{sequencialDocumento}](../sessoes/ata/excluir-documento-de-uma-ata.md) - Excluir Documento de uma Ata
- `400`: [DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}](../sessoes/contratacao/excluir-contratacao.md) - Excluir Contratação
- `400`: [DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos/{sequencialDocumento}](../sessoes/contratacao/excluir-arquivo-documento-de-contratacao.md) - Excluir Arquivo/Documento de Contratação
- `400`: [DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria](../sessoes/contratacao/excluir-fonte-orcamentaria-da-contratacao.md) - Excluir Fonte Orçamentária da Contratação
- `400`: [DELETE /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/imagem/{sequencialImagem}](../sessoes/contratacao/remover-imagem-de-um-item-de-uma-contratacao.md) - Remover Imagem de um Item de uma Contratação
- `400`: [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}](../sessoes/contrato-empenho/excluir-instrumento-de-cobranca-de-contrato-empenho.md) - Excluir Instrumento de Cobrança de Contrato/Empenho
- `400`: [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}](../sessoes/contrato-empenho/excluir-contrato.md) - Excluir Contrato
- `400`: [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos/{sequencialDocumento}](../sessoes/contrato-empenho/excluir-arquivo-documento-de-contrato-empenho.md) - Excluir Arquivo/Documento de Contrato/Empenho
- `400`: [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}](../sessoes/termo-de-contrato/excluir-termo-de-contrato.md) - Excluir Termo de Contrato
- `400`: [DELETE /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/{sequencialDocumento}](../sessoes/termo-de-contrato/excluir-arquivo-documento-de-termo-de-contrato.md) - Excluir Arquivo/Documento de Termo de Contrato
- `400`: [DELETE /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}](../sessoes/plano-de-contratacao/excluir-plano-de-contratacoes.md) - Excluir Plano de Contratações
- `400`: [DELETE /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens](../sessoes/plano-de-contratacao/excluir-itens-de-plano-de-contratacao.md) - Excluir Itens de Plano de Contratação
- `400`: [DELETE /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/contratacao](../sessoes/plano-de-contratacao/excluir-itens-de-plano-de-contratacao-por-numero-da-contratacao.md) - Excluir Itens de Plano de Contratação por número da Contratação
- `400`: [DELETE /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/plano-de-contratacao/excluir-item-de-plano-de-contratacao.md) - Excluir Item de Plano de Contratação
- `400`: [DELETE /v1/tipo-instrumento-convocatorio-modo-disputa/{tipoInstrumentoConvocatorioId}/{modoDisputaId}](../sessoes/conformidade-instrumento-convocatorio-modo-de-disputa/excluir-conformidade-entre-instrumento-convocatorio-e-modo-de-disputa.md) - Excluir conformidade entre instrumento convocatório e modo de disputa
- `400`: [DELETE /v1/usuarios/{id}](../sessoes/usuario/excluir-usuario.md) - Excluir usuário
- `400`: [DELETE /v1/usuarios/{id}/orgaos](../sessoes/usuario/excluir-entes-autorizados-de-um-usuario.md) - Excluir Entes Autorizados de um Usuário
- `400`: [GET /v1/amparos-legais](../sessoes/amparo-legal/consultar-amparos-legais.md) - Consultar amparos legais
- `400`: [GET /v1/amparos-legais/{id}](../sessoes/amparo-legal/consultar-amparo-legal-por-codigo.md) - Consultar amparo legal por código
- `400`: [GET /v1/catalogos](../sessoes/catalogo/consultar-catalogos.md) - Consultar catálogos
- `400`: [GET /v1/catalogos/{id}](../sessoes/catalogo/consultar-catalogo-por-codigo.md) - Consultar catálogo por código
- `400`: [GET /v1/categoriaItemPcas](../sessoes/categoria-de-item/consultar-categorias-de-item.md) - Consultar categorias de item
- `400`: [GET /v1/categoriaItemPcas/{id}](../sessoes/categoria-de-item/consultar-categoria-de-item-por-codigo.md) - Consultar categoria de item por código
- `400`: [GET /v1/criterios-julgamentos](../sessoes/criterio-de-julgamento/consultar-criterios-de-julgamentos.md) - Consultar critérios de julgamentos
- `400`: [GET /v1/criterios-julgamentos/{id}](../sessoes/criterio-de-julgamento/consultar-criterio-de-julgamento-por-codigo.md) - Consultar critério de julgamento por código
- `400`: [GET /v1/fontes-orcamentarias](../sessoes/fonte-orcamentaria/consultar-fontes-orcamentarias.md) - Consultar fontes orçamentárias
- `400`: [GET /v1/fontes-orcamentarias/{id}](../sessoes/fonte-orcamentaria/consultar-fonte-orcamentaria-por-codigo.md) - Consultar fonte orçamentária por código
- `400`: [GET /v1/instrumento-convocatorio-modalidade-amparo-legal](../sessoes/conformidade-instrumento-convocatorio-modalidade-amparo-legal/consultar-conformidade-instrumento-convocatorio-modalidade-de-contratacao-e-amparo-legal.md) - Consultar Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal
- `400`: [GET /v1/instrumento-convocatorio-modalidade-amparo-legal/{amparoLegalId}/{modalidadeId}/{tipoInstrumentoConvocatorioId}](../sessoes/conformidade-instrumento-convocatorio-modalidade-amparo-legal/consultar-conformidade-instrumento-convocatorio-modalidade-de-contratacao-e-amparo-legal-por-codigo.md) - Consultar Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal por código
- `400`: [GET /v1/modalidade-criterio-julgamento](../sessoes/conformidade-modalidade-criterio-de-julgamento/consultar-conformidade-entre-modalidade-de-contratacao-e-criterio-de-julgamento.md) - Consultar conformidade entre modalidade de contratação e critério de julgamento
- `400`: [GET /v1/modalidade-criterio-julgamento/{modalidadeId}/{criterioJulgamentoId}](../sessoes/conformidade-modalidade-criterio-de-julgamento/consultar-conformidade-entre-modalidade-de-contratacao-e-criterio-de-julgamento-por-codigo.md) - Consultar conformidade entre modalidade de contratação e critério de julgamento por código
- `400`: [GET /v1/modalidade-fonte-orcamentaria](../sessoes/conformidade-modalidade-fonte-orcamentaria/consultar-conformidade-entre-modalidade-de-contratacao-e-fonte-orcamentaria.md) - Consultar conformidade entre modalidade de contratação e Fonte Orçamentaria
- `400`: [GET /v1/modalidade-fonte-orcamentaria/{modalidadeId}/{fonteOrcamentariaId}](../sessoes/conformidade-modalidade-fonte-orcamentaria/consultar-conformidade-entre-modalidade-de-contratacao-e-fonte-orcamentaria-por-codigo.md) - Consultar conformidade entre modalidade de contratação e Fonte Orçamentaria por código
- `400`: [GET /v1/modalidades](../sessoes/modalidade-de-contratacao/consultar-modalidades-de-contratacao.md) - Consultar modalidades de contratação
- `400`: [GET /v1/modalidades/{id}](../sessoes/modalidade-de-contratacao/consultar-modalidade-de-contratacao-por-codigo.md) - Consultar modalidade de contratação por código
- `400`: [GET /v1/modos-disputas](../sessoes/modo-de-disputa/consultar-modos-de-disputas.md) - Consultar modos de disputas
- `400`: [GET /v1/modos-disputas/{id}](../sessoes/modo-de-disputa/consultar-modo-de-disputa-por-codigo.md) - Consultar modo de disputa por código
- `400`: [GET /v1/orgaos/](../sessoes/orgao-entidade/consultar-orgao-por-filtro.md) - Consultar Órgão por Filtro
- `400`: [GET /v1/orgaos/id/{orgaoId}](../sessoes/orgao-entidade/consultar-orgao-por-id.md) - Consultar Órgão por ID
- `400`: [GET /v1/orgaos/{cnpj}](../sessoes/orgao-entidade/consultar-orgao-por-cnpj.md) - Consultar Órgão por CNPJ
- `400`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas](../sessoes/ata/consultar-atas-de-registro-de-preco-por-compra.md) - Consultar Atas de Registro de Preço por Compra
- `400`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}](../sessoes/ata/consultar-ata-de-registro-de-preco.md) - Consultar Ata de Registro de Preço
- `400`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos](../sessoes/ata/consultar-dados-de-todos-os-documentos-de-uma-ata-de-registro-de-preco.md) - Consultar Dados de Todos os Documentos de uma Ata de Registro de Preço
- `400`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos/excluidos/{sequencialDocumento}](../sessoes/ata/baixar-arquivo-documento-excluido-de-ata-de-registro-de-preco.md) - Baixar Arquivo/Documento Excluído de Ata de Registro de Preço
- `400`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos/quantidade](../sessoes/ata/consultar-quantidade-de-documentos-de-ata.md) - Consultar Quantidade de Documentos de Ata
- `400`: [GET /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos/{sequencialDocumento}](../sessoes/ata/baixar-arquivo-documento-de-ata-de-registro-de-preco.md) - Baixar Arquivo/Documento de Ata de Registro de Preço
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos](../sessoes/contratacao/consultar-documentos-de-contratacao.md) - Consultar Documentos de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos/excluidos/{sequencialDocumento}](../sessoes/contratacao/baixar-arquivo-documento-excluido-de-contratacao.md) - Baixar Arquivo/Documento Excluído de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos/quantidade](../sessoes/contratacao/consultar-quantidade-de-documentos-de-contratacao.md) - Consultar Quantidade de Documentos de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos/{sequencialDocumento}](../sessoes/contratacao/baixar-arquivo-documento-de-contratacao.md) - Baixar Arquivo/Documento de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/atas/{sequencialAta}/historico](../sessoes/ata/consultar-historico-de-ata.md) - Consultar Histórico de Ata
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/atas/{sequencialAta}/historico/quantidade](../sessoes/ata/consultar-quantidade-historico-de-ata.md) - Consultar Quantidade Histórico de Ata
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria](../sessoes/contratacao/consultar-todas-as-fontes-orcamentarias-da-contratacao.md) - Consultar Todas as Fontes Orçamentárias da Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria/{fonteOrcamentariaId}](../sessoes/contratacao/consultar-fonte-orcamentaria-da-contratacao.md) - Consultar Fonte Orçamentária da Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/historico](../sessoes/contratacao/consultar-historico-de-contratacao.md) - Consultar Histórico de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/historico/quantidade](../sessoes/contratacao/consultar-quantidade-historico-de-contratacao.md) - Consultar Quantidade Histórico de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens](../sessoes/contratacao/consultar-todos-os-itens-de-contratacao.md) - Consultar Todos os Itens de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/quantidade](../sessoes/contratacao/consultar-quantidade-item-de-contratacao.md) - Consultar Quantidade Item de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/contratacao/consultar-item-de-contratacao.md) - Consultar Item de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/imagem](../sessoes/contratacao/recuperar-imagens-de-um-item-de-uma-contratacao.md) - Recuperar Imagens de um Item de uma Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/imagem/{sequencialImagem}](../sessoes/contratacao/recuperar-imagem-de-um-item-de-uma-contratacao.md) - Recuperar Imagem de um Item de uma Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados](../sessoes/contratacao/consultar-resultados-de-item-de-contratacao.md) - Consultar Resultados de Item de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados/{sequencialResultado}](../sessoes/contratacao/consultar-resultado-de-item-de-contratacao.md) - Consultar Resultado de Item de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/contratos/contratacao/{anoContratacao}/{sequencialContratacao}](../sessoes/contrato-empenho/consultar-contratos-de-uma-contratacao.md) - Consultar Contratos de uma Contratação
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca](../sessoes/contrato-empenho/consultar-instrumentos-de-cobranca-de-um-contrato-empenho.md) - Consultar Instrumentos de Cobrança de um Contrato/Empenho
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}](../sessoes/contrato-empenho/consultar-instrumento-de-cobranca-de-um-contrato-empenho.md) - Consultar Instrumento de Cobrança de um Contrato/Empenho
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}](../sessoes/contrato-empenho/consultar-contrato.md) - Consultar Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos](../sessoes/contrato-empenho/consultar-documentos-de-contrato.md) - Consultar Documentos de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos/excluidos/{sequencialDocumento}](../sessoes/contrato-empenho/baixar-arquivo-documento-excluido-de-contrato-empenho.md) - Baixar Arquivo/Documento Excluído de Contrato/Empenho
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos/quantidade](../sessoes/contrato-empenho/consultar-quantidade-de-documentos-de-contrato.md) - Consultar Quantidade de Documentos de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos/{sequencialDocumento}](../sessoes/contrato-empenho/consultar-documento-de-um-contrato-empenho.md) - Consultar Documento de um Contrato/Empenho
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/historico](../sessoes/contrato-empenho/consultar-historico-de-contrato.md) - Consultar Histórico de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/historico/quantidade](../sessoes/contrato-empenho/consultar-quantidade-historico-de-contrato.md) - Consultar Quantidade Histórico de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos](../sessoes/termo-de-contrato/consultar-termos-de-contrato.md) - Consultar Termos de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/quantidade](../sessoes/termo-de-contrato/consultar-quantidade-de-termos-de-contrato.md) - Consultar Quantidade de Termos de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}](../sessoes/termo-de-contrato/consultar-termo-de-contrato.md) - Consultar Termo de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos](../sessoes/termo-de-contrato/consultar-documentos-de-termo-de-contrato.md) - Consultar Documentos de Termo de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/excluidos/{sequencialDocumento}](../sessoes/termo-de-contrato/baixar-arquivo-documento-excluido-de-termo-de-contrato.md) - Baixar Arquivo/Documento Excluído de Termo de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/quantidade](../sessoes/termo-de-contrato/consultar-quantidade-de-documentos-de-termo-de-contrato.md) - Consultar Quantidade de Documentos de Termo de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos/{sequencialDocumento}](../sessoes/termo-de-contrato/baixar-arquivo-documento-de-termo-de-contrato.md) - Baixar Arquivo/Documento de Termo de Contrato
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/consolidado](../sessoes/plano-de-contratacao/consultar-planos-de-contratacao-consolidados-por-orgao-e-ano.md) - Consultar Planos de Contratação Consolidados por Órgão e Ano
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/consolidado/unidades](../sessoes/plano-de-contratacao/consultar-planos-de-contratacao-consolidados-das-unidades-por-orgao-e-ano.md) - Consultar Planos de Contratação Consolidados das Unidades por Órgão e Ano
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/csv](../sessoes/plano-de-contratacao/baixar-csv-dos-planos-de-contratacao-por-orgao-e-ano.md) - Baixar CSV dos Planos de Contratação por Órgão e Ano
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/quantidade](../sessoes/plano-de-contratacao/consultar-quantidade-de-planos-de-contratacao.md) - Consultar Quantidade de Planos de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/valorescategoriaitem](../sessoes/plano-de-contratacao/consultar-valores-de-planos-de-contratacao-de-um-orgao-por-categoria.md) - Consultar Valores de Planos de Contratação de um Órgão por Categoria
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/consolidado](../sessoes/plano-de-contratacao/consultar-plano-de-contratacao-consolidado.md) - Consultar Plano de Contratação Consolidado
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens](../sessoes/plano-de-contratacao/consultar-itens-do-plano-de-contratacao.md) - Consultar Itens do Plano de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/contratacao](../sessoes/plano-de-contratacao/retornar-itens-de-plano-de-contratacao-por-numero-da-contratacao.md) - Retornar Itens de Plano de Contratação por número da Contratação
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/plano](../sessoes/plano-de-contratacao/consultar-plano-de-contratacao-com-itens.md) - Consultar Plano de Contratação com Itens
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/quantidade](../sessoes/plano-de-contratacao/consultar-quantidade-de-itens-do-plano-de-contratacao.md) - Consultar Quantidade de Itens do Plano de Contratação
- `400`: [GET /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/valorescategoriaitem](../sessoes/plano-de-contratacao/consultar-valores-de-um-plano-de-contratacao-por-categoria.md) - Consultar Valores de um Plano de Contratação por Categoria
- `400`: [GET /v1/orgaos/{cnpj}/pca/{uasg}/{ano}/sequenciaisplano](../sessoes/plano-de-contratacao/get-v1-orgaos-cnpj-pca-uasg-ano-sequenciaisplano.md) - GET /v1/orgaos/{cnpj}/pca/{uasg}/{ano}/sequenciaisplano
- `400`: [GET /v1/orgaos/{cnpj}/unidades](../sessoes/orgao-entidade/consultar-unidades.md) - Consultar Unidades
- `400`: [GET /v1/orgaos/{cnpj}/unidades/{codigoUnidade}](../sessoes/orgao-entidade/consultar-unidade.md) - Consultar Unidade
- `400`: [GET /v1/tipo-instrumento-convocatorio-modo-disputa](../sessoes/conformidade-instrumento-convocatorio-modo-de-disputa/consultar-conformidade-entre-instrumentos-convocatorios-e-modos-de-disputa.md) - Consultar conformidade entre instrumentos convocatórios e modos de disputa
- `400`: [GET /v1/tipo-instrumento-convocatorio-modo-disputa/{tipoInstrumentoConvocatorioId}/{modoDisputaId}](../sessoes/conformidade-instrumento-convocatorio-modo-de-disputa/consultar-conformidade-entre-instrumentos-convocatorios-e-modos-de-disputa-por-codigo.md) - Consultar conformidade entre instrumentos convocatórios e modos de disputa por código
- `400`: [GET /v1/tipos-instrumentos-cobranca](../sessoes/tipo-de-instrumento-de-cobranca/consultar-tipos-de-instrumentos-de-cobranca.md) - Consultar Tipos de Instrumentos de Cobrança
- `400`: [GET /v1/tipos-instrumentos-cobranca/{id}](../sessoes/tipo-de-instrumento-de-cobranca/consultar-tipo-de-instrumento-de-cobranca-por-codigo.md) - Consultar Tipo de Instrumento de Cobrança por Código
- `400`: [GET /v1/tipos-instrumentos-convocatorios](../sessoes/instrumento-convocatorio/consultar-instrumentos-convocatorios.md) - Consultar instrumentos convocatórios
- `400`: [GET /v1/tipos-instrumentos-convocatorios/{id}](../sessoes/instrumento-convocatorio/consultar-instrumento-convocatorio-por-codigo.md) - Consultar instrumento convocatório por código
- `400`: [GET /v1/usuarios](../sessoes/usuario/consultar-usuario-por-login-ou-por-cpf-cnpj.md) - Consultar usuário por login ou por CPF/CNPJ
- `400`: [GET /v1/usuarios/permissoes](../sessoes/usuario/consultar-permissoes.md) - Consultar permissões
- `400`: [GET /v1/usuarios/{id}](../sessoes/usuario/consultar-usuario-por-id.md) - Consultar usuário por ID
- `400`: [PATCH /v1/amparos-legais/{id}](../sessoes/amparo-legal/alterar-amparo-legal.md) - Alterar amparo legal
- `400`: [PATCH /v1/catalogos/{id}](../sessoes/catalogo/alterar-catalogo.md) - Alterar catálogo
- `400`: [PATCH /v1/categoriaItemPcas/{id}](../sessoes/categoria-de-item/alterar-categoria-de-item.md) - Alterar categoria de item
- `400`: [PATCH /v1/criterios-julgamentos/{id}](../sessoes/criterio-de-julgamento/alterar-criterio-de-julgamento.md) - Alterar critério de julgamento
- `400`: [PATCH /v1/fontes-orcamentarias/{id}](../sessoes/fonte-orcamentaria/alterar-fonte-orcamentaria.md) - Alterar fonte orçamentária
- `400`: [PATCH /v1/modalidades/{id}](../sessoes/modalidade-de-contratacao/alterar-modalidade-de-contratacao.md) - Alterar modalidade de contratação
- `400`: [PATCH /v1/modos-disputas/{id}](../sessoes/modo-de-disputa/alterar-modo-de-disputa.md) - Alterar modo de disputa
- `400`: [PATCH /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}](../sessoes/contratacao/retificar-parcialmente-uma-contratacao.md) - Retificar parcialmente uma Contratação
- `400`: [PATCH /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/contratacao/retificar-parcialmente-um-item-de-contratacao.md) - Retificar Parcialmente um Item de Contratação
- `400`: [PATCH /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca/{sequencialInstrumentoCobranca}](../sessoes/contrato-empenho/retificar-parcialmente-instrumento-de-cobranca-de-contrato-empenho.md) - Retificar Parcialmente Instrumento de Cobrança de Contrato/Empenho
- `400`: [PATCH /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens](../sessoes/plano-de-contratacao/retificar-parcialmente-itens-de-plano-de-contratacao.md) - Retificar Parcialmente itens de Plano de Contratação
- `400`: [PATCH /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/plano-de-contratacao/retificar-parcialmente-item-de-plano-de-contratacao.md) - Retificar Parcialmente item de Plano de Contratação
- `400`: [PATCH /v1/tipos-instrumentos-cobranca/{id}](../sessoes/tipo-de-instrumento-de-cobranca/alterar-tipo-de-instrumento-de-cobranca.md) - Alterar Tipo de Instrumento de Cobrança
- `400`: [PATCH /v1/tipos-instrumentos-convocatorios/{id}](../sessoes/instrumento-convocatorio/alterar-instrumento-convocatorio.md) - Alterar instrumento convocatório
- `400`: [PATCH /v1/usuarios/{id}/permissoes](../sessoes/usuario/alterar-permissoes-do-usuario.md) - Alterar permissões do usuário
- `400`: [POST /v1/amparos-legais](../sessoes/amparo-legal/inserir-amparo-legal.md) - Inserir amparo legal
- `400`: [POST /v1/catalogos](../sessoes/catalogo/inserir-catalogo.md) - Inserir catálogo
- `400`: [POST /v1/categoriaItemPcas](../sessoes/categoria-de-item/inserir-categoria-de-item.md) - Inserir categoria de item
- `400`: [POST /v1/criterios-julgamentos](../sessoes/criterio-de-julgamento/inserir-criterio-de-julgamento.md) - Inserir critério de julgamento
- `400`: [POST /v1/fontes-orcamentarias](../sessoes/fonte-orcamentaria/inserir-fonte-orcamentaria.md) - Inserir fonte orçamentária
- `400`: [POST /v1/instrumento-convocatorio-modalidade-amparo-legal](../sessoes/conformidade-instrumento-convocatorio-modalidade-amparo-legal/inserir-conformidade-instrumento-convocatorio-modalidade-de-contratacao-e-amparo-legal.md) - Inserir Conformidade Instrumento Convocatório, Modalidade de Contratação e Amparo Legal
- `400`: [POST /v1/modalidade-criterio-julgamento](../sessoes/conformidade-modalidade-criterio-de-julgamento/inserir-conformidade-entre-modalidade-de-contratacao-e-criterio-de-julgamento.md) - Inserir conformidade entre modalidade de contratação e critério de julgamento
- `400`: [POST /v1/modalidade-fonte-orcamentaria](../sessoes/conformidade-modalidade-fonte-orcamentaria/inserir-conformidade-entre-modalidade-de-contratacao-e-fonte-orcamentaria.md) - Inserir conformidade entre modalidade de contratação e Fonte Orçamentaria
- `400`: [POST /v1/modalidades](../sessoes/modalidade-de-contratacao/inserir-modalidade-de-contratacao.md) - Inserir modalidade de contratação
- `400`: [POST /v1/modos-disputas](../sessoes/modo-de-disputa/inserir-modo-de-disputa.md) - Inserir modo de disputa
- `400`: [POST /v1/orgaos](../sessoes/orgao-entidade/inserir-orgao.md) - Inserir Órgão
- `400`: [POST /v1/orgaos/{cnpj}/compras](../sessoes/contratacao/inserir-contratacao.md) - Inserir Contratação
- `400`: [POST /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas](../sessoes/ata/inserir-ata-de-registro-de-preco.md) - Inserir Ata de Registro de Preço
- `400`: [POST /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}/arquivos](../sessoes/ata/inserir-documento-de-uma-ata.md) - Inserir Documento de uma Ata
- `400`: [POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/arquivos](../sessoes/contratacao/inserir-documento-de-contratacao.md) - Inserir Documento de Contratação
- `400`: [POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/fonte-orcamentaria](../sessoes/contratacao/inserir-fonte-orcamentaria-da-contratacao.md) - Inserir Fonte Orçamentária da Contratação
- `400`: [POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens](../sessoes/contratacao/inserir-itens-a-uma-contratacao.md) - Inserir Itens a uma Contratação
- `400`: [POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/imagem](../sessoes/contratacao/inserir-imagem-de-um-item-de-contratacao.md) - Inserir Imagem de um Item de Contratação
- `400`: [POST /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados](../sessoes/contratacao/inserir-resultado-de-item-de-contratacao.md) - Inserir Resultado de Item de Contratação
- `400`: [POST /v1/orgaos/{cnpj}/contratos](../sessoes/contrato-empenho/inserir-contrato.md) - Inserir Contrato
- `400`: [POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencialContrato}/instrumentocobranca](../sessoes/contrato-empenho/inserir-instrumento-de-cobranca-de-um-contrato-empenho.md) - Inserir Instrumento de Cobrança de um Contrato/Empenho
- `400`: [POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/arquivos](../sessoes/contrato-empenho/inserir-documento-de-contrato.md) - Inserir Documento de Contrato
- `400`: [POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos](../sessoes/termo-de-contrato/inserir-termo-de-contrato.md) - Inserir Termo de Contrato
- `400`: [POST /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermo}/arquivos](../sessoes/termo-de-contrato/inserir-documento-de-termo-de-contrato.md) - Inserir Documento de Termo de Contrato
- `400`: [POST /v1/orgaos/{cnpj}/pca](../sessoes/plano-de-contratacao/inserir-plano-de-contratacao.md) - Inserir Plano de Contratação
- `400`: [POST /v1/orgaos/{cnpj}/pca/{ano}/{sequencial}/itens](../sessoes/plano-de-contratacao/inserir-itens-de-plano-de-contratacao.md) - Inserir itens de Plano de Contratação
- `400`: [POST /v1/orgaos/{cnpj}/unidades](../sessoes/orgao-entidade/inserir-unidade.md) - Inserir Unidade
- `400`: [POST /v1/tipo-instrumento-convocatorio-modo-disputa](../sessoes/conformidade-instrumento-convocatorio-modo-de-disputa/inserir-conformidade-entre-instrumentos-convocatorios-e-modos-de-disputa.md) - Inserir conformidade entre instrumentos convocatórios e modos de disputa
- `400`: [POST /v1/tipos-instrumentos-cobranca](../sessoes/tipo-de-instrumento-de-cobranca/inserir-tipo-de-instrumento-de-cobranca.md) - Inserir Tipo de Instrumento de Cobrança
- `400`: [POST /v1/tipos-instrumentos-convocatorios](../sessoes/instrumento-convocatorio/inserir-instrumento-convocatorio.md) - Inserir instrumento convocatório
- `400`: [POST /v1/usuarios](../sessoes/usuario/inserir-usuario.md) - Inserir usuário
- `400`: [POST /v1/usuarios/login](../sessoes/usuario/autenticacao-login-no-sistema.md) - Autenticação/login no sistema
- `400`: [POST /v1/usuarios/{id}/orgaos](../sessoes/usuario/inserir-entes-autorizados-para-um-usuario.md) - Inserir Entes Autorizados para um Usuário
- `400`: [PUT /v1/orgaos](../sessoes/orgao-entidade/atualizar-orgao.md) - Atualizar Órgão
- `400`: [PUT /v1/orgaos/{cnpj}/compras/{anoCompra}/{sequencialCompra}/atas/{sequencialAta}](../sessoes/ata/retificar-ata-de-registro-de-preco.md) - Retificar Ata de Registro de Preço
- `400`: [PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}](../sessoes/contratacao/retificar-contratacao.md) - Retificar Contratação
- `400`: [PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}](../sessoes/contratacao/retificar-item-de-contratacao.md) - Retificar Item de Contratação
- `400`: [PUT /v1/orgaos/{cnpj}/compras/{ano}/{sequencial}/itens/{numeroItem}/resultados/{sequencialResultado}](../sessoes/contratacao/retificar-resultado-de-item-de-contratacao.md) - Retificar Resultado de Item de Contratação
- `400`: [PUT /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}](../sessoes/contrato-empenho/retificar-contrato.md) - Retificar Contrato
- `400`: [PUT /v1/orgaos/{cnpj}/contratos/{ano}/{sequencial}/termos/{sequencialTermoContrato}](../sessoes/termo-de-contrato/retificar-termo-de-contrato.md) - Retificar Termo de Contrato
- `400`: [PUT /v1/orgaos/{cnpj}/unidades](../sessoes/orgao-entidade/atualizar-unidade.md) - Atualizar Unidade
- `400`: [PUT /v1/usuarios/{id}](../sessoes/usuario/atualizar-usuario.md) - Atualizar usuário

## Fonte

- OpenAPI pública do PNCP: <https://pncp.gov.br/pncp-api/v3/api-docs>
