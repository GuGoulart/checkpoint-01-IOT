# Projeto de Data Science e Machine Learning – Checkpoint 01  

Este repositório contém as soluções do **Checkpoint 01 – Data Science e Machine Learning no Python e Orange Data Mining**, que aborda análise de dados de consumo de energia elétrica residencial e modelagem com diferentes técnicas.  

## Estrutura do Projeto  
- **Parte 1 – Exploração inicial (Python / Pandas / Matplotlib)**  
  - Carregamento do dataset *Individual Household Electric Power Consumption*  
  - Tratamento de dados ausentes e conversão de datas  
  - Análises exploratórias (médias, histogramas, séries temporais)  
  - Criação de novas variáveis (ex.: `Total_Sub_metering`)  
  - Modelagem simples com Regressão Linear  
  - Clustering com K-Means e decomposição de séries temporais  

- **Parte 2 – Exercícios adicionais (Python / Scikit-learn)**  
  - Reamostragem horária e análise de padrões de consumo  
  - Autocorrelação em diferentes lags  
  - PCA (Análise de Componentes Principais)  
  - Regressão polinomial vs linear  
  - Visualização de clusters no espaço PCA  

- **Parte 3 – Novo dataset: Appliances Energy Prediction**  
  - Carregamento do dataset de previsão de consumo de eletrodomésticos  
  - Análises descritivas, histogramas e correlações  
  - Normalização dos dados (Min-Max Scaling)  
  - Modelos de Regressão Linear Múltipla e Random Forest  
  - Clustering com K-Means  
  - Classificação binária (alto vs baixo consumo) com Logistic Regression e Random Forest  
  - Avaliação com matriz de confusão e métricas de classificação  

- **Parte 4 – Orange Data Mining**  
  - Importação do dataset via **CSV File Import**  
  - Visualização inicial em **Data Table**  
  - Amostragem de 1% com **Sample Data**  
  - Distribuição do consumo em **Distribution**  
  - Relação entre `Voltage` e `Global_intensity` em **Scatter Plot**  
  - Clustering com **k-Means** usando `Sub_metering_1`, `Sub_metering_2` e `Sub_metering_3`  

## Tecnologias Utilizadas  
- **Python 3.x**  
  - Pandas  
  - Matplotlib / Seaborn  
  - Scikit-learn  
  - Statsmodels  
- **Orange Data Mining**  
  - CSV File Import  
  - Data Table  
  - Sample Data  
  - Distribution  
  - Scatter Plot  
  - k-Means  

##  Autor  
- Nome: *Gustavo Goulart Bretas*
- RMM: *555708*
