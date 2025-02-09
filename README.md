# Análise e Seleção de Features em Conjuntos de Dados de Saúde e Titanic

Este repositório contém análises exploratórias e experimentos de seleção de features em três conjuntos de dados distintos: Diabetes, Doenças Cardíacas e Titanic. O objetivo principal é compreender a importância das variáveis e identificar quais delas são mais relevantes para modelos de aprendizado de máquina.

## Estrutura do Repositório

O repositório está organizado em três diretórios principais:

- **Diabetes/**
  - `FS_Diabetes.ipynb`: Notebook contendo a análise exploratória e seleção de features para o conjunto de dados de diabetes.
  - `diabetes.csv`: Conjunto de dados sobre diabetes.

- **Predicao_Doencas_Cardiacas/**
  - `FS_PDC.ipynb`: Notebook contendo a análise exploratória e seleção de features para o conjunto de dados de doenças cardíacas.
  - `Heart_Disease_Prediction.xls`: Conjunto de dados sobre doenças cardíacas.

- **Titanic/**
  - `FS_Titanic.ipynb`: Notebook contendo a análise exploratória e seleção de features para o conjunto de dados do Titanic.
  - `gender_submission.csv`, `test.csv`, `titanic.csv`, `train.csv`: Conjuntos de dados relacionados ao naufrágio do Titanic.

## Metodologia

O fluxo de trabalho seguido nos notebooks é o seguinte:

1. **Análise e Entendimento dos Dados**
   - Inspeção inicial dos dados.
   - Verificação de estatísticas descritivas.
   
2. **Tratamento de Dados**
   - Manipulação de valores ausentes.
   - Identificação e remoção de constantes.
   
3. **Preparação dos Dados**
   - Separação da variável target.
   - Divisão dos dados em treino e teste (80% treino, 20% teste).
   
4. **Normalização das Variáveis**
   - Aplicação de técnicas de normalização para padronizar os dados.
   
5. **Seleção de Features**
   - Aplicação e comparação de diferentes métodos de seleção de features:
     - **Boruta**
     - **Recursive Feature Elimination (RFE)**
     - **Feature Importance (Baseado em Modelos de Árvores)**
     - **PCA + Information Value (IV)**
     - **Corte por Information Value (IV)**
     - **Correlação de Pearson**
   
6. **Comparação dos Métodos**
   - Análise das variáveis selecionadas por cada método.
   - Identificação das features mais relevantes com base na consistência entre os métodos.

Caso tenha dúvidas ou sugestões, entre em contato!

