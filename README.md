# Análise e Modelagem de Dados Imobiliários em Boston

Neste projeto, realizamos uma análise exploratória e modelagem de dados imobiliários em Boston, utilizando técnicas de aprendizado de máquina. Abaixo, destacamos os principais passos e conclusões obtidas durante o processo:

## Tecnologias Utilizadas:

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy
- scikit-learn

## Passos da Análise e Modelagem:

1. **Importação de bibliotecas e dados**: Iniciamos importando as bibliotecas necessárias, como Pandas, Matplotlib, Seaborn, NumPy e scikit-learn, e carregamos o conjunto de dados.

2. **Seleção de variáveis contínuas e análise estatística**: Selecionamos três variáveis contínuas do conjunto de dados e realizamos uma análise estatística básica, como média, mediana, percentis, entre outros.

3. **Identificação de outliers através de Boxplot**: Utilizamos boxplots para visualizar a distribuição dos dados das variáveis selecionadas e identificar a presença de outliers.

4. **Visualização da correlação entre variáveis com Heatmap**: Construímos um mapa de calor para visualizar a correlação entre todas as variáveis iniciais do conjunto de dados.

5. **Matriz de diagramas de dispersão**: Analisamos as relações entre as variáveis selecionadas e a variável-alvo através de uma matriz de diagramas de dispersão.

6. **Divisão do conjunto de dados e escalonamento**: Dividimos o conjunto de dados em treino e teste e escalonamos os dados utilizando StandardScaler para melhorar o desempenho do modelo.

7. **Ajuste do modelo de regressão linear simples**: Ajustamos um modelo de regressão linear simples utilizando uma das três variáveis escolhidas e calculamos o RMSE para avaliar o desempenho do modelo.

8. **Ajuste do modelo de regressão linear múltipla**: Ajustamos um modelo de regressão linear múltipla utilizando as três variáveis selecionadas e calculamos o RMSE para avaliar o desempenho do modelo.

## Conclusões:

- A presença de outliers foi identificada nas variáveis 'DIS' e 'RM', justificando a necessidade de escalonamento dos dados.
- O modelo de regressão linear múltipla obteve um desempenho superior ao modelo simples, indicando que a inclusão de mais variáveis preditoras melhora a precisão das previsões.
- O RMSE mais baixo no modelo múltiplo sugere que ele foi mais preciso na previsão dos valores das casas, devido à capacidade de capturar a influência de mais fatores.

Este projeto demonstra a aplicação de técnicas de análise exploratória de dados e modelagem para entender e prever valores imobiliários em Boston. Para mais detalhes, consulte o código fonte e os notebooks fornecidos neste repositório.
