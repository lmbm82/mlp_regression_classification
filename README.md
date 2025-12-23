# Redes Neuronais para Regressão e Classificação com Scikit-learn

Este projeto em Jupyter Notebook demonstra a utilização de redes neuronais artificiais (MLP - Multi-Layer Perceptron) para resolver dois tipos de problemas em Machine Learning:
- Regressão (previsão de valores contínuos)
- Classificação (previsão de classes)

## Objetivo
Explorar o desempenho de redes neuronais em:
- Previsão de preços de casas (dataset California Housing)
- Classificação de imagens de rostos (dataset LFW - Labeled Faces in the Wild)

## Tecnologias
- Python
- NumPy
- Matplotlib
- Scikit-learn
  - MLPRegressor
  - MLPClassifier
  - StandardScaler
  - GridSearchCV

## Exercício 1 — Regressão
Utilização do dataset **California Housing** para prever o valor médio das casas.

Etapas:
- Carregamento e divisão dos dados (train/test)
- Normalização com StandardScaler
- Treino de uma rede neural MLPRegressor
- Avaliação com MSE e R²

Objetivo: prever valores contínuos com redes neuronais.

## Exercício 2 — Classificação
Classificação de imagens de rostos do dataset **LFW (Labeled Faces in the Wild)** usando MLPClassifier.

Resultados iniciais:
- Precisão no treino: **1.00**
- Precisão no teste: **~0.81**

Relatório de classificação (antes de otimização):
- Accuracy global: **81%**
- Avaliação por classe com precision, recall e f1-score

Inclui:
- Normalização dos dados
- Treino do classificador
- Matriz de confusão
- Relatório detalhado de métricas

## Resultados
O modelo de classificação apresentou boa capacidade de generalização, com cerca de **81% de accuracy** no conjunto de teste antes da otimização de hiperparâmetros.

## Ficheiros
- `mlp_regression_classification.ipynb` — Notebook principal com ambos os exercícios

## 📚 Notas
Projeto desenvolvido no contexto de formação em Machine Learning, com foco na compreensão e aplicação prática de redes neuronais em Python.
