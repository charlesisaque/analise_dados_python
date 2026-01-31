# 📊 Análise de Salários na Área de Dados

Projeto educacional focado em **análise, limpeza, visualização de dados
e construção de dashboard interativo**, utilizando Python, Pandas,
Plotly, Seaborn e Streamlit.

Dashboard publicado:

👉 https://dashboard-salarios-dados.streamlit.app/

------------------------------------------------------------------------

## 🚀 Tecnologias Utilizadas

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn\
-   Plotly\
-   Streamlit\
-   PyCountry

------------------------------------------------------------------------

## 📁 Dataset

Fonte original:

https://raw.githubusercontent.com/guilhermeonrails/data-jobs/main/salaries.csv

Após limpeza e preparação, o dataset final é salvo como:

dados-imersao-final.csv

------------------------------------------------------------------------

## 📚 Estrutura do Projeto

### Aula 1 --- Análise Exploratória

-   Leitura do CSV\
-   Inspeção inicial (`head`, `info`, `describe`)\
-   Renomeação de colunas\
-   Tradução de categorias\
-   Análise de variáveis categóricas

Objetivo: entender o dataset e preparar os dados.

------------------------------------------------------------------------

### Aula 2 --- Limpeza de Dados

-   Verificação de valores nulos\
-   Preenchimento com média, mediana, ffill e bfill\
-   Remoção de linhas vazias\
-   Conversão de tipos

------------------------------------------------------------------------

### Aula 3 --- Visualização

-   Gráficos de barras\
-   Histogramas\
-   Boxplots\
-   Pizza / Donut\
-   Mapa mundial de salários

Bibliotecas usadas:

-   Seaborn\
-   Matplotlib\
-   Plotly

------------------------------------------------------------------------

### Aula 4 --- Dashboard com Streamlit

Funcionalidades:

-   Filtros por ano, senioridade, contrato e empresa\
-   KPIs principais\
-   Gráficos interativos\
-   Mapa mundial\
-   Tabela dinâmica

------------------------------------------------------------------------

## ⚙️ Executar Localmente

### Criar ambiente virtual

python -m venv .venv

### Ativar

Windows: .venv`\Scripts`{=tex}`\Activate`{=tex}

Mac/Linux: source .venv/bin/activate

------------------------------------------------------------------------

### requirements.txt

pandas==2.2.3\
streamlit==1.44.1\
plotly==5.24.1\
pycountry\
seaborn\
matplotlib\
numpy

------------------------------------------------------------------------

### Instalar dependências

pip install -r requirements.txt

------------------------------------------------------------------------

### Rodar projeto

streamlit run app.py

------------------------------------------------------------------------

## 🌎 Deploy

Realizado no Streamlit Cloud:

https://streamlit.io/cloud

------------------------------------------------------------------------

## 🎯 Objetivo

Demonstrar um fluxo completo de Data Analytics:

-   Exploração\
-   Limpeza\
-   Visualização\
-   Storytelling\
-   Dashboard interativo

Aplicado ao mercado real de dados.
