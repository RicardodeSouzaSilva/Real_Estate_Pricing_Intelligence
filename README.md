---

# 🏡 Real Estate Intelligence — King County

## 📌 Visão Geral

Este projeto foi desenvolvido para a **Cascade Urban Analytics**, uma empresa de inteligência imobiliária focada na região de King County (Seattle).

O objetivo é transformar dados históricos de vendas em **vantagem competitiva**, por meio de modelagem preditiva, análise exploratória e geração de insights acionáveis.

---

## 🏢 Contexto de Negócio

A Cascade Urban Analytics atua com:

* Valuation de imóveis
* Recomendação de investimentos
* Insights para incorporadoras
* Suporte a plataformas de compra e venda

Nos últimos 18 meses, o mercado apresentou alta volatilidade, resultando em:

* Variações inconsistentes de preços entre regiões próximas
* Aumento da exigência por previsões mais precisas
* Concorrência com modelos mais sofisticados

O modelo atual (regressão linear simples) tornou-se insuficiente para capturar a complexidade do mercado.

---

## 🎯 Objetivo do Projeto

Desenvolver uma solução baseada em dados capaz de:

* Prever preços de imóveis com alta precisão
* Identificar oportunidades de investimento
* Explicar os principais drivers de valor
* Segmentar o mercado imobiliário

---

## 📊 Dataset

O dataset contém informações de vendas de imóveis em King County, incluindo:

* Características físicas (área, quartos, banheiros)
* Localização geográfica (latitude e longitude)
* Qualidade do imóvel (grade, condition)
* Histórico (ano de construção e reformas)

---

## 🧩 Problemas de Negócio

### 🔴 1. Valuation inconsistente

**Desafio:**
Imóveis semelhantes apresentam preços divergentes, especialmente em regiões próximas.

**Impacto:**

* Perda de confiança dos clientes
* Aumento do churn
* Decisões de investimento imprecisas

**Solução proposta:**

* Modelos de regressão avançados
* Feature engineering (idade, renovação, área útil)
* Uso intensivo de variáveis geoespaciais

---

### 🔵 2. Identificação de oportunidades de investimento

**Desafio:**
A empresa não consegue identificar imóveis subvalorizados de forma quantitativa.

**Abordagem:**

* Comparação entre preço real e preço predito

**Métrica-chave:**

```
desvio = preço_real - preço_predito
```

**Insight:**

* Desvio negativo relevante → potencial oportunidade de compra

---

### 🟢 3. Drivers de preço

**Desafio:**
Falta de clareza sobre o que realmente impacta o valor dos imóveis.

**Abordagem:**

* Feature importance
* SHAP values
* Análise de não-linearidade

**Objetivo:**

Responder perguntas como:

* Localização vs estrutura: o que pesa mais?
* Qual o impacto real de banheiros adicionais?
* Reformas aumentam o valor significativamente?

---

### 🟡 4. Segmentação de mercado

**Desafio:**
O mercado é tratado como homogêneo, reduzindo a performance dos modelos.

**Abordagem:**

* Clustering (K-Means / DBSCAN)

**Possíveis segmentos:**

* Alto padrão (waterfront, alta qualidade)
* Médio padrão
* Baixo padrão

---

## 🧠 Abordagem Técnica

O projeto segue um pipeline estruturado:

1. **Data Understanding & Cleaning**
2. **Feature Engineering**
3. **Exploratory Data Analysis (EDA)**
4. **Modelagem Preditiva**
5. **Validação e Métricas**
6. **Interpretabilidade**
7. **Geração de Insights**

---

## ⚙️ Tecnologias Utilizadas

* Python
* Pandas / NumPy
* Scikit-learn
* XGBoost / LightGBM
* Matplotlib / Seaborn
* SHAP

---

## 📈 Resultados Esperados

* Redução significativa do erro de previsão
* Identificação sistemática de oportunidades de investimento
* Clareza sobre os fatores que impactam o preço
* Melhor segmentação de clientes e ativos

---

## 🚀 Impacto de Negócio

Este projeto transforma dados em decisões estratégicas, permitindo que a empresa:

* Aumente a precisão de valuation
* Ganhe vantagem competitiva
* Ofereça recomendações baseadas em dados
* Fortaleça a confiança dos clientes

---

## 📌 Diferencial do Projeto

Este não é apenas um modelo de regressão.

É uma solução completa para:

* Pricing imobiliário
* Tomada de decisão financeira
* Inteligência de mercado baseada em dados

---

## 📬 Contato

Se você quiser discutir o projeto ou oportunidades:

* LinkedIn: *www.linkedin.com/in/ricardosouzasilva*
* Email: *r2d2ss@bol.com.br*

---
