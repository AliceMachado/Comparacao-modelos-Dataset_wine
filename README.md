# Comparacao-modelos-Dataset_wine / Para melhor visualização, utilize o modo 'Code' do arquivo README!

Exercício de Classificação de Vinhos com o Conjunto de Dados "Wine"

Este exercício envolve a utilização do conjunto de dados "Wine" do scikit-learn para treinar e avaliar diferentes modelos de classificação. O objetivo é comparar o desempenho dos modelos e identificar o mais eficaz para a classificação de vinhos.

#Passos do Exercício

1. Carregar e Explorar o Dataset
O conjunto de dados "Wine" foi carregado do scikit-learn e explorado para entender suas características principais.

2. Pré-processamento dos Dados
Os dados foram divididos em conjuntos de treino e teste, e normalizados utilizando `StandardScaler`.

3. Treinar e Avaliar Modelos
Três modelos de classificação foram treinados e avaliados:
- Árvore de Decisão
- Random Forest
- K-Nearest Neighbors (KNN)

4. Comparação dos Modelos
Resultados:
-> Árvore de Decisão:
  - Acurácia: 0.96
  - Matriz de Confusão:
    [[18  1  0]
     [ 0 21  0]
     [ 1  0 13]]
  - Relatório de Classificação:
                precision    recall  f1-score   support

             0       0.95      0.95      0.95        19
             1       0.95      1.00      0.98        21
             2       1.00      0.93      0.96        14

      accuracy                           0.96        54
     macro avg       0.97      0.96      0.96        54
  weighted avg       0.96      0.96      0.96        54

-> Random Forest:
  - Acurácia: 1.00
  - Matriz de Confusão:
    [[19  0  0]
     [ 0 21  0]
     [ 0  0 14]]
  - Relatório de Classificação:
                precision    recall  f1-score   support

             0       1.00      1.00      1.00        19
             1       1.00      1.00      1.00        21
             2       1.00      1.00      1.00        14

      accuracy                           1.00        54
     macro avg       1.00      1.00      1.00        54
  weighted avg       1.00      1.00      1.00        54

-> KNN:
  - Acurácia: 0.96
  - Matriz de Confusão:
    [[19  0  0]
     [ 1 19  1]
     [ 0  0 14]]
  - Relatório de Classificação:
                precision    recall  f1-score   support

             0       0.95      1.00      0.97        19
             1       1.00      0.90      0.95        21
             2       0.93      1.00      0.97        14

      accuracy                           0.96        54
     macro avg       0.96      0.97      0.96        54
  weighted avg       0.96      0.96      0.96        54
