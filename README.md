# Future-Sales-Prediction

O objetivo desta competição disponível no Kaggle é a obtenção de modelos de predição para obter estimativas sobre o volume de vendas futuro de alguns itens. Na abordagem aqui apresentada, optou-se por comparar os resultados entre a aplicação de um modelo de regressão random forest e os de uma regressão linear.

## 1. Exploração dos dados

A primeira etapa do pipeline de análise definido foi explorar a base de dados a fim de compreender os registros existentes, verificar a existência de missing values e outras anomalias nos dados. A partir dessa análise, foi possíevl extrair insights como pro exemplo:

* Relação entre o preço do item e seu volume de vendas mensais
* Quais produtos são os mais vendidos
* Quais lojas possuem os maiores volumes de vendas
![](https://github.com/luisgustavob78/Future-Sales-Prediction/blob/master/sales_exploration.gif)

## 2. Preparação dos dados para aplicação do modelo

Após identificar as particularidades dos dados e identificar potenciais features relevantes para o modelo, a próxima etapa foi converter os dados em formatos adequados para a aplicação do modelo, o que envolve o tratamento de dados anômalos e a conversão de variáveis categóricas.
![](https://github.com/luisgustavob78/Future-Sales-Prediction/blob/master/sales_preparation.gif)

## 3. Aplicação do modelo e avaliação dos resultados

Com o dataframe preparado, é hora de aplicar o modelo e avaliar os resultados:

### Random Forest
![](https://github.com/luisgustavob78/Future-Sales-Prediction/blob/master/sales_random_forest.jpg)

### Regressão Linear
![](https://github.com/luisgustavob78/Future-Sales-Prediction/blob/master/sales_linear_regression.jpg)

## 4. Conclusão

Para os dados desse projeto em específico, os algortimos de regressão linear e random forest apresentaram resultados semelhantes quando comparados pela métrica de erro quadrático médio (RMSE)

## 5. Instalação Apache Spark

OS & Linux: https://medium.com/luckspark/installing-spark-2-3-0-on-macos-high-sierra-276a127b8b85

Windows: https://changhsinlee.com/install-pyspark-windows-jupyter/

## 6. Competição e dados

https://www.kaggle.com/c/data-science-bowl-2019


