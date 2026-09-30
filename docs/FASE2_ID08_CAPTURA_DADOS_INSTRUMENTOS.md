# Fase 2 — Pesquisa documental inicial da ideia ID 08

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia (aba Ideias, linha 13):** “Captura automática de dados de instrumentos (balança, pHmetro etc.), sem redigitar”.  
**Nota/ranking:** não alterado; nenhuma nota atribuída.

## Síntese executiva

- [FATO] A necessidade técnica é conhecida como interface/integração de instrumentos, aquisição de dados ou instrument interfacing. Fornecedores já oferecem captura automática de balanças, medidores de pH e instrumentos analíticos, seja no software do próprio fabricante, em middleware ou como módulo de LIMS/ELN.
- [FATO] Exemplos comerciais concretos: METTLER TOLEDO EasyDirect (captura de dados de várias famílias, com limites de instrumentos e conexões por produto), LabX (ecossistema e integração com LIMS), Sartorius (conectividade balance–LIMS/ELN, protocolos/portas e software Ingenix Suite), Anton Paar AP Connect (hub de instrumentos, com conectividade via Ethernet/RS232 e licença por faixas de instrumentos), LabCollector (módulos de integração/parse de arquivo e LIMS) e LabWare (interfacing por RS-232, arquivos, redes e sistemas).
- [FATO] O problema de produto não é simplesmente “conectar um cabo”: equipamentos diferentes podem transmitir por RS-232, USB/porta serial virtual, Ethernet, arquivos, impressora ou protocolo específico; formato, metadados, software intermediário e compatibilidade variam por modelo/fabricante. A documentação de fabricante confirma ainda que soluções simples podem ter escopo limitado a certos instrumentos e até um número máximo de conexões.
- [FATO] Para laboratórios acreditados segundo ABNT NBR ISO/IEC 17025, controle dos dados e sistemas de gestão da informação laboratorial são requisitos relevantes. O DOQ-Cgcre-087 da Cgcre é orientação (não a norma) e a cópia consultada é Rev. 00, março de 2018; descreve a versão 2017 da ISO/IEC 17025 e orienta que sistemas informatizados sejam validados para uso pretendido, incluindo alterações aplicáveis. Não se deve transformar isso em afirmação de que todo laboratório precisa comprar um LIMS ou que toda integração tem o mesmo nível de validação.
- [NÃO ENCONTRADO] Prova de que laboratórios do público de Will/Lucas redigitam com frequência, sofrem erros materiais, pagariam por uma camada independente ou não estão bem atendidos pelos softwares dos fabricantes/LIMS existentes. Sem entrevistas, observação ou dados de transações, não há base para estimar mercado, preço, taxa de erro ou economia.
- [PENDENTE-HUMANO] Auditar pelo menos um fluxo real de um segmento definido e inventariar por modelo a interface, software habilitado/licenciado, formato, campos capturados, identificação da amostra, usuário, horário, equipamento, método, aprovação e procedimento de contingência. Obter autorização do laboratório e validar requisitos de dados com responsável técnico/qualidade/IT.

## 1. Escopo e hipótese

- [FATO] A planilha define a ideia com os exemplos “balança, pHmetro etc.” e a promessa “sem redigitar”. Isso é descrição de conceito, não evidência observada de dor nem especificação funcional.
- [HIPÓTESE] Em um segmento ainda a escolher, a equipe pode copiar resultados de telas, impressões ou arquivos para planilhas/LIMS/laudos; uma camada que associa resultado diretamente à amostra e ao equipamento pode reduzir transcrição manual.
- [HIPÓTESE] Uma oportunidade pode estar em laboratórios pequenos/médios com parque misto ou instrumentos legados, sem LIMS/integração completa, se a instalação e o suporte forem simples e o benefício for maior que o custo de integração.
- [NÃO ENCONTRADO] Frequência, volume de redigitação, erros, retrabalho, custo de integração, orçamento, critério de compra e quais modelos são mais usados pelo ICP.
- [INFERÊNCIA] O escopo deve se diferenciar de software fechado de uma marca e módulos de LIMS; isso exigiria compatibilidade verificável e custo de integração/manutenção competitivo. O site do fornecedor não confirma o desempenho real ou suporte a todos os modelos.

## 2. Contexto técnico e de qualidade

### 2.1 Dados e interfaces não são homogêneos

- [FATO] O material técnico oficial Sartorius para balanças Cubis II descreve conexões RS232, USB, Ethernet e protocolos como SBI, SICS e Webservices; transferência para sistemas LIMS/ELN pode incluir CSV/PDF ou integração mais profunda conforme interface/necessidade. A página também anuncia software standalone Ingenix Suite. Fonte: https://www.sartorius.com/en/products/weighing/laboratory-balances/cubis-ii/balance-connectivity (consultada em 29/09/2026).
- [FATO] Manual do medidor METTLER TOLEDO SevenExcellence descreve USB, RS232 e Ethernet, opções de transferência para EasyDirect/LabX e exportação por USB. A página oficial EasyDirect pH descreve compatibilidade apenas com famílias selecionadas, conexão por USB/RS232 e até três instrumentos. Fontes: https://www.mt.com/us/en/home/products/Laboratory_Analytics_Browse/pH-meter/pH-automation-and-software/Software-EasyDirect-pH-License.html e manual consultado via fabricante/revendedor técnico em https://gwb.fi/wp-content/uploads/2025/04/Mettler-Toledo-SevenExcellence-pH-manual.pdf.
- [FATO] O LabCollector descreve instrumento simples (saída única; exemplos: balança e pHmetro) conectado por USB/RS232, enquanto equipamentos complexos geram arquivos que exigem parsing/interpretação. Também anuncia add-on para importar e interpretar dados CSV de diretórios compartilhados. Fonte oficial em português: https://labcollector.com/pt/solutions/applications/automation-and-instrument-integration/ (acesso 29/09/2026).
- [FATO] METTLER TOLEDO informa que EasyDirect Balance suporta até 10 balanças por Ethernet/RS232; EasyDirect Moisture até cinco analisadores por RS232/USB; EasyDirect pH até três medidores compatíveis. A linha se apresenta como opção para ambientes não regulados, educação e pesquisa acadêmica. Fonte oficial: https://www.mt.com/us/en/home/products/lab-solutions/lab-software/easydirect.html (acesso 29/09/2026).
- [INFERÊNCIA] A integração pode exigir adaptação por modelo, interface, formato, versão de software, driver, associação com amostra e configuração do instrumento; há risco de uma atualização interromper o conector. Não presumir que “RS-232” por si só resolve o protocolo de mensagens.

### 2.2 Dados, validação e acreditação

- [FATO] Cgcre disponibiliza DOQ-Cgcre-087, “Orientações gerais sobre os requisitos da ABNT NBR ISO/IEC 17025:2017”, como documento orientativo, para laboratórios acreditados/postulantes e avaliadores. O conteúdo consultado é Rev. 00 (março/2018). Fonte oficial: https://www.gov.br/cdtn/pt-br/centrais-de-conteudo/documentos-cgcre-abnt-nbr-iso-iec-17025/doq-cgcre-087 (consulta 29/09/2026).
- [FATO] O DOQ descreve o requisito 7.11 de acesso/gestão de dados e informações e, na orientação sobre sistemas informatizados, associa validação ao uso pretendido e controle de alterações, incluindo sistemas comerciais configurados. O DOQ é orientação; não substitui a norma integral, documentos vigentes da Cgcre ou avaliação de aplicabilidade pelo laboratório.
- [FATO] O INMETRO esclarece que documentos DOQ-Cgcre são orientativos e não compulsórios por si só; servem de orientação para implementação dos requisitos de acreditação. Página institucional: https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/acreditacao.
- [INFERÊNCIA] Para fluxo de resultado regulado/acreditado, a captura precisa preservar contexto suficiente para reconstruir origem e tratamento do dado (p.ex. amostra, equipamento, método, data/hora, unidade, operador/revisão e alterações), conforme uso pretendido e procedimentos do laboratório. Um valor isolado copiado para banco não prova integridade nem rastreabilidade.
- [NÃO ENCONTRADO] A norma ABNT integral e a revisão vigente de cada documento Cgcre/NIT aplicável não foram adquiridas/analisadas nesta pesquisa. Não foi feita interpretação normativa especializada nem avaliação de requisito para laboratório específico.

## 3. Concorrentes e alternativas

### A01 — Software do fabricante: METTLER TOLEDO EasyDirect

- **URL oficial:** https://www.mt.com/us/en/home/products/lab-solutions/lab-software/easydirect.html.
- **[FATO]** Captura automática em produtos próprios: balanças (até 10, Ethernet/RS232), pH (até três modelos compatíveis), analisadores de umidade (até cinco, USB/RS232), titulação e outros segmentos descritos pelo fornecedor; armazena/revisa/exporta resultados. O fornecedor diferencia a oferta standard para ambiente não regulado das soluções mais sofisticadas LabX.
- **Preço Brasil:** não encontrado na página oficial consultada; há trial/demonstração e solicitação de cotação. Não importar preços de revendedores dos EUA para o Brasil.
- **Limitação competitiva:** boa alternativa quando instrumentos são compatíveis; oferta fragmentada por família de instrumentos, possíveis restrições por fabricante e quantidade.

### A02 — METTLER TOLEDO LabX

- **URL oficial:** https://www.mt.com/us/en/home/products/lab-solutions/lab-software/labx.html.
- **[FATO]** Fornecedor anuncia conexão e gestão de diversas famílias próprias, tarefas/usuários, captura automática, banco de dados e integração com LIMS/ELN/MES/CDS.
- **Preço/implantação:** não público na página; cotação/demonstração.
- **Limitação:** solução do ecossistema do fabricante; não é prova de integração independente universal. Recursos específicos dependem de módulos/instrumentos/configuração e precisam de validação técnica/comercial.

### A03 — Sartorius connectivity / Ingenix Suite

- **URL oficial:** https://www.sartorius.com/en/products/weighing/laboratory-balances/cubis-ii/balance-connectivity.
- **[FATO]** Anuncia transferência de registros de balanças Cubis para ELN/LIMS, interfaces e protocolos (SBI/SICS/Webservices, RS232/USB/Ethernet), relatórios/exportação e software independente para gestão de balanças. A empresa anuncia recursos de integridade de dados em determinadas configurações/produtos.
- **Preço:** não encontrado para a configuração/software aplicável no Brasil.
- **Limitação:** foco documentado em balanças e produtos Sartorius; afirmar conformidade apenas com base em claims do fornecedor seria impróprio.

### A04 — Anton Paar AP Connect

- **URL oficial:** https://www.anton-paar.com/us-en/products/details/ap-connect/.
- **[FATO]** Oferta declarada de sistema de execução/conectividade laboratorial com captura, armazenamento, visualização e exportação; lista Ethernet/RS232, CSV/XLSX/PDF/JSON, integração LIMS/API e planos por capacidade (um, até 100 instrumentos conforme plano descrito na página). A página declara taxa única/licença por faixa, mas não publica preço final.
- **Preço Brasil:** não encontrado; verificar cotação, escopo de adaptadores, suporte local e licença.
- **Limitação:** compatibilidade de verdade depende de instrumento/modelo e adaptador disponível; fornecedor demonstra presença de uma alternativa ampla, não cobertura comprovada para parque brasileiro específico.

### A05 — LabCollector LIMS + add-ons de instrumento/parse

- **URL oficial em português:** https://labcollector.com/pt/solutions/applications/automation-and-instrument-integration/.
- **[FATO]** Anuncia integração de instrumentos simples via USB/RS232, leitura de arquivos, parsing CSV, API e associação com módulos LIMS. Há add-ons e lógica de integração descritos nas páginas do produto.
- **Preço:** não apurado para a combinação necessária.
- **Limitação:** precisa identificar módulos/add-ons, configuração, integração para cada parque e condições de suporte; as páginas são declarações do fornecedor.

### A06 — LabWare LIMS / interfacing

- **URLs oficiais:** https://www.labware.com/lims/integration ; https://www.labware.com/industries/healthcare.
- **[FATO]** Fornecedor descreve conexões diretas ou por arquivo/rede, ferramentas de parsing, RS-232 e comunicação unidirecional/bidirecional; integração em LIMS e sistemas externos.
- **Preço/implantação:** não encontrado; produto empresarial e cotação.
- **Limitação:** não se sabe se é economicamente/operacionalmente adequado a laboratórios menores; implantação e suporte por caso precisam de validação.

### A07 — Actiz LIMS (oferta brasileira de LIMS com integração declarada)

- **URLs oficiais:** https://actiz.com.br/blog/integracao-instrumentos-lims-automacao/ ; https://actiz.com.br/blog/o-que-e-lims/.
- **[FATO]** Em página comercial/editorial, Actiz declara captura automática de resultados de instrumentos (incluindo balanças e instrumentos analíticos), vínculo com amostras, comunicação bidirecional, APIs/padrões abertos e serviços de integração. Outro artigo explica opções por arquivo, comunicação serial/rede ou middleware para equipamentos antigos. São claims da própria empresa, sem validação independente.
- **Preço/custo de integração:** não verificado; não tomar afirmação comercial de serviço ou custo como preço de proposta.
- **Limitação competitiva:** LIMS completo, não apenas camada autônoma de captura; compatibilidade real, dispositivos já suportados, customização e custo devem ser demonstrados por modelo.

### A08 — LIMS, scripts internos, exportação manual, papel e planilha

- [FATO] Há funcionalidades de captura nos sistemas e equipamentos listados acima. O próprio fabricante pode fornecer exportação ou software de marca; LIMS pode integrar instrumento/arquivo e customizações podem atuar como alternativa.
- [HIPÓTESE] Em alguns laboratórios pequenos, planilha, papel, copiar/colar, arquivos CSV e desenvolvimento local podem ser substitutos suficientemente baratos.
- [NÃO ENCONTRADO] Quais alternativas os potenciais clientes usam de fato, o custo, satisfação e o volume de adaptação manual.

### Concorrência e implicação

- [FATO] Não se trata de espaço sem oferta: já existem funções nativas de fabricante, sistemas de captura, middleware, módulos de LIMS e serviços de integração.
- [INFERÊNCIA] Possível oportunidade é uma faixa específica não bem resolvida: um parque com marcas/modelos definidos, fluxo simples e usuário sem LIMS/recursos de integração. Isso precisa ser testado; não está provado que a lacuna existe.
- [NÃO ENCONTRADO] Nenhuma fonte pública revisada fornece comparação neutra, preço completo local, cobertura de modelos no Brasil, taxa de falha ou satisfação de clientes.

## 4. Mercado, preço e sinais de demanda

- [NÃO ENCONTRADO] Quantidade de laboratórios ICP no Brasil/SP/Guarulhos, número de instrumentos conectáveis, taxa de redigitação, impacto de erros, budget, CAC, churn e disposição a pagar.
- [FATO] Alguns produtos oferecem avaliação ou demonstração, e diversos fornecedores requerem cotação. Isso indica modalidade de venda disponível, não disposição a pagar de clientes de Will/Lucas.
- [FATO] Preços de revendedores estrangeiros não são comparáveis sem impostos, licenças, câmbio, suporte, escopo e condições brasileiras; não foram usados para estimar preço.
- [ESTIMATIVA] Não calculada; qualquer TAM/SAM/SOM ou economia de tempo seria prematura sem definir segmento, compatibilidade, volume e preço validado.

## 5. Riscos e advogado do diabo

1. [INFERÊNCIA] “Instrumento” cobre desde saída serial simples até sistemas que geram arquivos complexos; integração universal pode exigir alto custo de engenharia e suporte.
2. [FATO] Marcas e modelos têm ferramentas e interfaces próprias; parte do valor proposto pode já estar incluída no equipamento ou LIMS atual.
3. [INFERÊNCIA] Dado pode ser capturado sem metadados suficientes, ligado à amostra errada, duplicado ou importado com unidade/configuração incorreta. Eliminar redigitação não elimina erro de medição ou de identificação.
4. [INFERÊNCIA] Em dados regulados/acreditados, segurança, trilha de mudanças, acesso, backup, validação do uso e alterações e preservação do dado original tornam o produto mais exigente que um importador CSV genérico.
5. [HIPÓTESE] Muitos laboratórios já possuem interface/software do fabricante ou baixa frequência de medições, e podem não justificar integração adicional.
6. [NÃO ENCONTRADO] Viabilidade de capturar sem alterar operação/configuração, acesso a SDK/protocolo, direitos/licenças, compatibilidade com Windows/infra local, manutenção de conectores e obrigação de suporte.

## 6. Próximo teste humano

1. **Escolher segmento antes do protótipo:** ex. laboratório de ensaio ambiental, alimentos, controle industrial ou calibração; os fluxos e exigências não devem ser tratados como iguais.
2. **Inventário autorizado:** fabricante/modelo/firmware; interface; software já licenciado; formatos; destino dos resultados; quantidade de análises/turno; conectores existentes; quem configura e dá suporte.
3. **Observar 5–10 medições reais por um fluxo** (quantidade proposta para investigação, não amostra estatística): acompanhar captura atual, tempo, campos copiados, conferência, exceções e recuperação quando a interface cai. Anonimizar amostra/cliente conforme acordo.
4. **Medir antes de prometer:** taxa de retrabalho/erro documentado e horas efetivamente gastas; checar se exportação nativa ou ferramenta já contratada resolve sem novo software.
5. **Prova técnica limitada:** com autorização, ler dados de um ou dois modelos já encontrados no ICP em ambiente de teste; comparar captura com saída original e registrar unidade, timestamp, equipamento, amostra, operador, duplicidade, integridade e logs. Não usar em laudo real até responsável técnico validar e o laboratório executar controles necessários.
6. **Entrevistas/comercial:** discutir orçamento e proposta com comprador identificado, sem tratar respostas hipotéticas ou elogios como disposição a pagar; solicitar piloto pago somente se os usuários julgarem apropriado.
7. **Critério continuar/parar:** Will/Lucas devem definir antes dos testes quais evidências (p.ex. custo de conexão por instrumento, repetição do problema, ganho medido e capacidade de implantação) justificariam seguir. Não criar limiares arbitrários neste relatório.

## 7. Fontes e registro de pesquisa

### Referências documentais consultadas

- **S01 — DOQ-Cgcre-087, orientações gerais ISO/IEC 17025:2017:** https://www.gov.br/cdtn/pt-br/centrais-de-conteudo/documentos-cgcre-abnt-nbr-iso-iec-17025/doq-cgcre-087 — fonte oficial, acesso 29/09/2026; conteúdo consultado informa Rev. 00, março/2018.
- **S02 — Política/página institucional Cgcre/INMETRO sobre acreditação e DOQs:** https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/acreditacao — DOQs são orientativos, consulta 29/09/2026.
- **S03 — METTLER TOLEDO EasyDirect, página central:** https://www.mt.com/us/en/home/products/lab-solutions/lab-software/easydirect.html — oficial, consultada 29/09/2026; transferência automática, interfaces e limites por família.
- **S04 — METTLER TOLEDO EasyDirect pH:** https://www.mt.com/us/en/home/products/Laboratory_Analytics_Browse/pH-meter/pH-automation-and-software/Software-EasyDirect-pH-License.html — oficial, consultada 29/09/2026; compatibilidade e limite de instrumentos.
- **S05 — METTLER TOLEDO LabX:** https://www.mt.com/us/en/home/products/lab-solutions/lab-software/labx.html — oficial, consultada 29/09/2026; gerenciamento de instrumentos e integração declarada.
- **S06 — Sartorius Cubis II connectivity:** https://www.sartorius.com/en/products/weighing/laboratory-balances/cubis-ii/balance-connectivity — oficial, acesso 29/09/2026; portas/protocolos, transferência e integração.
- **S07 — Sartorius software/OPC Server:** https://www.sartorius.com/en/products/weighing/weighing-accessories/software — oficial, acesso 29/09/2026; servidor OPC e interface de integração.
- **S08 — METTLER TOLEDO SevenExcellence manual:** https://gwb.fi/wp-content/uploads/2025/04/Mettler-Toledo-SevenExcellence-pH-manual.pdf — cópia técnica acessada via terceiro em 29/09/2026; informação de conexão deve ser confirmada na edição oficial vigente do fabricante antes de implantação.
- **S09 — LabCollector integração (PT):** https://labcollector.com/pt/solutions/applications/automation-and-instrument-integration/ — oficial, acesso 29/09/2026; simples/complexo, USB/RS232, arquivos/CSV.
- **S10 — LabCollector aquisição automatizada CSV:** https://labcollector.com/solutions/applications/automation-and-instrument-integration/automated-data-acquisition/ — oficial, consultada por busca em 29/09/2026; add-on e parsing anunciados.
- **S11 — Anton Paar AP Connect:** https://www.anton-paar.com/us-en/products/details/ap-connect/ — oficial, busca consultada 29/09/2026; funcionalidades, interfaces, planos e limites declarados.
- **S12 — LabWare integration:** https://www.labware.com/lims/integration — oficial, busca consultada 29/09/2026; interfaces e captura anunciadas.
- **S13 — LabWare healthcare instrument interfacing:** https://www.labware.com/industries/healthcare — oficial, consulta 29/09/2026; exemplo de RS-232, importação de arquivo e interface LIMS.
- **S14 — LabWare LIMS:** https://www.labware.com/lims — oficial, busca consultada 29/09/2026; capacidades de integração e gestão de amostras declaradas.
- **S15 — Actiz integração de instrumentos/LIMS:** https://actiz.com.br/blog/integracao-instrumentos-lims-automacao/ ; https://actiz.com.br/blog/o-que-e-lims/ — páginas comerciais/editoriais da Actiz, consultadas por busca em 29/09/2026; integração e opções declaradas pelo fornecedor, não verificadas independentemente.

### Log de verificação

| Data local | Item | Ação/resultado | Fontes | Classificação/confiança | Pendência |
|---|---|---|---|---|---|
| 29/09/2026 | Contexto qualidade | Consultado DOQ-Cgcre-087 e página Cgcre; documento orientativo Rev.00/2018 e contexto ISO/IEC 17025:2017 | S01–S02 | [FATO] texto/documentos oficiais; não substitui interpretação da norma integral | Verificar revisão vigente e requisitos do ICP |
| 29/09/2026 | Interfaces instrumentais | Conferidas páginas oficiais de Mettler Toledo, Sartorius e manual SevenExcellence | S03–S08 | [FATO] capacidades/interface descritas pelos fabricantes; confiança no escopo declarado | Testar modelos concretos e confirmar documento oficial vigente |
| 29/09/2026 | Concorrentes LIMS/middleware | Verificadas páginas oficiais LabCollector, Anton Paar e LabWare | S09–S14 | [FATO] oferta e funções anunciadas; não comprova adoção, performance ou cobertura local | Solicitar demonstrações/cotações e comparar por modelo |
| 29/09/2026 | Dor e mercado | Nenhuma entrevista, observação de trabalho ou preço de cliente | — | [NÃO ENCONTRADO]/[PENDENTE-HUMANO] | Definir segmento e validar fluxo real |
