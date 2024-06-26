# Previsão de Preços de Ações usando LSTM

Este projeto visa prever os preços de fechamento de ações, especificamente da PETR4.SA (Petrobras), usando uma rede neural LSTM (Long Short-Term Memory). A seguir, estão detalhados os passos e a lógica implementada para alcançar esse objetivo.

## Índice

- [Introdução](#introdução)
- [Instalação](#instalação)
- [Uso](#uso)
- [Explicação do Código](#explicação-do-código)
  - [Coleta de Dados](#coleta-de-dados)
  - [Pré-processamento dos Dados](#pré-processamento-dos-dados)
  - [Construção e Treinamento do Modelo](#construção-e-treinamento-do-modelo)
  - [Avaliação do Modelo](#avaliação-do-modelo)
  - [Previsão de Preços](#previsão-de-preços)
- [Resultados](#resultados)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Introdução

Este projeto utiliza uma rede neural LSTM para prever o preço de fechamento das ações da PETR4.SA com base nos dados históricos de preços. A LSTM é especialmente eficaz para tarefas de previsão de séries temporais devido à sua capacidade de capturar dependências de longo prazo nos dados.

## Instalação

Para rodar este projeto, você precisa ter o Python 3.x instalado. Além disso, você precisará instalar as seguintes bibliotecas:

```bash
pip install yfinance numpy pandas scikit-learn keras tensorflow matplotlib
