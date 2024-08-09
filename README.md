# ML-Clustering-Classification
A tarefa consiste na aplicação de técnicas de agrupamento e classificação de frutas com base em um conjunto de dados fornecido pela empresa fictícia "Grupo Flora", que é especializada na exportação de frutas.

## Descrição do Projeto

O objetivo principal desta tarefa era utilizar técnicas de agrupamento e classificação para analisar um conjunto de dados de frutas, sendo:
1. **Agrupamento de Frutas**: Utilização de um algoritmo de clustering para agrupar frutas com base em suas características.
2. **Classificação de Frutas**: Treinamento de um modelo de classificação usando os grupos formados pelo algoritmo de clustering como uma das variáveis.

## Metodologia

### Agrupamento

Para o agrupamento, foi utilizado o algoritmo K-Means, que é um método amplamente conhecido e eficiente para particionar dados em k grupos baseados em características comuns. A escolha do número de clusters foi determinada usando o método do cotovelo (Elbow Method).

### Classificação

Após o agrupamento, utilizou-se o algoritmo Random Forest para realizar a classificação das frutas. O modelo foi treinado utilizando os grupos formados como uma das variáveis de entrada, além das características originais das frutas.

### Avaliação

A avaliação do modelo foi realizada utilizando uma bateria de testes, com métricas como acurácia, precisão, recall e F1-score para medir o desempenho dos modelos de classificação. Para o agrupamento, foram utilizadas métricas como a inércia (no caso do K-Means) e a silhueta para avaliar a qualidade dos clusters formados.
