# miniguia-seguranca-bancaria-notebooklm
# 📘 Miniguia de Inteligência Artificial na Mitigação de Engenharia Social no Setor Bancário

Projeto prático desenvolvido durante o Bootcamp Bradesco na plataforma DIO. Este repositório documenta a criação de um Caderno Temático inteligente utilizando o **NotebookLM (Google)**, com foco em analisar, compreender e mitigar golpes financeiros e engenharia social baseados no ecossistema bancário e Pix.

---

## 🎯 Contexto e Objetivos

### Contexto
O elo mais visado em fraudes financeiras atuais não é o software, mas o fator humano. Golpes de engenharia social (como falsos funcionários, phishing e golpes do Pix) desafiam grandes instituições financeiras diariamente. Este projeto utiliza IA para analisar a anatomia desses golpes a partir de cartilhas públicas de segurança, gerando um material de conscientização rápido e eficiente.

### Objetivos de Estudo
* Centralizar e cruzar dados de cartilhas de segurança bancária utilizando o NotebookLM.
* Identificar os padrões mais comuns de abordagens criminosas (gatilhos emocionais e urgência).
* Desenvolver um miniguia prático de respostas que possa servir de apoio para treinamento de equipes de atendimento ou conscientização de clientes.

---

## 📚 Curadoria de Fontes

Para alimentar a base de conhecimento local do NotebookLM, foram selecionadas fontes públicas, oficiais e abertas, garantindo a total segurança e privacidade de dados:

1. **Cartilha de Segurança do Bradesco** - Orientações oficiais do banco aos clientes sobre como se prevenir de fraudes, uso seguro de canais digitais e o que o banco nunca solicita.
2. **Guias Antifraude e Segurança da FEBRABAN (Federação Brasileira de Bancos)** - Manuais e dicas públicas focados na conscientização e proteção contra golpes do Pix, links falsos e engenharia social.
3. **Relatórios Públicos de Tendências de Fraude Cibernética** - Dados estatísticos abertos do mercado financeiro nacional sobre o comportamento de cibercriminosos no ecossistema de pagamentos instantâneos.

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Abaixo está o registro dos testes de refinamento dos comandos enviados à IA para obter as melhores respostas técnicas baseadas exclusivamente no nosso material.

### Prompt Versão 1 (Genérico)
> **Prompt:** "Como acontecem os golpes bancários?"
* **Resultado:** A IA trouxe respostas amplas sobre fraudes de cartão de crédito internacionais, fugindo do foco específico de engenharia social e do ecossistema Pix do cenário brasileiro.

### Prompt Versão 2 (Refinado - Engenharia de Prompts)
> **Prompt:** "Atue como um Especialista em Prevenção de Fraudes e Segurança da Informação Bancária. Com base exclusivamente nas cartilhas da FEBRABAN e do Bradesco anexadas, identifique quais são os 3 principais gatilhos emocionais utilizados em golpes de falsos funcionários e estruture uma matriz de identificação rápida para o usuário."
* **Resultado:** Resposta perfeita. A IA limitou-se ao escopo brasileiro, destacando os gatilhos de *Urgência*, *Autoridade* e *Medo*, citando as ações de prevenção recomendadas nas fontes.

### Cicatrizes & Aprendizados (Troubleshooting)
* **Dificuldade:** O NotebookLM, por padrão, pode tentar usar o conhecimento geral da internet para responder.
* **Solução:** O uso de travas textuais nos prompts como *"com base exclusivamente nos documentos fornecidos"* e *"atue como um analista de prevenção de perdas/fraudes bancárias"* garantiu o foco absoluto na base de dados selecionada.

---

## 📝 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado dos Padrões de Fraude
* **Golpe do Falso Funcionário:** O criminoso simula ser da central de segurança do banco, alega uma transação suspeita (geralmente Pix agendado) e induz a vítima a transferir valores para uma "conta de segurança" ou instalar um aplicativo de acesso remoto.
* **Phishing Direcionado:** Mensagens SMS ou WhatsApp falsas contendo alertas de segurança urgentes com links que clonam a interface do banco para capturar credenciais.

### 2. Glossário Técnico Baseado nas Fontes
* **Engenharia Social:** Técnica de manipulação psicológica utilizada para induzir pessoas a executar ações ou gerenciar informações confidenciais de forma inadequada.
* **Phishing:** Tipo de ataque cibernético que utiliza comunicações fraudulentas que parecem vir de uma fonte confiável para roubar dados.
* **Mula de Conta (Money Mule):** Contas bancárias de terceiros utilizadas por golpistas para pulverizar e lavar o dinheiro oriundo de fraudes de forma rápida.

### 3. Prompts Reutilizáveis para Treinamentos Futuros
* `"Crie um cenário simulado de engenharia social baseado no golpe do falso funcionário e me faça perguntas passo a passo para testar se eu saberia identificar a fraude."`
* `"Gere um sumário executivo em tópicos curtos destacando quais procedimentos um cliente deve tomar imediatamente após perceber que foi vítima de engenharia social, conforme as cartilhas."`

---
