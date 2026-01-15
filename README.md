# 🍷 Previsão de Qualidade de Vinhos com Random Forest

Este projeto utiliza Machine Learning para classificar a qualidade do "Vinho Verde" com base em suas características químicas. O modelo foi desenvolvido utilizando o algoritmo **Random Forest** e implementado no Google Colab. O dataset que utilizarei se encontra nesse link: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

## 📊 Sobre o Dataset
O conjunto de dados contém diversas propriedades de vinhos, como:
* Acidez fixa e volátil
* Teor alcoólico
* pH
* Densidade
* **Quality (Target):** Qualidade do vinho

## 🛠️ Tecnologias e Ferramentas
* **Linguagem:** Python 3.x
* **Bibliotecas:**  `Pandas` para manipulação de dados.
    * `Seaborn` e `Matplotlib` para visualização e correlação.
    * `Scikit-Learn` para o modelo de Machine Learning.
* **Modelo:** `RandomForestClassifier`

## 🚀 Fluxo do Projeto
1. **Captura dos dados** 
2. **Análise dos dados**
3. **Pré-processamento dos dados:** Separando os dados dos rótulos. Aqui, vinhos com qualidade igual ou maior que 7 receberam o rótulo 1(boa qualidade), e abaixo disso receberam o rótulo 0
4. **Divisão dos dados:** Dividindo os dados de teste e treinamento 
5. **Alimentar/treinar o modelo**
6. **Testando o modelo**

## 📈 Resultados
O modelo demonstrou uma excelente capacidade de generalização, alcançando:
* **Acurácia de Treino:** 100%
* **Acurácia de Teste:** 94%
