# Fase 2 — Pesquisa documental inicial da ideia ID 10

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia (aba Ideias, linha 15):** “Gestão de formulações para pequenas indústrias (versões de receita, custo, ficha técnica)”.  
**Nota/ranking:** não alterado; nenhuma nota atribuída.

## Síntese executiva

- [FATO] Formulação, ficha técnica, versões e custos de composição são funções anunciadas por ERPs industriais e soluções de manufatura já no mercado. Exemplos verificados em páginas de fornecedores brasileiros: ACEDATA ERP, WebMais ERP químico e Methos Cloud ERP; alternativas generalistas incluem Nomus ERP Industrial e Odoo PLM/MRP.
- [FATO] Essas ofertas costumam vir integradas a produção, compras, estoque, lotes, qualidade, custos e faturamento — podem competir com uma solução independente e elevar a dificuldade de substituição, mas também implicam implantação e escopo maiores. As páginas comerciais não provam implantação bem-sucedida, qualidade, adoção ou adequação de preço.
- [FATO] “Pequena indústria” não define um segmento regulatório: cosméticos, saneantes, alimentos, suplementos, tintas, produtos químicos e outras categorias têm requisitos próprios. Como exemplo delimitado, a RDC Anvisa 48/2013 de BPF para cosméticos descreve fórmula padrão/mestra e registro por lote baseado na versão aprovada vigente. Isso não deve ser generalizado para qualquer fábrica ou produto.
- [HIPÓTESE] Pode haver oportunidade numa camada simples para desenvolver, versionar, aprovar, calcular custo estimado e publicar ficha técnica sem substituir o ERP. Ainda não existe evidência de que empresas-alvo tenham essa dor sem solução, nem de que aceitem uma ferramenta isolada.
- [NÃO ENCONTRADO] Dor/fluxo dos clientes de Will/Lucas, quantidade de mudanças de fórmula, erros por versão, tempo/custo, orçamento, preço aceito e adoção de ferramentas concorrentes. Nenhuma entrevista, teste, lead ou piloto foi realizado.
- [PENDENTE-HUMANO] Escolher segmento industrial e usuário comprador; observar formulação até fabricação, levantar campos/documentos e exceções, comparar processo atual com ERP existente e validar custos/benefícios com dados da empresa. Para segmento regulado, revisão por responsável técnico/regulatório.

## 1. Interpretação do conceito e escopo desconhecido

- [FATO] A ideia na planilha menciona versões de receita, custo e ficha técnica, mas não define setor, regime de produção, unidade de lote, papel da ferramenta ou integração pretendida.
- [HIPÓTESE] A dor poderia ser manter várias fórmulas e documentos espalhados (planilhas, arquivos, ERP), saber qual revisão está aprovada, calcular custo conforme atualização de matérias-primas e impedir que a produção use instrução antiga.
- [NÃO ENCONTRADO] Quais usuários editam/aprovam, se versões são por produto, cliente, planta ou lote, como se faz escalonamento/ajuste de rendimento, como se calculam custos (padrão, real, impostos, embalagem, mão de obra, perdas) e se a fórmula contém informação sigilosa.
- [INFERÊNCIA] É importante distinguir uma formulação de P&D (propriedades, ensaios, condições, justificativas e histórico) de BOM/ficha técnica operacional (componentes, quantidades e roteiro usados pela produção). Alguns clientes podem precisar dos dois, mas o relatório não comprova essa necessidade comum.
- [DECISÃO DE PESQUISA] Não assumir “pequenas indústrias químicas” como segmento validado. Os achados abaixo são sinais de oferta em alguns setores, não prova de mercado ou de uma oportunidade uniforme.

## 2. Escopo regulatório: exemplo cosméticos, sem extrapolação

- [FATO] RDC Anvisa 48/2013 aprova BPF para produtos de higiene pessoal, cosméticos e perfumes. O texto define fórmula padrão/mestra como documento(s) com matérias-primas/quantidades, materiais de embalagem e procedimentos/precauções de fabricação. Prevê fórmula padrão/mestra para cada produto e registro de produção por lote baseado na versão aprovada vigente; registros de fabricação devem permitir rastreabilidade. Texto oficial consultado: https://bvsms.saude.gov.br/bvs/saudelegis/anvisa/2013/rdc0048_25_10_2013.html (29/09/2026).
- [FATO] A Anvisa citou RDC 48/2013 em atos/notícias de fiscalização publicados em 2026, o que confirma que a norma foi referenciada como requisito de BPF para cosméticos no período consultado. Exemplo: https://www.gov.br/anvisa/pt-br/assuntos/noticias-anvisa/2026/anvisa-proibe-protetores-solares-e-repelentes (08/05/2026).
- [FATO] RDC 48/2013 se aplica ao escopo cosmético especificado, não automaticamente a todas as pequenas indústrias. A resolução remete segurança ocupacional e ambiental a legislação própria; outras categorias precisam de pesquisa regulatória específica.
- [NÃO ENCONTRADO] Nesta rodada não foi concluída uma revisão consolidada de todas as alterações posteriores, nem revisão da lista regulatória para alimentos, saneantes, medicamentos, dispositivos, produtos químicos ou outras categorias. A norma deve ser validada em fonte oficial consolidada e com responsável regulatório antes de desenhar software de compliance.
- [INFERÊNCIA] Para cosméticos, há aderência textual entre fórmula mestra/versionamento e controles de produção, mas isso não prova que uma plataforma autônoma seja suficiente para cumprir BPF, nem que implantação de software substitua procedimentos/validações e registros exigidos.

## 3. Concorrentes e alternativas

### A01 — ACEDATA ERP (indústria química)

- **URL oficial:** https://acedata.com.br/noticias/da-formula-a-expedicao-como-um-erp-otimiza-a-producao-quimica/ (consultada 29/09/2026).
- **[FATO]** Página comercial descreve ficha técnica/formulação mestra, histórico de versões, custo teórico de batelada comparado ao custo real, produção por batelada, coprodutos/subprodutos e vínculo com análise/liberação do CQ. O fornecedor oferece apresentação comercial.
- **Preço:** não publicado na página; solicitar proposta.
- **Limitação:** declarações do próprio fornecedor. Não foram verificados produto em uso, implantação, desempenho ou se a configuração serve a microempresa.

### A02 — WebMais ERP (indústria química)

- **URL oficial:** https://webmaissistemas.com.br/erp-para-industria-quimica/ (consultada 29/09/2026).
- **[FATO]** Página apresenta ERP para indústria química, com formulação/ficha técnica, matérias-primas, produção, estoque, rastreabilidade, custo/preço, qualidade e controles de acesso às fórmulas. Requer demonstração.
- **Preço:** não publicado na página consultada.
- **Limitação:** funcionalidades e claims de resultado são do fornecedor; compatibilidade com operação/segmento-alvo depende de demonstração.

### A03 — Methos Cloud ERP (pequena indústria química)

- **URL comercial:** https://www.methos.com.br/artigo/sistema-erp-industria-quimica-modulos-especiais-e-integracoes (busca consultada 29/09/2026).
- **[FATO]** Artigo comercial anuncia cadastro de formulações/receitas com percentuais, versões, custos, atualização de custo pela variação dos insumos e simulação de novas fórmulas, ligado a qualidade/rastreabilidade.
- **Preço:** não localizado; a afirmação de ser “acessível” é do próprio fornecedor, não preço verificável.
- **Limitação:** texto de marketing, sem confirmação por demonstração ou cliente.

### A04 — Odoo PLM/MRP (ERP generalista)

- **Documentação oficial:** https://www.odoo.com/documentation/19.0/applications/inventory_and_mrp/plm/manage_changes/version_control.html (consultada 29/09/2026).
- **[FATO]** Documentação Odoo 19 descreve controle de versões de BOM com ECO, histórico de revisões, usuário responsável, efetividade e arquivos associados; a documentação também liga a BOM vigente à fabricação. Pode servir como alternativa generalista/customizável.
- **Preço/custo total:** não apurado para configuração, implementação e suporte no Brasil; recursos PLM e integrações devem ser cotados conforme edição/escopo.
- **Limitação:** documenta BOM/PLM; não demonstra, por si só, que resolve cálculos e workflow de formulação química nem obrigações específicas de um setor.

### A05 — Nomus ERP Industrial (ERP industrial para PMEs)

- **URL oficial:** https://www.nomus.com.br/erpindustrial/ (busca consultada 29/09/2026).
- **[FATO]** Página posiciona ERP industrial para pequenas e médias indústrias. Publica preço inicial “a partir de R$ 1.290 mensais”. É preço de entrada declarado pelo fornecedor, não proposta para esse caso ou módulo de formulação. Produção, estoque e outros módulos podem alterar a cotação.
- **Limitação:** a pesquisa não confirmou recurso específico de gestão de fórmula com versões/validação; não assumir paridade com soluções químicas especializadas.

### A06 — Planilha, documentos internos e ERP atual

- [HIPÓTESE] Alternativas possíveis são planilha controlada, documentos aprovados, ERP contábil/industrial já contratado ou consultoria/serviço de implantação, sem compra de outro produto.
- [NÃO ENCONTRADO] Quais opções são usadas pelo ICP, custo, satisfação, incidência de erro ou dificuldade de manter versão aprovada sincronizada entre P&D e produção.

### A07 — Solução vertical por categoria

- [FATO] Há soluções próprias para setores adjacentes, por exemplo, FórmulaCerta da Fagron Tech para farmácias magistrais, com fluxo de manipulação e fichas técnicas. Não é diretamente equivalente a software de formulação de pequena indústria e não foi contabilizado como substituto genérico. Fonte comercial oficial: https://fagrontech.com.br/solucoes/formulacerta (resultado da busca em 29/09/2026).
- [INFERÊNCIA] Produtos verticais de cosmético, alimento, farmácia magistral e químico podem cobrir requisitos distintos; comparação concorrencial só é válida depois da seleção de setor e workflow.

### Implicação competitiva

- [FATO] A oferta comercial encontrada inclui versionamento, custo e ficha técnica em ERPs químicos brasileiros e versionamento BOM em ERP generalista. A proposta não está numa categoria sem concorrência.
- [INFERÊNCIA] Uma ferramenta independente pode precisar focar em R&D/Formula Lifecycle, privacidade da fórmula, comparações e aprovações ágeis, mantendo interface com o ERP existente. Nenhuma lacuna foi comprovada e a ideia pode ser funcionalidade de um ERP, não negócio autônomo.

## 4. Mercado, preço e demanda

- [NÃO ENCONTRADO] Número de pequenas indústrias por categoria e geografia, orçamento, softwares instalados, quantidade de formulações ativas, frequência de revisão, usuários envolvidos, erro de fabricação, custo de refugo e tempo gasto em planilha.
- [FATO] Apenas Nomus publica preço de entrada na página consultada (R$ 1.290/mês); isso não é preço da funcionalidade de formulação, nem benchmark adequado para software autônomo.
- [FATO] Os outros fornecedores verificados pedem demonstração/contato e não exibem preço final na fonte consultada.
- [ESTIMATIVA] Não calculada. TAM/SAM/SOM, ticket e retorno dependem da categoria industrial, tamanho, processo, buyer e escopo de implantação que ainda não foram definidos.

## 5. Riscos e advogado do diabo

1. [INFERÊNCIA] A ideia pode ser uma feature dentro de ERP/MES/QMS/PLM existente, reduzindo urgência de comprar ferramenta independente.
2. [FATO] Fabricantes ERP já anunciam versionamento, custo, produção e qualidade; disputa pode envolver integração profunda e migração de dados, não apenas interface.
3. [INFERÊNCIA] Custo de produto não é só soma de matérias-primas: rendimento, perdas, embalagem, mão de obra, energia, overhead, tributos, conversão/unidades e custo real podem fazer um “cálculo automático” parecer preciso sem sê-lo.
4. [INFERÊNCIA] Falha em publicar a versão certa pode contaminar produção; acessos, aprovação, vigência, cópias offline, lote que usou a receita e trilha de alteração exigem processo bem modelado.
5. [INFERÊNCIA] Fórmulas podem constituir segredo comercial; controle de acesso, segregação por cliente/planta e exportação/backup são riscos de segurança importantes.
6. [FATO] Requisitos regulatórios variam por categoria. Usar cosméticos como argumento para toda indústria seria extrapolação.
7. [NÃO ENCONTRADO] Disposição a pagar, força da dor e adoção em pequenas empresas; claims de ROI e redução de perdas publicados por fornecedor não são evidência independente.

## 6. Próximo teste humano

1. **Escolher um segmento e delimitar comprador:** por exemplo, fabricante pequeno de cosméticos/saneantes ou uma classe de fabricantes de produtos químicos. Não misturar setores sem comprovação.
2. **Mapear processo com um caso recente:** nova formulação, mudança de fornecedor/insumo, ajuste de custo, revisão de ficha, lote piloto e publicação para produção. Identificar responsável de P&D, qualidade, produção, compras e diretor que paga.
3. **Solicitar evidências não confidenciais:** modelo de ficha técnica mascarada, histórico de versão, ordem de produção, cálculo de custo, logs/revisão de fórmula; não pedir a composição secreta em entrevista inicial.
4. **Medir estado atual:** formulações ativas, alterações por mês/ano, duração e aprovadores por mudança, fórmulas divergentes, erros de versão, reprocessos/refugos atribuíveis documentados, tempo de recálculo e custo de implantação do ERP existente.
5. **Comparar substitutos:** solicitar demonstração de fornecedor atual/ERP; verificar se o gargalo pode ser resolvido com função/licença já paga, workflow/documento controlado ou melhoria de processo.
6. **Teste de protótipo seguro:** usar fórmula fictícia ou sintética; testar versionamento, diffs, aprovação, vigência e cálculo com unidade/rendimento; não carregar segredos ou usar em produção sem avaliação de segurança, validação e aprovação técnica.
7. **Decisão:** Will/Lucas e operador definem antecipadamente evidências mínimas para avançar. Elogio hipotético, interesse genérico ou estudo documental não equivale a piloto ou disposição a pagar.

## 7. Fontes e log

### Fontes verificadas

- **S01 — Anvisa RDC 48/2013, texto oficial no BVS-MS:** https://bvsms.saude.gov.br/bvs/saudelegis/anvisa/2013/rdc0048_25_10_2013.html — escopo BPF cosméticos; fórmula mestra e registro de lote. Consultada 29/09/2026.
- **S02 — Anvisa notícia de ação fiscalizatória em 2026:** https://www.gov.br/anvisa/pt-br/assuntos/noticias-anvisa/2026/anvisa-proibe-protetores-solares-e-repelentes — referência à RDC 48/2013 em contexto cosmético; não é consolidação normativa.
- **S03 — ACEDATA ERP, indústria química:** https://acedata.com.br/noticias/da-formula-a-expedicao-como-um-erp-otimiza-a-producao-quimica/ — página do fornecedor aberta 29/09/2026; versão, custo, batelada e CQ declarados.
- **S04 — WebMais ERP químico:** https://webmaissistemas.com.br/erp-para-industria-quimica/ — página do fornecedor aberta 29/09/2026; módulos declarados para formulação/ficha, custo e produção.
- **S05 — Methos Cloud ERP, soluções químicas:** https://www.methos.com.br/artigo/sistema-erp-industria-quimica-modulos-especiais-e-integracoes — artigo comercial localizado via busca 29/09/2026; funções declaradas.
- **S06 — Odoo 19 PLM version control:** https://www.odoo.com/documentation/19.0/applications/inventory_and_mrp/plm/manage_changes/version_control.html — documentação oficial aberta 29/09/2026; histórico e versionamento de BOM por ECO.
- **S07 — Nomus ERP Industrial:** https://www.nomus.com.br/erpindustrial/ — página oficial localizada via busca em 29/09/2026; preço inicial promocional/de entrada declarado pelo fornecedor, sem cotação para caso específico.
- **S08 — Fagron Tech FórmulaCerta:** https://fagrontech.com.br/solucoes/formulacerta — página oficial localizada via busca em 29/09/2026; software vertical para farmácia magistral, adjacente e não equivalente.

| Data local | Item | Ação/resultado | Fonte | Classificação/confiança | Pendência |
|---|---|---|---|---|---|
| 29/09/2026 | Escopo de formulação | Verificada ideia literal no workbook; setor e fluxo não definidos | — | [FATO] planilha | Escolher ICP e comprador |
| 29/09/2026 | Requisito regulatório cosméticos | Lida RDC 48/2013 oficial e página Anvisa recente; fórmula mestra e registro de lote no escopo cosmético | S01–S02 | [FATO] fonte governamental; não extrapolado | Revisão consolidada e técnica antes de produto |
| 29/09/2026 | Oferta concorrente Brasil | Abertas páginas ACEDATA e WebMais; verificados claims Methos e Nomus | S03–S05, S07 | [FATO] oferta/preço publicamente anunciado pelo fornecedor; performance não validada | Demonstrações e cotações |
| 29/09/2026 | Alternativa ERP generalista/vertical | Aberta documentação Odoo; identificada solução magistral Fagron como adjacente | S06, S08 | [FATO] recursos declarados/documentados | Confirmar fit funcional no segmento selecionado |
| 29/09/2026 | Dor, ROI e preço próprio | Não houve entrevistas, testes, dados de clientes ou cálculo de mercado | — | [NÃO ENCONTRADO]/[PENDENTE-HUMANO] | Validação primária e custo observado |
