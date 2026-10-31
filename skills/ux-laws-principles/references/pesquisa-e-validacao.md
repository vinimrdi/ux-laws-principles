# Pesquisa, avaliação e validação de UX

Escolha métodos pela pergunta. Nenhum método isolado explica toda a experiência.

| Pergunta | Métodos |
|---|---|
| A pessoa conclui a tarefa? | Teste de usabilidade, análise de tarefas |
| Por que há dificuldade? | Entrevistas, observação contextual, suporte |
| Encontra informação? | Tree testing, first-click testing, análise de busca |
| Como agrupa conceitos? | Card sorting e entrevistas |
| O que ocorre em escala? | Analytics, funis e coortes |
| Qual variante funciona melhor? | Experimento controlado |
| A interface é acessível? | Verificação automática e avaliação manual |
| É rápida? | Dados de campo, laboratório, rede e dispositivos |
| O que a pessoa espera? | Entrevistas, testes de conceito e protótipos |

## Teste de usabilidade
**Referências:** [Nielsen & Molich (1990), avaliação heurística](https://doi.org/10.1145/97243.97281) é uma técnica distinta do teste com participantes; Nielsen Norman Group, [Discount Usability](https://www.nngroup.com/articles/web-discount-usability/); ISO 9241-210:2019, [design centrado no ser humano](https://www.iso.org/standard/77520.html). Para planejamento e moderação, consulte Rubin & Chisnell, *Handbook of Usability Testing* (2ª ed., 2008).
- **O quê:** observar pessoas representativas tentando tarefas relevantes.
- **Por quê:** revela problemas de compreensão, execução, feedback e recuperação.
- **Para quem:** usuários atuais ou potenciais representativos.
- **Onde:** protótipos, interfaces existentes e fluxos críticos.
- **Quando:** antes de decisões importantes, após mudanças ou diante de dificuldades.
- **Como:** defina tarefas e critérios; peça objetivos reais; observe conclusão, erros e hesitação; evite perguntas direcionadas; registre limitações.
- **Medidas:** sucesso, tempo, erros, pedidos de ajuda, desvios e confiança.

## Entrevistas e pesquisa qualitativa
**Referência metodológica:** ISO 9241-210:2019, [Human-centred design for interactive systems](https://www.iso.org/standard/77520.html). O padrão descreve atividades de compreensão e especificação do contexto de uso; não prescreve um roteiro único de entrevista.
Compreenda contexto, motivações, linguagem, alternativas e expectativas. Pergunte sobre experiências reais e recentes. Evite conduzir respostas e não generalize uma opinião isolada.

## Analytics
**Referência complementar:** Rodden, Hutchinson & Fu (2010), [Measuring the User Experience on a Large Scale](https://doi.org/10.1145/1753326.1753687), para métricas centradas no usuário em aplicações web. Analytics observacional não estabelece causalidade por si só.
- **O quê:** dados agregados de eventos e comportamento.
- **Por quê:** revelam frequência, sequência e distribuição.
- **Para quem:** produto e negócio.
- **Onde:** funis, eventos, coortes, busca e erros.
- **Quando:** perguntas sobre volume, frequência e abandono.
- **Como:** defina eventos significativos, valide instrumentação, segmente contexto, respeite privacidade e combine com pesquisa.
Analytics mostra o que ocorreu, não necessariamente por quê.

## Experimentos e testes A/B
**Referências:** Kohavi, Tang & Xu, *Trustworthy Online Controlled Experiments* (Cambridge University Press, 2020), referência metodológica para experimentação online; [Kohavi et al. (2013), Online Controlled Experiments at Large Scale](https://doi.org/10.1145/2433396.2433413).
- **O quê:** comparação controlada entre variantes.
- **Por quê:** estima efeitos sob condições comparáveis.
- **Para quem:** produtos com volume e instrumentação adequados.
- **Onde:** conteúdo, fluxos e interfaces.
- **Quando:** hipótese clara e risco aceitável.
- **Como:** hipótese falsificável; métrica primária e guardrails; amostra e duração; randomização; monitoramento de efeitos adversos.

## Avaliação heurística
**Referências:** [Nielsen & Molich (1990)](https://doi.org/10.1145/97243.97281), trabalho seminal sobre avaliação heurística; [Nielsen, 10 Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/).
- **O quê:** inspeção especializada baseada em heurísticas.
- **Por quê:** encontra problemas potenciais com rapidez.
- **Para quem:** design, produto e qualidade.
- **Onde:** telas, fluxos e protótipos.
- **Quando:** descoberta e revisão contínua.
- **Como:** inspecione tarefas; registre problema, heurística e impacto; estime severidade com critérios. Ausência de achados não prova ausência de problemas.

## Acessibilidade
**Referências normativas:** [W3C, WCAG 2.2](https://www.w3.org/TR/WCAG22/) e [W3C WAI, WCAG Overview](https://www.w3.org/WAI/standards-guidelines/wcag/). Use avaliação manual e com tecnologias assistivas; ferramentas automáticas cobrem apenas parte dos critérios.
Combine automação, teclado, foco visível, leitor de tela, zoom, reflow, contraste, redução de movimento, rótulos e alternativas a gestos. Ferramenta automática não comprova conformidade WCAG sozinha.

## Nível de evidência
- **Direta:** comportamento observado, dado validado, bug reproduzível ou medição.
- **Corroborada:** sinais independentes sustentam a conclusão.
- **Inspeção especializada:** problema plausível ainda sem validação com usuários.
- **Hipótese:** explicação ou solução a testar.

Informe amostra, método, plataforma, data e limitações. Não infle confiança. Defina sucesso antes do redesign: conclusão, menos erros, encontrabilidade, recuperação, acessibilidade e abandono por custos inesperados. Combine métricas de negócio com resultados do usuário.
