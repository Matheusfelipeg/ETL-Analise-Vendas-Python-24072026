<h2 align="center">
  ETL e Análise de Vendas com Python
</h2>

<p align="center">
  Este projeto foi desenvolvido com o objetivo de criar um processo completo de ETL (Extract, Transform and Load) utilizando Python e Pandas para tratar, organizar e analisar dados de vendas. A partir de diferentes fontes de dados, foram realizadas etapas de limpeza, transformação, integração e geração de indicadores comerciais para apoiar a tomada de decisão.
</p>

<p align="center">
    <img alt="Python" src="https://img.shields.io/badge/Python-3.12-blue">
    <img alt="Pandas" src="https://img.shields.io/badge/Pandas-2.0-yellow">
    <img alt="NumPy" src="https://img.shields.io/badge/NumPy-1.26-green">
</p>


## 📄 Estrutura do repositório

- Veja o notebook completo do projeto:
[ETL_Analise_Vendas.ipynb](INSIRA_O_LINK_DO_NOTEBOOK)

- Arquivos gerados após o processo de transformação:
  - Vendas_SP.csv
  - Vendas_2024.csv


## ➕ Contexto

Empresas possuem diariamente grandes volumes de dados provenientes de diferentes sistemas e arquivos. Porém, antes que essas informações possam ser utilizadas em análises ou ferramentas de Business Intelligence, é necessário realizar etapas de tratamento, padronização e organização.

Neste projeto foi simulada uma situação real de uma empresa do setor de tecnologia que possui uma base de vendas e uma base contendo informações dos gerentes e metas comerciais.

O objetivo foi desenvolver um fluxo de ETL capaz de transformar dados brutos em uma base estruturada, permitindo a criação de indicadores relacionados ao desempenho comercial da empresa.


## ⚙️ Processo ETL

O projeto foi desenvolvido seguindo as três etapas principais:

### Extração

- Importação dos dados de vendas através de arquivo CSV;
- Importação das informações dos gerentes através de arquivo Excel.

### Transformação

Durante essa etapa foram realizadas:

- Remoção de informações desnecessárias;
- Tratamento de valores ausentes;
- Padronização dos nomes das lojas e produtos;
- Conversão de tipos de dados;
- Remoção de registros duplicados;
- Criação da coluna de faturamento;
- Classificação das vendas entre Online e Presencial;
- Identificação das regiões das lojas.

### Carga

Após o tratamento dos dados foram gerados novos arquivos contendo informações específicas para utilização em análises.


## 📊 Análises realizadas

Foram desenvolvidas análises comerciais utilizando a base tratada:

- Faturamento por loja;
- Faturamento por região;
- Produtos com maior faturamento;
- Produtos com maior faturamento no canal online;
- Comparativo entre vendas Online e Presencial;
- Avaliação dos gerentes em relação às metas;
- Evolução do faturamento ao longo do tempo.


## 🚀 Tecnologias

- 🐍 Python
- 📄 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- ⚡ Google Colaboratory
- 💻 GitHub


---

Desenvolvido por Matheus
