# Fase 2 — Pesquisa documental inicial da ideia ID 06

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia (aba Ideias, linha 11):** “Controle estatístico e incerteza de medição (labs acreditados)”.  
**Nota/ranking:** em branco na cópia de trabalho. Não atribuí nota nem fiz alteração.

## Síntese

- [FATO] A oferta concorrente é visível. O Metroex, brasileiro, anuncia avaliação de incerteza, gestão metrológica, análise estatística/CEP e MSA. A Calibre.Software anuncia cálculos de incerteza segundo ISO GUM para gestão metrológica e laboratórios. A Actiz LIMS (também oferecida em projeto com a Biochemie) divulga avaliação de incerteza e cartas de controle/controle estatístico dentro de um LIMS.
- [FATO] Há ferramentas de estatística generalista: a Minitab divulga cartas de controle e análise de sistemas de medição (MSA). Podem ser alternativas/insumos de workflow, embora não sejam por isso equivalentes a um LIMS ou a um método metrológico validado para qualquer ensaio.
- [FATO] Para laboratórios de calibração, a Cgcre publica NIT-Dicla-021 revisão 10, intitulada “Expressão da incerteza de medição por laboratórios de calibração”. Inmetro disponibiliza GUM e suplementos em português. A Cgcre também descreve ensaios de proficiência (EP) como parte de avaliação/acreditação e controle da qualidade dos resultados; EP não equivale a controle estatístico interno nem a software de cálculo de incerteza.
- [INFERÊNCIA] “Controle estatístico” e “incerteza de medição” são problemas técnicos relacionados, mas diferentes: cartas/CEP monitoram comportamento de processo/dados ao longo do tempo; orçamento de incerteza quantifica contribuições associadas ao resultado de uma medição. Um módulo genérico que os trate como uma única feature pode não atender os contextos distintos.
- [NÃO ENCONTRADO] Dor, método atual, erros, custo, frequência, orçamento, sistema instalado, comprador e disposição a pagar de qualquer laboratório ligado a Will/Lucas. Nenhum dado de adoção/mercado independente foi localizado.
- [PENDENTE-HUMANO] Definir laboratório (ensaio químico, calibração ou clínico), mensurando/métodos e usuário especialista; testar um caso real de cálculo e de controle estatístico, revisar contra procedimento do laboratório e profissional metrologista/estatístico.

## 1. Escopo e distinções técnicas

- [FATO] A formulação da planilha associa “controle estatístico” e “incerteza de medição”, com observação “labs acreditados”. Não define setor, método, resultado ou workflow.
- [INFERÊNCIA] Convém separar ao menos: (a) cálculo/atualização de orçamento de incerteza por método/escopo; (b) registro da memória de cálculo e revisão; (c) carta de controle/monitoramento estatístico de processo ou CQI; (d) MSA/estudos de repetibilidade e reprodutibilidade; (e) resultados de ensaio de proficiência/comparações. Cada item tem entradas, objetivos e critérios diferentes.
- [HIPÓTESE] Valor potencial pode estar menos em “calcular um número” e mais em reuso/versionamento do orçamento, captura de dados, auditoria da memória de cálculo e vínculo com método/resultado. Nenhum cliente confirmou isso.
- [NÃO ENCONTRADO] Não se sabe se a oportunidade pretendida é ferramenta independente, módulo de LIMS, serviço técnico, consultoria ou aplicação vertical para ensaio químico.

## 2. Concorrentes e substitutos documentados

### C01 — Metroex (concorrente brasileiro próximo/direto)

- **Fontes oficiais:** https://metroex.com.br/ ; https://metroex.com.br/gestao/ ; https://metroex.com.br/industrias/ ; https://metroex.com.br/laboratorios-de-calibracao/ — acessadas em 29/09/2026.
- **[FATO]** O fornecedor divulga avaliação de incerteza conforme ISO GUM, gestão de laboratório/calibração, relatórios e registros técnicos customizáveis. Para indústria divulga CEP e MSA; para laboratórios de calibração declara emissão de certificados, avaliação de incerteza, equipamentos/padrões e rastreabilidade. Página de gestão cita cartas de QR em certificados e portal, mas não são o foco da ideia ID06.
- **[FATO — atribuição]** Site declara implantação de 3 a 12 meses conforme escopo e custo de implantação dependente do esforço/equipe; comercialização por licença de empresa sem limite de máquinas/usuários segundo FAQ publicada. Não há preço monetário público capturado.
- **Limitações:** reivindicações de aderência/conformidade são do fornecedor, não atestam adequação do produto ao método de um cliente. Depoimentos e números do próprio site não são validação independente de resultado. A página Gestão tinha contadores renderizados como “+0” em alguns elementos; esses placeholders não foram usados como contagem.

### C02 — Calibre.Software (software metrológico brasileiro; concorrente parcial)

- **Fonte oficial:** https://calibre.software/ — aberta em 29/09/2026.
- **[FATO]** Declara módulo de metrologia, cálculo de incerteza conforme ISO GUM e conformidade declarada com ISO/IEC 17025, mais SaaS, gestão documental e certificados. A página atende especialmente gestão laboratorial/metrológica e laboratórios de calibração.
- **Preço público:** não capturado; página pede demonstração e anuncia SaaS/servidor compartilhado ou dedicado em FAQ. Não estimei valor.
- **Limitações:** calculadora promocional de ROI exibe campos sem valores (“x horas”, “R$ xx.xx,xx”) e claim de produtividade de 30% sem estudo/método exposto na captura. Não foram usados como evidência de ganho real. Não foi confirmado na página um pacote de CEP para química analítica equivalente à proposta.

### C03 — Actiz LIMS / projeto Biochemie + Actiz (concorrente parcial/direto em módulo integrado)

- **Fontes oficiais:** https://actiz.com.br/en/ ; https://biochemie.com.br/sistema-lims-para-laboratorios/ — abertas em 29/09/2026.
- **[FATO]** Actiz apresenta LIMS com imagem/recurso de Statistical Process Control (SPC), amostras, testes e certificados. A página da Biochemie descreve projeto LIMS implementado pela Actiz e lista cartas de controle, controle estatístico, cálculos automatizados, memória de cálculo e avaliação de incerteza.
- **Preço:** não publicado; demonstração/diagnóstico.
- **Limitações:** descrição é do fornecedor/parceiro; não esclarece algoritmo, métodos cobertos, independência de cálculos, versionamento de orçamento, integração de CEP com cada ensaio nem custo do escopo específico.

### C04 — Minitab Statistical Software (substituto estatístico generalista)

- **Fonte oficial:** https://www.minitab.com/en-us/products/minitab/ — consultada em 29/09/2026.
- **[FATO]** Minitab lista Measurement System Analysis (gage studies e attribute agreement), cartas de controle variáveis/atributo/multivariadas/time-weighted/rare-event e análise de capacidade de processo.
- **Preço público:** não confirmado nas páginas consultadas; não preencher por valores de revendedores/terceiros.
- **Limitação:** ferramenta estatística ampla; não foi verificada implementação específica de orçamento de incerteza de laboratório conforme GUM/NIT-Dicla-021, integração LIMS ou configuração para segmento da ideia. É alternativa para parte analítica, não necessariamente concorrente substituto integral.

### C05 — Planilhas e software científico/estatístico (substitutos)

- [HIPÓTESE] Planilhas e ferramentas estatísticas existentes podem sustentar memória de cálculo, análises e cartas de controle, especialmente com consultoria interna.
- [FATO] O GUM e guias do Inmetro oferecem método/orientação técnica, mas não constituem por si só software de gestão/fluxo do laboratório. A existência de método, guia ou planilha disponível não comprova que o público atual a usa.
- [NÃO ENCONTRADO] Ferramentas e planilhas realmente utilizadas pelo público-alvo, custo de manutenção, histórico de erros e validação do cálculo.

## 3. Referências técnicas e regulatórias

### 3.1 Incerteza de medição

- **[FATO]** Cgcre/Inmetro lista NIT-Dicla-021 revisão 10, publicada/atualizada em 26/08/2025, como “Expressão da incerteza de medição por laboratórios de calibração”. Página e PDF: https://www.gov.br/cdtn/pt-br/centrais-de-conteudo/documentos-cgcre-abnt-nbr-iso-iec-17025/nit-dicla-21/view (acesso 29/09/2026). Escopo declarado no título é laboratório de calibração; não generalizar automaticamente para toda análise química.
- **[FATO]** Inmetro lista o GUM (edição brasileira de 2008), GUM Suplemento 1 (propagação por Monte Carlo) e Suplemento 2 (múltiplas grandezas de saída, versão brasileira 2025) na página https://www.gov.br/inmetro/pt-br/assuntos/metrologia-cientifica/documentos-tecnicos-em-metrologia (acesso 29/09/2026). São documentos técnicos para avaliação de dados/incerteza, não especificação completa de software de negócio.
- **[FATO]** Manual da Qualidade Cgcre, Rev. 30, nov/2025, declara que a acreditação de laboratórios de ensaio/calibração se baseia na ABNT NBR ISO/IEC 17025 e de laboratórios clínicos na ISO 15189, e referencia NIT-Dicla-030 para política de rastreabilidade metrológica. Fonte: https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/manual-de-qualidade-da-cgcre-mq-cgcre.pdf.
- [NÃO ENCONTRADO] Texto integral da ISO/IEC 17025 e da ISO 15189 não foi consultado nesta etapa; não declaro cláusulas específicas nem todos os requisitos para cada tipo de laboratório. Normas ABNT completas podem exigir aquisição.

### 3.2 Estatística, controle de resultados e ensaios de proficiência

- **[FATO]** Página oficial da Cgcre sobre EP, atualizada em 07/02/2025, diz que EP integra avaliação/acreditação e serve como mecanismo de controle da qualidade dos resultados previstos na ISO/IEC 17025; benefícios descritos incluem avaliação externa da validade, comparação com laboratórios semelhantes e subsídios para ações preventivas. A página remete requisitos à NIT-Dicla-026. URL: https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/ensaios-de-proficiencia (acesso 29/09/2026).
- [INFERÊNCIA] EP/comparação interlaboratorial e monitoramento interno por cartas de controle são atividades relacionadas à garantia de validade, mas não intercambiáveis; uma não substitui automaticamente a outra.
- [FATO] O conteúdo oficial da Cgcre recomenda contato com provedores para obter custos, protocolos e detalhes técnicos de cada programa. Não há custo publicado capturado nem frequência universal estabelecida neste relatório.
- [NÃO ENCONTRADO] NIT-Dicla-026 em sua revisão corrente não foi recuperada como texto integral nessa captura; apenas a página Cgcre atual e referência ao documento foram verificadas. Portanto não resumimos todos os requisitos/frequências.

### 3.3 Software e validação técnica

- [INFERÊNCIA] Para uso em contexto acreditado, um cálculo precisa ser correto para o modelo e método, rastreável, reproduzível e verificável; a escolha da abordagem e dos componentes não pode ser automatizada com segurança sem avaliação técnica do caso. Software não torna um orçamento de incerteza tecnicamente adequado apenas por anunciar conformidade.
- [HIPÓTESE] Produto pode enfrentar responsabilidade técnica se usuário confiar em resultados errados, escolhas inadequadas de distribuição/componentes ou cartas configuradas incorretamente.
- [PENDENTE-HUMANO — ESPECIALISTA] Um metrologista/estatístico e o responsável técnico devem revisar a seleção do método, unidades, dados de entrada, regras de arredondamento, propagação, fator/intervalo, correlações e evidências de verificação antes de qualquer uso operacional.

## 4. Mercado, dor, comprador e preço

- [NÃO ENCONTRADO] Número de laboratórios-alvo acessíveis, quantos fazem incerteza em planilha, frequência de revisão, esforço por método, não conformidades atribuíveis ao processo, preço de licenças existentes e disposição a pagar.
- [FATO] Produtos comerciais oferecem componentes da proposta, mas páginas comerciais e guias técnicos não demonstram demanda ou espaço de mercado.
- [ESTIMATIVA] Não realizada: sem população/ICP, incidência de dor, preço real e tamanho dos segmentos não há fórmula defensável para mercado acessível.
- [PENDENTE-HUMANO] Entrevistar responsáveis de pelo menos um segmento homogêneo (p.ex., laboratórios de calibração elétrica ou laboratórios de ensaio químico acreditados — escolha ainda aberta). Pedir demonstração de orçamento/cartas atuais, revisar uma ocorrência real e quantificar horas, retrabalho, auditorias e integrações.

## 5. Avaliação crítica e nota

- [FATO] A nota da ideia permanece sem preenchimento na planilha; não atribuí pontuação.
- [INFERÊNCIA] Uma aplicação generalista de CEP e incerteza competiria com LIMS/módulos e suites estatísticas já anunciados. Oportunidade pode depender de um nicho, interface ou método técnico específico; não há evidência para definir qual.
- **Riscos:**
  1. [INFERÊNCIA] Escopo amplo combina metrologia, estatística, validação de método, LIMS e qualidade, com requisitos diferentes entre laboratório de calibração, ensaio químico e clínico.
  2. [HIPÓTESE] Usuários podem preferir planilhas auditadas ou ferramenta estatística generalista integrada ao LIMS atual.
  3. [INFERÊNCIA] “Cálculo automático” pode criar confiança indevida em modelo/método selecionado incorretamente.
  4. [FATO] Existem soluções de mercado com cálculo de incerteza ou SPC divulgados (C01–C04), reduzindo plausibilidade de novidade ampla.
  5. [NÃO ENCONTRADO] Preço, implantação, custo de validação/configuração e vantagem mensurável em relação às ferramentas já usadas.

## 6. Próximo teste humano

- **Hipótese:** um segmento de laboratório tem retrabalho ou risco significativo na elaboração/revisão de incerteza e monitoramento estatístico que não é resolvido por ferramenta atual.
- **Participantes:** responsável técnico/metrologista, analista que prepara dados e comprador/gestor do laboratório; segmentar por laboratório de calibração ou ensaio químico — não misturar grupos na primeira rodada.
- **Teste:** mapear e acompanhar um estudo de incerteza e uma carta de controle reais, anonimizados; comparar planilha/sistema atual com uma demonstração de Metroex/Actiz/Minitab ou protótipo, sem considerar output de demo como validação. Avaliar de forma independente um conjunto conhecido de dados de referência.
- **Métricas:** tempo por estudo, retrabalho/erros documentados, número de métodos/orçamentos mantidos, frequência de atualização, etapas de revisão, reprodutibilidade contra cálculo independente e integração com relatório/LIMS.
- **Critério de avanço:** Will/Lucas e especialista definem antes de entrevistas; limiar não inventado aqui.
- **Segurança:** não usar dados identificáveis/sensíveis nem resultado do protótipo em liberação operacional sem validação e autorização formais do laboratório.

## 7. Fontes e log de verificação

- **S01 Metroex:** https://metroex.com.br/ ; https://metroex.com.br/gestao/ ; https://metroex.com.br/industrias/ ; https://metroex.com.br/laboratorios-de-calibracao/ — páginas oficiais abertas 29/09/2026; CEP/MSA e incerteza declarados; preço não encontrado.
- **S02 Calibre.Software:** https://calibre.software/ — página oficial aberta 29/09/2026; metrologia e incerteza GUM anunciadas; preço não encontrado; ROI não utilizado como evidência.
- **S03 Actiz LIMS:** https://actiz.com.br/en/ — página oficial aberta 29/09/2026; SPC apresentado dentro de LIMS.
- **S04 Biochemie + Actiz:** https://biochemie.com.br/sistema-lims-para-laboratorios/ — página oficial aberta 29/09/2026; lista incerteza, cartas de controle, estatística e memória de cálculo; produto por demonstração.
- **S05 Minitab:** https://www.minitab.com/en-us/products/minitab/ — página oficial consultada 29/09/2026; control charts e MSA divulgados; preço e função específica de incerteza GUM não confirmados.
- **S06 Cgcre NIT-Dicla-021 rev.10:** https://www.gov.br/cdtn/pt-br/centrais-de-conteudo/documentos-cgcre-abnt-nbr-iso-iec-17025/nit-dicla-21/view — documento oficial atualizado 26/08/2025; escopo indicado no próprio título: calibração.
- **S07 Inmetro documentos GUM:** https://www.gov.br/inmetro/pt-br/assuntos/metrologia-cientifica/documentos-tecnicos-em-metrologia — acesso 29/09/2026; GUM, suplementos e lista de documentos.
- **S08 Cgcre EP:** https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/ensaios-de-proficiencia — página atualizada 07/02/2025, acesso 29/09/2026; papel do EP e referência à NIT-Dicla-026.
- **S09 MQ-Cgcre Rev.30:** https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/manual-de-qualidade-da-cgcre-mq-cgcre.pdf — novembro/2025; bases de acreditação e NIT-Dicla-030.

| Data local | Item | Ação/resultado | Fontes | Classificação/confiança | Pendência |
|---|---|---|---|---|---|
| 29/09/2026 | ID06 oferta | Verificados Metroex, Calibre.Software, Actiz/Biochemie e Minitab com funções anunciadas de incerteza, SPC/CEP ou MSA | S01–S05 | [FATO] sobre páginas dos fornecedores; média para oferta, não desempenho | Demonstrações, escopo, método, licença e preço |
| 29/09/2026 | ID06 normativo | Aberta NIT-Dicla-021 Rev.10, documentos GUM, página EP e MQ-Cgcre Rev.30 | S06–S09 | [FATO] quanto aos documentos oficiais; alta para metadados/texto consultado | Verificar aplicabilidade por segmento e revisar textos normativos completos |
| 29/09/2026 | ID06 dor/mercado | Sem entrevistas, orçamento, custo ou método do público; nenhuma estimativa/nota | S01–S09 | [NÃO ENCONTRADO]/[PENDENTE-HUMANO] | Pesquisa primária e revisão especialista |

## Correção de inventário da planilha — 29/09/2026

**Errata:** a afirmação anterior de que a nota da ID 06 estava em branco estava incorreta. A conferência direta da cópia `pesquisa-ideias-will-lucas_v2.xlsx`, aba Análise, linha 19, identificou a avaliação preexistente de **3,50**, posição **14**. Trata-se da hipótese inicial da planilha, não de nota nova nem de evidência de mercado. O texto acima é preservado como histórico e esta correção o substitui quanto ao estado da planilha. Nenhuma célula foi alterada.
