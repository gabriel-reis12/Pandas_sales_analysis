# 📊 Projeto de Análise de Vendas com Python e Pandas

## 📝 Descrição do Projeto

Este projeto utiliza Python 🐍 e a biblioteca Pandas 🐼 para analisar um conjunto de dados de vendas. O objetivo é calcular médias e porcentagens relevantes para ajudar a entender melhor o desempenho das vendas.

## 🔧 Requisitos

- Python 3.10.12
- Biblioteca Pandas

## 🚀 Como Executar o Projeto

1. Clone este repositório.
2. Instale as dependências com o comando `pip install pandas`.

## 📈 Detalhes da Implementação

O script principal lê um arquivo CSV de vendas utilizando a função `pandas.read_csv()`. Em seguida, ele realiza várias operações para calcular as médias e porcentagens desejadas.

Aqui está um exemplo de como o código pode se parecer:

```python
import pandas as pd

# Ler o arquivo de dados
df = pd.read_csv('train.csv')

# Calcular a média de vendas
media_de_vendas = df.groupby('Categoria')['Vendas'].mean().round(2)

# Calcular a porcentagem de vendas por categoria
total_de_vendas = novo_df['Media de vendas'].sum()
novo_df['% de Vendas'] = novo_df['Media de vendas'].apply(lambda x: (x / total_de_vendas) * 100).round(2)
novo_df

