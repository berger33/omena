# Fase 2 — Pesquisa documental inicial da ideia ID 03

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia:** “Emissão automática de laudos e certificados de análise a partir dos resultados.”  
**Triagem original:** posição 5, nota 4,29. Nota mantida; nenhuma evidência primária de cliente foi coletada.

## Síntese executiva

- [FATO] Existem ofertas de LIMS que declaram geração automática de relatório/laudo/certificado: ALLIMS, Ultra LIMS, LabWay-LIMS, Gerencialab e Labguru. ALLIMS e Ultra LIMS são ofertas nacionais consultadas; LabWay é de Portugal e Labguru opera internacionalmente.
- [FATO] Vários fornecedores combinam emissão com captura de resultados, revisão, rastreabilidade, amostras e workflows; a ideia não é apenas um gerador isolado no mercado observado.
- [NÃO ENCONTRADO] Não há evidência no repositório sobre formato atual de laudos, volume, campos manuais, erros, retrabalho, tempo de emissão, necessidade de clientes, comprador, preço aceito ou concorrentes atualmente usados por Will/Lucas.
- [INFERÊNCIA] Diferenciação teria que vir de um segmento, formato, integração ou etapa que as alternativas atuais não cubram; não foi encontrada lacuna funcional verificável que justifique software separado.
- [PENDENTE-HUMANO] Testar com pessoas que preparam/revisam laudos e com quem aprova compra, usando modelos e dados autorizados. Nenhuma entrevista, piloto ou contato ocorreu.

## 1. Problema e cliente

- [HIPÓTESE] Laboratórios que emitem relatório de ensaio ou certificado de análise podem compilar resultados, unidades, métodos, critérios, identificação de amostra e assinatura em um documento para cliente.
- [NÃO ENCONTRADO] Setor, público e tipo de laudo não foram especificados. Um COA de controle de qualidade industrial, relatório de ensaio acreditado e laudo de análises clínicas podem ter escopos, formatos e obrigações distintas.
- [PENDENTE-HUMANO] Mapear um caso recente: resultados de origem, edição/cálculo manual, revisão, aprovação, emissão, correção/reemissão, tempo e consequência para cliente. Confirmar quem usa, assina, compra e pode autorizar teste.

## 2. Alternativas/concorrência verificadas

### C01 — ALLIMS (LIMS brasileiro; sobreposição direta)

- **URL aberta:** https://www.allims.com.br/ — acesso 29/09/2026.
- **[FATO]** Homepage declara funcionalidades LIMS, incluindo execução de cálculos, comparação de resultados, emissão e envio automático de Relatório de Ensaio para clientes; declara atendimento a laboratórios de prestadores, controle de qualidade e P&D.
- **Preço público:** não informado na homepage; solicita contato/demonstração.
- **Por que alternativa:** cobre explicitamente emissão/envio do relatório no contexto laboratorial.
- **Limitações:** alegação do fabricante; formato, configuração, idiomas, assinaturas, controles de revisão, setores atendidos e qualidade não foram testados. A subpágina https://www.allims.com.br/sistema retornou erro/indisponibilidade na consulta anterior; não infiro que funções não existam.

### C02 — Ultra LIMS (LIMS brasileiro; sobreposição direta)

- **URL aberta:** https://ultralims.com.br/blog/gestao-de-laboratorios-tecnologia-ultra-lims-como-aliada — conteúdo datado na página de 03/04/2025, acesso 29/09/2026. Página geral: https://ultralims.com.br/.
- **[FATO]** Artigo do fornecedor descreve Ultra One cobrindo amostragem até geração de relatórios e Ultra Zap para envio automatizado de laudos via WhatsApp Cloud. A página inicial também lista ferramenta de configuração de modelos de relatório e depoimento de cliente que diz centralizar laudos.
- **Preço público:** não informado nas páginas abertas; convite para demonstração.
- **Por que alternativa:** oferece geração e distribuição de laudos como parte de sistema laboratorial mais amplo.
- **Limitações:** artigo e depoimento são publicações do fornecedor, sem verificação independente de resultados ou de aderência às necessidades do ICP.

### C03 — Gerencialab (LIMS brasileiro; sobreposição direta)

- **URL aberta:** https://gerencialab.com.br/pt — acesso 29/09/2026; site indica ©2026.
- **[FATO]** Página declara um fluxo de propostas/coleta/análise/revisão/emissão de laudo assinado digitalmente/faturamento, com LIMS, qualidade, coleta e financeiro. Declara importar dados de equipamentos e planilhas, revisar resultados antes de emitir laudo e reunir rastreabilidade/controle de qualidade.
- **Preço público:** não informado; a página orienta conversar sobre planos, módulos, implantação e valores. Demonstração gratuita anunciada.
- **Nota sobre métrica comercial:** site afirma “mais de 100 laboratórios usam o sistema”; é uma declaração do próprio fornecedor, sem base ou período esclarecidos na página. Não usei como estatística de mercado, adoção independente ou receita.
- **Por que alternativa:** sobreposição direta na geração/revisão/assinatura de laudo e no fluxo do laboratório.
- **Limitações:** oferta, números e recursos não foram testados; não prova preço, disponibilidade ou sucesso dos clientes.

### C04 — LabWay-LIMS (LIMS internacional; sobreposição direta)

- **URL aberta:** https://www.labway-lims.com/industria — acesso 29/09/2026.
- **[FATO]** Página de fornecedor descreve gestão de especificações e controle da qualidade, emissão automática de relatórios de ensaio e certificados, dados de equipamentos, acesso a resultados e integração de produção; apresenta casos de estudo de clientes em Portugal.
- **Preço público:** não informado na página aberta; convites a reunião.
- **Por que alternativa:** é uma solução de LIMS para indústria que declara exatamente emissão automática de relatórios e certificados de qualidade.
- **Limitações:** foco/condições no Brasil, moeda/preço, suporte local e escopo contratual não confirmados; casos publicados pelo fornecedor não são prova independente de desempenho.

### C05 — Labguru (LIMS/ELN internacional; alternativa mais ampla)

- **URL aberta:** https://www.labguru.com/lims — acesso 29/09/2026.
- **[FATO]** Página descreve sistema LIMS com gestão de amostras, workflow, dados, relatórios/análises, gestão de instrumentos e automação de operações laboratoriais. A página consultada não explicita detalhes de formato de certificado/laudo na parte obtida.
- **Preço público:** não encontrado; opção de demonstração.
- **Por que alternativa:** pode centralizar resultados e workflows e oferecer relatório/analítica, potencialmente substituindo um gerador avulso dependendo do uso.
- **Limitações:** a funcionalidade exata de geração do tipo de laudo da ideia não foi comprovada nesta página; não classificado como concorrente direto exato.

**Resumo concorrencial:** quatro alternativas publicam a geração/emissão de relatório, laudo ou certificado como parte de LIMS; uma alternativa LIMS ampla verificada sem confirmação de detalhe do laudo. Não se conclui que todos os produtos atendam às mesmas regras ou segmento.

## 3. Regulação/qualidade

- [FATO] A aplicabilidade de requisitos a um laudo depende do tipo de serviço, produto, contrato e atividade. A fonte anteriormente verificada do Inmetro sobre acreditação descreve que laboratórios de ensaio/calibração são acreditados sob ISO/IEC 17025, mas este dado geral não define sozinho o conteúdo obrigatório para todos os relatórios.
- [NÃO ENCONTRADO] Não foi identificado o tipo de relatório, setor e norma aplicável à ideia; assim, não apresento lista de campos legais ou parecer regulatório para ID03.
- [INFERÊNCIA] Regras de cálculo, revisão, identificação, incerteza, unidade, assinatura, versão, rastreabilidade e correções podem ser críticas em usos específicos; precisam ser confirmadas para o segmento antes de modelar o produto.
- [PENDENTE-HUMANO — CONSULTA PROFISSIONAL] Delimitar setor e uso do laudo; verificar legislação/norma vigente em fonte oficial e consultar profissional de qualidade/regulação antes de prometer conformidade. Não constitui parecer.

## 4. Mercado, dor e economia

- [NÃO ENCONTRADO] Número de laboratórios no ICP, quantidade de laudos por mês, custo/tempo de preparação, erro/reemissão, orçamento, disposição a pagar e parcela acessível.
- [ESTIMATIVA] Não calculada. Não há população definida, dado oficial adequado ou premissas para TAM/SAM/mercado inicial.
- [FATO] Fornecedores oferecem emissão de relatórios como funcionalidade dentro de produtos maiores; isso comprova disponibilidade de categoria, não problema não resolvido nem disposição a comprar produto separado.
- [PENDENTE-HUMANO] Medir duração de um fluxo real desde os resultados até liberação do laudo, revisões e correções; comparar processo atual com os sistemas já contratados e descobrir o orçamento/decisor.

## 5. Preço/economia

- [NÃO ENCONTRADO] Preços públicos verificáveis de ALLIMS, Ultra LIMS, Gerencialab, LabWay-LIMS e Labguru nas páginas abertas; todos direcionam a demonstração/contato ou não apresentam valor.
- [FATO] “Sob consulta”/contato comercial não foi convertido em estimativa. Valores de outro tipo de LIMS não foram transportados para esta ideia.
- [PENDENTE-HUMANO] Solicitar proposta comparável com número de usuários, implantação, módulos, assinatura/periodicidade e integrações para segmento escolhido. Nenhuma empresa foi contatada.

## 6. Nota e ranking

- [FATO] Nota inicial 4,29; posição 5 na aba Análise.
- [HIPÓTESE] Nota mantida. As páginas confirmam oferta de funcionalidades, mas não evidenciam a dor, gasto, mercado acessível, dificuldade do MVP ou receita recorrente no segmento proposto.
- [INFERÊNCIA] A suposição de baixa concorrência da versão ampla precisa ser reavaliada se houver evidências suficientes nos critérios originais: foram encontradas alternativas diretas de LIMS. Não recalculo nesta etapa porque a concorrência sozinha não determina nota ponderada completa.

## 7. Advogado do diabo — riscos

1. [FATO] Várias soluções LIMS publicam geração automatizada de relatórios/laudos/certificados. [INFERÊNCIA] Um produto isolado pode ser redundante frente a módulos já integrados ao sistema operacional do laboratório.
2. [HIPÓTESE] A implantação pode depender de integração com planilhas/equipamentos, configuração por método/cliente, cálculos e revisão, tornando o escopo mais complexo do que “montar PDF”.
3. [HIPÓTESE] Responsáveis podem não confiar em emissão sem revisão ou podem precisar preservar assinatura e rastreabilidade; exigências variam e ainda não foram pesquisadas para ICP definido.
4. [INFERÊNCIA] Erros de cálculo/identificação no laudo podem ter consequência mais séria que atraso de formatação; é necessário desenhar revisão, controle de versão e correções antes de automação em produção.

## 8. Próximo teste humano

- **Hipótese:** em um segmento laboratorial definido, preparar e revisar laudos consome tempo significativo ou produz retrabalho que não é resolvido pelo sistema atual.
- **Público:** pessoa que prepara laudo, revisor/assinante e comprador/gestor, no mesmo tipo de laboratório.
- **Teste:** observar, com autorização, um ciclo real de dados → cálculo → conferência → aprovação → emissão/correção. Comparar uma amostra representativa de documentos com módulo do LIMS existente e protótipo/conciliação manual.
- **Métricas:** tempo por laudo, pontos de digitação, número de revisões/correções, campos de alto risco, proporção de dados estruturados disponíveis, integração necessária, custo de operação atual e responsável por orçamento.
- **Critério de seguir/parar:** definir limiares em conjunto antes do teste, segundo risco de erro e economia potencial. Não estabeleço taxa artificial nesta rodada.
- **Custo/tempo:** [NÃO ENCONTRADO] sem orçamento e agenda informados.

## Fontes e log de auditoria

- **S01 ALLIMS:** https://www.allims.com.br/ — acesso 29/09/2026; conteúdo institucional sobre cálculo e emissão/envio automático de relatório; preço não informado.
- **S02 Ultra LIMS:** https://ultralims.com.br/blog/gestao-de-laboratorios-tecnologia-ultra-lims-como-aliada — página indica 03/04/2025; acesso 29/09/2026; emissão/relatórios e envio via WhatsApp declarados pelo fornecedor.
- **S03 Ultra homepage:** https://ultralims.com.br/ — acesso 29/09/2026; ferramenta de modelo de relatório e conteúdo comercial.
- **S04 Gerencialab:** https://gerencialab.com.br/pt — acesso 29/09/2026; fluxo de análise/revisão/laudo e preço sob consulta.
- **S05 LabWay-LIMS:** https://www.labway-lims.com/industria — acesso 29/09/2026; emissão automática de relatórios e certificados declarada pelo fornecedor.
- **S06 Labguru:** https://www.labguru.com/lims — acesso 29/09/2026; LIMS amplo, geração específica não confirmada.
- **S07 Inmetro acreditação:** https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/acreditacao — página oficial anteriormente aberta em 29/09/2026; atualização informada 21/05/2026; usada somente para contexto geral de acreditação de laboratórios, não como requisito universal de conteúdo do laudo.

| Data local | Fase | Item | Ação/resultado | Fontes | Classificação/confiança | Pendência |
|---|---|---|---|---|---|---|
| 29/09/2026 | 2 | ID03 concorrência | Verificadas quatro ofertas LIMS com emissão/laudo declarados e uma alternativa ampla adicional | S01–S06 | [FATO] sobre páginas de fornecedores; confiança média para oferta declarada | Comparar funções/preços atuais com ICP definido |
| 29/09/2026 | 2 | ID03 regulação | Não foi possível determinar normas aplicáveis sem tipo de laudo/setor; evitada generalização | S07 | [NÃO ENCONTRADO]/[INFERÊNCIA], insuficiente | Delimitar segmento e pesquisar norma vigente |
| 29/09/2026 | 2 | ID03 dor/preço/mercado | Não há dado primário, preço público ou base de mercado suficiente; nota mantida | S01–S07 | [NÃO ENCONTRADO]/[HIPÓTESE], insuficiente | Entrevistas e observação de fluxo autorizada |
