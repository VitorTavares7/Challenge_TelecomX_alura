# 📈 Análise de Evasão de Clientes (Churn) – TelecomX

Este projeto tem como objetivo analisar os dados de uma empresa fictícia de telecomunicações chamada **TelecomX** para entender o comportamento de **evasão de clientes (churn)** e propor estratégias para sua redução. O trabalho foi realizado inteiramente no **Google Colab**.

---

## 📌 Objetivo

Identificar os principais fatores que levam os clientes a abandonarem os serviços da TelecomX e fornecer **insights práticos** para auxiliar na **retenção de clientes**.

---

## 🧪 Etapas do Projeto

### 1. **Importação dos Dados**
- Leitura do arquivo CSV com as informações dos clientes diretamente no ambiente Colab.

### 2. **Limpeza e Tratamento**
- Conversão de tipos de dados.
- Normalização de valores categóricos.
- Substituição de inconsistências como `"No phone service"` → `"No"`.
- Criação de colunas auxiliares (ex: conversão de `Churn` em variável binária).

### 3. **Análise Exploratória (EDA)**
- Visualizações com `matplotlib` e `seaborn`.
- Análise do impacto de serviços adicionais, tempo de contrato, valor cobrado, entre outros, no churn.
- Gráficos de barras, pizza, histogramas e boxplots.

### 4. **Conclusões e Insights**
- Clientes com contratos mensais são os que mais evadem.
- Adesão a serviços adicionais está ligada à maior permanência.
- Valores altos de cobrança estão associados à saída, especialmente quando não correspondem ao uso.

### 5. **Recomendações**
- Incentivar contratos anuais com benefícios.
- Oferecer pacotes com suporte, segurança e outros serviços.
- Acompanhar clientes de alto risco com alertas internos.

---

## 🛠️ Tecnologias Utilizadas

- Python 🐍
- Google Colab
- Pandas
- NumPy
- Matplotlib

  
