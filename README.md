# Previsão de Doença Cardíaca com Aprendizado de Máquina: Um Estudo com Dados Clínicos da UCI (University of California, Irvine)

O objetivo deste projeto é prever a **presença ou ausência de doença cardíaca** em pacientes com base em diversas **características clínicas**. A análise é realizada usando um conjunto de **dados de um estudo cardíaco** da  [Universidade da Califórnia, Irvine (UCI).](https://archive.ics.uci.edu/)

## Estrutura do Projeto:

1. `Preparação das Ferramentas`: Importamos as bibliotecas necessárias.
2. `Carregamento dos Dados`: Pegamos o dataset de doenças cardíacas.
3. `Tratamento de Valores Faltantes`: Verificamos e tratamos valores faltantes nos dados.
4. `Análise Exploratória`: Exploramos a distribuição das variáveis numéricas e categóricas e analisamos a correlação entre as variáveis.
5. `Divisão do Dataset`: Separamos os dados em features e alvo, pré-processamos os dados e dividimos em conjuntos de treinamento e teste.
6. `Treinamento do Modelo`: Treinamos um modelo de Árvore de Decisão com os dados de treinamento.
7. `Avaliação do Modelo`: Avaliamos o desempenho do modelo usando acurácia, matriz de confusão e relatório de classificação.
8. `Interpretação dos Resultados`: Analisamos a importância das variáveis e visualizamos a matriz de confusão e o scatterplot das predições versus valores reais.
