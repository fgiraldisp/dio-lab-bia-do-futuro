# Código da Aplicação

# 📊 Orion — Agente Financeiro Inteligente

## 🧠 Descrição

O **Orion** é um agente financeiro inteligente desenvolvido para auxiliar no controle e análise de orçamento pessoal.  
Ele transforma dados de receitas, despesas e planejamento financeiro em **insights claros, objetivos e acionáveis**, permitindo ao usuário tomar decisões financeiras mais conscientes.

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

- 📊 **Processamento local em Python**
  - cálculo de saldo  
  - análise de despesas  
  - comparação com planejamento  

- 🤖 **Modelo de linguagem (IA)**
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
````

---

## 📊 Base de Conhecimento

A base de conhecimento do Orion é composta por arquivos estruturados que armazenam dados do usuário e suas finanças.

| Arquivo | Formato | Função |
|--------|--------|--------|
| `transacoes.csv` | CSV | Registra receitas e despesas |
| `planejamento_financeiro.json` | JSON | Define orçamento planejado |
| `perfil_usuario.json` | JSON | Contém perfil e objetivos do usuário |
| `categorias_financeiras.json` | JSON | Padroniza categorias financeiras |
| `historico_interacoes.csv` | CSV | Armazena interações anteriores |

---

## 🚀 Funcionalidades

- ✔ Cálculo automático de saldo  
- ✔ Comparação entre planejado e realizado  
- ✔ Identificação de padrões de consumo  
- ✔ Geração de insights financeiros  
- ✔ Recomendações práticas para o usuário  
- ✔ Interface interativa com Streamlit  

---

## 🧠 Exemplo de Análise

**Entrada:**
- Receita: R$ 5.000  
- Despesas: R$ 625,40  

**Saída do Orion:**
- Saldo positivo de R$ 4.374,60  
- Nenhuma categoria ultrapassou o orçamento  
- Situação financeira estável  

---

## 🔐 Segurança e Confiabilidade

O Orion foi projetado para minimizar erros e alucinações:

- ✔ Utiliza apenas dados fornecidos  
- ✔ Não inventa informações  
- ✔ Realiza processamento local antes da IA  
- ✔ Solicita mais dados quando necessário  
- ✔ Não faz recomendações sem contexto  

---

## ⚠️ Limitações

- Não substitui um consultor financeiro profissional  
- Não realiza previsões de mercado  
- Não acessa dados externos em tempo real  
- Depende da qualidade dos dados fornecidos  

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Streamlit  
- Pandas  
- JSON / CSV  
- Ollama (IA local) ou API de modelo de linguagem  

---

## ▶️ Como Executar

### Instalar dependências

```bash
pip install -r requirements.txt
```

### Executar aplicação

```bash
streamlit run src/app.py
```
