---
slug: pt-br/real-world-development/cloud
title: "GitHub Copilot cloud agent"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

O **[GitHub Copilot cloud agent](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)** permite que o GitHub Copilot trabalhe de forma assíncrona na nuvem. Você atribui uma tarefa no GitHub, e o cloud agent a executa em segundo plano — explorando o repositório, fazendo alterações e abrindo um pull request — enquanto você fica livre para cuidar de outras atividades.

Nestes exercícios, você adicionará instruções personalizadas para o cloud agent seguir e, em seguida, atribuirá uma issue do GitHub para que ele implemente o trabalho. Você revisará e usará agentes personalizados para orientar a abordagem, monitorará e conduzirá sessões pelo painel de agentes e, por fim, revisará os pull requests abertos pelo agente e iterará sobre os resultados.

## Exercícios

| Exercício | Tópico | Descrição |
|----------|-------|-------------|
| [0. Pré-requisitos][ex0] | Configuração | Crie o repositório e o Codespace |
| [1. Instruções personalizadas][ex1] | Contexto | Adicione instruções personalizadas para o cloud agent seguir |
| [2. Cloud Agent][ex2] | Agente assíncrono | Atribua issues ao GitHub Copilot cloud agent |
| [3. Agentes personalizados][ex3] | Agentes especializados | Revise e use agentes personalizados |
| [4. Gerenciamento de agentes][ex4] | Monitoramento | Monitore e oriente sessões de agentes |
| [5. Iteração][ex5] | Revisão | Revise pull requests, itere sobre o trabalho do Copilot e escolha os próximos passos |

## Pré-requisitos

Antes de participar deste workshop, verifique se você tem:

- [ ] Uma conta do GitHub com um plano **Copilot Student, Pro, Pro+, Business ou Enterprise** ativo
- [ ] O GitHub Copilot cloud agent habilitado para sua conta ou organização

> [!TIP]
> Não tem um plano pago? Estudantes verificados podem obter o GitHub Copilot gratuitamente pelo [GitHub Education][callout-student-plan-education]. O plano **Copilot Student** inclui o agente, MCP, revisão de código e os recursos do Copilot CLI usados neste workshop — assim, você pode concluir todos os percursos.

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> O cloud agent está disponível nos planos **Copilot Student, Pro, Pro+, Business e Enterprise** — em todos, exceto no Copilot Free. No Copilot Business ou Enterprise, um administrador precisa habilitá-lo para a organização.

> [!NOTE]
> Este percurso não aborda MCP. Para explorar o uso de servidores MCP com o Copilot, consulte o [percurso de CLI][cli] ou o [percurso de VS Code][vscode].

## Comece

**[Comece pelo exercício 0: Pré-requisitos →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
[cli]: ../cli/
[vscode]: ../vscode/
