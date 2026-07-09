# Previsão de Score de Crédito com Machine Learning

Projeto desenvolvido a partir da Imersão Python da Hashtag - Treinamentos, com o objetivo de explorar o uso de Inteligência Artificial para prever o score de crédito de clientes com base em características cadastrais e comportamentais.

## ✨ Sobre o projeto

Este projeto mostra, de forma prática, como construir um modelo de machine learning capaz de analisar dados de clientes e classificar o nível de risco de crédito. A abordagem utiliza técnicas de processamento de dados, treinamento de modelos e avaliação de performance.

A ideia central é transformar dados brutos em informações úteis para tomada de decisão, simulando um cenário real de análise financeira.

## 🎯 Objetivo

Criar um modelo preditivo que consiga identificar, com uma boa margem de assertividade, a categoria de score de crédito de um cliente, ajudando a automatizar avaliações financeiras.

## 📁 Estrutura do repositório

- [inicial.ipynb](inicial.ipynb): notebook com todo o fluxo do projeto, desde a análise dos dados até a geração das previsões.
- [clientes.csv](clientes.csv): base de dados utilizada para treinar e testar o modelo.
- [novos_clientes.csv](novos_clientes.csv): conjunto de novos clientes para aplicação do modelo treinado.
- [LICENSE](LICENSE): licença do projeto.

## 🧠 Fluxo do projeto

O notebook acompanha os seguintes passos:

1. Carregamento e exploração dos dados.
2. Limpeza e tratamento das colunas.
3. Transformação de variáveis categóricas em valores numéricos.
4. Divisão dos dados em treino e teste.
5. Treinamento de modelos de Machine Learning.
6. Comparação de desempenho entre os modelos.
7. Aplicação do melhor modelo para prever novos clientes.

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## ▶️ Como executar

1. Clone este repositório.
2. Instale as dependências:

```bash
pip install pandas scikit-learn notebook
```

3. Abra o notebook:

```bash
jupyter notebook
```

4. Execute as células do arquivo [inicial.ipynb](inicial.ipynb).

## 📊 Resultado esperado

O projeto demonstra como modelos de classificação podem ser aplicados em cenários financeiros e como a análise de dados pode gerar previsões com valor real para negócios e decisão automatizada.

## 🚀 Próximos passos

- Testar outros algoritmos de Machine Learning.
- Ajustar hiperparâmetros para melhorar a acurácia.
- Criar uma interface simples para inserir dados e gerar previsões.
- Salvar o modelo treinado para uso posterior.

## 📝 Observação

Este repositório foi criado como parte de um estudo prático e de aprendizado em ciência de dados e inteligência artificial, com foco em aplicações reais no contexto financeiro.
