# Fase 2 — Pesquisa documental inicial da ideia ID 01

**Data de acesso:** 29/09/2026 (America/Sao_Paulo)  
**Ideia (aba Ideias, linha 6):** “Controle de reagentes e estoque (validades, alertas, FISPQ, etiquetas com QR code)”.  
**Nota/ranking:** em branco na cópia. Nenhuma pontuação atribuída.

## Síntese executiva

- [FATO] Existem alternativas que já publicam funcionalidades centrais da proposta. No Brasil, UNILAB anuncia controle de estoque laboratorial e controle de validade/estoque mínimo; Concent anuncia gestão de reagentes e consumíveis com lote, validade, condições de armazenamento, rastreabilidade de uso e compras. Internacionalmente, LabCollector publica gestão de químicos, documentos SDS, pictogramas de perigo, CAS, alertas de vencimento/baixo estoque e descarte; Quartzy anuncia inventário, expiração, documentos SDS e etiquetas com código de barras.
- [FATO] Para laboratórios analíticos sob o escopo da RDC Anvisa 512/2021, os artigos 35–38 tratam de materiais de referência e de reagentes (especificação/aquisição, recebimento, armazenamento, estoque, validade, distribuição, descarte, rotulagem e rastreabilidade de soluções preparadas). O escopo da norma não deve ser generalizado a todo laboratório ou setor.
- [FATO] A NR-26 do MTE estabelece obrigações de classificação de perigos químicos e disponibilização da ficha de dados de segurança pelo fabricante/fornecedor para produto químico classificado como perigoso. O MTE remete a norma técnica oficial; a norma ABNT integral não foi acessada nesta pesquisa. Fontes consultadas ainda usam a sigla FISPQ, enquanto a edição ABNT NBR 14725:2023 adota FDS. O relatório usa “FDS (antes denominada FISPQ)” quando descreve a mudança terminológica, sem pretender substituir consulta à ABNT.
- [FATO] A Portaria MJSP 240/2019 regula produtos químicos listados sob controle da Polícia Federal, com obrigações que dependem do produto, atividade e condições aplicáveis. Não se deve tratar todo reagente como produto controlado nem afirmar que o software, por si, garante conformidade.
- [NÃO ENCONTRADO] Nenhuma evidência de frequência de perdas/vencimentos, gasto atual, processo dos laboratórios-alvo de Will/Lucas, uso de etiquetas QR, adequação das soluções existentes ou disposição a pagar.
- [PENDENTE-HUMANO] Definir setor e entrevistar responsável por estoque/segurança/compras, observar inventário real anonimizado e validar com profissional de segurança química/qualidade se o produto evoluir.

## 1. Problema, usuário e escopo

- [HIPÓTESE] A proposta procura evitar perda de reagentes por vencimento, falta de insumos, dificuldade de localização, dados de lote incompletos e acesso lento à documentação de segurança, por meio de estoque por lote/localização, alertas, documento e etiqueta escaneável.
- [FATO] Essa hipótese aparece como ideia na planilha, mas não como relato real de cliente. As situações descritas em conteúdo promocional de fornecedores não são evidência independente de que ocorram no público de Will/Lucas.
- [NÃO ENCONTRADO] Segmento (clínico, ambiental, alimentos, industrial, pesquisa, ensino), porte, quantidade de itens, número de unidades, perfis autorizados, processo de compras, ERP/LIMS e quem é comprador.
- [PENDENTE-HUMANO] Determinar caso recente verificável: entrada, armazenamento, retirada/consumo, lote, validade, preparo/aliquotagem, atualização de estoque e descarte. Identificar custo do erro e quem responde por segurança e aquisição.

## 2. Concorrentes e substitutos verificados

### C01 — UNILAB / módulo Controle de Estoque (Brasil; alternativa direta em laboratórios clínicos)

- **Fontes oficiais:** https://www.unilab.com.br/solucoes/controle-de-estoque/ ; conteúdo do fornecedor https://www.unilab.com.br/materiais-educativos/controle-de-estoque-para-laboratorios/ e https://www.unilab.com.br/gestao-de-estoque/software-para-controle-de-estoque/ — acessados em 29/09/2026.
- **[FATO]** A página do fornecedor declara módulo de estoque para laboratório, movimentação de materiais, alerta de estoque mínimo, validade de produtos, pedidos entre unidades e integração financeira. Conteúdo educativo do próprio fornecedor trata de alertas de validade e gestão de materiais. Isso confirma oferta anunciada, não impacto medido.
- **Preço público:** não localizado nas páginas consultadas; há demonstração/contato.
- **Escopo/limitação:** produto voltado a gestão laboratorial, com material especialmente direcionado a análises clínicas; QR code e fluxo detalhado de FDS não confirmados nas páginas abertas.

### C02 — Concent LIS / gestão empresarial e qualidade (Brasil; alternativa próxima)

- **Fonte oficial:** https://concentsistemas.com.br/ — acessada em 29/09/2026.
- **[FATO]** O fornecedor declara estoque e compras por lote/data de validade e gestão de reagentes/consumíveis com observância das recomendações do fabricante, armazenamento, validade e rastreabilidade de uso. Também declara importar XML de NF-e para entrada de produtos.
- **Preço público:** não encontrado.
- **Escopo/limitação:** autodescrição de software para laboratórios clínicos e veterinários; QR code, FDS anexada por lote e funcionamento específico em setores não clínicos não foram confirmados.

### C03 — LabCollector Reagents & Supplies / MSDS & Safety (alternativa internacional especializada)

- **Fontes oficiais:** https://labcollector.com/solutions/applications/msds-safety/ ; https://labcollector.com/solutions/industries/analytical-laboratories/ — acessadas em 29/09/2026.
- **[FATO]** O fornecedor declara cadastro de químicos, fabricante/fornecedor, CAS, pictogramas, dados e documentos de segurança, organização dos documentos em localizações, alertas de vencimento e estoque baixo (opção FIFO), compras e histórico de descarte. Oferece versão inicial gratuita/solicitação de cotação conforme página. A própria página ressalta que os usuários são responsáveis por obter as fichas SDS; portanto, a funcionalidade de gestão documental não significa que o fornecedor garante conteúdo atualizado ou correto.
- **Preço público:** a página de segurança oferece início gratuito e contato para cotação; preço completo/licença não confirmado.
- **Escopo/limitação:** página menciona apoio a padrões OSHA/UE, não prova conformidade com legislação brasileira, disponibilidade do módulo no Brasil ou qualidade da importação de dados. Código QR não confirmado na página consultada.

### C04 — Quartzy Inventory (alternativa internacional)

- **Fonte oficial:** https://www.quartzy.com/tour/inventory — acessada em 29/09/2026.
- **[FATO]** Página declara inventário customizável, quantidades/localizações, alertas de validade, documentos SDS, pedidos de compra a partir do inventário, importação de planilhas existentes, etiquetação e leitura de código de barras por aplicativo móvel e permissões de edição. Página usa “barcode”; não foi confirmado suporte especificamente a QR code.
- **Preço público:** sem preço integral capturado; pede demonstração/cadastro. Valores não estimados.
- **Limitação:** produto internacional; adequação linguística, fiscal, regulatória, suporte e disponibilidade comercial para laboratório brasileiro não verificados.

### C05 — Alternativas de menor custo/estado atual

- [HIPÓTESE] Planilhas, registros em papel, etiquetas manuais, planilha de compras/ERP ou módulo de estoque já incluído em LIMS podem substituir uma ferramenta dedicada.
- [NÃO ENCONTRADO] Não foi observado qual alternativa os laboratórios entrevistáveis usam nem custo de migração.
- [FATO] Quartzy publica importação de Excel/Google Sheets/FileMaker; isso documenta suporte do seu produto à importação, não a prevalência de planilhas nos laboratórios.

**Resultado concorrencial:** há pelo menos duas ofertas brasileiras próximas e duas estrangeiras que cobrem uma parcela grande das funções descritas. A amostra não é exaustiva e não permite concluir participação de mercado ou saturação em um nicho definido.

## 3. Referências regulatórias e segurança química

### 3.1 Laboratórios analíticos sujeitos à RDC 512/2021

- **[FATO]** RDC Anvisa 512, de 27/05/2021, “Boas Práticas para Laboratórios de Controle de Qualidade”: arts. 35–38 descrevem procedimentos para materiais de referência; para reagentes, especificação, aquisição, recebimento, armazenamento, estoque, validade, distribuição e descarte, identificação inequívoca de frascos/soluções e registro/rastreabilidade das soluções de trabalho. Fonte oficial BVS/Ministério da Saúde: https://bvsms.saude.gov.br/bvs/saudelegis/anvisa/2020/rdc0512_27_05_2021.pdf (acesso 29/09/2026).
- [INFERÊNCIA] As funcionalidades propostas podem apoiar registros e alertas desses processos, mas não certificam cumprimento da resolução, qualidade do conteúdo nem adequação do procedimento.
- [NÃO ENCONTRADO] Não foi determinado se o laboratório-alvo está no escopo da RDC 512 ou sob outra norma setorial.

### 3.2 Comunicação de perigos e FDS

- **[FATO]** Página oficial da NR-26 do Ministério do Trabalho e Emprego, atualizada em 02/06/2025, descreve classificação de produtos químicos segundo GHS e dever do fabricante ou fornecedor nacional de disponibilizar ficha para produto químico classificado como perigoso. Página e versão vinculada: https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/participacao-social/conselhos-e-orgaos-colegiados/comissao-tripartite-partitaria-permanente/normas-regulamentadora/normas-regulamentadoras-vigentes/norma-regulamentadora-no-26-nr-26 (acesso 29/09/2026).
- **[FATO]** A edição ABNT NBR 14725:2023 passa a denominar o documento FDS (Ficha com Dados de Segurança), em vez de FISPQ. Fonte primária sobre o status/nome: [NÃO ENCONTRADO] acesso ao texto integral ABNT não disponível nesta pesquisa. Há conteúdo secundário de fornecedor especializado que reporta edição em 03/07/2023 e fim de prazo de transição em julho/2025, mas não é fonte normativa primária e não foi tratado como base legal autônoma.
- [INFERÊNCIA] Para produto, convém guardar ficha recebida do fornecedor com identificação de produto/fabricante e data/versão, permitir substituição/rastreio e vincular ao químico certo. Repositório do cliente não garante a atualidade do documento. O LabCollector explicita que o cliente deve obter SDS.
- [PENDENTE-HUMANO] Validar requisitos documentais específicos e processo de revisão com profissional de segurança do trabalho/química; confirmar redação vigente da NR e norma ABNT diretamente antes de implementar requisito regulatório.

### 3.3 Produtos químicos controlados pela Polícia Federal

- **[FATO]** Portaria MJSP 240/2019 estabelece controle/fiscalização de produtos constantes de listas próprias. Fonte oficial PF: https://www.gov.br/pf/pt-br/assuntos/produtos-quimicos/legislacao/portaria-240.pdf (publicada em 14/03/2019; acesso 29/09/2026). A PF publica FAQ de cadastro/licença que menciona deveres aplicáveis a agentes/atividades controlados e envio mensal de mapa, inclusive quando não há movimento, conforme hipótese explicada no FAQ: https://www.gov.br/pf/pt-br/assuntos/produtos-quimicos/arquivos-siproquim2/duvidas-frequentes-cadastro-e-licenca.
- [INFERÊNCIA] Uma solução pode precisar identificar produtos sujeitos a controles e suportar registros pertinentes se esse segmento/atividade for alvo; isso requer regras atualizadas por substância, concentração, quantidade, atividade e exceções. Não basta um marcador genérico.
- [NÃO ENCONTRADO] Não foi mapeada a lista completa contra um catálogo de reagentes nem determinada a aplicabilidade ao negócio de Will/Lucas. Este documento não é parecer jurídico/regulatório.

## 4. Mercado, custos e disposição a pagar

- [NÃO ENCONTRADO] Número de laboratórios com estoque manual, valor anual perdido por vencimento, proporção que anexa FDS ou usa QR/barcode, custo de conferência, taxa de falta, valor de implantação e preço aceito.
- [FATO] UNILAB e Concent anunciam controle de estoque/reagentes para laboratórios; LabCollector e Quartzy anunciam soluções internacionais. Páginas comerciais não comprovam demanda, adoção, satisfação ou resultado financeiro.
- [ESTIMATIVA] Não calculada: sem definição do mercado/ICP, população, incidência e gasto comprovados. Nenhum cálculo a partir de número de laboratórios foi feito.
- [PENDENTE-HUMANO] Levantar inventário anonimizado de 1–2 laboratórios do mesmo segmento e examinar amostra de registros: quantos itens, lotes, vencimentos próximos, sem ficha vinculada, divergências físico-sistema, itens sem consumo e tempo para inventário. Entrevistar comprador para custo/alternativas.

## 5. Nota e revisão cética

- [FATO] A nota da ideia ID 01 permanece em branco na planilha. Não atribuí valor.
- [INFERÊNCIA] A hipótese genérica de “falta de concorrência” não se sustenta para controle de estoque/validade/FDS como categoria ampla. Pode haver lacuna em fluxo/localização/integração ou nicho particular, ainda não encontrada.
- **Riscos principais:**
  1. [INFERÊNCIA] Estoque, alertas, FDS e compras já aparecem em sistemas lab/LIS/ELN; produto separado pode duplicar dados e fluxo.
  2. [HIPÓTESE] Usuário pode não escanear etiqueta ou atualizar consumo no ponto de uso; inventário rapidamente desatualizado anula alertas.
  3. [INFERÊNCIA] FDS errada, antiga ou vinculada a reagente com composição/concentração diferente pode produzir falsa segurança. Armazenar documento não substitui avaliação profissional e controles físicos.
  4. [INFERÊNCIA] Gestão de produtos controlados aumenta complexidade e risco de erro se pretender automatizar obrigações oficiais sem atualização normativa e validação técnica.
  5. [NÃO ENCONTRADO] Custos e nível de integração requeridos por potenciais clientes.

## 6. Próximo teste humano

- **Hipótese:** em um segmento delimitado, existe perda/falha recorrente no inventário de reagentes que uma solução já usada não resolve e que tem custo superior ao custo operacional de atualizar estoque.
- **Participantes:** responsável por estoque/qualidade/segurança e comprador em laboratórios de um único segmento; incluir operadores que fazem baixa/retirada.
- **Teste:** entrevista sobre último vencimento/falta real e demonstração de registros atuais; percorrer uma retirada real e comparar cadastro com frascos/etiquetas, sem transferir dados identificáveis. Mostrar protótipo de entrada por lote, etiqueta escaneável e vínculo de documento; observar uso sem instruir excessivamente.
- **Métricas:** diferença entre estoque físico e registrado, lotes sem validade/documento, eventos de vencimento/falta, tempo de inventário e localização, baixas não registradas, horas de compra emergencial e custo observado.
- **Critério de continuar/parar:** Will/Lucas devem definir antes de entrevistas; não estipulei limiares sem base.
- **Pendente técnico/regulatório:** revisar política de documentos, histórico de versão, leitores/etiquetas e regras de produtos controlados com especialistas e escopo definido.

## 7. Fontes e log de verificação

- **S01 — UNILAB módulo Controle de Estoque:** https://www.unilab.com.br/solucoes/controle-de-estoque/ — página oficial acessada em 29/09/2026; oferta/módulo, detalhes de preço não publicados na página consultada.
- **S02 — UNILAB conteúdo de estoque:** https://www.unilab.com.br/materiais-educativos/controle-de-estoque-para-laboratorios/ — artigo do fornecedor, publicado 24/08/2026; contém alegações sobre perdas/vencimentos e funcionalidade de módulo; não é pesquisa independente.
- **S03 — Concent:** https://concentsistemas.com.br/ — página oficial acessada 29/09/2026; lote, validade e gestão de reagentes declarados; preço não encontrado.
- **S04 — LabCollector Analytical Laboratories:** https://labcollector.com/solutions/industries/analytical-laboratories/ — página oficial acessada 29/09/2026; alertas de estoque/vencimento e FIFO declarados.
- **S05 — LabCollector MSDS & Safety:** https://labcollector.com/solutions/applications/msds-safety/ — página oficial acessada 29/09/2026; cadastro e documentos de segurança; o fornecedor explicita que usuário é responsável por obter SDS.
- **S06 — Quartzy Inventory:** https://www.quartzy.com/tour/inventory — página oficial acessada 29/09/2026; inventário, alertas, SDS e códigos de barras declarados; preço não capturado.
- **S07 — Anvisa RDC 512/2021:** https://bvsms.saude.gov.br/bvs/saudelegis/anvisa/2020/rdc0512_27_05_2021.pdf — acesso 29/09/2026; artigos 35–38 sobre materiais de referência, reagentes, validade, rotulagem e rastreabilidade.
- **S08 — MTE NR-26:** https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/participacao-social/conselhos-e-orgaos-colegiados/comissao-tripartite-partitaria-permanente/normas-regulamentadora/normas-regulamentadoras-vigentes/norma-regulamentadora-no-26-nr-26 — atualização da página 02/06/2025, acesso 29/09/2026; informação oficial sobre classificação GHS e ficha para químico perigoso.
- **S09 — Polícia Federal Portaria 240/2019:** https://www.gov.br/pf/pt-br/assuntos/produtos-quimicos/legislacao/portaria-240.pdf — acesso 29/09/2026; produtos listados e controle PF.
- **S10 — PF FAQ:** https://www.gov.br/pf/pt-br/assuntos/produtos-quimicos/arquivos-siproquim2/duvidas-frequentes-cadastro-e-licenca — acesso 29/09/2026; requisitos explicativos de cadastro/licença/mapa para situações aplicáveis.
- **S11 — ABNT NBR 14725:2023:** norma integral não acessada; referência ao nome FDS e período de transição não apoiada como conclusão legal independente nesta pesquisa. Fontes secundárias consultadas: https://www.lisam.com/pt-br/documentos/ficha-com-dados-de-seguranca-fds-abnt-nbr-147252023/ (página do fornecedor, atualizada 15/09/2026); não substitui norma ABNT.

| Data local | Fase/item | Ação/resultado | Fonte | Classificação | Pendência |
|---|---|---|---|---|---|
| 29/09/2026 | ID01 concorrência BR | UNILAB e Concent consultados; funções próximas declaradas | S01–S03 | [FATO] de oferta publicada; alegações comerciais | Demo e preço/cobertura exatos |
| 29/09/2026 | ID01 concorrência global | LabCollector e Quartzy consultados; estoque, expiração e SDS anunciados | S04–S06 | [FATO] de oferta publicada; não prova desempenho | Adequação Brasil/idioma/integrações/preço |
| 29/09/2026 | ID01 regulação laboratorial | RDC 512 consultada; arts. 35–38 têm controles explícitos de reagentes no escopo da norma | S07 | [FATO] do texto oficial; escopo dependente | Definir setor/norma aplicável |
| 29/09/2026 | ID01 segurança química | MTE NR-26 e PF Portaria/FAQ consultadas; obrigações variam por perigo, lista, atividade e contexto | S08–S10 | [FATO] oficial; aplicação ao produto não avaliada | Consultar profissional e norma ABNT integral |
| 29/09/2026 | ID01 dor/mercado/preço | Sem dados primários ou preço comparável validado | S01–S11 | [NÃO ENCONTRADO]/[PENDENTE-HUMANO] | Entrevistas e observação do inventário |

## Correção de inventário da planilha — 29/09/2026

**Errata:** a afirmação anterior de que a nota da ID 01 estava em branco estava incorreta. A conferência direta da cópia `pesquisa-ideias-will-lucas_v2.xlsx`, aba Análise, linha 14, identificou a avaliação preexistente de **4,00**, posição **9**. Trata-se da hipótese inicial da planilha, não de nota nova nem de evidência de mercado. O texto acima é preservado como histórico e esta correção o substitui quanto ao estado da planilha. Nenhuma célula foi alterada.
