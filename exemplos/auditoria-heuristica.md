# Exemplo: auditoria heurística de um formulário

> Exemplo didático. O cenário é hipotético e não representa pesquisa com usuários reais.

## Contexto

Um formulário de cadastro pede nome, e-mail, telefone, CPF, endereço e senha em uma única tela. Os erros aparecem apenas após o envio. O botão principal usa o rótulo "Continuar".

## Achados

### 1. Erros apresentados somente após o envio

- **Observação:** a pessoa precisa submeter o formulário para descobrir campos inválidos.
- **Conceitos:** prevenção de erros; visibilidade do estado do sistema.
- **O Quê:** a interface não ajuda a evitar ou corrigir erros no momento adequado.
- **Por Quê:** erros tardios aumentam retrabalho e incerteza.
- **Para Quem:** todos, especialmente pessoas com baixa familiaridade digital ou tecnologias assistivas.
- **Onde:** campos e resumo de validação.
- **Quando:** sempre que a validação puder ocorrer com segurança durante a entrada.
- **Como:** validar no momento apropriado, associar mensagem ao campo, preservar valores e anunciar erros acessivelmente.
- **Confiança:** problema confirmado pela inspeção; impacto precisa ser validado.

### 2. Coleta de dados sem explicação

- **Observação:** CPF e telefone são solicitados sem explicar finalidade.
- **Conceitos:** correspondência com o mundo real, confiança e autonomia.
- **Recomendação:** explicar por que cada dado é necessário, distinguir campos obrigatórios e opcionais e evitar coleta sem finalidade.

### 3. Rótulo genérico no botão

- **Observação:** "Continuar" não explica o resultado imediato.
- **Recomendação:** usar rótulo que antecipe a ação, como "Criar conta", se esse for de fato o próximo passo.

## Como validar

- Testar com participantes representativos.
- Medir conclusão, erros, tempo e pedidos de ajuda.
- Verificar teclado, leitor de tela, foco, mensagens e preservação de dados.
- Comparar resultados antes e depois sem assumir que a mudança causará melhoria.
