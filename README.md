# 📊 Projeto ETL - Análise de Vendas com Python

## 📌 Sobre o projeto

Este projeto tem como objetivo desenvolver um processo completo de **ETL (Extract, Transform and Load)** utilizando Python e Pandas para tratamento, organização e análise de uma base de dados de vendas.

O projeto simula um cenário empresarial onde uma empresa possui informações de vendas e metas comerciais armazenadas em diferentes arquivos. A partir desses dados, foi realizado um processo de limpeza, transformação, integração e geração de indicadores para apoiar a tomada de decisão.

---

# 🎯 Objetivos

- Realizar a extração de dados provenientes de diferentes fontes;
- Realizar limpeza e padronização das informações;
- Criar novas métricas para análise de desempenho;
- Integrar bases de dados utilizando Python;
- Gerar arquivos tratados para utilização posterior;
- Desenvolver análises comerciais utilizando os dados processados.

---

# 🛠️ Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Jupyter Notebook / Google Colab
- GitHub

---

# 🔄 Fluxo do Projeto ETL

```
                 EXTRAÇÃO
                    |
                    ↓
        Leitura dos arquivos CSV e Excel
                    |
                    ↓
               TRANSFORMAÇÃO
                    |
                    ↓
       - Tratamento de valores ausentes
       - Padronização de textos
       - Conversão de datas
       - Remoção de duplicados
       - Criação de novas métricas
       - Integração entre bases
                    |
                    ↓
                  CARGA
                    |
                    ↓
        Exportação dos dados tratados
        para novos arquivos
```

---

# 📥 Extração dos dados

Foram utilizadas duas bases de dados:

### Base de vendas

Contém informações relacionadas aos pedidos realizados pela empresa, como:

- ID do pedido;
- Data da venda;
- Loja;
- Produto;
- Quantidade;
- Preço unitário.

### Base de gerentes

Contém informações dos responsáveis pelas lojas e suas respectivas metas mensais.

---

# 🧹 Tratamento e transformação dos dados

Durante a etapa de transformação foram realizadas as seguintes operações:

✅ Remoção de colunas desnecessárias;

✅ Tratamento de valores ausentes;

✅ Conversão da coluna de datas para o formato adequado;

✅ Padronização dos nomes das lojas e produtos;

✅ Remoção de registros duplicados utilizando o ID do pedido;

✅ Criação da coluna de faturamento;

✅ Classificação das vendas entre Online e Presencial;

✅ Identificação da região de cada loja.

---

# 📤 Carga dos dados

Após o tratamento, foram gerados novos arquivos contendo informações específicas para utilização em análises.

Arquivos exportados:

- Vendas realizadas na loja de São Paulo;
- Vendas realizadas durante o ano de 2024.

Essa etapa representa a disponibilização dos dados tratados após o processo de ETL.

---

# 📈 Análises realizadas

## 🏪 Faturamento por loja

Análise do faturamento total de cada loja para identificar quais unidades apresentaram maior desempenho financeiro.

---

## 🌎 Faturamento por região

Análise do desempenho comercial agrupando as lojas por região do Brasil.

---

## 🛒 Produtos com maior faturamento

Identificação dos produtos que mais contribuíram para a receita total da empresa.

---

## 💻 Produtos com maior faturamento no canal online

Análise específica das vendas realizadas pelo canal digital, identificando os produtos com maior participação no faturamento online.

---

## 🔄 Comparativo Online x Presencial

Comparação entre os dois canais de venda para identificar qual modalidade possui maior contribuição no faturamento.

---

## 🎯 Desempenho dos gerentes e metas

Integração da base de vendas com a base de gerentes para avaliar:

- Faturamento realizado;
- Meta mensal;
- Status da meta;
- Percentual de atingimento.

---

## 📊 Evolução do faturamento

Visualização da evolução das vendas ao longo do tempo para identificar tendências e variações no desempenho comercial.

---

# 📂 Estrutura do projeto

```
Projeto-ETL-Vendas/
│
├── ETL_Analise_Vendas.ipynb
│
├── README.md
│
├── dados/
│   ├── vendas.csv
│   └── gerentes.xlsx
│
└── output/
    ├── Vendas_SP.csv
    └── Vendas_2024.csv
```

---

# 📌 Principais aprendizados

Durante o desenvolvimento deste projeto foram aplicados conhecimentos de:

- Manipulação de dados com Pandas;
- Limpeza e tratamento de dados;
- Criação de indicadores;
- Integração de diferentes fontes de dados;
- Análise exploratória;
- Organização de projetos de dados.

---

# 🚀 Próximas melhorias

Algumas melhorias que podem ser implementadas futuramente:

- Automatização do pipeline ETL;
- Integração com banco de dados SQL;
- Criação de dashboard em Power BI;
- Implementação de atualização automática dos dados.

---

# 👨‍💻 Autor

Matheus

Projeto desenvolvido com o objetivo de aprimorar habilidades em **Análise de Dados, Python e Business Intelligence**.
