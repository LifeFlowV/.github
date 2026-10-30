# LifeFlow

**Finanças e calendário para organizar o presente e planejar o que vem pela frente.**

O LifeFlow é um projeto de finanças pessoais que conecta a organização do dinheiro à rotina. A proposta é ajudar você a entender seus gastos, acompanhar vencimentos e se preparar para compromissos futuros.

[Acessar a aplicação](https://lifeflow-six-sigma.vercel.app) · [Frontend](https://github.com/LifeFlowV/FrontEnd) · [Backend](https://github.com/LifeFlowV/BackEnd)

## O que o projeto reúne

O código atual contém módulos para:

- **Finanças:** receitas, despesas, transferências, contas, categorias e orçamentos mensais.
- **Cartões e dívidas:** compras parceladas, faturas e acompanhamento de pagamentos.
- **Agenda:** calendário com tarefas, eventos e vencimentos financeiros.
- **Visão geral:** painel e relatórios para acompanhar as informações registradas.

Essa descrição se baseia na leitura dos repositórios; não representa uma validação de todos os fluxos na aplicação publicada.

## Planejar antes de gastar

Imagine um **hackathon daqui a duas semanas**. Além de marcar a data no calendário, você quer estimar alimentação, hospedagem e transporte, comparar alternativas — como transporte público ou aplicativo — e saber quanto precisa reservar até o evento.

Essa é a direção de evolução do LifeFlow: aproximar **evento, estimativa de custos e planejamento financeiro**, para comparar o previsto com o realizado.

O fluxo completo de estimativas e reserva financeira vinculadas a eventos **ainda é uma proposta de produto**. Carteiras de investimentos e integrações bancárias também são ideias futuras, fora do escopo imediato.

## Repositórios e tecnologias

| Repositório | Responsabilidade | Tecnologias verificadas |
| --- | --- | --- |
| [FrontEnd](https://github.com/LifeFlowV/FrontEnd) | Interface web | React 18, TypeScript, Vite, FullCalendar, TanStack Query e Vitest |
| [BackEnd](https://github.com/LifeFlowV/BackEnd) | API e regras de negócio | Java 21, Spring Boot 3.3, Spring Security, Spring Data JPA, Maven, PostgreSQL e Flyway |
| [.github](https://github.com/LifeFlowV/.github) | Apresentação da organização | Markdown |

O backend é privado: seu conteúdo e suas instruções dependem de permissão de acesso. Os READMEs de cada projeto orientam a preparação do ambiente local.

## Status do projeto

**Em desenvolvimento.** Contexto documental conferido em **30/10/2026**.

O endereço da aplicação acima é o informado no repositório do frontend. Há registros de testes locais de backend e frontend, mas eles não garantem a disponibilidade atual nem o funcionamento completo do ambiente publicado. Esta revisão do perfil não executou novamente as suítes nem validou fluxos em produção.

## Próximos passos

- Alinhar a explicação de parcelas na interface às regras do backend.
- Validar o fluxo completo entre interface, API e banco em ambiente local com dados descartáveis.
- Melhorar as instruções para reproduzir o ambiente e os testes.
- Definir e revisar a jornada de planejamento de eventos, começando pelo exemplo do hackathon, antes de implementá-la.

## Como contribuir

1. Consulte o README do repositório relevante e as instruções de contribuição existentes, incluindo `AGENTS.md`, quando disponível.
2. Para sugerir melhorias ou relatar problemas, use as [issues do frontend](https://github.com/LifeFlowV/FrontEnd/issues). Descreva o objetivo ou os passos para reproduzir, o comportamento esperado e o observado.
3. Trabalhe em uma branch e abra um pull request com escopo claro, explicação da mudança e resultados dos testes realmente executados. Informe também o que ficou sem verificar.
4. Use dados fictícios nos testes e exemplos. Não inclua senhas, tokens, credenciais ou dados financeiros pessoais em issues, código ou capturas.

Para contribuir com a API, é necessário acesso ao backend. Mudanças devem passar por revisão antes de integração ou publicação.
