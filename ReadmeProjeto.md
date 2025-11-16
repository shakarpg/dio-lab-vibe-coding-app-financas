# 🤖 Agente Financeiro Conversacional (FinChat)

![Status do Projeto](https://img.shields.io/badge/Status-MVP%20Planejado-blue)
![Linguagem Principal](https://img.shields.io/badge/Linguagem-Portugu%C3%AAs%20(BR)-green)
![Foco](https://img.shields.io/badge/Foco-Finan%C3%A7as%20Pessoais%20Iniciantes-orange)

## 🌟 Visão Geral do Projeto

O **Agente Financeiro Conversacional** (FinChat) é um Produto Mínimo Viável (MVP) projetado para revolucionar a forma como as pessoas organizam suas finanças pessoais. Nosso objetivo é eliminar a alta fricção e a complexidade dos aplicativos tradicionais, substituindo formulários e planilhas por uma experiência de controle financeiro simples, natural e baseada em conversas.

### O Problema
Muitas pessoas, especialmente iniciantes, desistem de controlar seus gastos porque os aplicativos atuais exigem muita entrada manual, são visualmente complexos e carecem de personalização e empatia.

### A Solução
Um aplicativo que utiliza **Processamento de Linguagem Natural (NLP)** para permitir que o usuário registre gastos via chat, de forma tão simples quanto enviar uma mensagem. O aplicativo atua como um **parceiro educativo**, oferecendo dicas proativas e relatórios descomplicados.

### Público-Alvo
Pessoas que buscam começar a organizar suas finanças de forma prática e sem complicação, valorizando a simplicidade e o aprendizado contínuo.

## ❤️ O Conceito "Lovable" (Adorável)

O design do FinChat é centrado na criação de uma experiência emocionalmente positiva, transformando a tarefa de controle financeiro de um "dever" em um "hábito prazeroso".

O **Agente Financeiro** é a chave para o conceito "lovable", atuando como um **Parceiro Educador, Não um Fiscal**.

| Característica | Abordagem "Lovable" (Parceiro Educador) |
| :--- | :--- |
| **Tom de Voz** | Empático, acessível, focado em progresso e aprendizado. |
| **Registro de Gastos** | Chat em Linguagem Natural, com confirmação e sugestão de categoria. |
| **Recomendações** | Dicas proativas, contextualizadas e educativas ("Se você reduzir X, pode atingir Y"). |
| **Feedback** | Positivo e contextualizado, celebrando pequenas "Vitórias Financeiras" (Gamificação Leve). |

## 🔑 Funcionalidades do MVP

O MVP foca em três telas principais para garantir a máxima simplicidade e usabilidade:

### Telas Principais

| Tela | Objetivo Principal | Conteúdo Chave |
| :--- | :--- | :--- |
| **1. Chat (Home)** | Interação diária e registro de transações. | Campo de texto principal, histórico de conversas e botão de atalho para "Novo Gasto". |
| **2. Metas & Progresso** | Acompanhamento visual das metas. | Lista de metas ativas (Ex: "Reserva de Emergência"), progresso em porcentagem e valor. |
| **3. Relatório Simples** | Visão geral da saúde financeira. | Gráfico de pizza das categorias de gastos do mês e o saldo atual. |

### Recursos-Chave e Requisitos Técnicos

| Funcionalidade-Chave | Detalhe do MVP | Recurso Técnico Necessário |
| :--- | :--- | :--- |
| **Registro via Chat** | Extração de valor, descrição e data de frases em linguagem natural. | **Processamento de Linguagem Natural (NLP)** básico. |
| **Classificação Automática** | Sugestão de categoria com base na descrição do gasto. | **Modelo de Classificação de Texto** (Machine Learning leve). |
| **Metas Financeiras** | Cálculo do valor mensal necessário e acompanhamento do progresso. | **Banco de Dados** e lógica de cálculo de progresso. |
| **Dicas Contextuais** | Recomendações de economia baseadas na comparação com a média histórica de gastos. | **Motor de Regras** simples. |
| **Relatórios Personalizados** | Agregação de dados e visualização simples (Gráfico de Pizza). | **Lógica de Agregação de Dados** e visualização. |

## 🛠️ Arquitetura Técnica (MVP)

O projeto requer uma arquitetura que suporte a interação em tempo real e o processamento de linguagem natural:

*   **Frontend:** Interface de chat responsiva (Web/Mobile).
*   **Backend:** API para processamento de transações e regras de negócio.
*   **NLP/ML:** Módulo dedicado para extração de entidades e classificação de texto.
*   **Banco de Dados:** Para armazenamento de transações, metas e perfis de usuário.

## 📈 Validação e Métricas de Sucesso (KPIs)

A validação inicial (Alpha/Beta Fechado) será focada em 10 a 20 usuários que já falharam em controlar suas finanças com apps tradicionais.

### Hipótese Central
*A interface de chat e a personalidade do Agente Financeiro tornam o registro de gastos mais rápido e agradável para iniciantes, resultando em maior consistência no uso.*

### Métricas de Sucesso (KPIs)

| Métrica (KPI) | Definição | Meta Inicial (30 dias) |
| :--- | :--- | :--- |
| **Taxa de Registro Diário** | Porcentagem de dias em que o usuário registra pelo menos uma transação. | > 70% |
| **Tempo Médio de Registro** | Tempo (em segundos) entre abrir o app e concluir o registro de um gasto via chat. | < 10 segundos |
| **NPS (Net Promoter Score) da Experiência** | Medida da satisfação geral com a experiência conversacional. | > 50 (Indicativo de uma experiência "lovable") |

## 🔗 Protótipo e Acesso

O protótipo inicial está sendo desenvolvido na plataforma Lovable.

**Link de Acesso (Protótipo de Autenticação):**
[https://preview--conversaflow-fin.lovable.app/auth](https://preview--conversaflow-fin.lovable.app/auth)


Codigo no Github: [Finchat](https://github.com/shakarpg/conversaflow-fin.git)

## 🤝 Como Contribuir

Agradecemos o interesse em contribuir com o projeto.

1.  Faça um fork deste repositório.
2.  Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`).
3.  Commit suas mudanças (`git commit -m 'feat: Adiciona nova funcionalidade X'`).
4.  Faça o push para a branch (`git push origin feature/nova-funcionalidade`).
5.  Abra um Pull Request detalhando as mudanças.

---
*Desenvolvido por Manus AI*
