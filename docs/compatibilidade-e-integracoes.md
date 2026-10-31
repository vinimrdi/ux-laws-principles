# Compatibilidade e integrações com ferramentas de IA

## Objetivo

Esta página explica como utilizar a metodologia Leis de UX em diferentes assistentes, agentes de programação e construtores de produtos digitais.

**Compatibilidade não é binária.** Uma ferramenta pode executar Agent Skills nativamente, carregar Markdown como contexto ou aceitar instruções específicas sem reconhecer o formato de skill. A disponibilidade pode mudar conforme plano, versão, interface, extensão e configuração.

Não declare suporte nativo sem confirmação na documentação oficial da ferramenta.

## Categorias de integração

| Categoria | O que significa | O que esperar |
|---|---|---|
| **Nativa** | A ferramenta reconhece e carrega o formato de skill diretamente. | Pode descobrir e invocar a skill conforme seu mecanismo. |
| **Adaptada** | A ferramenta tem mecanismo próprio de regras, agentes ou instruções. | É necessário converter ou referenciar a metodologia nesse mecanismo. |
| **Contextual** | A ferramenta aceita arquivos ou texto como contexto. | O modelo pode consultar o conteúdo durante a conversa, sem instalação persistente. |

## Matriz de plataformas

A classificação abaixo é uma orientação operacional. Confirme a documentação e a versão atuais antes de distribuir instruções de instalação.

| Plataforma | Forma recomendada | Categoria inicial |
|---|---|---|
| Claude Code | Instalar a pasta da skill no mecanismo de skills suportado pelo Claude Code. | Nativa, quando o formato e a versão forem reconhecidos. |
| OpenAI Codex | Disponibilizar a pasta da skill no diretório de skills reconhecido pelo Codex. | Nativa, quando habilitada no ambiente. |
| Lovable | Adicionar a documentação como contexto do projeto e usar o guia específico abaixo. | Adaptada / contextual. |
| Cursor | Referenciar os arquivos nas regras e no contexto do agente; verificar suporte a Agent Skills na versão utilizada. | Adaptada / contextual. |
| GitHub Copilot | Usar instruções e arquivos de contexto suportados pelo ambiente Copilot; verificar suporte a skills na versão utilizada. | Adaptada / contextual. |
| ChatGPT | Anexar os arquivos, configurar instruções de um GPT ou usar ambiente de desenvolvimento compatível. | Contextual; varia por produto. |
| Gemini | Fornecer os arquivos como contexto ou usar o mecanismo de extensões/instruções do ambiente Gemini utilizado. | Contextual / adaptada. |
| Claude Desktop | Anexar ou disponibilizar os arquivos por recursos de contexto suportados. | Contextual / adaptada. |
| Windsurf, Cline, Roo Code e OpenCode | Verificar o mecanismo de regras, contexto e skills da versão instalada. | Adaptada / contextual. |

Esta tabela não substitui a documentação oficial dos fornecedores. A ausência de classificação nativa não impede o uso do conteúdo.

## Estrutura da skill

A skill principal está em `skills/ux-laws-principles/SKILL.md`. As referências são arquivos Markdown separados para que agentes possam consultar apenas o conteúdo necessário.

Ao integrar em outro ambiente, preserve:
- O arquivo principal e seu frontmatter.
- Os caminhos relativos para as referências.
- O método O Quê, Por Quê, Para Quem, Onde, Quando e Como.
- As regras de rigor, evidência, acessibilidade e ética.

Se a ferramenta não reconhecer skills, forneça a pasta completa como contexto e instrua o agente a consultar o arquivo principal antes de avaliar ou propor mudanças.

## Integração com Lovable

O Lovable é prioritário para este projeto porque permite criar sites, dashboards, plataformas e aplicações com assistência de IA. O uso recomendado é como metodologia de análise e decisão durante o desenvolvimento, não como autorização para alterar código indiscriminadamente.

### Preparação

1. Disponibilize a documentação no contexto do projeto, anexando os arquivos relevantes ou copiando o conteúdo necessário para as instruções do projeto.
2. Mantenha o design system, tokens, componentes e decisões aprovadas como fonte de verdade.
3. Peça primeiro uma auditoria somente de leitura.
4. Solicite implementação apenas após revisar os achados e aprovar o escopo.
5. Faça QA e valide a experiência em dispositivos e fluxos relevantes.

### Prompt de auditoria somente leitura

```text
Utilize a metodologia Leis de UX como referência para auditar esta interface.

Analise os fluxos e componentes considerando o objetivo do usuário, a tarefa e o contexto. Identifique apenas problemas observáveis ou hipóteses claramente classificadas.

Para cada achado, apresente:
1. O que foi observado.
2. Evidência ou limitação da inspeção.
3. Lei, efeito, princípio, heurística ou modelo relacionado.
4. O Quê, Por Quê, Para Quem, Onde, Quando e Como.
5. Impacto provável para usuário e produto.
6. Trade-offs.
7. Recomendação e forma de validação.
8. Nível de confiança: confirmado, provável ou hipótese.

Não altere arquivos, código, banco de dados, configurações ou design system. Não aplique migrações, não publique e não execute operações externas. Preserve as decisões visuais e técnicas já aprovadas. Entregue primeiro o diagnóstico.
```

### Prompt de implementação após aprovação

```text
Implemente somente os achados aprovados da auditoria Leis de UX.

Respeite o escopo autorizado e preserve o design system, tokens, componentes, nomenclaturas e decisões existentes. Antes de alterar uma estrutura compartilhada, identifique o impacto. Não faça refatorações ou melhorias adicionais fora do escopo.

Para cada mudança, explique o problema corrigido e o conceito de UX aplicado. Não altere banco de dados, secrets, integrações pagas ou publique sem autorização explícita. Ao final, informe arquivos alterados, testes executados, limitações e pontos que exigem QA visual.
```

### Prompt para revisar uma tela nova

```text
Antes de implementar esta tela, use a metodologia Leis de UX para avaliar a arquitetura da informação, hierarquia, compreensão, estados, acessibilidade e fluxo da tarefa.

Apresente uma proposta estruturada e os trade-offs. Não invente necessidades de usuários nem trate leis de UX como regras determinísticas. Preserve os padrões existentes do produto e aguarde aprovação antes de implementar.
```

### Limites importantes no Lovable

- A documentação não substitui pesquisa com usuários nem testes reais.
- O agente pode não carregar automaticamente todos os arquivos; indique explicitamente o caminho da skill e das referências.
- Não presuma que o modelo tenha acesso ao repositório público em toda sessão.
- Não permita que uma auditoria se transforme em refatoração não solicitada.
- Confirme suporte atual a recursos específicos na documentação oficial do Lovable.

## Integração com Claude Code, Codex e agentes de programação

Quando o ambiente suportar Agent Skills, disponibilize a pasta `skills/ux-laws-principles` no local reconhecido pelo agente. Preserve os caminhos relativos das referências. Verifique a documentação oficial do produto para determinar o diretório, escopo global ou por projeto e política de descoberta.

Quando não houver suporte direto, use o arquivo `SKILL.md` como instrução principal e mantenha as referências acessíveis no contexto do projeto.

## Manutenção desta matriz

A compatibilidade deve ser revista quando:
- Um fornecedor anunciar suporte a Agent Skills.
- O formato ou frontmatter mudar.
- O mecanismo de instalação for alterado.
- Uma integração for testada de ponta a ponta.

Registre data, versão da ferramenta e evidência antes de promover uma integração de contextual para nativa.
