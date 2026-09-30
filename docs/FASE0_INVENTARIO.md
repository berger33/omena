# Fase 0 — Inventário e integridade inicial

**Data:** 29/09/2026 (UTC)  
**Escopo desta etapa:** identificar os materiais fornecidos, o estado da triagem e os pré-requisitos para pesquisa. Ainda não é pesquisa de mercado nem validação de ideias.

## Arquivos encontrados

- `pesquisa-ideias-will-lucas_analisada.xlsx` — arquivo existente no repositório, preservado sem alteração.
- `pesquisa-ideias-will-lucas_v2.xlsx` — cópia de trabalho criada para cumprir a regra de não sobrescrever o original. Nesta Fase 0, é uma cópia byte a byte, sem pesquisa ou alterações nas abas.
- `docs/PROMPT_ORQUESTRADOR_PESQUISA_MERCADO.md` — protocolo de pesquisa presente no repositório.

## Estrutura identificada na planilha

A cópia de trabalho contém nove abas: **Análise**, **Como usar**, **Ideias**, **Critérios**, **Roteiro Lucas**, **Dores do Lucas**, **Matriz de validação**, **Plano de ação** e **Fontes**. A aba Ideias lista 16 propostas iniciais e duas linhas livres. A planilha também contém pesos/avaliações preliminares, roteiro de entrevista, exemplos demonstrativos, plano de validação e quatro referências externas listadas.

## Estado inicial — interpretação e limites

- [FATO] A aba Análise identifica suas notas como hipóteses analíticas, não como respostas de clientes.
- [FATO] A aba Como usar condiciona a validade da pontuação à conversa com Lucas e à pesquisa de mesa; as notas iniciais, portanto, não são evidência de dor, compra ou mercado.
- [FATO] A aba Dores do Lucas contém uma linha explicitamente marcada como exemplo. Ela não foi tratada como relato real.
- [FATO] A planilha contém quatro linhas de referência na aba Fontes (cinco URLs, pois cannabis tem duas). No momento da Fase 0, as URLs estavam apenas inventariadas. Na Fase 1, as cinco URLs foram abertas e tiveram o resultado documentado em `docs/FASE1_VERIFICACAO_FONTES_INICIAIS.md`; isso não significa que os PDFs/normas tenham sido integralmente lidos nem valida afirmações de mercado.
- [NÃO ENCONTRADO] Não há no repositório registros de entrevista, respostas de clientes, vendas, pilotos, testes comerciais, custos calculados ou dados primários validados.
- [NÃO ENCONTRADO] O arquivo original com o nome exato `pesquisa-ideias-will-lucas_v2.xlsx` não estava presente. Foi criado como cópia do arquivo `..._analisada.xlsx`; isso resolve a necessidade operacional de manter cópia de trabalho, mas não confirma que o arquivo analisado seja a versão-base original pretendida pelos autores.

## Integridade e pendências técnicas

- [FATO] O arquivo de origem não foi editado nem sobrescrito.
- [FATO] O ambiente não tem `openpyxl` nem LibreOffice/soffice disponíveis nesta execução; por isso não foi possível recalcular a pasta de trabalho nem verificar o resultado visual das fórmulas no mecanismo do Excel/LibreOffice. As fórmulas, validações e formatação da cópia não foram intencionalmente modificadas.
- [FATO] Will confirmou que `..._analisada.xlsx` é o arquivo-base correto para a cópia de trabalho `..._v2.xlsx`. A pendência de identificação da base foi resolvida em 29/09/2026.
- [PENDENTE-HUMANO] Validar com Will/Lucas o contexto, as competências, o orçamento, o acesso a potenciais clientes e os critérios de recursos disponíveis antes de avaliar viabilidade ou gerar ideias novas.

## Próximos passos da pesquisa

1. Conferir individualmente as quatro fontes já citadas na planilha, abrindo os documentos originais e registrando conteúdo, data, escopo e limitações; corrigir ou marcar como não verificadas as referências inadequadas.
2. Definir, com os responsáveis, geografia, perfil de cliente, restrições, capacidade técnica/comercial e limite de custo/tempo para validação.
3. Só então iniciar a pesquisa documental das ideias existentes. Não recalcular notas nem promover novas ideias sem evidência.

## Log de auditoria

| Data (UTC) | Fase | Item | Ação/resultado | Fonte | Classificação | Confiança | Pendência humana / próximo passo |
|---|---|---|---|---|---|---|---|
| 29/09/2026 | 0 | Repositório | Inventariados prompt, planilha e abas; original preservado e cópia de trabalho criada | Arquivos locais do repositório; leitura de estrutura XLSX | [FATO] | Alta para inventário local | Confirmar versão-base com os responsáveis |
| 29/09/2026 | 0 | Evidências | Identificada distinção da planilha entre notas preliminares e evidência de clientes; exemplos não tratados como dados reais | Abas Análise, Como usar e Dores do Lucas | [FATO] | Alta para conteúdo do arquivo | Nenhuma conclusão sobre realidade de mercado |
| 29/09/2026 | 0 | Fontes citadas | Quatro URLs listadas, ainda não abertas/verificadas | Aba Fontes | [FATO] quanto à presença; [NÃO ENCONTRADO] quanto à verificação | Alta para presença, insuficiente como evidência | Abrir fontes originais e registrar cadeia de evidência |
| 29/09/2026 | 0 | Fórmulas e recálculo | Não foi possível recalcular/verificar erros no Excel/LibreOffice neste ambiente | Disponibilidade de ferramentas local | [FATO] | Alta | Usar ambiente compatível antes de qualquer edição de fórmulas |
| 29/09/2026 | 0 | Identificação da base | Will confirmou que `..._analisada.xlsx` é o arquivo-base correto; mantida cópia de trabalho `_v2.xlsx` | Confirmação do usuário nesta conversa | [FATO] | Alta | Resolvido |
