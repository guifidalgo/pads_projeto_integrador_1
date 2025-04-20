# Projeto Integrador – Master em Data Science (1º Trimestre)

## Descrição

Este projeto foi desenvolvido como parte do primeiro trimestre do Master em Data Science no Insper. O desafio consistia em construir um pipeline completo de dados e desenvolver modelos de classificação capazes de prever se uma empresa europeia deixaria de operar em até dois anos.

O trabalho integrou os conhecimentos adquiridos nas disciplinas de **Python para Ciência de Dados** e **Aprendizagem Estatística de Máquina I**, utilizando uma base de dados real com empresas atuantes entre 2005 e 2016.

## Objetivo

Criar, testar e avaliar modelos preditivos com base em dados financeiros e operacionais, simulando uma situação real de aplicação de Data Science em contexto empresarial.

## Pipeline do Projeto

- **Pré-processamento em Python:**
  - Limpeza de dados e remoção de colunas com alto índice de valores ausentes
  - Criação de novas variáveis (idade da empresa, transformação de vendas)
  - Ajustes em variáveis com inconsistências (ex.: vendas negativas)
  - Definição da variável-alvo com base em operação futura
  - Filtragem de empresas com receita entre 1 mil e 10 milhões de euros

- **Modelagem em R:**
  - Construção e avaliação de modelos preditivos:
    - Regressão Logística
    - Árvore de Decisão
    - Random Forest
    - XGBoost
  - Avaliação com métricas:
    - Acurácia
    - AUC
    - Sensibilidade e Especificidade
  - Interpretação de modelos com:
    - VIP (Variable Importance Plot)
    - PDP (Partial Dependence Plot)

## Resultados

O modelo final apresentou excelente desempenho preditivo, com destaque para variáveis de vendas, idade da empresa e estrutura de capital. O projeto recebeu **nota máxima** pela banca avaliadora.


## Requisitos

### Python
- pandas
- numpy
- matplotlib
- seaborn
- missingno

### R
- glmnet
- rpart
- ranger
- xgboost
- vip
- pdp
- DALEX
- caret

## Autores

Projeto desenvolvido por **Grupo 02 - Guilherme Fidalgo, Arthur Campedelli, Eric Lee** do Master em Data Science – Insper.  
