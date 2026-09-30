# Fase 2 — Pesquisa documental inicial da ideia ID 12

**Data de acesso às fontes:** 29/09/2026 (America/Sao_Paulo)  
**Ideia da planilha:** “Leitura automática de laudos de fornecedores em PDF, com conferência e alertas.”  
**Posição na triagem original:** 1º lugar; nota 4,79. A classificação/nota é apenas triagem preliminar da planilha, não evidência de demanda ou de potencial comercial. Nenhuma nota foi alterada.

## Resumo executivo — sem recomendação empresarial

- [FATO] Há produtos publicados que leem/extraiem dados de PDFs de forma genérica (Parseur) e uma solução LIMS que publica importação por IA de dados não estruturados e exemplos de importação de dados de amostra/documentos (LDB). Portanto, “ler PDFs com IA” isoladamente não é uma diferenciação demonstrada nesta pesquisa.
- [FATO] Empresas brasileiras Ultra LIMS e ALLIMS oferecem LIMS para gestão laboratorial, que podem ser alternativas mais amplas de workflow; as páginas abertas não demonstram explicitamente leitura por IA de laudos PDF de fornecedores por essas empresas.
- [NÃO ENCONTRADO] Não foi encontrada nesta busca evidência verificável de quantos laboratórios comprariam a solução, da frequência de recebimento desses laudos, do custo atual de digitação/conferência, do custo de erro, nem da disposição a pagar.
- [INFERÊNCIA] A hipótese que resta testar não é simplesmente “consegue ler PDF”; pode ser se uma solução focada em relatórios de fornecedores, critérios configuráveis, evidência de conferência e integração ao sistema usado pelo laboratório resolve um fluxo sem cobertura suficiente pelas alternativas. Isso ainda não está provado.
- [PENDENTE-HUMANO] Dor, frequência, gravidade, comprador, orçamento, confiança/aceitação do resultado automatizado e disposição de pagar exigem entrevistas e teste com documentos reais autorizados. Não houve contato com clientes nem experimento.

## 1. Problema e cliente

- [HIPÓTESE] Usuários possíveis: responsáveis/analistas de qualidade e equipe de laboratório que recebe relatórios/laudos/certificados de fornecedores em PDF e precisa transcrever ou conferir campos contra especificações internas.
- [NÃO ENCONTRADO] A planilha não identifica tipo de fornecedor, setor industrial, perfil de laboratório, volume de documentos, fluxo de conferência, comprador ou sistema de destino.
- [PENDENTE-HUMANO] Perguntar por um caso recente: documento recebido, etapas manuais, retrabalho/erro ocorrido, pessoa responsável, consequência, ferramenta atual e quem aprova compra. Não perguntar apenas “você usaria IA?”.

## 2. Alternativas e concorrência verificadas

A verificação demonstra ofertas publicadas, não adoção, qualidade real ou sucesso comercial. “Preço público” abaixo distingue informação visível na página de orçamento personalizado.

### C01 — Parseur (alternativa direta/genérica de extração de dados de PDF)

- **Fonte/URL:** https://parseur.com/pdf-parser — página oficial de produto aberta em 29/09/2026.
- **[FATO] Público/uso declarado:** extração automatizada de dados de PDFs; a página menciona faturas, recibos, contratos, conhecimentos de embarque e relatórios.
- **[FATO] Funcionalidades declaradas:** carregar PDFs, definir campos por IA ou templates, exportar para Excel/Google Sheets e conectar a outras aplicações; página também menciona API.
- **Preço observado:** fonte de preço separada https://parseur.com/pricing, aberta em 29/09/2026. A página mostra plano grátis de 20 páginas/mês e descreve planos Base (até 3.000 páginas/mês), Scale (até 1 milhão) e Enterprise (até 10 milhões), mas o preço numérico do controle de volume não ficou exposto no conteúdo acessível. Enterprise: orçamento por consulta. **Preço público verificável em valor monetário: não encontrado nesta captura.** Moeda/periodicidade das faixas de preço pagas: não informada na seção textual obtida.
- **Por que é alternativa:** cobre a etapa de extrair campos de documentos PDF e exportar dados, ainda que não seja específica para laudos de fornecedores em laboratório.
- **Limitações/lacunas observáveis:** a página aberta não prova validação de limites/especificações químicas, workflow de aprovação laboratorial ou trilha de auditoria apropriada a determinado uso regulado. Não se infere que não existam recursos em outros planos.
- **Confiança:** média para funcionalidades/preços da página pública; nenhuma evidência independente de precisão para esse caso de uso.

### C02 — LDB LIMS / Labordatenbank (alternativa direta integrada a LIMS)

- **Fonte/URL:** https://lims.eu/en/aiimports — página oficial de importações por IA aberta em 29/09/2026. Página geral: https://lims.eu/en.
- **[FATO] Funcionalidade declarada:** a página diz que interfaces de importação por IA transformam dados não estruturados em importações estruturadas. Exemplos publicados incluem criar amostras a partir de uma comunicação/documento de cliente e atribuir certificados externos de calibração automaticamente (manual vinculado na página).
- **[FATO] A página geral declara:** gestão e rastreabilidade de amostras, workflows e dados de laboratório; atende setores/laboratórios variados, segundo a empresa.
- **Preço público:** não informado na página aberta; há opção de demonstração/reunião. Não estimado.
- **Por que é alternativa:** oferece importação assistida por IA dentro de um sistema laboratorial; é mais próximo do fluxo de ingestão e estruturação de documentos, embora a prova consultada não seja exatamente a leitura de laudo de fornecedor com comparação contra especificações.
- **Limitações:** fonte do próprio fornecedor; recursos e casos não foram testados. Não confirma disponibilidade no Brasil, localização de dados, idioma português, suporte local, preço ou aderência aos tipos específicos de PDF de potenciais clientes.
- **Confiança:** média para o que a página declara; insuficiente sobre adequação ao caso e comercialização no Brasil.

### C03 — Ultra LIMS / Ultra One (alternativa indireta: sistema laboratorial completo)

- **Fonte/URL:** https://ultralims.com.br/produtos/ultra-one e https://ultralims.com.br/ — páginas oficiais abertas em 29/09/2026.
- **[FATO] Oferta declarada:** Ultra One é apresentado para laboratórios pequenos (a página indica até cinco colaboradores/usuários em trechos diferentes) e inclui fluxo comercial, planejamento, amostragem, recebimento, execução, relatórios, financeiro e portal do cliente. Página geral declara rastreabilidade e integrações/importação de dados.
- **Preço público:** não informado; página convida a agendar apresentação. Não estimado.
- **Por que é alternativa:** pode cobrir processos e registros relacionados a laboratório de ponta a ponta, potencialmente tornando desnecessária uma ferramenta independente se o problema puder ser resolvido por configuração/integrador do LIMS.
- **Limitações:** as páginas consultadas não demonstram especificamente OCR/IA para interpretação de laudos de fornecedores em PDF nem regras de comparação com especificações. Depoimentos comerciais da própria empresa não são tratados como evidência independente de resultados.
- **Confiança:** média para a descrição do produto declarada pelo fabricante; insuficiente para confirmar a lacuna funcional.

### C04 — ALLIMS (alternativa indireta: LIMS nacional)

- **Fonte/URL:** https://www.allims.com.br/ — página oficial aberta em 29/09/2026. URL de subpágina do sistema https://www.allims.com.br/sistema retornou página de erro/indisponibilidade durante a tentativa.
- **[FATO] Oferta declarada:** a página inicial descreve sistema modular para laboratórios de prestadores de serviço, controle de qualidade e P&D; lista rastreabilidade, integração com equipamentos, acompanhamento de rotina, emissão/envio de relatório e conexão com outros sistemas.
- **Preço público:** não informado na página aberta; menciona contato/demonstração. Não estimado.
- **Por que é alternativa:** sistema laboratorial mais amplo pode ser usado para gerir dados, relatórios e registros hoje tratados manualmente ou por ferramenta avulsa.
- **Limitações:** a página inicial não confirma leitura automática de PDFs nem comparação de campos com especificações. A indisponibilidade da subpágina impede verificar informação adicional; não é prova de inexistência da funcionalidade.
- **Confiança:** média para características mostradas na homepage; baixa/insuficiente para escopo detalhado.

**Número de concorrentes/alternativas diretamente verificáveis:** duas alternativas com funcionalidade de extração/importação de documentos em algum grau (C01 genérico e C02 integrado a LIMS), com níveis de correspondência distintos. Duas alternativas indiretas de LIMS brasileiras (C03/C04). Não se afirma que essa lista seja exaustiva ou que todos sejam concorrentes diretos.

## 3. Regulação e risco de uso

- [FATO] A planilha já listava uma página da Anvisa sobre perguntas e respostas da RDC 978/2025. A verificação do material e de um roteiro oficial de inspeção está registrada em Fase 1/fontes iniciais. A RDC 978/2025 trata de serviços relacionados a exames de análises clínicas; não se presume que se aplique a qualquer laboratório industrial ou a todo laudo de fornecedor.
- [FATO] O roteiro oficial de inspeção EAC Tipo III aberto em https://www.gov.br/anvisa/pt-br/assuntos/servicosdesaude/projeto-de-melhoria-do-processo-de-inspecao-sanitaria-em-servicos-de-saude-e-de-interesse-para-a-saude/harmonizacao-de-roteiros-objetivos-de-inspecao-roi/13.1ROIparaEACSTIII_verso1.51.pdf/@@display-file/file identifica versão 1.5, data 04/12/2025, e inclui tópicos de controle de documentos, laudos e validação em partes do roteiro. Isso é evidência de critérios de inspeção para EAC Tipo III, não de que a ideia ID12 está sujeita a uma obrigação específica.
- [INFERÊNCIA] Se o software for usado para decisão de aceitação/rejeição de insumo ou liberação de lote, erros de extração podem ter consequências operacionais/de qualidade; controles humanos, proveniência, logs, validação e possibilidade de revisão seriam aspectos a investigar. Não foi encontrada evidência de que um requisito regulatório específico imponha este produto/arquitetura.
- [PENDENTE-HUMANO — CONSULTA PROFISSIONAL] Delimitar setor, uso pretendido, se documentos/dados pessoais ou clínicos são processados, quem toma decisão e normas aplicáveis antes de alegar conformidade. Esta pesquisa não constitui parecer jurídico ou regulatório.

## 4. Mercado e dimensão

- [NÃO ENCONTRADO] Universo de laboratórios-alvo definido para a ideia; quantidade de estabelecimentos no perfil; fração com recebimento de documentos PDF; volume de documentos; orçamento ou mercado inicial acessível.
- [NÃO ENCONTRADO] A pesquisa nesta etapa não encontrou dado oficial com correspondência suficiente ao ICP ainda não definido. Não se usa o total de um CNAE como TAM/SAM, e nenhum valor de faturamento ou tamanho de mercado é calculado.
- [PENDENTE-HUMANO] Definir primeiro segmentos prioritários (por exemplo, tipo de ensaio/material, porte, processo de compras, geografia). Depois buscar base oficial com definição compatível e verificar amostra de empresas e acesso realista.

## 5. Dor documentada e economia

- **Evidência primária de clientes:** [NÃO ENCONTRADO]. Nenhuma entrevista, piloto ou observação de fluxo foi realizada.
- **Evidência secundária:** páginas de fornecedores demonstram que existem ofertas de extração/importação e sistemas laboratoriais, mas não provam prevalência nem gravidade de uma dor dos clientes.
- [NÃO ENCONTRADO] Tempo por documento, taxa de erro, retrabalho, custo de pessoal, perdas associadas, volume e custo da solução atual.
- [PENDENTE-HUMANO] Coletar documentos anonimizados/autorizados, mapear campos críticos, verificar cada saída manualmente e registrar tempo, correções e falsos alertas. Não enviar documentos de cliente a serviços de terceiros sem autorização/avaliação de privacidade e segurança.

## 6. Preço e economia

- [FATO] Parseur expõe plano gratuito limitado por volume e planos pagos baseados em páginas, mas o valor monetário não foi exibido na captura acessível de preço. LDB, Ultra LIMS e ALLIMS não publicaram valor verificável nas páginas acessadas.
- [NÃO ENCONTRADO] Preço aceitável ou disposição a pagar por laboratório; economia unitária; custo por documento; custo de integração e suporte.
- [HIPÓTESE] Uma oferta inicial poderia ser serviço assistido por pessoa + software para aprender os tipos de documento e os critérios de revisão. Esta hipótese não representa solução escolhida nem economia comprovada.
- [PENDENTE-HUMANO] Apresentar oferta/piloto com escopo, preço e responsabilidade claros a compradores reais, sem prometer desempenho antes de medir.

## 7. Notas e ranking

- [FATO] Nota inicial na triagem: 4,79; posição inicial: 1º. Valor foi lido da aba Análise.
- [HIPÓTESE] Mantém-se a nota preliminar da planilha como hipótese não validada. Não foi alterada porque não há evidência de dor, gasto ou mercado que permita recalibrá-la.
- [INFERÊNCIA] As ofertas C01 e C02 tornam a diferenciação ampla (“IA que lê PDF”) menos evidente do que a descrição inicial poderia sugerir; isso não quantifica concorrência nem invalida uma especialização de workflow.

## 8. Advogado do diabo — riscos classificados

1. [FATO] Parseur e LDB publicam recursos de extração/importação de dados documentais. [INFERÊNCIA] Concorrer em extração genérica pode ter diferenciação difícil sem foco de workflow, validação ou integração demonstrável.
2. [HIPÓTESE] PDFs de fornecedores podem variar em leiaute, unidades, nomenclatura e qualidade; isso pode gerar falsos positivos/negativos e revisão manual cara. A variação real nos arquivos-alvo ainda precisa ser observada.
3. [HIPÓTESE] Compradores podem preferir ampliar o LIMS já contratado a comprar uma ferramenta isolada; não há entrevistas ou dados de compras para confirmar.
4. [INFERÊNCIA] A página do LDB declara importações de IA dentro de LIMS, sugerindo que incumbentes podem incorporar funções semelhantes. A direção futura de produtos é incerta.

## 9. Evidências favoráveis e contrárias

- **Favoráveis:** [FATO] duas soluções publicam formas de extração/importação de documentos em fluxo laboratorial/genérico; isso demonstra existência técnica/comercial de categoria adjacente, não demanda pelo produto proposto. Pode reduzir risco de viabilidade técnica básica, mas não prova precisão nos laudos específicos.
- **Contrárias:** [FATO] existem alternativas de parser genérico e de importação em LIMS; [INFERÊNCIA] proposta genérica aparenta espaço de diferenciação não demonstrado.
- **Neutras/insuficientes:** reclamações, avaliações públicas e relatos independentes de clientes sobre conferência manual de laudos de fornecedores não foram encontrados nesta etapa. Não se conclui ausência da dor.

## 10. Lacunas e próximos testes humanos

1. Definir ICP com Will/Lucas: segmento, região, tamanho de laboratório, tipo de documento e sistemas existentes.
2. Entrevistar pessoas que executam e aprovam a conferência, partindo de episódios recentes e processo atual; separar usuário, influenciador e comprador.
3. Com autorização, coletar pequeno conjunto de PDFs anonimizados e representativos de fornecedores distintos. Proibir uso de dados confidenciais sem autorização explícita.
4. Executar teste cego em que a pessoa revisa extrações; medir campos críticos corretos, erros graves, tempo total de conferência, documentos não processáveis e correções manuais. Fixar tolerâncias com o responsável do processo antes do teste.
5. Testar solução existente (parser/LIMS) versus serviço manual assistido, não construir produto antes de verificar a lacuna.
6. Testar preço com oferta concreta/piloto pago; interesse verbal sozinho não confirma disposição a pagar.

**Métrica e critério numérico:** [PENDENTE-HUMANO]. Os limites de erro, taxa mínima de automação, volume e preço devem ser acordados com o dono do processo e com os recursos de Will/Lucas antes do teste. Definir números arbitrários aqui criaria aparência de validação.

## 11. Fontes críticas (todas abertas)

- **S01:** Parseur, PDF Parser, página oficial: https://parseur.com/pdf-parser — acesso 29/09/2026; conteúdo de produto/fluxo de extração; publicação/atualização não identificada na página capturada; fonte comercial primária, limita-se a alegações do fornecedor.
- **S02:** Parseur, pricing: https://parseur.com/pricing — acesso 29/09/2026; conteúdo de tiers/limites; valor monetário pago não apareceu na captura; fonte comercial primária.
- **S03:** LDB, AI imports: https://lims.eu/en/aiimports — acesso 29/09/2026; importações estruturadas de dados não estruturados, amostras e certificado externo de calibração; fonte comercial primária, sem demonstração independente.
- **S04:** LDB, produto: https://lims.eu/en — acesso 29/09/2026; escopo declarado do LIMS e workflows de laboratório; preço não encontrado na página consultada.
- **S05:** Ultra LIMS, Ultra One: https://ultralims.com.br/produtos/ultra-one — acesso 29/09/2026; público e módulos declarados; preço não informado.
- **S06:** Ultra LIMS, página inicial: https://ultralims.com.br/ — acesso 29/09/2026; rastreabilidade, integrações e catálogo; fonte comercial primária.
- **S07:** ALLIMS, página inicial: https://www.allims.com.br/ — acesso 29/09/2026; escopo e funcionalidades declaradas; fonte comercial primária. A subpágina https://www.allims.com.br/sistema foi aberta e retornou erro 404/serviço indisponível; não usada para afirmar recursos.
- **S08:** Anvisa, ROI para EAC Tipo III: https://www.gov.br/anvisa/pt-br/assuntos/servicosdesaude/projeto-de-melhoria-do-processo-de-inspecao-sanitaria-em-servicos-de-saude-e-de-interesse-para-a-saude/harmonizacao-de-roteiros-objetivos-de-inspecao-roi/13.1ROIparaEACSTIII_verso1.51.pdf/@@display-file/file — acesso 29/09/2026; PDF aberto; versão/data indicadas no documento; aplicabilidade limitada a EAC Tipo III.

## Log de auditoria

| Data/hora local | Fase | Item | Ação/resultado | Fontes | Classificação | Confiança | Pendência / próximo passo |
|---|---|---|---|---|---|---|---|
| 29/09/2026 | 2 | ID12 problema/cliente | Delimitada descrição da planilha; ICP e ocorrência da dor não identificados | Planilha; nenhum relato primário | [HIPÓTESE]/[NÃO ENCONTRADO] | Insuficiente | Definir ICP e entrevistar potenciais usuários |
| 29/09/2026 | 2 | ID12 alternativas | Verificadas duas alternativas com extração/importação em algum grau e duas alternativas indiretas LIMS | S01–S07 | [FATO] quanto às páginas; limitação comercial registrada | Média | Testar adequação real e alternativas usadas pelo ICP |
| 29/09/2026 | 2 | ID12 preço/mercado/dor | Não estimados por falta de dados; nota da triagem mantida | S01–S08; matriz da planilha | [NÃO ENCONTRADO]/[HIPÓTESE] | Insuficiente | Pesquisa primária após recorte do público |
| 29/09/2026 | 2 | ID12 regulação | Recorte de EAC Tipo III separado de laboratórios industriais; sem parecer de aplicabilidade | S08 e referência regulatória prévia da Fase 1 | [FATO]/[INFERÊNCIA] | Insuficiente para caso específico | Consulta profissional após definir uso/segmento |
