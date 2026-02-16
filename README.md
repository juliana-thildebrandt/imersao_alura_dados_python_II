# Imersão Alura — Dados com Python

Repositório criado para acompanhar minha primeira Imersão de Dados com Python.

## Status
Concluido 🚀

# Refazendo para consolidar aprendizado

Este projeto está sendo refeito manualmente no Google Colab como forma de consolidar o aprendizado.
O foco atual não é apenas executar o código, mas compreender cada etapa da análise.

## Conteúdo
- Aula 01 — Explore Dados com Pandas
- Aula 02 — Limpe e Prepare os Dados
- Aula 03 — Crie Gráficos e Conte Histórias com Dados
- Aula 04 — Construa um Dashboard Interativo

# Tecnologias utilizadas
- Google Colab
- Git & GitHub
- Python
- Pandas
- Plotly
- Streamlit

# Estrutura do projeto
📁 imersao-alura-dados
 ├── app.py
 ├── requirements.txt
 ├── dados-imersao-final.csv
 └── README.md

# Etapas realizadas
# 1 Leitura dos dados

df.head()
df.info()
df.describe()
df.shape

- Carregamento do dataset
- Transformação em DataFrame

# 2 Exploração inicial

df.head()
df.info()
df.describe()
df.shape

- Visualização das primeiras linhas
- Análise de tipos de dados
- Estatísticas básicas

# 3 Organização das colunas 

df.rename(columns=novos_nomes, inplace=True) 

- Padronização dos nomes

# 4 Análise de categorias

df['senioridade'].value_counts()

- Distribuição dos níveis de experiência
- Observação de padrões nos dados

# Dashboard

- Foi desenvolvido um dashboard utilizando Streamlit para visualizar:
- Distribuição salarial
- Comparação por senioridade
- Informações sobre trabalho remoto

- Local URL: http://localhost:8501
- Network URL: http://192.168.15.125:8501