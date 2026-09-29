# People Analytics: Análise de Indicadores de RH e Fatores Associados à Rotatividade de Colaboradores

[![Medium](https://img.shields.io/badge/Artigo%20completo-Medium-black?logo=medium\&logoColor=white)](https://medium.com/@luizamarchenib/people-analytics-an%C3%A1lise-de-indicadores-de-rh-e-fatores-associados-%C3%A0-rotatividade-de-colaboradores-844712462b25?postPublishedType=repub)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bBd4CWWKiKBigRE-VyQfEmY4AIjv8IBq?usp=sharing)

## Contexto

A Atlas Labs identificou a necessidade de desenvolver um relatório de People Analytics para acompanhar seus principais indicadores de Recursos Humanos e compreender os fatores associados à rotatividade dos colaboradores (attrition).

Os dados disponibilizados estão organizados em um Snowflake Schema, composto por uma tabela fato e cinco tabelas dimensão, contendo informações sobre colaboradores, avaliações de desempenho, satisfação e características profissionais e demográficas.

## Objetivo

Desenvolver um relatório de People Analytics capaz de monitorar os principais indicadores de RH e identificar características associadas à rotatividade dos colaboradores, utilizando a Análise Exploratória dos Dados como direcionador para a construção do dashboard.

## Análise

O projeto realizou:

* Mapeamento e entendimento da estrutura e das variáveis disponíveis;
* Definição dos principais KPIs de RH;
* Preparação e integração dos dados para a EDA;
* Análise exploratória univariada e bivariada;
* Teste qui-quadrado para análise de associações entre variáveis categóricas;
* Correlação de Pearson e análise de variância explicada (R²);
* Information Value (IV) para avaliar a diferenciação das variáveis em relação ao Attrition;
* Construção de um dashboard interativo em Power BI, orientado pelos resultados da EDA.

## Tecnologias

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Power Query
* Power BI
* DAX

## Estrutura do projeto

```text
hr_analytics/
│
├── EDA_HR_Analytics.ipynb    # Notebook com a análise exploratória
├── Power BI                   # Dashboard de People Analytics
├── README.md                  # Documentação do projeto
