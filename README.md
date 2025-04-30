# 🏦 Previsão de Inadimplência de Crédito

Projeto de ciência de dados com foco em prever inadimplência de clientes com base em dados demográficos, financeiros e de histórico de crédito. Dataset utilizado: [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/)

## Objetivo

Criar um modelo preditivo que classifique clientes como adimplentes ou inadimplentes, apoiando decisões de concessão de crédito.

## 📦 Tecnologias utilizadas

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Técnicas Utilizadas

- Análise Exploratória de Dados (EDA)
- Engenharia de Variáveis
- Seleção de Variáveis
- Modelos de Classificação:
  - Regressão Logística
  - Random Forest
- Avaliação com métricas e gráficos (ROC AUC, f1-score, matriz de confusão)
- Interpretação de variáveis mais relevantes

## Etapas do Projeto

- Leitura e limpeza dos dados
- Análise univariada e bivariada das variáveis categóricas e numéricas
- Criação de variáveis derivadas úteis
- Seleção de variáveis por correlação com TARGET
- Modelagem com pipelines de pré-processamento
- Avaliação com métricas clássicas e curva ROC

## Estrutura do Projeto

- `data/`: Deve conter os conjuntos de dados utilizados no projeto. Disponiveis em https://www.kaggle.com/competitions/home-credit-default-risk/
- `notebooks/`: Notebook Jupyter com desenvolvimento do modelo.
- `README.md`: Documentação do projeto.

## 🚀 Como rodar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/MatheusFL99/home-credit-risk.git
   cd home-credit-risk
   ```
2. Crie um ambiente virtual python:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Execute os notebooks. (lembre de baixar o dataset e colocar na pasta `data/`)

## Futuramente

- Melhorar a predição, pois o resultado pode melhorar.
- Criar dashboards interativos para testar diversos casos e ter uma visualização disso.
