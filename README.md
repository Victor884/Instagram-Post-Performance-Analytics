# 📱 Instagram Data Analysis - EDA

Este projeto consiste numa **Análise Exploratória de Dados (EDA)** detalhada sobre métricas de alcance e engajamento do Instagram. O objetivo principal é identificar padrões estatísticos que explicam o crescimento de um perfil e a eficiência de diferentes fontes de tráfego.

## 🎯 Objetivos do Projeto
- Analisar a distribuição de impressões (Home, Explore, Hashtags).
- Identificar a correlação entre interações (Likes, Comments, Saves) e o alcance real.
- Analisar a relação entre visitas ao perfil e a conversão de novos seguidores.
- Visualizar as tendências de conteúdo através de processamento de texto simples (Hashtags).

## 📊 Principais Insights
- **Conversão de Seguidores:** Encontrou-se uma correlação de **0.85** entre as visitas ao perfil e o ganho de seguidores, indicando que a otimização da Bio/Feed é crucial.
- **Fontes de Tráfego:** Embora a "Home" concentre o volume, as "Hashtags" e o "Explore" são os principais motores de descoberta para novas audiências.
- **Engajamento:** O uso de gráficos interativos permitiu identificar que o número de *Shares* (partilhas) tem um peso crescente no alcance orgânico total.

## 🛠️ Tecnologias Utilizadas
- **Python 3.10+**
- **Pandas & NumPy:** Limpeza e manipulação de séries temporais.
- **Plotly:** Gráficos interativos (Scatter, Pie, Line plots).
- **Matplotlib & Seaborn:** Visualizações estatísticas.
- **WordCloud:** Geração de nuvens de palavras para análise de hashtags.

## 📂 Estrutura do Repositório
| Arquivo | Descrição |
| :--- | :--- |
| `EDA - Exploratory Data Analysis.ipynb` | Notebook Jupyter com todo o workflow da análise. |
| `Instagram_data.csv` | Dataset utilizado (https://www.kaggle.com/datasets/tahirmohd/my-datasat). |
