# Projeto - Limpeza e Tratamento de Dados para Machine Learning

## Objetivo

Este projeto tem como objetivo realizar a limpeza, o tratamento e a preparação de um conjunto de dados de uma empresa de telecomunicações, estruturando a base para futuras etapas de análise e construção de modelos de Machine Learning.

Durante o processo, foram identificados e tratados problemas relacionados à qualidade dos dados, como valores ausentes, valores vazios, registros duplicados, inconsistências, tipos incorretos, outliers e variáveis categóricas, garantindo uma base mais consistente e adequada para análises e modelagem preditiva.

O conjunto de dados utilizado apresenta informações relacionadas ao **churn de clientes**, permitindo preparar dados de qualidade para futuros modelos capazes de prever o cancelamento de serviços.

---

## Tecnologias utilizadas

* Python
* Pandas
* NumPy
* JSON
* Seaborn
* Jupyter Notebook / Google Colab

---

## Etapas do projeto

### 1. Importação das bibliotecas

* Importação das bibliotecas utilizadas durante o processo de análise, tratamento e visualização dos dados.

### 2. Carregamento da base de dados

* Importação do conjunto de dados em formato JSON.
* Leitura e carregamento inicial da base utilizando Pandas e a biblioteca JSON.

### 3. Entendimento inicial dos dados

* Visualização das primeiras informações do dataset.
* Identificação da estrutura dos dados.
* Análise da quantidade de registros e colunas.
* Verificação dos tipos das variáveis.
* Identificação de possíveis problemas na qualidade dos dados.

### 4. Normalização dos dados

* Tratamento da estrutura dos dados em formato JSON.
* Normalização de dados aninhados para transformação em uma estrutura tabular.
* Conversão dos dados para um formato adequado para análise utilizando Pandas.

### 5. Tratamento e limpeza dos dados

Foram aplicadas técnicas de tratamento e preparação dos dados, incluindo:

* Identificação e tratamento de valores ausentes.
* Identificação e remoção de registros duplicados.
* Tratamento de valores vazios.
* Correção de valores inconsistentes.
* Ajuste dos tipos de dados.
* Padronização das informações.
* Identificação e tratamento de outliers.
* Tratamento e transformação de variáveis categóricas.
* Preparação da base para utilização em análises e modelos de Machine Learning.

### 6. Exportação dos dados tratados

Após o processo de limpeza e tratamento, foi gerado um novo dataset em formato CSV, contendo os dados tratados e estruturados para utilização em análises futuras e desenvolvimento de modelos preditivos.

---

## Estrutura do projeto

```text
limpeza-tratamento-churn/
│
├── dados/
│   ├── bruto/
│   │   └── dataset-original.json
│   └── tratado/
│       └── dataset-tratado.csv
│
├── notebook/
│   └── tratamento_limpeza_dados.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Resultado

Ao final do projeto, foi obtida uma base de dados limpa, padronizada e estruturada, pronta para utilização em processos de análise exploratória e etapas futuras de construção de modelos de Machine Learning.

Este projeto demonstra a aplicação de técnicas de preparação, limpeza e tratamento de dados, uma etapa fundamental no ciclo de desenvolvimento de soluções de dados e inteligência artificial.
