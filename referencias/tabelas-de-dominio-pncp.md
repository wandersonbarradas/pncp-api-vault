# Tabelas de Domínio e Regras de Conformidade do PNCP

Fonte: página pública `https://pncp.gov.br/app/entidades-dominio`, capturada em MHTML local em 2026-05-02.

> Nota: a página usa tabelas paginadas. Este arquivo contém os registros visíveis na captura MHTML, não necessariamente a lista completa quando a própria página indica mais itens. Para integração, confirme também os endpoints de domínio e conformidade documentados no vault.

## Uso Rápido para LLM

- Use este arquivo para entender códigos e combinações válidas citadas pela página pública do PNCP.
- Para detalhes de endpoints CRUD desses domínios, consulte `sessoes/<dominio>/index.md`.
- Quando houver divergência entre esta página e a OpenAPI, prefira endpoints `openapi-confirmed` e registre a divergência.

## Contexto

As tabelas de domínio têm como objetivo categorizar os dados relacionados a licitações e contratos, assegurando que todas as esferas públicas sigam um padrão nas contratações. Ao utilizar essas tabelas, as plataformas integradas ao Portal garantem a padronização das informações enviadas, o que otimiza a busca, a análise e o acompanhamento das contratações públicas.
O uso das tabelas de domínio contribui para a transparência, a eficiência e o controle das informações sobre contratações públicas.
**Benefícios das Tabelas de Domínio e Regras de Conformidade no PNCP:**
**Padronização:**
Assegura que todas as plataformas integradas utilizem os mesmos dados, evitando divergências e inconsistências.
**Integração:**
Facilita a integração de dados de diferentes plataformas.
**Transparência:**
Torna os dados mais claros e acessíveis ao público.
**Eficiência:**
Acelera o envio e a análise das informações.
**Controle:**
Proporciona um melhor controle sobre as contratações públicas.
**Envio de Publicações de Contratações Públicas ao PNCP:**
Ao enviar publicações de contratações públicas ao PNCP, as plataformas devem seguir as tabelas de domínio definidas nesta página. Isso garante que as informações sejam enviadas de maneira padronizada e consistente, permitindo que o PNCP processe e publique os dados de forma eficiente.

## Instrumento Convocatório

| Código | Nome | Descrição | Ativo |
| --- | --- | --- | --- |
| 1 | Edital | Instrumento convocatório utilizado no leilão, no diálogo competitivo, no concurso, na concorrência e no pregão. | Sim |
| 2 | Aviso de Contratação Direta | Instrumento convocatório utilizado na Dispensa com Disputa. | Sim |
| 3 | Ato que autoriza a Contratação Direta | Instrumento convocatório utilizado na Dispensa sem Disputa ou Inexigibilidade. | Sim |
| 4 | Edital de Chamamento Público | Instrumento convocatório utilizado para processos auxiliares de manifestação de interesse, de pré-qualificação e de credenciamento. | Sim |

## Instrumento de Cobrança

| Código | Nome | Descrição | Ativo |
| --- | --- | --- | --- |
| 1 | Nota Fiscal Eletrônica (NF-e) | Documento de existência apenas digital, emitido e armazenado eletronicamente, com o intuito de documentar, para fins fiscais, uma operação de circulação de mercadorias ou uma prestação de serviços, ocorrida entre as partes. Sua validade jurídica é garantida pela assinatura digital do remetente (garantia de autoria e de integridade) e a Autorização de uso fornecida pelo Fisco, antes da ocorrência do fato gerador. | Sim |

## Modalidade de Contratação

| Código | Nome                                    | Descrição                                                                                                                                                                                                                                                                                                                                                                   | Ativo |
| ------ | --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| 1      | Leilão - Eletrônico                     | Modalidade de licitação para alienação de bens imóveis ou de bens móveis inservíveis ou legalmente apreendidos a quem oferecer o maior lance                                                                                                                                                                                                                                | Sim   |
| 2      | Diálogo Competitivo                     | Modalidade de licitação para contratação de obras, serviços e compras em que a Administração Pública realiza diálogos com licitantes previamente selecionados mediante critérios objetivos, com o intuito de desenvolver uma ou mais alternativas capazes de atender às suas necessidades, devendo os licitantes apresentar proposta final após o encerramento dos diálogos | Sim   |
| 3      | Concurso                                | Modalidade de licitação para escolha de trabalho técnico, científico ou artístico, cujo critério de julgamento será o de melhor técnica ou conteúdo artístico, e para concessão de prêmio ou remuneração ao vencedor                                                                                                                                                        | Sim   |
| 4      | Concorrência - Eletrônica               | Modalidade de licitação para contratação de bens e serviços especiais e de obras e serviços comuns e especiais de engenharia                                                                                                                                                                                                                                                | Sim   |
| 5      | Concorrência - Presencial               | Modalidade de licitação para contratação de bens e serviços especiais e de obras e serviços comuns e especiais de engenharia                                                                                                                                                                                                                                                | Sim   |
| 6      | Pregão - Eletrônico                     | Modalidade de licitação obrigatória para aquisição de bens e serviços comuns, cujo critério de julgamento poderá ser o de menor preço ou o de maior desconto                                                                                                                                                                                                                | Sim   |
| 7      | Pregão - Presencial                     | Modalidade de licitação obrigatória para aquisição de bens e serviços comuns, cujo critério de julgamento poderá ser o de menor preço ou o de maior desconto                                                                                                                                                                                                                | Sim   |
| 8      | Dispensa                                | Processo de contratação direta onde a licitação é dispensável ou dispensada                                                                                                                                                                                                                                                                                                 | Sim   |
| 9      | Inexigibilidade                         | Processo de contratação direta onde a licitação é inexigível                                                                                                                                                                                                                                                                                                                | Sim   |
| 10     | Manifestação de Interesse               | Procedimento auxiliar em que a Administração poderá solicitar à iniciativa privada, iniciado com a publicação de edital de chamamento público, a propositura e a realização de estudos, investigações, levantamentos e projetos de soluções inovadoras que contribuam com questões de relevância pública                                                                    | Sim   |
| 11     | Pré-qualificação                        | Procedimento auxiliar seletivo prévio à licitação, convocado por meio de edital, destinado à análise das condições de habilitação, total ou parcial, dos interessados ou do objeto                                                                                                                                                                                          | Sim   |
| 12     | Credenciamento                          | Procedimento auxiliar. Processo administrativo de chamamento público em que a Administração Pública convoca interessados em prestar serviços ou fornecer bens para que, preenchidos os requisitos necessários, se credenciem no órgão ou na entidade para executar o objeto quando convocados                                                                               | Sim   |
| 13     | Leilão - Presencial                     | Modalidade de licitação realizada sob a forma presencial para alienação de bens imóveis ou de bens móveis inservíveis ou legalmente apreendidos a quem oferecer o maior lance                                                                                                                                                                                               | Sim   |
| 14     | Inaplicabilidade da Licitação           | Situação em que, por especificidades da legislação ou natureza da atividade, não se exige o processo licitatório. Refere-se aos casos em que a lei determina que a licitação não é aplicável, seja pela natureza única do objeto ou pela impossibilidade de competição.                                                                                                     | Sim   |
| 15     | Chamada pública                         | Procedimento administrativo em que o poder público convoca interessados para apresentar propostas, visando selecionar fornecedores ou parceiros de forma aberta e previamente regulamentada.                                                                                                                                                                                | Sim   |
| 16     | Concorrência – Eletrônica Internacional | Modalidade de licitação utilizada pela Administração Pública para a contratação de bens e serviços comuns ou especiais, inclusive obras e serviços de engenharia, com participação de fornecedores nacionais e estrangeiros, realizada por meio eletrônico.                                                                                                                 | Sim   |
| 17     | Concorrência – Presencial Internacional | Modalidade de licitação utilizada pela Administração Pública para a contratação de bens e serviços comuns ou especiais, inclusive obras e serviços de engenharia, com a participação de fornecedores nacionais e estrangeiros, realizada de forma presencial, conforme regras estabelecidas no edital.                                                                      | Sim   |
| 18     | Pregão – Eletrônico Internacional       | Modalidade de licitação utilizada pela Administração Pública para a aquisição de bens e serviços comuns, com a participação de fornecedores nacionais e estrangeiros, realizada exclusivamente por meio eletrônico, conforme as regras previstas na legislação vigente.                                                                                                     | Sim   |
| 19     | Pregão – Presencial Internacional       | Modalidade de licitação utilizada pela Administração Pública para a aquisição de bens e serviços comuns, com a participação de fornecedores nacionais e estrangeiros, realizada de forma presencial, conforme as disposições legais e as regras estabelecidas no edital.                                                                                                    | Sim   |

> Atualizado via API ao vivo `GET /v1/modalidades` em 2026-05-13. O vault original capturou apenas os 10 primeiros (página paginada).

## Amparo Legal

| Código | Nome | Descrição | Tipo | Ativo |
| --- | --- | --- | --- | --- |
| 1 | Lei 14.133/2021, Art. 28, I | pregão: modalidade de licitação obrigatória para aquisição de bens e serviços comuns | Contratação | Sim |
| 2 | Lei 14.133/2021, Art. 28, II | concorrência: modalidade de licitação para contratação de bens e serviços especiais e de obras e serviços comuns e especiais de engenharia | Contratação | Sim |
| 3 | Lei 14.133/2021, Art. 28, III | concurso: modalidade de licitação para escolha de trabalho técnico, científico ou artístico, cujo critério de julgamento será o de melhor técnica ou conteúdo artístico, e para concessão de prêmio ou remuneração ao vencedor | Contratação | Sim |
| 4 | Lei 14.133/2021, Art. 28, IV | Leilão: modalidade de licitação para alienação de bens imóveis ou de bens móveis inservíveis ou legalmente apreendidos a quem oferecer o maior lance | Contratação | Sim |
| 5 | Lei 14.133/2021, Art. 28, V | diálogo competitivo: modalidade de licitação para contratação de obras, serviços e compras em que a Administração Pública realiza diálogos com licitantes previamente selecionados mediante critérios objetivos, com o intuito de desenvolver uma ou mais alternativas capazes de atender às suas necessidades, devendo os licitantes apresentar proposta final após o encerramento dos diálogos | Contratação | Sim |
| 6 | Lei 14.133/2021, Art. 74, I | Inexigibilidade de Licitação: aquisição de materiais, de equipamentos ou de gêneros ou contratação de serviços que só possam ser fornecidos por produtor, empresa ou representante comercial exclusivos | Contratação | Sim |
| 7 | Lei 14.133/2021, Art. 74, II | Inexigibilidade de Licitação: contratação de profissional do setor artístico, diretamente ou por meio de empresário exclusivo, desde que consagrado pela crítica especializada ou pela opinião pública | Contratação | Sim |
| 8 | Lei 14.133/2021, Art. 74, III, a | Inexigibilidade de Licitação: a) estudos técnicos, planejamentos, projetos básicos ou projetos executivos. | Contratação | Sim |
| 9 | Lei 14.133/2021, Art. 74, III, b | Inexigibilidade de Licitação: b) pareceres, perícias e avaliações em geral. | Contratação | Sim |
| 10 | Lei 14.133/2021, Art. 74, III, c | Inexigibilidade de Licitação: c) assessorias ou consultorias técnicas e auditorias financeiras ou tributárias. | Contratação | Sim |

> Captura paginada: a página indicava mais itens do que os listados acima.

## Modo de Disputa

| Código | Nome | Descrição | Ativo |
| --- | --- | --- | --- |
| 1 | Aberto |  | Sim |
| 2 | Fechado |  | Sim |
| 3 | Aberto-Fechado |  | Sim |
| 4 | Dispensa Com Disputa |  | Sim |
| 5 | Não se aplica |  | Sim |
| 6 | Fechado-Aberto |  | Sim |

## Critério de Julgamento

| Código | Nome | Descrição | Ativo |
| --- | --- | --- | --- |
| 1 | Menor preço |  | Sim |
| 2 | Maior desconto |  | Sim |
| 3 | Melhor técnica ou conteúdo artístico |  | Não |
| 4 | Técnica e preço |  | Sim |
| 5 | Maior lance |  | Sim |
| 6 | Maior retorno econômico |  | Sim |
| 7 | Não se aplica |  | Sim |
| 8 | Melhor técnica |  | Sim |
| 9 | Conteúdo artístico |  | Sim |

## Fonte Orçamentária

| Código | Nome | Descrição | Ativo |
| --- | --- | --- | --- |
| 1 | Não se aplica | Opção destinada às modalidades Leilão (Presencial ou Eletrônico), Credenciamento, Manifestação de Interesse e Pré-qualificação. | Sim |
| 2 | Municipal | Recurso orçamentário municipal disponível e devidamente vinculado à despesa que será realizada. | Sim |
| 3 | Estadual | Recurso orçamentário estadual disponível e devidamente vinculado à despesa que será realizada. | Sim |
| 4 | Federal | Recurso orçamentário federal disponível e devidamente vinculado à despesa que será realizada. | Sim |
| 5 | Organismo Internacional | Recurso proveniente de empréstimo ou doação oriundos de agência oficial de cooperação estrangeira ou de organismo financeiro do qual o Brasil seja parte, conforme os incisos I e II do § 3º do artigo 1º da Lei nº 14.133/2021. | Sim |
| 6 | Distrital | Recurso orçamentário distrital disponível e devidamente vinculado à despesa que será realizada. | Sim |

## Catálogo

| Código | Nome | Descrição | Ativo |
| --- | --- | --- | --- |
| 1 | Catálogo do Compras.gov.br | Catálogo de bens e serviços do Compras.gov.br | Sim |
| 2 | Outros |  | Sim |

## Categoria de Item

| Código | Nome | Descrição | Ativo |
| --- | --- | --- | --- |
| 1 | Material |  | Sim |
| 2 | Serviço |  | Sim |
| 3 | Obra |  | Sim |
| 4 | Serviços de Engenharia |  | Sim |
| 5 | Soluções de TIC |  | Sim |
| 6 | Locação de Imóveis |  | Sim |
| 7 | Alienação/Concessão/Permissão |  | Sim |
| 8 | Obras e Serviços de Engenharia |  | Sim |

## Regra de conformidade entre Instrumento Convocatório, Modalidade de Contratação e Amparo Legal

| Instrumento Convocatório | Modalidade de Contratação | Amparo Legal |
| --- | --- | --- |
| 1 - Edital | 1 - Leilão - Eletrônico | 4 - Lei 14.133/2021, Art. 28, IV |
| 1 - Edital | 2 - Diálogo Competitivo | 5 - Lei 14.133/2021, Art. 28, V |
| 1 - Edital | 3 - Concurso | 3 - Lei 14.133/2021, Art. 28, III |
| 1 - Edital | 4 - Concorrência - Eletrônica | 2 - Lei 14.133/2021, Art. 28, II |
| 1 - Edital | 5 - Concorrência - Presencial | 2 - Lei 14.133/2021, Art. 28, II |
| 1 - Edital | 6 - Pregão - Eletrônico | 1 - Lei 14.133/2021, Art. 28, I |
| 1 - Edital | 7 - Pregão - Presencial | 1 - Lei 14.133/2021, Art. 28, I |
| 2 - Aviso de Contratação Direta | 8 - Dispensa | 18 - Lei 14.133/2021, Art. 75, I |
| 3 - Ato que autoriza a Contratação Direta | 8 - Dispensa | 18 - Lei 14.133/2021, Art. 75, I |
| 2 - Aviso de Contratação Direta | 8 - Dispensa | 19 - Lei 14.133/2021, Art. 75, II |

> Captura paginada: a página indicava mais itens do que os listados acima.

## Regra de conformidade entre Modalidade de Contratação e Critério de Julgamento

| Modalidade de Contratação | Critério de Julgamento |
| --- | --- |
| 1 - Leilão - Eletrônico | 5 - Maior lance |
| 2 - Diálogo Competitivo | 1 - Menor preço |
| 2 - Diálogo Competitivo | 2 - Maior desconto |
| 2 - Diálogo Competitivo | 4 - Técnica e preço |
| 2 - Diálogo Competitivo | 6 - Maior retorno econômico |
| 2 - Diálogo Competitivo | 8 - Melhor técnica |
| 2 - Diálogo Competitivo | 9 - Conteúdo artístico |
| 3 - Concurso | 8 - Melhor técnica |
| 3 - Concurso | 9 - Conteúdo artístico |
| 4 - Concorrência - Eletrônica | 1 - Menor preço |

> Captura paginada: a página indicava mais itens do que os listados acima.

## Regra de conformidade entre Instrumento Convocatório e Modo de Disputa

| Instrumento Convocatório | Modo de Disputa |
| --- | --- |
| 1 - Edital | 1 - Aberto |
| 1 - Edital | 2 - Fechado |
| 1 - Edital | 3 - Aberto-Fechado |
| 1 - Edital | 5 - Não se aplica |
| 1 - Edital | 6 - Fechado-Aberto |
| 2 - Aviso de Contratação Direta | 4 - Dispensa Com Disputa |
| 3 - Ato que autoriza a Contratação Direta | 5 - Não se aplica |
| 4 - Edital de Chamamento Público | 5 - Não se aplica |

## Regra de conformidade entre Modalidade de Contratação e Fonte Orçamentária

| Modalidade de Contratação | Fonte Orçamentária |
| --- | --- |
| 1 - Leilão - Eletrônico | 1 - Não se aplica |
| 10 - Manifestação de Interesse | 1 - Não se aplica |
| 11 - Pré-qualificação | 1 - Não se aplica |
| 12 - Credenciamento | 1 - Não se aplica |
| 13 - Leilão - Presencial | 1 - Não se aplica |
| 2 - Diálogo Competitivo | 2 - Municipal |
| 3 - Concurso | 2 - Municipal |
| 4 - Concorrência - Eletrônica | 2 - Municipal |
| 5 - Concorrência - Presencial | 2 - Municipal |
| 6 - Pregão - Eletrônico | 2 - Municipal |

> Captura paginada: a página indicava mais itens do que os listados acima.

## Links Relacionados

- [Domínios](../mapas/dominios.md)
- [Índice LLM](../mapas/indice-llm.md)
- [Instrumento Convocatório](../sessoes/instrumento-convocatorio/index.md)
- [Modalidade de Contratação](../sessoes/modalidade-de-contratacao/index.md)
- [Amparo Legal](../sessoes/amparo-legal/index.md)
- [Modo de Disputa](../sessoes/modo-de-disputa/index.md)
- [Critério de Julgamento](../sessoes/criterio-de-julgamento/index.md)
- [Fonte Orçamentária](../sessoes/fonte-orcamentaria/index.md)
