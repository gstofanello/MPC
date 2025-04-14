# 📈 Previsão do Mercado Financeiro com Modelos Estatísticos e de Deep Learning

Este projeto tem como objetivo analisar e comparar diferentes modelos preditivos para séries temporais financeiras, focando na previsão de ativos da bolsa brasileira, como IBOVESPA e ITUB4. Utilizamos desde métodos estatísticos tradicionais até redes neurais profundas e modelos híbridos, além de uma etapa posterior com análise via LLMs para insights de investimentos.

---

## 🔍 Objetivos

- Comparar a performance de diferentes modelos de previsão de séries temporais no contexto financeiro.
- Aplicar modelos como ARIMA, GARCH, LSTM, CNN, TCN e combinações híbridas.
- Avaliar os modelos com métricas como MSE, MAE, MAPE e R².
- Utilizar LLMs (como DeepSeek) para análise de predições e insights sobre ativos em tempo real (Fase 2).

---

## 🛠 Tecnologias e Ferramentas

- **Linguagem:** Python 3.10+
- **Bibliotecas:** 
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `statsmodels`, `arch`, `sklearn`
  - `tensorflow`, `keras`, `torch`
  - `yfinance`, `investpy` ou scraping do **Investing.com**
  - `DeepSeek` ou outro LLM local/API
- **IDE recomendada:** Jupyter Notebook / VS Code
- **Requisitos:** ver arquivo `requirements.txt`

---

## 📊 Conjunto de Dados

- **Fonte:** [Investing.com](https://www.investing.com/)
- **Ativos analisados:** IBOVESPA, ITUB4, S&P500, APPL
- **Frequência:** Diária
- **Período:** Últimos 4 anos 01/01/2021 - 01/04/2025

---

## 🔁 Modelos Implementados

### Estatísticos
- **ARIMA** (AutoRegressive Integrated Moving Average)
- **GARCH** (Generalized Autoregressive Conditional Heteroskedasticity)

### Deep Learning
- **LSTM** (Long Short-Term Memory)
- **CNN** (Convolutional Neural Network)

### Híbridos
- **ARIMA + LSTM**
- **CNN + LSTM**

---

## 📐 Métricas de Avaliação

- **MSE** (Mean Squared Error)
- **MAE** (Mean Absolute Error)
- **MAPE** (Mean Absolute Percentage Error)
- **R²** (Coeficiente de Determinação)

---

