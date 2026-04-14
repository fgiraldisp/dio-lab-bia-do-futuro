# 📊 Orion — Agente Financeiro Inteligente

## 🧠 Descrição

Esta pasta contém o código fonte do **Orion**, desenvolvido para análise de orçamento pessoal com suporte a processamento local em Python e geração de respostas em linguagem natural. Ele é um agente financeiro inteligente desenvolvido para auxiliar no controle e análise de orçamento pessoal, transforando dados de receitas, despesas e planejamento financeiro em **insights claros, objetivos e acionáveis**, permitindo ao usuário tomar decisões financeiras mais conscientes.

---

## 🎯 Objetivo

O objetivo do Orion é resolver a dificuldade que muitos usuários têm em:

- interpretar seus dados financeiros  
- comparar valores planejados com realizados  
- identificar padrões de consumo  
- tomar decisões financeiras práticas  

O agente atua como um **analista financeiro pessoal automatizado**, focado em clareza e eficiência.

---

## ⚙️ Arquitetura

O Orion utiliza uma abordagem híbrida:

### 📊 Processamento local em Python

- cálculo de saldo  
- análise de despesas  
- comparação com planejamento  

### 🤖 Modelo de linguagem (IA)

- geração de explicações  
- recomendações em linguagem natural  

Essa arquitetura reduz custo, melhora performance e aumenta a confiabilidade das respostas.

---

## 📁 Estrutura do Projeto

```bash
.
├── data/                 # Base de conhecimento (JSON e CSV)
├── src/                  # Código da aplicação
│   ├── app.py
│   ├── agente.py
│   ├── analisador.py
│   ├── carregador_dados.py
│   └── config.py
├── requirements.txt
└── README.md
