# Leis e efeitos de UX

Leis de UX são tendências comportamentais ou perceptivas, não fórmulas determinísticas. Para cada conceito: **O quê** (definição), **Por quê** (mecanismo), **Para quem** (público), **Onde** (aplicação), **Quando** (condição) e **Como** (decisão prática).

## Lei de Fitts
- **O quê:** tempo de seleção depende do tamanho do alvo e da distância; alvos maiores e próximos tendem a ser mais fáceis.
- **Por quê:** alvos pequenos exigem precisão motora.
- **Para quem:** todos, sobretudo usuários touch e pessoas com limitações motoras.
- **Onde:** botões, links, ícones, menus e controles.
- **Quando:** erros de toque, cliques imprecisos ou alvos difíceis de alcançar.
- **Como:** aumente área clicável, espaçamento e alcance confortável; separe ações destrutivas.
- **Limite:** não significa que tudo deve ser enorme; hierarquia e critérios de acessibilidade também importam.

## Lei de Hick-Hyman
- **O quê:** o tempo de decisão tende a crescer com o número de alternativas plausíveis e a incerteza entre elas.
- **Por quê:** comparar opções exige atenção e redução de incerteza.
- **Para quem:** iniciantes, usuários com baixa familiaridade ou sob pressão.
- **Onde:** menus, navegação, filtros, planos, onboarding e configurações.
- **Quando:** escolha demorada, alternativas semelhantes ou abandono.
- **Como:** agrupe por significado, diferencie opções, use padrões seguros e revele complexidade gradualmente.
- **Limite:** não reduza toda lista; especialistas podem preferir mais opções visíveis.

## Lei de Jakob
- **O quê:** usuários trazem expectativas aprendidas em outros produtos.
- **Por quê:** convenções familiares reduzem aprendizagem e surpresa.
- **Para quem:** novos usuários e pessoas que alternam entre produtos.
- **Onde:** navegação, busca, login, formulários e controles comuns.
- **Quando:** padrões novos geram hesitação ou erros.
- **Como:** respeite convenções úteis e ensine inovações no ponto de uso.
- **Limite:** não significa copiar concorrentes nem perpetuar padrões ruins.

## Lei de Tesler
- **O quê:** a complexidade inerente a um sistema não desaparece; é distribuída entre sistema e usuário.
- **Por quê:** regras e decisões do domínio continuam existindo.
- **Para quem:** usuários de processos complexos, SaaS e ferramentas profissionais.
- **Onde:** cadastro, importação, configuração, automação e aprovação.
- **Quando:** o usuário enfrenta detalhes técnicos que o sistema poderia tratar.
- **Como:** automatize repetição, solicite dados no momento certo e exponha decisões importantes.
- **Limite:** automação pode retirar transparência e controle.

## Lei de Postel (princípio de robustez)
- **O quê:** princípio de engenharia: ser conservador no que se envia e liberal no que se aceita.
- **Por quê:** sistemas precisam lidar com variações de dados.
- **Para quem:** equipes de produto/engenharia e usuários que inserem dados.
- **Onde:** campos, datas, telefones, importações e integrações.
- **Quando:** variações benignas causam falhas.
- **Como:** aceite variações seguras, normalize, valide e produza saídas consistentes.
- **Limite:** permissividade excessiva gera ambiguidade e riscos; não é lei universal de UX.

## Lei de Prägnanz (boa forma)
- **O quê:** percepção tende a organizar estímulos ambíguos em formas simples e estáveis.
- **Por quê:** estruturas coerentes são mais fáceis de interpretar.
- **Para quem:** todos, especialmente em interfaces densas.
- **Onde:** composição, dashboards, agrupamentos e gráficos.
- **Quando:** hierarquia fraca ou excesso de competição visual.
- **Como:** use alinhamento, agrupamento e hierarquia; remova decoração que compete.
- **Limite:** simplicidade não é ausência de informação.

## Lei de Miller e memória de trabalho
- **O quê:** pesquisa clássica sobre memória imediata; “7 ± 2” não é limite universal de itens em uma interface.
- **Por quê:** memória de trabalho é limitada e varia por tarefa, conhecimento e agrupamento.
- **Para quem:** pessoas diante de informação nova ou tarefas longas.
- **Onde:** formulários, menus, tabelas e onboarding.
- **Quando:** usuários esquecem dados entre telas ou perdem contexto.
- **Como:** agrupe, mantenha instruções junto à ação, mostre resumos e permita retomar.
- **Limite:** não limite menus a sete itens.

## Reconhecimento em vez de recordação
- **O quê:** reconhecer opções visíveis costuma exigir menos esforço que lembrá-las sem pistas.
- **Por quê:** pistas ajudam a identificar alternativas.
- **Para quem:** iniciantes e usuários ocasionais.
- **Onde:** menus, filtros, formulários, histórico e configurações.
- **Quando:** a pessoa esquece códigos, requisitos ou opções.
- **Como:** mostre opções, exemplos, escolhas recentes e resumos.
- **Limite:** não exponha tantas opções que crie sobrecarga.

## Efeito de posição serial
- **O quê:** itens no início e no fim podem ser mais lembrados.
- **Por quê:** primazia e recência influenciam memória.
- **Para quem:** pessoas que percorrem listas e sequências.
- **Onde:** menus, onboarding, listas e apresentações.
- **Quando:** a ordem influencia lembrança.
- **Como:** dê posição clara a informações críticas e reforce pontos em resumos.
- **Limite:** contexto e relevância podem dominar o efeito.

## Efeito Von Restorff (isolamento)
- **O quê:** elemento diferente do conjunto pode receber mais atenção e ser lembrado.
- **Por quê:** contraste atrai atenção relativa.
- **Para quem:** usuários que precisam identificar prioridade.
- **Onde:** CTA, alertas, recomendações e estados selecionados.
- **Quando:** há prioridade real sem hierarquia suficiente.
- **Como:** reserve destaque para prioridades e justifique recomendações.
- **Limite:** se tudo se destaca, nada se destaca; não induza escolhas.

## Efeito Zeigarnik
- **O quê:** tarefas incompletas podem permanecer cognitivamente salientes em certos contextos.
- **Por quê:** metas pendentes continuam ocupando atenção.
- **Para quem:** usuários em tarefas longas ou interrompíveis.
- **Onde:** onboarding, formulários, projetos e rascunhos.
- **Quando:** a pessoa precisa pausar e retomar.
- **Como:** salve, mostre o que falta e permita retomar.
- **Limite:** não fabrique ansiedade ou pressão; evidência varia.

## Regra do pico-fim
- **O quê:** avaliação retrospectiva pode ser influenciada por momentos intensos e pelo encerramento.
- **Por quê:** memória não é média perfeita de cada instante.
- **Para quem:** usuários que avaliam jornadas, compras e suporte.
- **Onde:** checkout, suporte, onboarding e conclusão.
- **Quando:** é preciso encerrar tarefa ou recuperar experiência difícil.
- **Como:** confirme resultados, explique próximos passos e preserve trabalho.
- **Limite:** final agradável não compensa jornada ruim.

## Limiar de Doherty
- **O quê:** respostas rápidas favorecem continuidade; 400 ms é referência histórica, não orçamento universal moderno.
- **Por quê:** atrasos sem feedback geram incerteza.
- **Para quem:** usuários em tarefas frequentes ou sequenciais.
- **Onde:** busca, salvamento, geração e navegação.
- **Quando:** interface parece congelada ou ações são repetidas.
- **Como:** feedback imediato, progresso real e otimização da latência.
- **Limite:** feedback não torna operação lenta; meça.

## Efeito de gradiente de objetivo
- **O quê:** motivação pode aumentar quando a pessoa percebe proximidade do objetivo.
- **Por quê:** progresso torna conclusão mais concreta.
- **Para quem:** usuários em tarefas com etapas claras.
- **Onde:** onboarding, configuração, cursos e publicação.
- **Quando:** tarefa longa e progresso mensurável.
- **Como:** mostre etapas reais, marcos e pendências.
- **Limite:** não invente progresso nem pressione.

## Efeito estético-usabilidade
- **O quê:** interface atraente pode ser percebida como mais fácil mesmo sem ganho objetivo de usabilidade.
- **Por quê:** estética influencia expectativa e confiança.
- **Para quem:** todos, especialmente em primeiras impressões.
- **Onde:** landing pages, onboarding e dashboards.
- **Quando:** percepção de qualidade afeta confiança.
- **Como:** cuide de hierarquia e legibilidade; avalie estética e tarefa separadamente.
- **Limite:** beleza não prova usabilidade.

## Princípio de Pareto
- **O quê:** padrão de distribuição desigual popularizado como 80/20.
- **Por quê:** impactos podem se concentrar em poucos fatores.
- **Para quem:** equipes que priorizam problemas e recursos.
- **Onde:** analytics, suporte e backlog.
- **Quando:** há dados para identificar concentração.
- **Como:** analise distribuição real; priorize frequência, gravidade e valor.
- **Limite:** não assuma proporção fixa; não é lei de UX.

## Sobrecarga de escolha
- **O quê:** muitas alternativas podem dificultar decisões em determinadas condições.
- **Por quê:** comparar exige atenção e critérios.
- **Para quem:** pessoas com baixa familiaridade ou critérios pouco claros.
- **Onde:** planos, catálogos, filtros e configurações.
- **Quando:** usuário não consegue comparar ou justificar escolha.
- **Como:** organize, destaque diferenças e permita comparação.
- **Limite:** variedade pode ser valorizada; resultados dependem do contexto.

## Efeito de dotação
- **O quê:** pessoas podem valorizar mais algo que sentem possuir.
- **Por quê:** propriedade psicológica e aversão à perda.
- **Para quem:** usuários que criam e personalizam ativos digitais.
- **Onde:** projetos, bibliotecas e coleções.
- **Quando:** propriedade percebida favorece cuidado.
- **Como:** permita personalizar, exportar e excluir.
- **Limite:** não dificulte cancelamento ou exclusão.

## Efeito de custo afundado
- **O quê:** investimento irrecuperável pode influenciar decisões futuras.
- **Por quê:** pessoas tentam justificar esforço passado.
- **Para quem:** usuários em fluxos longos, assinaturas e compras.
- **Onde:** onboarding, renovação e cancelamento.
- **Quando:** esforço passado é usado para pressionar continuidade.
- **Como:** permita sair sem penalidade artificial e explique perdas reais.
- **Limite:** não explore o efeito para retenção.

Nem todo conceito popular chamado de “lei” é lei científica. Identifique se é tendência empírica, efeito psicológico, princípio, heurística, modelo ou metáfora. Não invente autoria ou data.
