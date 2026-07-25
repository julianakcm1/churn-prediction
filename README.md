# Customer Churn Prediction

Projeto de Machine Learning desenvolvido para prever clientes com maior probabilidade de cancelamento (churn) utilizando o dataset Telco Customer Churn.

O projeto contempla todo o ciclo de desenvolvimento de um modelo preditivo, incluindo preparação dos dados, análise exploratória, engenharia de atributos, pré-processamento, comparação de algoritmos, otimização de hiperparâmetros e avaliação do modelo final.

## Objetivo

Identificar clientes com maior risco de churn para apoiar estratégias de retenção e permitir ações preventivas por parte da empresa.

## Tecnologias utilizadas

- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Modelos avaliados

Foram comparados diferentes algoritmos de classificação:

- Logistic Regression
- Logistic Regression com balanceamento de classes
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine

A avaliação foi realizada utilizando validação cruzada estratificada (Stratified K-Fold).

## Modelo final

A Regressão Logística Balanceada foi selecionada como modelo final devido ao melhor equilíbrio entre Precision e Recall, sendo posteriormente otimizada utilizando GridSearchCV.

## Principais métricas avaliadas

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Average Precision

## Principais resultados

O modelo final apresentou:

- Accuracy aproximada: 75%
- Precision aproximada: 52%
- Recall aproximado: 80%
- F1-score aproximado: 63%

O modelo prioriza a identificação de clientes em risco de cancelamento, reduzindo falsos negativos e permitindo ações de retenção mais eficientes.