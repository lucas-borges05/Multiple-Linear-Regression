# 🚗 Previsão de Emissões de CO₂ — Regressão Linear Múltipla

Projeto de Machine Learning utilizando **Regressão Linear Múltipla** para prever emissões de CO₂ de veículos a partir de múltiplas características.

## 🎯 Objetivo

Desenvolver um modelo capaz de estimar as **emissões de CO₂ (g/km)** considerando simultaneamente diferentes características dos veículos.

## 🧠 Conceitos aplicados

* Regressão Linear Múltipla
* Análise exploratória de dados
* Matriz de correlação
* Seleção de variáveis
* Identificação de multicolinearidade
* Padronização de variáveis
* Divisão entre treino e teste
* Interpretação de coeficientes
* Visualização dos resultados

## 🛠️ Tecnologias

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 📊 Variáveis analisadas

Entre as características utilizadas na modelagem estão:

* Tamanho do motor (`ENGINESIZE`)
* Consumo combinado (`FUELCONSUMPTION_COMB_MPG`)
* Emissões de CO₂ (`CO2EMISSIONS`)

Durante a análise, também são avaliadas relações entre variáveis para reduzir redundâncias e selecionar atributos mais relevantes para o modelo.

## 🔎 Abordagem

O projeto passa pelas principais etapas de um fluxo de Machine Learning:

1. Exploração dos dados;
2. Análise das correlações;
3. Seleção das variáveis;
4. Pré-processamento;
5. Separação entre treino e teste;
6. Treinamento do modelo;
7. Análise dos coeficientes;
8. Visualização e avaliação dos resultados.

## 💡 Aprendizados

O projeto permitiu compreender como múltiplas variáveis podem ser utilizadas conjuntamente para explicar uma variável-alvo e como correlação e multicolinearidade podem influenciar modelos de regressão.

## 📁 Estrutura

```text
├── Mulitple-Linear-Regression-v1.ipynb
└── README.md
```
