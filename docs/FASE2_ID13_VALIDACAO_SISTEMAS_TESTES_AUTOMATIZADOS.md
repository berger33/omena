# Fase 2 — Pesquisa documental inicial da ideia ID 13

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia (aba Ideias, linha 18):** “Validação de sistemas computadorizados e testes automatizados como serviço”.  
**Nota/ranking:** não alterado; nenhuma nota atribuída.

## Síntese executiva

- [FATO] A ideia combina duas ofertas que podem ter clientes, entregáveis e critérios de compra diferentes: **(A) validação de sistemas informatizados (VSI/CSV) no contexto GxP/regulado** e **(B) engenharia/automação de testes de software para times de desenvolvimento em geral**. Testes automatizados podem ser parte da evidência de validação, mas não são equivalentes à validação do sistema.
- [FATO] No escopo específico de fabricação de medicamentos, a IN Anvisa 134/2022 aparece como vigente na base AnvisaLegis. Ela cobre sistemas computadorizados usados como parte de atividades reguladas por BPF de medicamentos; determina validação do aplicativo, qualificação da infraestrutura, gestão de risco ao longo do ciclo de vida, requisitos rastreáveis, evidência apropriada de teste e validação de ferramentas/ambientes de teste automatizado. Essa norma não deve ser apresentada como regra universal para qualquer software ou empresa.
- [FATO] RDC Anvisa 665/2022 é o regulamento de BPF de produtos médicos e produtos para diagnóstico in vitro. A Anvisa diz que consolidou o regramento anterior e manteve os requisitos de mérito. Escopo e aplicação devem ser determinados para o tipo de fabricante/atividade; não extrapolar IN 134/2022 de medicamentos para dispositivos médicos.
- [FATO] Há ofertas brasileiras visíveis para consultoria CSV/VSI e também para QA/testes automatizados: AEDRU (serviço com foco explícito em laboratórios), One Consultoria Regulatória, NebulaCSV, Testing Company e Base2 Tecnologia. Portanto, existe oferta concorrente; não foi verificado tamanho da demanda nem lacuna de mercado.
- [FATO] Empresas e clientes regulados continuam tendo responsabilidades próprias sobre seu sistema, seus processos e a decisão de uso. Terceirizar testes ou documentação não comprova automaticamente que o sistema esteja adequado; a IN 134 prevê seleção/avaliação de fornecedores, responsabilidades contratuais, avaliação de risco e documentação sob governança do fabricante.
- [NÃO ENCONTRADO] Entrevistas, clientes, projetos pagos, preço aceito, recorrência, ciclo comercial, custo de aquisição, taxa de automação útil, retorno ou disposição a pagar de clientes ligados a Will. Páginas comerciais e alegações de experiência/ROI não substituem validação humana.
- [PENDENTE-HUMANO] Escolher qual das duas ofertas testar primeiro e para qual setor. Para CSV, entrevistar QA/Validação/IT de empresa regulada e entender sistema, escopo GxP, risco e evidências que faltam. Para automação de testes, entrevistar CTO/QA/Engineering e observar pipeline, regressão e manutenção de testes. Não combinar os dois perfis na mesma hipótese de negócio.

## 1. Desambiguação do conceito

### A — Validação de sistemas informatizados (VSI/CSV)

- [FATO] No vocabulário da Anvisa, “sistema computadorizado” inclui componentes de software e hardware e o trabalho pode envolver planejamento, risco, requisitos do usuário, testes, documentação, operação/manutenção, mudanças e eventual desativação — de acordo com o regime aplicável.
- [HIPÓTESE] Uma oferta pode ser diagnóstico de lacunas, estratégia/planejamento de validação, execução documentada de testes, remediação de documentação, treinamento ou suporte recorrente a mudanças/revisões periódicas.
- [NÃO ENCONTRADO] Quais clientes, segmentos, sistemas e entregáveis seriam atendidos por Will; qual experiência/certificação demonstrável; contratação anterior; preço, capacidade e concorrência no ICP.

### B — QA/automação de testes de software

- [FATO] É serviço de engenharia de qualidade de software: selecionar e implementar testes automatizados (p.ex., regressão, API, UI, performance), conectar execução a pipelines CI/CD e manter scripts/relatórios.
- [HIPÓTESE] Possíveis modelos são diagnóstico/PoC, projeto de framework, entrega por escopo ou time/retainer.
- [NÃO ENCONTRADO] Stack mais familiar de Will, vertical de software, maturidade das equipes-alvo, gargalo mensurado em releases, decisão de terceirizar ou orçamento.

### Consequência de escopo

- [INFERÊNCIA] CSV tende a ser comprado por qualidade/regulatório/validação/IT em organizações reguladas e exige domínio de jurisdição, risco e documentação auditável. QA automation genérico tende a ser comprado por engenharia/produto/QA e é avaliado por cobertura útil, estabilidade, velocidade de feedback e manutenção. São funis comerciais distintos.
- [DECISÃO DE PESQUISA] Não calcular uma única nota de mercado para a ideia combinada. Se desejarem prosseguir, separar em duas hipóteses e escolher uma para validação humana; preservar a redação original da planilha sem alteração.

## 2. Evidência regulatória e seus limites

### 2.1 Medicamentos — Anvisa IN 134/2022 e RDC 658/2022

- **[FATO]** A base AnvisaLegis consultada identifica a IN nº 134, de 30/03/2022, como **vigente**. Seu art. 2º limita o escopo às formas de sistemas computadorizados usadas como parte de atividades reguladas pelas BPF de medicamentos, inclusive medicamentos experimentais; a IN revogou a IN 43/2019. Texto consultado: https://anvisalegis.datalegis.net/action/ActionDatalegis.php?acao=abrirTextoAto&tipo=INM&numeroAto=00000134&seqAto=000&valorAno=2022&orgao=DC/ANVISA/MS&codTipo=&desItem=&desItemFim=&cod_menu=9434&cod_modulo=310&pesquisa=true.
- **[FATO]** Arts. 5–9 tratam de validação do aplicativo, qualificação de infraestrutura e abordagem documentada, baseada em risco considerando qualidade do produto, integridade dos dados e segurança do paciente. Arts. 15–24 abordam ciclo de vida, documentação, inventário, requisitos do usuário rastreáveis, avaliação de fornecedor, validação de sistemas customizados, evidência de cenários de teste e verificação de migração de dados.
- **[FATO]** Art. 23, §2º: ferramentas automatizadas e ambientes de teste devem ter avaliações documentadas de sua adequação. Isso é uma exigência específica do contexto da IN para fabricação de medicamentos sob BPF; não implica que um fornecedor externo possa declarar uma certificação universal de software.
- **[FATO]** Arts. 25–45 tratam de controles de troca de dados, verificações de exatidão, backup/restauração, trilha de auditoria conforme risco, controle de alterações, avaliação periódica, acesso, incidentes, assinatura eletrônica, continuidade do negócio e arquivamento.
- **[FATO]** Art. 11 exige contrato com prestadores/terceiros quando fornecem, instalam, configuram, integram, validam, mantêm, modificam ou armazenam sistemas/serviços/dados, com responsabilidades claramente estabelecidas. Art. 12 trata competência/confiabilidade do fornecedor. A contratação de consultoria, por si, não transfere as responsabilidades do fabricante nem aprova a adequação do sistema.
- **[FATO]** A Anvisa disponibiliza Guia de Validação de Sistemas Computadorizados nº 33 (2020). A página identifica-o como guia de orientação; em roteiro oficial comentado da Anvisa, o guia é descrito como recomendatório/não vinculante. Fonte do guia: https://www.gov.br/anvisa/pt-br/centraisdeconteudo/publicacoes/medicamentos/publicacoes-sobre-medicamentos/guia-de-validacao-de-sistemas-computadorizados.pdf/@@display-file/file. Exemplo de roteiro oficial que o caracteriza como não vinculante: https://www.gov.br/anvisa/pt-br/assuntos/sangue/inspecao/arquivos/roteiro-comentado-rdc508_21_cph_v00.pdf/@@display-file/file.
- [INFERÊNCIA] A entrega consultiva provavelmente depende de acesso a documentação de fornecedor, processos e dados controlados do cliente; independência, confidencialidade e quem aprova/libera o sistema são fatores de compra e execução.

### 2.2 Dispositivos médicos — RDC 665/2022 (regime distinto)

- **[FATO]** Anvisa descreve a RDC 665/2022 como consolidação das BPF/BP de distribuição e armazenamento de produtos médicos e de diagnóstico in vitro; a agência informou que a consolidação não alterou o mérito dos requisitos em relação à RDC 16/2013 e IN 8/2013. Fonte oficial: https://www.gov.br/anvisa/pt-br/assuntos/noticias-anvisa/2022/rdc-665-de-2022.
- **[FATO]** Em versão inglesa oficial da RDC 665, arts. 104–106 incluem validação de sistemas computadorizados/software que possam afetar adversamente a qualidade do produto ou do sistema da qualidade, verificação periódica e controle de alterações. Página/download Anvisa: https://www.gov.br/anvisa/en/regulation-of-companies/arquivos/rdc-665-2022-e.pdf/view (consulta 29/09/2026; o fetch do PDF retornou 404, então conteúdo do texto em inglês foi confirmado pelo resultado de busca e não por leitura direta do arquivo).
- [NÃO ENCONTRADO] Nesta rodada não foi feita análise integral da versão oficial em português da RDC 665, nem enquadramento jurídico de empresa/produto específico.

### 2.3 Outros setores e padrões externos

- [FATO] A Anvisa possui guias/roteiros específicos para contextos como ensaios clínicos e hemoterapia, além de regimes próprios por produto/atividade. A referência de uma norma setorial não autoriza generalizar a obrigação a qualquer software empresarial.
- [INFERÊNCIA] GAMP 5, 21 CFR Part 11, EU GMP Annex 11, ISO 13485 ou ISO/IEC 17025 podem aparecer em projeto conforme mercado, exportação ou uso do cliente; cada referência precisa ter escopo e aplicabilidade conferidos. Não tratar GAMP 5 como lei brasileira ou como certificado automático de produto.
- [NÃO ENCONTRADO] Revisão normativa completa dos demais setores listados por consultorias (cosméticos, saneantes, alimentos, logística, dispositivos, laboratórios) não executada.

## 3. Alternativas, concorrentes e substitutos

### A01 — AEDRU: VSI/CSV e integridade de dados com foco em laboratórios

- **Página do fornecedor:** https://www.aedru.com/servicos/vsi-validacao-sistemas-informatizados (aberta em 29/09/2026).
- **[FATO]** Declara atender laboratórios e sistemas como CDS, LIMS, software de instrumentos, planilhas e sistemas de aquisição de dados. Lista avaliação de risco, URS, QI/QO/QD, testes funcionais/segurança, audit trail, controle de acesso, integridade de dados, gestão de mudanças/revalidação e dossiê. A página convida a solicitar orçamento.
- **[FATO]** A página também oferece ferramenta interna Ergon para gestão de qualificações e apresenta serviço integrado de qualificação de instrumentos. É o concorrente mais diretamente adjacente ao perfil de laboratório identificado nesta ideia.
- **Preço público:** não encontrado; orçamento.
- **Limitação:** tudo acima é declaração de fornecedor; não prova desempenho, independência, escopo local ou satisfação de clientes.

### A02 — One Consultoria Regulatória: consultoria CSV por projeto/programa/recorrência

- **Página oficial:** https://oneconsultoriareg.com/consultoria-de-validacao-de-sistemas/ (aberta em 29/09/2026).
- **[FATO]** Declara diagnóstico/gap assessment, plano mestre, procedimentos, remediação, apoio em inspeções, execução terceirizada total/parcial, mentoria e suporte recorrente. A página menciona segmentos regulados e múltiplas normas.
- **Preço:** não público; proposta/cotação.
- **Limitação:** alcance e experiência são claims da empresa; não foi feita checagem de referências de clientes nem de capacidade técnica.

### A03 — NebulaCSV: validação de sistemas e planilhas

- **URL de serviço:** https://nebulacsv.com/pagina/validacao-de-sistemas-computadorizados/24/ (localizada em pesquisa 29/09/2026).
- **[FATO]** Página descreve inventário/classificação de sistemas, risco, URS, plano, qualificação IQ/OQ/PQ, matriz de rastreabilidade e relatório, inclusive planilhas.
- **Preço:** não encontrado; contato comercial.
- **Limitação:** página comercial; sem confirmação independente de entregas/adequação.

### A04 — Testing Company: automação e consultoria de QA

- **URL oficial:** https://www.testingcompany.com.br/ (aberta em 29/09/2026).
- **[FATO]** Declara automatizar ambientes SAP, Delphi, Web, Mobile e Desktop, implantar suítes ligadas a pipeline, oferecer consultoria/mentoria, outsourcing, performance e documentação. Publica cases e resultados de automação e oferece diagnóstico sem custo.
- **Preço:** não público na página consultada; conversa/escopo comercial.
- **Limitação:** métricas e cases são publicados pelo próprio fornecedor; não comprovam resultado reproduzível ou preço para o cliente-alvo.

### A05 — Base2 Tecnologia: QA, automação, auditoria, outsourcing e produtos

- **URL oficial:** https://base2.com.br/ (aberta em 29/09/2026).
- **[FATO]** Página anuncia consultoria QA, automação/performance, outsourcing, auditoria e produtos Melo QA (gestão de testes) e Crowdtest (rede de testadores). Apresenta cases e números próprios de experiência/escala.
- **Preço:** não público na página consultada.
- **Limitação:** oferta ampla de qualidade de software, não equivalente a validação regulatória CSV; métricas/claims não foram auditados.

### A06 — Abstracta: serviços de testes automatizados e quality engineering

- **Página oficial:** https://abstracta.us/solutions/qa-automation-services (resultado de busca em 29/09/2026).
- **[FATO]** Declara fornecer serviços de QA/testes automatizados e informa presença/contato no Brasil, além de atuação regional/internacional.
- **Preço:** não encontrado; contato comercial.
- **Limitação:** serviço geral de quality engineering, não prova especialização em CSV Anvisa.

### A07 — Equipe interna, frameworks abertos, ferramentas próprias/low-code e consultorias generalistas

- [FATO] Alternativas à contratação incluem desenvolvimento e manutenção de testes pela equipe do cliente, uso de frameworks open-source, ferramentas comerciais SaaS e equipe terceirizada/consultoria.
- [NÃO ENCONTRADO] Qual dessas alternativas o ICP usa, custos, satisfação, fragilidade dos scripts, velocidade do ciclo manual ou esforço de manutenção.
- [INFERÊNCIA] Para buyer técnico, concorre-se também com backlog interno (“fazer depois”), contratação de QA dedicado e consultoria de fábrica de software; para comprador regulatório, concorre-se com equipe de CSV interna e projetos consultivos de validação.

## 4. Mercado, modelo comercial e sinais de demanda

- [NÃO ENCONTRADO] Número de empresas sujeitas a cada regime regulatório, inventários de sistemas críticos, atrasos/falhas de validação, tamanho de gastos anuais, verba de consultoria, renovação/recorrência, ticket médio e disposição a pagar.
- [FATO] Concorrentes divulgam projetos pontuais, programas completos, outsourcing, suporte recorrente, automação de regressão, licenças de ferramenta e diagnósticos. Isso comprova variedade de oferta, não procura comprovada nem market size.
- [FATO] Nenhum dos fornecedores brasileiros consultados publicou preço completo para escopo CSV ou automação customizada. Não estimar tarifa por hora ou preço mensal com base em diretórios genéricos/internacionais.
- [ESTIMATIVA] Não calculada: sem ICP, pacote de entregáveis, duração real por projeto e preço confirmado não há estimativa de mercado defensável.

## 5. Riscos e advogado do diabo

1. [INFERÊNCIA] A ideia pode ser dois negócios diferentes sem sinergia suficiente: consultoria documental regulatória versus engenharia de automação contínua.
2. [FATO] Há concorrentes locais que já anunciam exatamente CSV de sistemas/planilhas e QA automation; diferenciação baseada somente em “testes automatizados” é fraca sem segmento, técnica, integração ou resultado distintivo comprovado.
3. [INFERÊNCIA] Em CSV, documentação impecável não basta se abordagem não é proporcional ao risco, não há entendimento do processo/dado, testes não cobrem uso pretendido ou o cliente não controla o ciclo de vida.
4. [INFERÊNCIA] Em automação, testes frágeis/flaky, falsa confiança de cobertura, custo inicial, manutenção após mudanças e demora para estabilizar framework podem tornar projeto antieconômico.
5. [INFERÊNCIA] Executar testes para um sistema e também declarar independentemente que ele está validado pode criar risco de conflito percebido; papéis de executor, revisor e aprovador devem ser acordados e documentados.
6. [INFERÊNCIA] Dados regulados, credenciais, dados pessoais e ambientes de produção exigem controles de confidencialidade/segurança, contrato, autorização e acesso mínimo; não improvisar cópia de dados reais em ferramentas externas.
7. [NÃO ENCONTRADO] Evidência de experiência/prova social de Will para CSV regulatório, contatos, capacidade comercial/técnica, certificações pertinentes ou disposição a assumir responsabilidade contratual.

## 6. Próximo teste humano

### Primeiro, escolher a pista

- **Pista A — CSV/VSI para sistemas de laboratórios:** focar laboratórios farmacêuticos, laboratórios de QC de fabricantes, CDS/LIMS, software de instrumento ou planilha GxP somente se houver experiência e acesso legítimo ao segmento. Entrevistar QA/Validação, proprietário de sistema/processo e laboratório. Mapear gatilho de compra (sistema novo, atualização, auditoria, migração, remediação) e escopo aprovado.
- **Pista B — QA automation:** escolher tipo de aplicação/equipe (p.ex., SaaS B2B, ERP legado, e-commerce) e observar pipeline, regressão atual, esforço manual, flakiness, custo de regressões e manutenção. Entrevistar liderança QA/engenharia/produto.
- Não usar conversas de uma pista como evidência para a outra.

### Teste inicial proposto (a definir com Will)

1. Fazer 5–8 entrevistas exploratórias como proposta de amostra, não evidência existente; pedir um exemplo recente de mudança/release/auditoria, não opiniões genéricas sobre a ideia.
2. Quando autorizado, rever um pacote anonimizado ou fluxo de trabalho atual: requisitos, análise de risco, testes, evidências, defeitos/desvios, aprovação, manutenção; identificar onde há trabalho repetido ou bloqueio observável.
3. Em QA automation, executar PoC apenas em aplicação/ambiente de demonstração ou sob contrato e autorização. Medir duração real para automatizar, cobertura dos fluxos de maior risco, taxa de falha não relacionada a produto e custo de manutenção por mudança.
4. Em CSV, não oferecer “certificado de conformidade” nem prometer aprovação de inspeção. Propor diagnóstico delimitado e confirmar quem é responsável pelo sistema e quem aprova entregáveis.
5. Registrar orçamento apenas por proposta/contratação real, distinguindo intenção verbal de compra efetiva. Definir com Will critério seguir/parar antes do teste; não inventar threshold ou ROI.

## 7. Fontes e log

### Fontes consultadas

- **S01 — Anvisa IN 134/2022, AnvisaLegis (status indicado “Vigente”):** https://anvisalegis.datalegis.net/action/ActionDatalegis.php?acao=abrirTextoAto&tipo=INM&numeroAto=00000134&seqAto=000&valorAno=2022&orgao=DC/ANVISA/MS&codTipo=&desItem=&desItemFim=&cod_menu=9434&cod_modulo=310&pesquisa=true — texto consultado nos dois trechos; escopo medicamentos e arts. 23, 11 etc.
- **S02 — Anvisa RDC 658/2022 e INs (perguntas e respostas):** https://www.gov.br/anvisa/pt-br/centraisdeconteudo/publicacoes/certificacao-e-fiscalizacao/perguntas-e-respostas/perguntas-e-respostas-rdc-301-de-2019.pdf/view — página oficial; escopo RDC 658 e INs vinculadas.
- **S03 — Anvisa RDC 665/2022, notícia institucional:** https://www.gov.br/anvisa/pt-br/assuntos/noticias-anvisa/2022/rdc-665-de-2022 — escopo e histórico de consolidação.
- **S04 — Anvisa Guia 33, validação de sistemas computadorizados:** https://www.gov.br/anvisa/pt-br/centraisdeconteudo/publicacoes/medicamentos/publicacoes-sobre-medicamentos/guia-de-validacao-de-sistemas-computadorizados.pdf/@@display-file/file — página oficial consultada; atualização publicada em 22/10/2020.
- **S05 — AEDRU VSI/CSV:** https://www.aedru.com/servicos/vsi-validacao-sistemas-informatizados — aberta 29/09/2026; oferta declarada para laboratórios.
- **S06 — One Consultoria Regulatória:** https://oneconsultoriareg.com/consultoria-de-validacao-de-sistemas/ — aberta 29/09/2026; serviços de CSV declarados.
- **S07 — NebulaCSV:** https://nebulacsv.com/pagina/validacao-de-sistemas-computadorizados/24/ — página comercial localizada via busca em 29/09/2026; entregáveis declarados.
- **S08 — Testing Company:** https://www.testingcompany.com.br/ — aberta 29/09/2026; automação e QA declarados.
- **S09 — Base2 Tecnologia:** https://base2.com.br/ — aberta 29/09/2026; consultoria QA, automação, produtos e outsourcing declarados.
- **S10 — Abstracta QA automation:** https://abstracta.us/solutions/qa-automation-services — resultado de busca consultado 29/09/2026; serviços e presença no Brasil declarados.
- **S11 — Anvisa roteiro comentado sobre sistemas informatizados:** https://www.gov.br/anvisa/pt-br/assuntos/sangue/inspecao/arquivos/roteiro-comentado-rdc508_21_cph_v00.pdf/@@display-file/file — fonte oficial; material de orientação e menção ao Guia 33 como recomendatório/não vinculante.

| Data local | Item | Ação/resultado | Fontes | Classificação/confiança | Pendência |
|---|---|---|---|---|---|
| 29/09/2026 | Regulação BPF medicamentos | Consultada IN 134 inteira via AnvisaLegis; status “vigente”; leu arts. 2, 5–24 e 25–45 | S01–S02 | [FATO] ato normativo em base regulatória; alta para o texto consultado, requer interpretação legal contextual | Avaliar aplicação ao cliente/setor concreto |
| 29/09/2026 | Guia oficial | Confirmado Guia Anvisa 33/2020 e caráter orientativo/não vinculante em roteiro oficial | S04, S11 | [FATO] documento oficial | Revisar guia integral para serviço específico |
| 29/09/2026 | Regime de dispositivo médico | Consultada notícia Anvisa da RDC 665; resultado oficial aponta artigos de validação de software/sistemas, mas PDF em inglês retornou erro 404 no fetch | S03 e resultado oficial de busca | [FATO] limite de verificação menor; conteúdo do artigo 104 não confirmado por leitura direta do arquivo nesta rodada | Consultar texto consolidado em português antes de aconselhamento |
| 29/09/2026 | Concorrentes de CSV/VSI | Abertas páginas AEDRU e One; consultada oferta NebulaCSV | S05–S07 | [FATO] serviços anunciados; capacidade/resultado não verificados | Pedir cotações e referências, se pista escolhida |
| 29/09/2026 | Concorrentes de QA automation | Aberta Testing Company e Base2; consultada Abstracta | S08–S10 | [FATO] ofertas declaradas; claims/cases não auditados | Comparar escopo, preço e nicho em proposta real |
| 29/09/2026 | Dor, preço e conversão | Nenhuma entrevista, contrato, cliente ou teste humano realizado | — | [NÃO ENCONTRADO]/[PENDENTE-HUMANO] | Escolher pista e validar com compradores reais |
