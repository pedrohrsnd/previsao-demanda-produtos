# Previsão de Demanda de Produtos com Machine Learning

## Sobre o Projeto

Este projeto foi desenvolvido como trabalho final da disciplina **Ciência de Dados**.  
O objetivo é construir uma aplicação prática utilizando técnicas de **Machine Learning** para prever a demanda de produtos em um ambiente de varejo, com base em características como categoria do produto, loja, investimento em marketing e semana de feriado.

## Problema Resolvido

A previsão de demanda é essencial para otimizar o estoque, reduzir desperdícios e melhorar a tomada de decisão em empresas varejistas. Neste projeto, utilizamos um modelo supervisionado para prever a demanda esperada de produtos com base em variáveis previamente conhecidas.

---

## Etapas Realizadas

### 1. Simulação dos Dados
Para fins educacionais e considerando o prazo do projeto, foi utilizado um **dataset sintético** (simulado), gerado programaticamente para representar um cenário realista de vendas.

As variáveis simuladas incluem:
- `Product_Category`: Categoria do produto (A, B, C)
- `Store_ID`: Identificador da loja
- `Stock_Available`: Estoque disponível
- `Marketing_Spend`: Investimento em marketing
- `Holiday_Week`: Se a semana tem feriado (1) ou não (0)
- `Demand`: Quantidade demandada (variável alvo)

>  A simulação foi usada como substituto viável a datasets reais públicos, mantendo a lógica e complexidade compatíveis com dados reais.

### 2. Pré-processamento
- Codificação de variáveis categóricas com `LabelEncoder`
- Verificação e limpeza de valores nulos

### 3. Análise Exploratória
- Estatísticas descritivas
- Mapa de correlação entre variáveis
- Gráficos com Matplotlib e Seaborn

### 4. Modelagem
Foram utilizados dois modelos:
- **Regressão Linear**  
- **Random Forest Regressor**

As métricas de avaliação utilizadas foram:
- **RMSE (Root Mean Squared Error)**
- **R² (Coeficiente de Determinação)**

### 5. Visualização dos Resultados
- Gráfico de dispersão comparando valores reais e previstos

---

## Tecnologias Utilizadas

- **Python 3**
- **Google Colab**
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## Autor

- Nome: Pedro Henrique Resende Alves
- RA: 5123177
- Curso: Engenharia da Computação
- Matéria: Ciência de Dados
- Professor: Clênio Eduardo
- Data: Junho de 2025

---
