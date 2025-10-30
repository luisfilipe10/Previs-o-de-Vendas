# Repositório de Previsão de Vendas

Este projeto tem como objetivo criar um modelo de previsão de vendas com Python, utilizando as bibliotecas pandas, plotly.express e scikit-learn.

## Estrutura do Projeto

- `historico.csv`: Arquivo com dados históricos de vendas mensais.
- `previsao_vendas.ipynb`: Notebook com o código de análise, visualização e criação do modelo de regressão linear.
- `README.md`: Este arquivo de documentação.

## Funcionalidades

- Carregamento dos dados históricos.
- Análise exploratória.
- Visualização gráfica das vendas e previsões.
- Modelagem preditiva usando regressão linear.
- Previsão de vendas futuras com base no histórico.

As bibliotecas (libs) usadas no seu projeto de previsão de vendas são:

pandas: para manipulação e análise de dados tabulares.

plotly.express: para visualização gráfica interativa dos dados e resultados.

sklearn.linear_model.LinearRegression: para criar e treinar o modelo de regressão linear para previsão das vendas.

Os métodos utilizados no exemplo básico são:

pd.read_csv(): para carregar os dados do arquivo CSV.

LinearRegression().fit(X, y): treina o modelo de regressão linear com os dados históricos.

LinearRegression().predict(X): gera as previsões de vendas com o modelo treinado.

px.line(): cria gráficos de linha para comparar vendas reais e previstas.

Essas bibliotecas e métodos formam uma base simples e eficiente para fazer análise, visualização e previsão de séries temporais como vendas por mês
