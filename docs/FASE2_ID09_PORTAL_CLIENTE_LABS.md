# Fase 2 — Pesquisa documental inicial da ideia ID 09

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia:** “Portal do cliente para labs prestadores: solicitar análise, acompanhar, baixar laudo.”  
**ID da ideia:** 09 (linha 14 da aba Ideias; não confundir com pontuação/ranking). A planilha mantém as sete avaliações sem preenchimento.

## Síntese

- [FATO] A proposta funcional já é oferecida por produtos LIMS: portal com solicitação de análises, acompanhamento do status e acesso a relatórios/resultados foi documentado em páginas de Ultra LIMS/Ultra Consult e LDB. A ALLIMS declara resultados online e envio automático de relatórios, mas a homepage consultada não comprova um portal de solicitação do cliente. Portanto, concorrência direta e adjacente existe; não se trata de funcionalidade inédita na categoria.
- [FATO] Na LDB, a página consultada descreve solicitações, estado, download de resultados e relatórios, isolamento dos dados entre clientes, aprovação da solicitação pela equipe do laboratório, MFA recomendado e acesso ao portal sem licença de cliente ou colaborador. A empresa afirma que o módulo portal é opcional no seu manual. Funcionalidades e condições são declarações do fornecedor.
- [NÃO ENCONTRADO] Não há evidência de que clientes de Will/Lucas pedem esse portal, têm consultas manuais recorrentes, pagariam por ele separadamente ou estejam mal atendidos por LIMS existente.
- [PENDENTE-HUMANO] Definir segmento laboratorial e entrevistar laboratório e seus clientes contratantes; medir chamadas/e-mails, retrabalho de entrada, pedidos com dados incorretos, status consultado, tempo para disponibilizar laudo e requisitos de integração/segurança.
- [HIPÓTESE] A oportunidade possível seria um portal simples e integrável para um segmento de prestadores sem LIMS/portal adequado, mas não há validação nem evidência de mercado suficiente para afirmar isso.

## Escopo da ideia e recorte ainda ausente

- [FATO] A linha da planilha descreve três tarefas: solicitar análise, acompanhar e baixar laudo.
- [NÃO ENCONTRADO] Não está definido se é produto independente, camada sobre LIMS, módulo para um LIMS, portal white-label, canal de atendimento, ou qual categoria de laboratório (ambiental, alimentos, químico, clínico, etc.).
- [HIPÓTESE] Escopo de “portal” pode incluir cadastro de cliente e usuários, catálogos de ensaios, formulário de pedido, anexos, orçamento, coleta/remessa, status, notificações, laudos assinados, histórico, faturamento e integração; esses itens não foram tomados como requisitos confirmados.
- [PENDENTE-HUMANO] Levantar jornada completa e limites do portal com laboratório e clientes externos antes de especificar MVP.

## Alternativas/concorrentes documentados

### C01 — Ultra LIMS / Ultra Consult (alternativa direta brasileira)

- **Fontes oficiais:** https://ultralims.com.br/ e https://ultralims.com.br/produtos/ultra-consult — abertas em 29/09/2026.
- **[FATO]** Site enumera “Portal do Cliente” entre os recursos. Ultra One declara fluxo com portal do cliente. Ultra Consult, voltado a consultoria/amostragem ambiental, também lista portal do cliente. Depoimento na homepage declara acesso a laudos e status de análise, mas depoimento comercial não é evidência independente de resultado.
- **Preço:** não publicado nas páginas consultadas; apresentação comercial.
- **Classificação:** concorrente direto ou módulo alternativo conforme segmento e escopo.
- **Lacuna:** página não descreve exatamente criação de pedidos pelo cliente, acesso a laudos por usuário/contrato, licenciamento do portal nem mecanismo de isolamento; confirmar em demonstração.

### C02 — LDB LIMS Customer Portal / Customer Zone (alternativa direta estrangeira)

- **Fonte oficial:** https://lims.eu/en/kundenzone — aberta em 29/09/2026. Manual: https://lims.eu/en/manual_page/95.
- **[FATO]** Declara entrada direta de pedidos pelo cliente, acesso a status/progresso, download de relatórios/resultados e dados brutos, integração ao site, formulários/catálogos configuráveis e possibilidade de exibir preços/prazos. Laboratório revisa a solicitação; ela só vira pedido/amostra após processamento pelo laboratório. FAQ declara isolamento de dados, contas individuais não obrigatórias (recomenda MFA), sem cobrança de licença de cliente/funcionário; a página do manual apresenta portal como módulo opcional. Ressalva: a descrição é do fornecedor e não substitui teste de segurança, preço do LIMS ou validação comercial para o Brasil.
- **Preço:** acesso ao portal declarado sem custo de licença por cliente/funcionário; preço do LIMS/implantação não confirmado nesta fonte.
- **Classificação:** concorrente direto funcional, embora fornecedor/mercado estrangeiro.

### C03 — ALLIMS (alternativa adjacente brasileira)

- **Fonte oficial:** https://www.allims.com.br/ — aberta em 29/09/2026.
- **[FATO]** Página declara consulta online de resultados, acompanhamento da rotina analítica em tempo real e emissão/envio automático de relatórios de ensaio para clientes, dentro de sistema LIMS modular para laboratórios prestadores e outros perfis.
- **Preço:** sem valor verificável; página pede demonstração e menciona condições promocionais sem quantia aplicável.
- **Classificação:** alternativa adjacente; a página aberta não demonstrou explicitamente portal de autoatendimento para pedido de análise. Não inferir a inexistência de portal.
- **Limitações:** página interna “/sistema” apresentou indisponibilidade/erro durante tentativa anterior; isso não é evidência de falta de função. Não usar a falha técnica como conclusão competitiva.

### C04 — LIMSview/LIMSview Plus+ (alternativa estrangeira)

- **Fonte oficial:** https://www.labtopiainc.com/informatix/limsview/ — resultado oficial consultado em 29/09/2026.
- **[FATO]** Página descreve portal para status, relatórios/COA e acesso histórico; versão Plus+ adiciona submissão de amostras, etiquetas e cadeia de custódia, com mapeamento ao LIMS e personalização por cliente.
- **Preço:** não publicado no conteúdo acessado.
- **Classificação:** concorrente direto funcional; foco/adequação ao mercado brasileiro e integração não verificados.

**Resumo da amostra:** duas alternativas diretas com portal declaradamente descrito (Ultra e LDB), uma alternativa adjacente brasileira (ALLIMS) e uma alternativa estrangeira adicional. Amostra documental não exaustiva; não permite estimar market share, adoção ou cobertura do mercado brasileiro.

## Riscos e aspectos regulatórios/técnicos

- [FATO] ANPD, Guia Orientativo para Definições dos Agentes de Tratamento e do Encarregado, versão 2, abril/2022: controlador é quem toma decisões referentes ao tratamento e operador trata dados em nome do controlador, conforme instruções; o papel depende da operação concreta. Fonte oficial: https://www.gov.br/anpd/pt-br/centrais-de-conteudo/materiais-educativos-e-publicacoes/Segunda_Versao_do_Guia_de_Agentes_de_Tratamento_retificada.pdf/@@display-file/file (acesso 29/09/2026).
- [INFERÊNCIA] Um portal que manipule contatos, pedidos e laudos pode tratar dados pessoais e eventualmente dados sensíveis conforme segmento; identidade dos agentes e responsabilidades precisam ser avaliadas por fluxo, contrato e legislação aplicável. Não se presume que todo laudo laboratorial contenha dado pessoal/sensível.
- [FATO] A página oficial da Anvisa descreve a RDC 978/2025 como norma técnico-sanitária para serviços que executam exames de análises clínicas (EAC). O roteiro de inspeção oficial EAC tipo III v1.5, 04/12/2025, traz critérios para laudos e entrega/comprovante de atendimento. Fontes: https://www.gov.br/anvisa/pt-br/centraisdeconteudo/publicacoes/servicosdesaude/perguntas-e-respostas/p-r__978_2025_1a-versao-revisada_portal_27ago2025.pdf/view e https://www.gov.br/anvisa/pt-br/assuntos/servicosdesaude/projeto-de-melhoria-do-processo-de-inspecao-sanitaria-em-servicos-de-saude-e-de-interesse-para-a-saude/harmonizacao-de-roteiros-objetivos-de-inspecao-roi/13.1ROIparaEACSTIII_verso1.51.pdf/@@display-file/file — acessos 29/09/2026.
- [INFERÊNCIA] Requisitos clínicos não podem ser generalizados para laboratórios ambientais, alimentos ou ensaio industrial; se o público for clínico, mapear cuidadosamente laudos, identificação, assinatura, entrega e acesso. Este relatório não é parecer regulatório.
- [HIPÓTESE] Controle de acesso por organização/usuário, segregação de clientes, autenticação forte, trilha de auditoria, integridade/versão de laudo, disponibilidade e resposta a incidentes podem ser requisitos decisivos. Ainda não houve threat modeling nem teste técnico.
- [NÃO ENCONTRADO] Não foi verificada arquitetura, certificação de segurança, hospedagem, contrato de tratamento, política de retenção/eliminação ou evidência de pentest dos produtos comparados.
- [PENDENTE-HUMANO — PROFISSIONAL] Se avançar, obter avaliação jurídica/privacidade e segurança da informação com o fluxo e o segmento definidos; validar integração e requisitos do laboratório.

## Dor, mercado, comprador e preço

- [NÃO ENCONTRADO] Frequência e custo de perguntas de status, pedidos incompletos, redigitação, reenvio de documentos, atraso de laudo e sobrecarga de atendimento para o público-alvo.
- [NÃO ENCONTRADO] Número de laboratórios compradores acessíveis, porte, sistemas instalados, penetração de portal, preço aceito, churn/retorno ou orçamento.
- [FATO] A existência de ofertas documenta fornecimento de funcionalidade, não demanda, adoção, satisfação, desempenho nem oportunidade lucrativa.
- [ESTIMATIVA] Não calculada: sem população/ICP, incidência da dor, preço e canal comprovados.
- [PENDENTE-HUMANO] Obter evidência de processo recente, logs agregados de atendimento e portal atual (se houver), entrevistar comprador e usuários externos e testar um protótipo com tarefas reais. Não simular respostas nem pilotos.

## Nota e advogado do diabo

- [FATO] A ideia está na linha 14 (ID 09) da aba Ideias. Notas e ranking estão em branco na cópia de trabalho; não atribuí nota.
- [INFERÊNCIA] A premissa de baixa concorrência para um portal de cliente integrado a laboratório não é sustentada: há funcionalidades anunciadas por LIMS concorrentes. Permanece em aberto se existe lacuna em um segmento/local específico.
- **Riscos principais:**
  1. [INFERÊNCIA] Portal isolado duplica funcionalidades de LIMS e pode exigir integração cara e sensível a mudanças.
  2. [HIPÓTESE] Cliente final pode preferir e-mail/WhatsApp ou portal já existente, reduzindo uso; precisa ser observado.
  3. [HIPÓTESE] Erro de permissão pode expor dados de outro cliente ou laudo preliminar/final; impacto potencial relevante, sem incidentes observados nesta pesquisa.
  4. [INFERÊNCIA] Diferentes matrizes e serviços geram formulários e fluxos não triviais; generalizar pode ampliar escopo.
  5. [FATO] Soluções comparáveis embutem portal em LIMS mais amplo, aumentando risco de competir contra suíte existente em vez de componente independente.

## Próximo teste humano

- **Hipótese testável:** em um segmento escolhido, clientes e equipe do laboratório gastam tempo relevante com entrada de pedidos e solicitações de status/laudos, e o LIMS atual não resolve de modo aceitável.
- **Amostra qualitativa inicial:** conversar separadamente com 3–5 prestadores de um só segmento e 2–3 clientes de cada prestador, como proposta de planejamento, não como amostra representativa nem resultado existente. Will/Lucas devem aprovar/ampliar a amostra.
- **Técnica:** pedir demonstração do último pedido real (anonimizado), contar etapas e trocas, observar portal/sistema em uso e testar protótipo de pedido/status/download sem inserir dados reais sensíveis até existir avaliação de privacidade/segurança.
- **Medidas:** minutos e contatos por pedido, proporção de pedidos incompletos, consultas de status por ordem, tempo de disponibilização/acesso ao laudo, taxa de uso do canal, custo de implantação/integrar ao LIMS e exigências de segurança.
- **Critério de avanço:** definir antes da pesquisa com Will/Lucas e entrevistados; sem limiares inventados neste relatório. Verificar C01–C04 por demonstração antes de construir.

## Log de evidências

| Data local | Item | Ação/resultado | Fonte | Classificação/confiança | Pendência |
|---|---|---|---|---|---|
| 29/09/2026 | Produto / concorrência | Página oficial Ultra e Ultra Consult descreve Portal do Cliente; escopo funcional detalhado não confirmado | https://ultralims.com.br/ ; https://ultralims.com.br/produtos/ultra-consult | [FATO] quanto ao conteúdo anunciado; média, fornecedor | Demonstração para validar pedidos, status, laudos, preços e acesso |
| 29/09/2026 | Produto / concorrência | LDB descreve pedidos, status, resultados, relatórios, controle de aprovação, isolamento e portal sem licenças individuais | https://lims.eu/en/kundenzone ; https://lims.eu/en/manual_page/95 | [FATO] quanto à documentação do fornecedor; média | Verificar oferta comercial/adequação local |
| 29/09/2026 | Produto / alternativa adjacente | ALLIMS anuncia resultados online e envio automático, sem confirmação de portal de autoatendimento na página aberta | https://www.allims.com.br/ | [FATO] para funcionalidades anunciadas; média | Confirmar em demonstração; falha de página interna não é evidência negativa |
| 29/09/2026 | Privacidade/regulação | Consultados guia ANPD de agentes e documentos oficiais Anvisa para escopo EAC | links na seção acima | [FATO] sobre documentos; aplicação ao produto é [INFERÊNCIA] | Determinar segmento e papéis; revisão especializada |
| 29/09/2026 | Dor/mercado/preço | Nenhuma entrevista, métrica de operação ou preço comparável local encontrado | S01–S06 | [NÃO ENCONTRADO] / [PENDENTE-HUMANO] | Pesquisa primária e demonstrações |

## Correção de inventário da planilha — 29/09/2026

**Errata:** a afirmação anterior de que notas e ranking da ID 09 estavam em branco estava incorreta. A conferência direta da cópia `pesquisa-ideias-will-lucas_v2.xlsx`, aba Análise, linha 13, identificou a avaliação preexistente de **4,14**, posição **8**. Trata-se da hipótese inicial da planilha, não de nota nova nem de evidência de mercado. O texto acima é preservado como histórico e esta correção o substitui quanto ao estado da planilha. Nenhuma célula foi alterada.
