# Fase 2 — Pesquisa documental inicial da ideia ID 11

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia:** “Assistente que responde perguntas sobre o manual de qualidade e os POPs da empresa.”  
**Triagem original:** posição 6, nota 4,29. Nota mantida; não houve entrevistas nem validação de uso.

## Síntese executiva

- [FATO] Há produtos publicados que fazem perguntas/respostas sobre procedimentos e documentos de qualidade, tanto ferramentas de QMS/qualidade específicas (QENSA, myQMS.ai e ZenQMS AI) como IA contextual incorporada a LIMS (LDB AI Explorer). A categoria já existe; não é correto tratar “chat com POP” como novidade sem recorte.
- [FATO] As páginas de QENSA e LDB descrevem respostas com base em documentos/conteúdo/contexto próprios; a ZenQMS descreve atualmente busca em linguagem natural nos documentos e gerador de perguntas para treinamento. O Q&A direto em documento aparece como “coming soon” na página ZenQMS consultada, portanto não foi contado como recurso já disponível.
- [FATO] QENSA publica um Pro Plan por $30/mês, com renovação automática por 30 dias; sem indicação inequívoca de moeda no conteúdo consultado. O valor não é convertido nem comparado como preço de mercado.
- [NÃO ENCONTRADO] Não há evidência de quantas equipes de laboratório têm a dor, frequência de busca, demora para achar procedimento, impacto de instrução desatualizada, orçamento ou aceitação de IA nas operações de Will/Lucas.
- [INFERÊNCIA] Diferenciação possível teria que considerar conteúdo controlado/vigente, respostas ancoradas em trechos e acesso por permissão, português e integração com o sistema documental real. Isso é requisito de investigação, não vantagem comprovada.
- [PENDENTE-HUMANO] Entrevistar usuários da qualidade e responsáveis, testar em documentos aprovados e revisar respostas. Não foi feito contato, teste com dados nem experimento.

## 1. Problema e público

- [HIPÓTESE] Pessoas no laboratório podem ter dificuldade de localizar rapidamente a versão vigente de um POP/manual ou entender uma instrução relevante durante o trabalho.
- [NÃO ENCONTRADO] A planilha não identifica quais documentos, perguntas, funções, frequência, consequência de erro, mecanismo atual ou decisor seriam envolvidos.
- [PENDENTE-HUMANO] Descobrir episódios concretos de busca e dúvida, quais repositórios já existem, como se confirma versão/validade, o que acontece quando não se encontra resposta e quem pode alterar ou aprovar procedimentos.

## 2. Alternativas/concorrentes verificadas

### C01 — QENSA (assistente dedicado a documentos de qualidade)

- **URL aberta:** https://qensa.org/en/ — acesso 29/09/2026.
- **[FATO]** Página descreve assistente para equipes de qualidade/manufatura, pesquisa em procedimentos, instruções, relatórios, reclamações e base de conhecimento, análise de documentos, geração de relatórios, avaliação de produtos contra padrões e suporte a CAPA. Diz que, conforme configuração, pode citar documento/seção e ter controle de acesso, cloud/on-premise e configuração sem treinamento dos modelos com dados enviados.
- **Preço público observado:** Pro Plan $30/mês, plano de 30 dias com renovação automática, e $36/mês sem renovação automática, conforme a página. **Moeda não explicitada no conteúdo da página capturada**; unidade mensal, escopo de plano e condições conforme exibidos. Oferta individual não comparável diretamente a contrato empresarial.
- **Por que alternativa:** sobreposição direta para perguntas baseadas em procedimentos e documentação de qualidade.
- **Limitações:** informações da própria empresa; configuração de privacidade, implantação, citações e acesso dependem do plano/implantação; não prova precisão ou aderência a laboratórios brasileiros.

### C02 — myQMS.ai (QMS com busca e assistente de qualidade)

- **URL aberta:** https://www.myqms.ai/ — acesso 29/09/2026.
- **[FATO]** Página diz que a ferramenta responde perguntas sobre processos QMS a partir de procedimentos, instruções de trabalho e templates carregados, além de oferecer geração de conteúdo, auditoria de documentos e orientação por IA. A própria página prevê busca complementar em base de conhecimento/LLM quando não acha resposta nos documentos.
- **Preço público:** não informado na página aberta; oferece consulta.
- **Por que alternativa:** sobreposição direta em Q&A sobre documentos de qualidade e assistente de processo.
- **Limitações:** página comercial; não foram confirmados fonte/citação por resposta, idioma, precisão, implantação, segurança técnica ou atendimento a laboratórios brasileiros. Busca em conhecimento externo/LLM quando não encontra no material pode não ser adequada para instrução operacional sem guardrails, questão a testar, não falha demonstrada.

### C03 — LDB LIMS AI Explorer (assistente contextual dentro de LIMS)

- **URL aberta:** https://lims.eu/en/aiexplorer — acesso 29/09/2026.
- **[FATO]** Página descreve assistente contextual em diferentes registros do LIMS (amostra, pedido, cliente, equipamento, material e documento), seleção visível do contexto enviado, respeito a direitos de acesso declarados pelo sistema e conversas guardadas junto ao registro. Exemplos incluem perguntar sobre resultado/amostra e equipamentos.
- **Preço público:** página remete a custos de IA, mas preço total/condições do LIMS não foram estabelecidos nesta consulta; não estimado.
- **Por que alternativa:** poderia responder perguntas usando dados e documentos já presentes em LIMS, reduzindo necessidade de aplicativo separado para usuário desse sistema.
- **Limitações:** oferta integrada a produto proprietário; disponibilidade no Brasil, dados em português, preço, contrato, desempenho e Q&A específico sobre POP/manual não confirmados por teste. Alegações do fornecedor.

### C04 — ZenQMS AI (QMS farmacêutico/regulado; alternativa adjacente)

- **URL aberta:** https://www.zenqms.com/zenqms-ai-features — acesso 29/09/2026.
- **[FATO]** Página diz que busca inteligente em linguagem natural e gerador de questões de treinamento baseadas em SOPs estão “available now”; cada interação/decisão humana é descrita como registrada. Document Q&A com respostas citadas, comparação de documentos e redação de SOP estão marcados “coming soon” na página.
- **Preço público:** não informado; opção de demonstração.
- **Por que alternativa:** produto de QMS com pesquisa em documentos/SOPs e treinamento; potencial alternativa para organizações em ambiente GxP.
- **Limitações:** produto comercial dirigido a QMS/GxP; não prova fit ou disponibilidade no Brasil. Diferenciar claramente funções já disponíveis das anunciadas para depois.

### C05 — Qualiex Quality Assistant / Qualiex (alternativa SGQ)

- **URL aberta:** https://qualiex.com/iso-9001/ — acesso 29/09/2026 (página pública sobre ISO 9001; o trecho recuperado na consulta indica Quality Assistant como agente IA integrado ao SGQ que apoia análise de não conformidades, interpretação de dados e busca de informações). Página de produto: https://qualiex.com/servicos/ aberta anteriormente.
- **[FATO]** A informação acessível descreve agente de IA integrado a sistema de gestão da qualidade, incluindo busca de informação e apoio à análise. Não foi possível confirmar nesta captura uma função específica de Q&A ancorada em POPs/trechos ou regras do produto.
- **Preço público:** não encontrado; páginas direcionam a demonstração/consulta.
- **Por que alternativa:** potencial substituto dentro do SGQ de uma organização que já utiliza Qualiex.
- **Limitações:** descrição no material comercial/educativo do fornecedor e escopo do assistente ainda impreciso para o caso. Não contar como prova de Q&A rastreável sobre um manual específico.

**Concorrência observada:** pelo menos três ferramentas com Q&A/busca sobre conhecimento de qualidade diretamente declarados (C01–C03), uma ferramenta com busca de SOPs e treino integrado (C04), e uma oferta do SGQ com busca por IA em escopo não totalmente verificado (C05). Essa contagem não é exaustiva e não demonstra qualidade comparável.

## 3. Regulação, segurança e riscos técnicos

- [FATO] As ofertas revisadas destacam controles distintos: QENSA menciona, conforme configuração, fontes/citações, acesso e opção on-premise; LDB menciona lista de contexto e permissões do LIMS; ZenQMS menciona logs e decisão humana. São declarações dos fornecedores, não auditorias independentes de segurança.
- [INFERÊNCIA] Para responder sobre procedimentos operacionais, falhar em versão, contexto ou citação pode levar a resposta errada parecer oficial. Uma camada de pergunta-resposta não deve substituir o procedimento controlado, a aprovação ou treinamento formal sem validação da organização.
- [NÃO ENCONTRADO] Não foi feito mapeamento jurídico/regulatório de tratamento de documentos, dados pessoais, dados de saúde, sigilo, LGPD ou requisitos de validação de sistemas para segmento específico. Não se afirma conformidade por instalar um chatbot.
- [PENDENTE-HUMANO — CONSULTA PROFISSIONAL] Se usado em processo regulado, definir uso pretendido e revisar riscos/controles com profissionais de qualidade, segurança da informação, privacidade e jurídico.

## 4. Mercado e evidência de dor

- [NÃO ENCONTRADO] Universo de laboratórios-alvo, volume e distribuição de POPs, consultas por equipe, tempo de busca, erros por consulta, orçamento e tamanho do mercado acessível.
- [ESTIMATIVA] Não calculada: falta uma definição do ICP e dados populacionais adequados.
- [FATO] Páginas de fornecedores demonstram que produtos oferecem IA para busca/perguntas sobre documentação de qualidade; isso não substitui entrevistas e não prova que exista dor frequente ou lacuna de produto.
- [PENDENTE-HUMANO] Entrevistar trabalhadores e supervisores; acompanhar consultas reais e registrar resposta encontrada, fonte, tempo, versão e escalonamento. Sem copiar documentos confidenciais para ferramentas externas sem autorização.

## 5. Preço e economia

- [FATO] QENSA publica preço mensal de $30 ou $36 conforme modalidade, mas moeda não está explícita na captura; os demais fornecedores desta lista não mostraram preço público verificável.
- [NÃO ENCONTRADO] Disposição a pagar no Brasil, custo de implantação, preço de integração com repositórios/LIMS, custo de inferência, suporte e manutenção.
- [PENDENTE-HUMANO] Testar protótipo/serviço numa base documental de teste e pedir piloto pago só depois de definir controles e comprador. Não calcular economia antes de medir tempo e erro atual.

## 6. Nota e ranking

- [FATO] Nota original 4,29 e posição 6 na aba Análise.
- [HIPÓTESE] Nota mantida. Alternativas verificadas reduzem a sustentação de “pouca concorrência” na forma ampla, mas não medem os demais critérios nem a necessidade de um nicho laboratorial específico.
- [INFERÊNCIA] O diferencial pode depender da integração com documentos controlados do laboratório e das garantias de fonte/versão/permissão, não apenas de um modelo de linguagem. Essa hipótese requer comparação/teste.

## 7. Advogado do diabo — riscos

1. [FATO] Existem produtos que já respondem sobre documentos de qualidade ou incorporam IA a QMS/LIMS. [INFERÊNCIA] Chat genérico sobre PDF tende a enfrentar alternativas e não constitui diferencial demonstrado.
2. [HIPÓTESE] O sistema pode responder a partir de versão obsoleta, misturar documentos ou apresentar uma resposta plausível porém sem suporte. O risco precisa ser testado em perguntas críticas, não se declara taxa de erro conhecida.
3. [HIPÓTESE] Funcionários podem interpretar uma resposta como instrução aprovada; se não houver referências, data/versão, escopo e escalonamento, há risco operacional.
4. [INFERÊNCIA] Documentos internos podem conter segredos, dados pessoais ou know-how; hospedagem, retenção, suboperadores, permissões e uso para treinamento devem ser verificados antes de carregar conteúdo real.

## 8. Próximo teste humano

- **Hipótese:** colaboradores de um perfil específico de laboratório gastam tempo recorrente procurando/resolvendo dúvidas sobre POPs e um assistente com respostas rastreáveis reduz essa fricção sem substituir o controle documental.
- **Público:** analista/técnico que consulta POPs e gestor da qualidade/responsável que aprova e controla versão.
- **Teste:** em cópia sanitizada ou documentos públicos/de demonstração, criar conjunto acordado de perguntas com resposta conhecida e fonte/versão; comparar busca atual, resposta do assistente, correção, trecho citado e escalonamento quando não houver resposta. Realizar sob autorização e sem executar instrução real com resposta não aprovada.
- **Métricas:** precisão das respostas em perguntas críticas, cobertura com citação verificável, taxa de abstenção adequada, fonte/versão corretas, tempo por busca e casos que exigem escalonamento. Limites numéricos devem ser definidos previamente por responsável técnico, não arbitrados nesta pesquisa.
- **Critério de continuar/parar:** seguir para piloto apenas se respostas críticas forem sustentadas em versão vigente e aprovadas por responsáveis, sem contornar controles existentes; parar/ajustar se houver erro crítico, fonte incerta ou falta de problema mensurável. Esses critérios são proposta de teste, não resultado.
- **Custo/tempo:** [NÃO ENCONTRADO] sem recursos e agenda informados.

## Fontes críticas abertas e log

- **S01 QENSA:** https://qensa.org/en/ — acesso 29/09/2026; páginas e subpáginas de preço (chunk 1) consultadas; suporte a perguntas, documentos, configurações de segurança e Pro Plan; alegações do próprio fornecedor.
- **S02 myQMS.ai:** https://www.myqms.ai/ — acesso 29/09/2026; Q&A com base em procedimento/work instructions e outras funções declaradas; sem preço público.
- **S03 LDB AI Explorer:** https://lims.eu/en/aiexplorer — acesso 29/09/2026; assistente contextual de LIMS, direitos de acesso e chats vinculados a registros; sem preço total verificado.
- **S04 ZenQMS AI:** https://www.zenqms.com/zenqms-ai-features — acesso 29/09/2026; busca em linguagem natural e questões de treinamento declaradas disponíveis; Document Q&A e outros recursos explicitamente marcados como futuros na página.
- **S05 Qualiex:** https://qualiex.com/iso-9001/ — acesso 29/09/2026; conteúdo sobre Quality Assistant/SGQ; preço e escopo exato de respostas baseadas em POP não verificados.
- **S06 Qualiex serviços:** https://qualiex.com/servicos/ — acesso 29/09/2026; página de SGQ e documentos/POPs anteriormente consultada.

| Data local | Fase | Item | Ação/resultado | Fontes | Classificação/confiança | Pendência |
|---|---|---|---|---|---|---|
| 29/09/2026 | 2 | ID11 concorrência | Verificadas quatro soluções que declaram Q&A/busca contextual ou IA de documento, mais uma alternativa SGQ parcialmente descrita | S01–S06 | [FATO] sobre páginas públicas, confiança média em ofertas comerciais | Comparar em ambiente de demonstração e segmento definido |
| 29/09/2026 | 2 | ID11 preço | QENSA mostra $30/mês e $36 sem renovação; moeda não indicada na captura | S01 | [FATO], média para conteúdo da página | Confirmar moeda/condições antes de comparação |
| 29/09/2026 | 2 | ID11 problema/segurança | Não há dados primários de dor nem avaliação técnica/jurídica do tratamento de documentos | S01–S06 | [NÃO ENCONTRADO]/[HIPÓTESE], insuficiente | Entrevistas e teste controlado com autorização |
