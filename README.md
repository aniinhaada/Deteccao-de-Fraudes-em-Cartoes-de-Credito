# Detecção de Fraudes em Cartões de Crédito

Projeto de aprendizado não supervisionado utilizando técnicas de clusterização para identificar padrões em transações de cartões de crédito.

## Objetivo

O objetivo deste projeto é analisar transações financeiras e identificar grupos com características semelhantes utilizando técnicas de aprendizado não supervisionado.

O conjunto de dados possui uma variável chamada `Class`, que indica se uma transação é legítima ou fraudulenta:

- `0` representa uma transação legítima.
- `1` representa uma transação fraudulenta.

Como o projeto utiliza aprendizado não supervisionado, a variável `Class` não é utilizada durante a criação dos clusters.

Ela é separada antes da clusterização e utilizada apenas depois para analisar os grupos formados.

## Dataset

O projeto utiliza o dataset Credit Card Fraud Detection, disponibilizado no Kaggle.

O conjunto original possui:

- 284.807 transações;
- 31 colunas;
- variáveis `V1` até `V28`;
- variável `Time`;
- variável `Amount`;
- variável `Class`.

## Etapas do Projeto

1. Importação das bibliotecas
2. Obtenção e carregamento dos dados
3. Limpeza e pré-processamento
4. Separação da variável `Class`
5. Padronização dos dados
6. Escolha do número de clusters
7. Clusterização com K-Means
8. Análise da concentração de fraudes por cluster
9. Avaliação dos resultados
10. Comparação com Isolation Forest

## Tecnologias Utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

## Status do Projeto

Projeto em desenvolvimento.