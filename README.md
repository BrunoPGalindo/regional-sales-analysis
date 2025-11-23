### **[EN]**

# US Regional Sales Exploratory Data Analysis
This project's goal is to performs a Exploratory Data Analysis (EDA) on a US Regional Sales dataset. The primary goal is to analyze sales performance, profitability, and customer behavior across different regions, channels, and product lines.
The analysis process involves gathering data from a Excel file, data cleaning (merging different tables, handling missing values, type conversion etc.), feature engineering (calculating profit, margins), and visualization using Matplotlib, Seaborn, 
and Plotly. The information obtained from this project aims to identify high-performance states, seasonal trends, and revenue growth opportunities, simulating a real-world business intelligence task.

# Data
Data
The data source is a file named Regional Sales Dataset.xlsx. The raw data is in the spreadsheet, and it is organized as follows:

**Sales Orders:** Transactional data (Order Date, Quantity, Channel, etc.).

**Customers:** Customer names and IDs.

**Products:** Product names and IDs.

**Regions:** Geographic details (City, State, County, Population, Median Income).

**State Regions:** Mapping of states to broader US regions (South, West, Midwest, Northeast).

**2017 Budgets:** Budget targets for specific products.

## ****Key Engineered Features:****

`revenue`: Calculated as `order quantity * unit price`

`total_cost`: Calculated as `order quantity * unit cost`

`profit`: Calculated as `Revenue - Total Cost`

`profit_margin_pct`: Profitability percentage per order.

# Personal Contact Details
* **Bruno P. Galindo** [brunopgalindo@hotmail.com](mailto:brunopgalindo@hotmail.com) -- Contact for inquiries regarding data.

# Getting Started
For this analysis project, the file is contained within a Jupyter Notebook. To replicate the analysis:

1) Ensure the Regional Sales Dataset.xlsx file is in the correct directory.
2) Run the data scripts.
3) Run the visualization cells to generate the results as in the GitHub page.

# Requirements
To run this project, you will need a Python 3 environment with the following libraries installed:

**Step 1: Open the Python 3 environment of your choice**

**Step 2: Install the necessary libraries**
```
pip install pandas numpy matplotlib seaborn plotly openpyxl
```

**Step 3: Load the notebook scripts and run them all**

# Authors
* Bruno P. Galindo - Personal Project - https://www.linkedin.com/in/brunopgalindo/

# Project Motivation
* The intention of the project is to challenge me and develop critical thinking skills regarding the generated graphs, and to generate positive insights through their visualization.
* This is a public dataset and the only purpose of it is to be used for study. None of the data is sensitive in any way.
* Inspiration: Business intelligence workflows focusing on revenue optimization and regional performance analysis.
---

# **[PT/BR]**

# Análise Exploratória de Dados de Vendas Regionais dos EUA
O objetivo deste projeto é realizar uma Análise Exploratória de Dados (EDA) em um conjunto de dados de Vendas Regionais dos EUA. O objetivo principal é analisar o desempenho de vendas, lucratividade e comportamento do cliente em diferentes regiões, canais e linhas de produtos. O processo de análise envolve a coleta de dados 
de um arquivo Excel, limpeza de dados (mesclagem de tabelas diferentes, tratamento de valores ausentes, conversão de tipos etc.), engenharia de recursos (cálculo de lucro, margens) e visualização usando Matplotlib, Seaborn, e Plotly. As informações obtidas neste projeto visam identificar estados de alto desempenho, tendências sazonais
e oportunidades de crescimento de receita, simulando uma tarefa de inteligência de negócios do mundo real.

# Dados
Dados A fonte de dados é um arquivo chamado Regional Sales Dataset.xlsx. Os dados brutos estão na planilha e estão organizados da seguinte forma:

**Sales Orders**: Dados transacionais (Data do Pedido, Quantidade, Canal, etc.).

**Customers**: Nomes de clientes e IDs.

**Products**: Nomes de produtos e IDs.

**Regions**: Detalhes geográficos (Cidade, Estado, Condado, População, Renda Mediana).

**State Regions**: Mapeamento de estados para regiões mais amplas dos EUA (Sul, Oeste, Centro-Oeste, Nordeste).

**2017 Budgets**: Metas de orçamento para produtos específicos.

## **Variáveis Chaves Calculadas:**
`revenue`: Calculado como `order quantity * unit price`

`total_cost`: Calculado como `order quantity * unit cost`

`profit`: Calculado como `Revenue - Total Cost`

`profit_margin_pct`: Porcentagem de lucratividade por pedido.

# Dados Pessoais para Contato
* **Bruno P. Galindo** [brunopgalindo@hotmail.com](mailto:brunopgalindo@hotmail.com) -- Contato para perguntas relacionadas aos dados.

# Começando
Para este projeto, o arquivo está contido em um Jupyter Notebook. Para replicar a análise:

1) Garanta que o arquivo Regional Sales Dataset.xlsx esteja no diretório correto.
2) Execute os scripts de dados.
3) Execute as células de visualização para gerar os resultados como na página do GitHub.

# Requisitos
Para executar este projeto, você precisará de um ambiente Python 3 com as seguintes bibliotecas instaladas:

**Passo 1: Abra o ambiente Python 3 de sua escolha**

**Passo 2: Instale as bibliotecas necessárias**

```
pip install pandas numpy matplotlib seaborn plotly openpyxl
```

**Passo 3: Carregue os scripts do notebook e execute todos eles**

# Autores
* Bruno P. Galindo - Projeto Pessoal - https://www.linkedin.com/in/brunopgalindo/

# Motivação do Projeto
* O objetivo do projeto é me desafiar e desenvolver habilidades de pensamento crítico em relação aos gráficos gerados, além de gerar insights positivos por meio de sua visualização.
* Este é um conjunto de dados público e seu único propósito é ser usado para estudo. Nenhum dos dados é sensível de forma alguma.
* Inspiração: Fluxos de trabalho de Business Intelligence com foco em otimização de receita e análise de desempenho regional.
