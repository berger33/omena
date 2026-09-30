# Fase 2 — Pesquisa documental inicial da ideia ID 04

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia:** “Gestão de equipamentos: calibração, manutenção e verificação, com agenda e alertas.”  
**Triagem original:** posição 7, nota 4,14. Mantida sem alteração.

## Síntese

- [FATO] Existem produtos publicados para gestão metrológica/calibração que cobrem instrumentos, vencimentos, históricos e manutenção, inclusive ofertas brasileiras: Cali LAB/Cali WEB, Calibre.Software e LCDS MK. Os dois primeiros se posicionam para laboratórios de calibração/gestão metrológica; isso é alternativa próxima, embora o público da ideia possa também ser laboratório usuário que gere parque próprio.
- [FATO] Ultra LIMS/ALLIMS e LDB também descrevem funções de laboratório/qualidade mais amplas; a página AI do LDB inclui equipamento de ensaio/calibração e exemplo de consultar próxima calibração. A adequação específica deve ser demonstrada.
- [FATO] O Inmetro publica que a acreditação de laboratórios de ensaio/calibração se baseia na ISO/IEC 17025 e que a NIT-Dicla-030 rege política de rastreabilidade metrológica aplicável a essa acreditação. FAQ atualizada em 2021 diz que não há obrigação legal geral de contratar laboratório acreditado, porém contratos/licitações podem exigir acreditação e há política de rastreabilidade no escopo de laboratórios acreditados. Não é requisito universal para todos os instrumentos/empresas.
- [NÃO ENCONTRADO] Não foi observado o processo atual de Will/Lucas, quantidade de equipamentos, calibrações vencidas, custos, frequência de erros, setor, comprador ou disposição a pagar.
- [PENDENTE-HUMANO] Entrevistar responsável por equipamentos/qualidade e testar se controle atual é inadequado e se módulo existente resolve a lacuna. Nenhuma entrevista foi realizada.

## 1. Problema e cliente

- [HIPÓTESE] Um laboratório pode precisar controlar cadastro de equipamento, localização, responsável, criticidade, manutenção preventiva, verificação, certificado, histórico e próxima data de calibração.
- [NÃO ENCONTRADO] Não sabemos se o alvo é laboratório de calibração prestador de serviço (vende calibração), laboratório de ensaio usuário de instrumentos, indústria com laboratório de controle, clínica ou outro setor. Esses públicos têm workflows e custos diferentes.
- [PENDENTE-HUMANO] Mapear um equipamento em caso recente: como planejam a calibração, recebem certificado, avaliam resultado, controlam equipamento fora de tolerância e impedem uso quando necessário; qual sistema é fonte oficial e quem autoriza aquisição.

## 2. Concorrentes e alternativas verificadas

### C01 — Cali LAB e Cali WEB (concorrente próximo/nacional)

- **URL aberta:** https://cali.com.br/ — acesso 29/09/2026.
- **[FATO]** Página descreve Cali LAB para prestadores de serviços de calibração/manutenção/gestão metrológica, com gerenciamento de instrumentos e padrões, recepção de instrumentos, execução de calibrações, manutenções, certificados e envio de resultados. Cali WEB permite gerenciamento de instrumentos, datas de calibração, movimentos e relatórios para clientes. A empresa também descreve uso em indústrias.
- **Preço público:** não informado na homepage; contato comercial.
- **Por que alternativa:** cobre gestão de equipamentos e calibrações, com foco em laboratório prestador e gestão metrológica industrial.
- **Limitações:** autodescrição e depoimentos no site da empresa; não se verificou cotação, arquitetura, implantação nem aptidão para pequeno laboratório que só controla os próprios instrumentos.

### C02 — Calibre.Software (concorrente próximo/nacional)

- **URL aberta:** https://calibre.software/ — acesso 29/09/2026.
- **[FATO]** Página declara SaaS/metrologia, módulos para documentos, metrologia, NR-13 e vendas; divulga certificados/relatórios, cálculos, personalização e gestão de clientes/fornecedores. Declara acesso ilimitado e solicita demonstração.
- **Preço público:** não encontrado na homepage acessada; sem valor monetário publicamente verificável. Não estimado.
- **Por que alternativa:** cobre controle metrológico de equipamentos e gestão de calibrações, especialmente laboratórios de calibração.
- **Limitações importantes:** a página tem calculadora de ROI com campos de exemplo e placeholders (“x horas”, “R$ xx.xx,xx”) e alega “30% mais produtividade” sem metodologia apresentada na captura. Esses números/claims não foram usados como fatos, prova de economia ou média de mercado. Alegações normativas do próprio fornecedor não equivalem a certificação do software.

### C03 — LCDS MK (software de calibração/metrologia; alternativa direta)

- **URL aberta:** https://lcds.com.br/mk.asp — acesso 29/09/2026.
- **[FATO]** Página declara gestão de instrumentos, equipamentos e calibrações, cálculos e histórico, validade, personalização de certificados e acesso instalado/rede/web conforme opções anunciadas.
- **Preço público:** não encontrado; página oferece download/demonstração, sem preço verificável.
- **Por que alternativa:** faz controle de vencimentos/histórico e emissão de certificados, sobrepondo-se ao núcleo da ideia para usos de calibração.
- **Limitações:** fornecedor declara aderência a vários referenciais, mas a página não demonstra tecnicamente conformidade para um escopo/cliente específico. Versão, suporte, preço e implantação não foram verificados.

### C04 — Ultra LIMS (alternativa indireta via LIMS)

- **URLs abertas:** https://ultralims.com.br/ e https://ultralims.com.br/produtos/ultra-one — acesso 29/09/2026.
- **[FATO]** Sistema laboratorial apresenta gestão integrada e catálogo de recursos, além de registro de equipamentos em depoimento de cliente na homepage. A evidência não esclarece todas as funções do módulo de cadastro/calibração/manutenção.
- **Preço público:** não informado; demonstração.
- **Por que alternativa:** um LIMS que o laboratório já usa pode conter módulo ou permitir integração e competir com ferramenta separada.
- **Limitações:** função específica de agenda/alerta de calibração não confirmada pela página usada.

### C05 — LDB LIMS (alternativa indireta/adjacente)

- **URL aberta:** https://lims.eu/en/aiexplorer — acesso 29/09/2026.
- **[FATO]** Página do assistente contextual de LIMS inclui exemplo de consultar quando vence a próxima calibração do equipamento. A página geral e treinamento oferecem gestão laboratorial, mas a consulta não determinou o escopo/licenciamento do módulo de equipamento.
- **Preço público:** não informado para sistema completo nesta página; não estimado.
- **Por que alternativa:** pode responder/gerir equipamento dentro do LIMS que concentra a rotina.
- **Limitações:** produto estrangeiro e conteúdo de fornecedor; exemplo de IA não é prova de sistema completo de metrologia nem de disponibilidade no Brasil.

**Total:** três alternativas especializadas/próximas verificadas e duas alternativas LIMS indiretas. Não é lista exaustiva.

## 3. Regulação e rastreabilidade

- **[FATO]** Inmetro, FAQ “Existe obrigatoriedade de contratação de serviço em laboratório acreditado?”, publicado em 01/01/2011 e atualizado em 20/07/2021, URL https://www.gov.br/inmetro/pt-br/acesso-a-informacao/perguntas-frequentes/acreditacao/existe-obrigatoriedade-de-contratacao-de-servico-em-laboratorio-acreditado, aberta em 29/09/2026: informa que não há obrigação legal geral de contratar laboratório acreditado pela Cgcre; também indica que contratos/licitações podem exigir acreditação e que, para laboratório acreditado, instrumentos devem atender à política de rastreabilidade da NIT-Dicla-030.
- **[FATO]** Manual da Qualidade da Cgcre revisão 30, nov/2025, página oficial https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/manual-de-qualidade-da-cgcre-mq-cgcre.pdf, aberto em 29/09/2026, declara a NIT-Dicla-030 como política de rastreabilidade metrológica aplicável a acreditação de laboratórios de ensaio/calibração, laboratórios clínicos, provedores de ensaio de proficiência e produtores de materiais de referência (texto do manual da Cgcre).
- [INFERÊNCIA] Manter prazos e certificados pode apoiar a operação, mas um software não “garante acreditação”. A aplicabilidade das regras depende do perfil, escopo acreditado, equipamento e atividade.
- [NÃO ENCONTRADO] Não foi revisado o texto integral da NIT-Dicla-030 nem requisitos de todos os setores; não há conclusão jurídica sobre nenhum cliente.
- [PENDENTE-HUMANO — CONSULTA PROFISSIONAL] Definir laboratório/setor/escopo e consultar profissional de metrologia/qualidade antes de especificar controles ou alegar conformidade.

## 4. Mercado, dor, custo

- [NÃO ENCONTRADO] Quantidade de clientes compradores, parque instrumental por laboratório, proporção que usa planilha, frequência de calibração vencida, custo de instrumento parado/resultado afetado, orçamento para sistema.
- [ESTIMATIVA] Não calculada; população, ICP e dados primários ausentes. Não transformar a base de laboratório acreditado em mercado total.
- [FATO] Páginas de fornecedores confirmam oferta de soluções; não medem a prevalência do problema nem preço médio.
- [PENDENTE-HUMANO] Medir uma amostra de registros atuais: instrumentos ativos, prazos, atrasos, certificados incompletos, horas de gestão e consequências. Entrevistar dono/qualidade, não só usuário.

## 5. Reavaliação de nota

- [FATO] Nota original 4,14, posição 7.
- [HIPÓTESE] Mantida sem alteração. Concorrência do tipo específico já está verificada, mas não sabemos se o ICP é atendido pelas ferramentas encontradas nem qual é o custo da dor.
- [INFERÊNCIA] A premissa de “pouca concorrência” para controle de calibração amplo não é sustentada pela amostra documental (C01–C03). Não recalculei a nota sem evidência dos outros critérios e contexto.

## 6. Advogado do diabo — riscos

1. [FATO] Há software brasileiro publicado que trata gestão de instrumentos, calibrações e certificados (C01–C03). [INFERÊNCIA] Um novo produto genérico pode competir com incumbentes e com módulos existentes.
2. [HIPÓTESE] Se o laboratório já usa LIMS, ERP, CMMS ou planilha funcional, migração/redundância pode bloquear adoção.
3. [HIPÓTESE] Dados incorretos de periodicidade, faixa/critério, certificado ou status podem gerar falsa sensação de controle e uso de equipamento não adequado; ainda não observamos falhas reais no público.
4. [INFERÊNCIA] Atender laboratório prestador de calibração pode exigir cálculos/certificados e workflows especializados, escopo distinto de simplesmente gerar alertas; fazer ambos pode ampliar demasiado o produto.

## 7. Próximo teste humano

- **Hipótese:** um segmento definido tem falha frequente e consequente no acompanhamento de calibração/manutenção que não é resolvida por sua ferramenta atual.
- **Público:** responsável por equipamentos/qualidade e gestor que decide compra no mesmo segmento.
- **Teste:** entrevista baseada em episódio real + inspeção de uma lista anonimizada de instrumentos e rotina atual; demonstrar controle num protótipo ou software existente e observar resposta.
- **Métricas:** equipamentos sem responsável/status, vencimentos perdidos, dias de antecedência, tempo de localizar certificado, interrupções/retrabalho, integração e custo anual de controle.
- **Critério continuar/parar:** definir antes, com Will/Lucas e responsável do laboratório, limiares e impacto aceitável; não invento metas. Verificar soluções C01–C03 antes de desenvolver.
- **Custo/tempo:** [NÃO ENCONTRADO] até orçamento e disponibilidade serem informados.

## Fontes críticas e log

- **S01 Cali:** https://cali.com.br/ — acesso 29/09/2026; funções declaradas Cali LAB/WEB; sem preço público encontrado.
- **S02 Calibre.Software:** https://calibre.software/ — acesso 29/09/2026; produto, módulos e alegações de ROI; claims quantitativos não usados como evidência de resultado.
- **S03 LCDS MK:** https://lcds.com.br/mk.asp — acesso 29/09/2026; controle de equipamento, certificados e históricos declarados; preço não encontrado.
- **S04 Ultra LIMS:** https://ultralims.com.br/ e https://ultralims.com.br/produtos/ultra-one — acesso 29/09/2026; alternativa LIMS ampla, equipamento em depoimento não tratado como confirmação funcional detalhada.
- **S05 LDB AI Explorer:** https://lims.eu/en/aiexplorer — acesso 29/09/2026; exemplo de consulta de próxima calibração; preço do sistema não verificado.
- **S06 Inmetro FAQ:** https://www.gov.br/inmetro/pt-br/acesso-a-informacao/perguntas-frequentes/acreditacao/existe-obrigatoriedade-de-contratacao-de-servico-em-laboratorio-acreditado — página atualizada 20/07/2021, acesso 29/09/2026; escopo geral da FAQ e ressalva contratual.
- **S07 Manual Cgcre:** https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/cgcre/manual-de-qualidade-da-cgcre-mq-cgcre.pdf — Revisão 30, novembro/2025, acesso 29/09/2026; política aplicável à acreditação.

| Data local | Fase | Item | Ação/resultado | Fontes | Classificação/confiança | Pendência |
|---|---|---|---|---|---|---|
| 29/09/2026 | 2 | ID04 concorrência | Verificados três produtos de calibração/metrologia e dois LIMS como alternativas próximas | S01–S05 | [FATO] sobre páginas de produto; média para alegações comerciais | Confirmar escopo por demonstração após definir ICP |
| 29/09/2026 | 2 | ID04 rastreabilidade | Abertos FAQ e manual Cgcre Rev.30; escopo de acreditação separado de obrigação geral de contratação | S06–S07 | [FATO], alta para texto oficial consultado; insuficiente para aplicação individual | Definir setor/escopo e revisar NIT aplicável |
| 29/09/2026 | 2 | ID04 mercado/dor/notas | Sem entrevistas, população-alvo ou custo; nenhuma estimativa/alteração de nota | S01–S07 | [NÃO ENCONTRADO]/[HIPÓTESE], insuficiente | Pesquisa primária com usuários/compradores |
