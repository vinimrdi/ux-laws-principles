# Princípios, heurísticas e Gestalt em UX

## As 10 heurísticas de usabilidade de Jakob Nielsen

Heurísticas são princípios gerais de inspeção, não requisitos técnicos exatos nem fórmula de pontuação.

1. **Visibilidade do estado do sistema**
   - **O quê:** informar o que acontece por feedback oportuno.
   - **Por quê:** sem feedback, a pessoa não sabe se a ação foi recebida ou falhou.
   - **Para quem:** todos, sobretudo em operações demoradas.
   - **Onde:** carregamento, salvamento, upload, pagamento e navegação.
   - **Quando:** após ações ou mudanças de estado.
   - **Como:** estados claros, progresso real e confirmação.

2. **Correspondência com o mundo real**
   - **O quê:** linguagem e sequência compreensíveis ao público.
   - **Por quê:** reduz tradução mental.
   - **Para quem:** iniciantes e públicos não técnicos.
   - **Onde:** rótulos, formulários, relatórios e fluxos.
   - **Quando:** jargões confundem.
   - **Como:** vocabulário do público, unidades familiares e teste de compreensão.

3. **Controle e liberdade**
   - **O quê:** saídas, desfazer, voltar e corrigir.
   - **Por quê:** erros e mudanças de intenção são inevitáveis.
   - **Para quem:** todos, especialmente em ações irreversíveis.
   - **Onde:** modais, edição, checkout e exclusão.
   - **Quando:** ação acidental ou difícil de reverter.
   - **Como:** cancelar, voltar, desfazer, editar e preservar dados.

4. **Consistência e padrões**
   - **O quê:** elementos semelhantes devem ter linguagem e comportamento coerentes.
   - **Por quê:** reduz reaprendizado.
   - **Para quem:** iniciantes e recorrentes.
   - **Onde:** botões, ícones, navegação e campos.
   - **Quando:** mesma ação varia sem motivo.
   - **Como:** manter semântica e comportamento coerentes.

5. **Prevenção de erros**
   - **O quê:** evitar problemas antes de corrigi-los.
   - **Por quê:** prevenir custa menos esforço.
   - **Para quem:** todos, sobretudo em ações críticas.
   - **Onde:** formulários, pagamentos, permissões e exclusões.
   - **Quando:** erro previsível ou caro.
   - **Como:** formatos válidos, exemplos, validação contextual e confirmação.

6. **Reconhecimento em vez de memorização**
   - **O quê:** reduzir necessidade de lembrar informação entre telas.
   - **Por quê:** pistas visíveis diminuem carga de memória.
   - **Para quem:** iniciantes e usuários ocasionais.
   - **Onde:** menus, filtros, histórico e comparações.
   - **Quando:** usuário precisa recordar códigos ou dados.
   - **Como:** opções visíveis, exemplos e resumos.

7. **Flexibilidade e eficiência**
   - **O quê:** atender iniciantes e especialistas.
   - **Por quê:** experiência e frequência variam.
   - **Para quem:** públicos heterogêneos.
   - **Onde:** atalhos, comandos, filtros e ações em lote.
   - **Quando:** tarefas repetidas custam muito esforço.
   - **Como:** caminhos básicos claros e recursos avançados descobríveis.

8. **Estética e design minimalista**
   - **O quê:** informação irrelevante não deve competir com a importante.
   - **Por quê:** ruído dificulta prioridades.
   - **Para quem:** todos, especialmente em telas densas.
   - **Onde:** dashboards, formulários e relatórios.
   - **Quando:** decoração desvia atenção.
   - **Como:** remova o que não ajuda sem esconder contexto essencial.

9. **Reconhecer, diagnosticar e recuperar erros**
   - **O quê:** explicar problema e indicar recuperação.
   - **Por quê:** mensagens genéricas não orientam.
   - **Para quem:** todos, especialmente públicos não técnicos.
   - **Onde:** autenticação, pagamento, upload e integrações.
   - **Quando:** operação falha.
   - **Como:** diga o que ocorreu, o que foi preservado e como corrigir.

10. **Ajuda e documentação**
    - **O quê:** suporte fácil de encontrar, focado na tarefa.
    - **Por quê:** nem toda operação pode ser autoexplicativa.
    - **Para quem:** iniciantes e tarefas complexas.
    - **Onde:** ajuda contextual, FAQ e onboarding.
    - **Quando:** tarefa exige conhecimento específico.
    - **Como:** instruções curtas, exemplos e busca.

## Princípios de Don Norman
- **Descobribilidade:** perceber ações possíveis e onde executá-las. Use rótulos, estados e sinais claros.
- **Feedback:** comunicar resultado de uma ação de forma oportuna e proporcional.
- **Modelo conceitual:** representar de modo compreensível como o sistema funciona.
- **Affordances:** propriedades que possibilitam ações.
- **Signifiers:** sinais perceptíveis que indicam onde e como agir, como rótulos, ícones e handles.
- **Mapeamento:** relação entre controle e efeito; aproxime controle e objeto afetado.
- **Restrições:** limites físicos, lógicos, semânticos ou culturais que evitam ações inválidas; explique a restrição e ofereça alternativa.

Affordance e signifier não são sinônimos. Em interfaces digitais, os sinais ajudam a descobrir a possibilidade real de ação.

## Gestalt
- **Proximidade:** elementos próximos parecem relacionados. Aproxime rótulos, campos e ajuda.
- **Similaridade:** elementos semelhantes parecem da mesma categoria. Use padrões coerentes.
- **Região comum:** elementos na mesma área parecem agrupados. Evite contêineres aninhados demais.
- **Continuidade:** o olhar segue alinhamentos e sequências. Use grids e hierarquia.
- **Figura-fundo:** diferencie conteúdo e plano de fundo; preserve contraste.
- **Fechamento:** a percepção completa formas incompletas; não torne controles ambíguos.
- **Simetria e ordem:** equilíbrio pode ajudar, mas não force simetria.
- **Destino comum:** elementos que se movem juntos podem parecer relacionados; use movimento coordenado com significado.

## Princípios transversais
Consistência; revelação progressiva; padrões seguros e reversíveis; manipulação direta com alternativas acessíveis; tolerância a erros; agência do usuário; feedback proporcional; alinhamento entre aparência e comportamento.

## Acessibilidade: POUR da WCAG
- **Perceptível:** informação apresentada de formas que as pessoas consigam perceber.
- **Operável:** componentes e navegação utilizáveis, inclusive por teclado.
- **Compreensível:** conteúdo e funcionamento claros e previsíveis.
- **Robusto:** conteúdo interpretável por diferentes agentes, inclusive tecnologias assistivas.

WCAG 2.2 possui critérios testáveis e níveis A, AA e AAA. Verificação automática isolada não comprova conformidade. Avalie páginas completas e estados responsivos.

## Ética e autonomia
Mostre preços, renovação, taxas e consequências antes do compromisso. Mantenha cancelamento e controles acessíveis. Não fabrique escassez, prova social, progresso ou urgência. Evite custos ocultos, continuidade forçada e cancelamento obstrutivo. Otimize sucesso informado, não apenas cliques.
