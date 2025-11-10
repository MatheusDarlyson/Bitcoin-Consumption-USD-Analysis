# 💰 Bitcoin (BTC) Consumption Analysis in USD

Este projeto foca na análise exploratória e visualização do consumo de Bitcoin (BTC) em Dólar Americano (USD) ao longo do tempo. A análise é dividida em dois notebooks principais para examinar o consumo com base em datas específicas e em períodos agrupados.

## 💾 Estrutura do Repositório

O repositório está organizado da seguinte forma:

* **Notebooks de Análise (Source Code):**
    * `ConsumoDolar_Data.ipynb`: Análise de consumo de BTC em USD por **data**.
    * `ConsumoDolar_Período.ipynb`: Análise de consumo de BTC em USD agrupada por **períodos** (ex: mensal, anual).
* **Dados e Resultados:**
    * `resultado_Data.csv` / `resultado_Data.json`: Dados resultantes da análise por data.
    * `resultado_Periodo.csv` / `resultado_Periodo.json`: Dados resultantes da análise por período.
* **Relatório de Desafios:**
    * `# Relatório de Dificuldades.md`: Documentação das dificuldades e desafios técnicos enfrentados durante o desenvolvimento do projeto.

## 💻 Objetivo dos Notebooks

Ambos os notebooks utilizam o pandas para manipulação de dados e focarão em extrair insights sobre como o consumo de BTC em USD se distribui:

### **`ConsumoDolar_Data.ipynb`**

* **Foco:** Detalhar a tendência de consumo dia a dia.
* **Metodologia:** Extração e transformação de dados de consumo para gerar um resultado segmentado por data.

### **`ConsumoDolar_Período.ipynb`**

* **Foco:** Identificar padrões sazonais ou de longo prazo no consumo.
* **Metodologia:** Agrupamento dos dados de consumo em períodos definidos (como meses ou anos) para uma análise de série temporal.

## 📝 Relatório de Dificuldades

O arquivo `# Relatório de Dificuldades.md` documenta os obstáculos encontrados, servindo como registro de aprendizado e transparência sobre o processo de desenvolvimento.
