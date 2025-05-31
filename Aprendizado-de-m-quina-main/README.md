# Aprendizado-de-m-quina# Aprendizado-de-m-quina

Este projeto apresenta um teste prático de aprendizado de máquina utilizando o algoritmo k-Nearest Neighbors (kNN) aplicado ao famoso dataset Iris.

## Descrição

O notebook [`Knn.ipynb`](Knn.ipynb) contém as seguintes etapas:

1. **Importação de Bibliotecas**  
   Utilização de bibliotecas como `pandas`, `scikit-learn`, `matplotlib`, `seaborn` e `mlxtend` para manipulação de dados, visualização e implementação do kNN.

2. **Carregamento do Dataset**  
   O dataset [Iris.csv](docs/Iris.csv) é carregado e analisado para entender suas dimensões, classes e features.

3. **Visualização dos Dados**  
   Gráficos de dispersão são criados para visualizar a distribuição das espécies em relação às features.

4. **Pré-processamento**  
   As classes são transformadas em valores numéricos para facilitar o treinamento do modelo.

5. **Divisão dos Dados**  
   O conjunto de dados é dividido em treino e teste usando `train_test_split`.

6. **Treinamento do Modelo kNN**  
   O modelo `KNeighborsClassifier` é treinado com diferentes valores de k e métricas de distância (euclidiana, manhattan e uma métrica customizada).

7. **Avaliação do Modelo**  
   São gerados relatórios de classificação para avaliar a performance do modelo em cada configuração.

8. **Visualização das Regiões de Decisão**  
   As regiões de decisão do classificador são plotadas para melhor compreensão dos resultados.

## Como Executar

1. Instale as dependências listadas em [requirements/requirements.txt](requirements/requirements.txt).
2. Execute o notebook [`Knn.ipynb`](Knn.ipynb) em um ambiente Jupyter ou Google Colab.

## Dataset

O dataset utilizado está disponível em [docs/Iris.csv](docs/Iris.csv).

---

Sinta-se à vontade para explorar e modificar o notebook para testar outros algoritmos ou configurações!