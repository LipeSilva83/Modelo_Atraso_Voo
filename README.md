# Modelo_Atraso_Voo

# :computer: Projeto de Modelagem Preditiva de Atraso de Voos
Este projeto de machine learning visa a criação, avaliação e otimização de modelos de regressão para prever o tempo de atraso de voos (delay). Utilizando Python, construímos uma linha de base (baseline) com o DummyRegressor e avançamos para a implementação, validação cruzada e ajuste fino de hiperparâmetros com o RandomForestRegressor, além de realizar engenharia de recursos e análise de resíduos.

# ⚙️ Tecnologias Utilizadas ⚙️
O projeto foi desenvolvido inteiramente em Python, aproveitando o ecossistema de bibliotecas de Data Science e Machine Learning para a manipulação, visualização de dados e construção dos modelos.

Linguagem de Programação: Python

Bibliotecas:

Pandas:

NumPy:

Scikit-learn:

Matplotlib:

Seaborn:

Yellowbrick:

# 🎯 Objetivo do Projeto

🧠 Algoritmos Implementados

O cerne deste projeto é a implementação, comparação e otimização de modelos de regressão para estimar o tempo de atraso dos voos.

DummyRegressor (Baseline): Utilizado para estabelecer uma linha de base simples (prevendo a média), servindo de parâmetro mínimo de comparação para os demais modelos.

Random Forest Regressor: Algoritmo de aprendizado supervisionado baseado em um conjunto de árvores de decisão aleatórias, utilizado para capturar relações complexas não lineares entre as variáveis explicativas e o tempo de atraso.

# 📊 Resultados e Análise

Os modelos foram treinados e validados utilizando etapas de tratamento de dados, engenharia de recursos (feature engineering e one-hot encoding com get_dummies), seleção de variáveis mais importantes (feature importance) e otimização de hiperparâmetros via GridSearchCV.

Baseline (DummyRegressor): Definiu a meta inicial a ser superada.

Random Forest Regressor: Apresentou desempenho superior à linha de base, demonstrando alta capacidade de generalização após validação cruzada e análise gráfica de resíduos (Residuals Plot e Prediction Error Plot).

Otimização: A seleção das 13 features mais relevantes e o ajuste de parâmetros via GridSearchCV permitiram reduzir a complexidade do modelo sem perda de performance.

# 🚀 Como Rodar o Projeto
Para replicar a análise e os modelos localmente ou na nuvem, siga os passos abaixo.

Clique no botão abaixo para abrir e executar o notebook diretamente no Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/LipeSilva83/Modelo_Atraso_Voo/blob/main/modelo_atraso_voo.ipynb)
📌 **Instruções adicionais 1:**

Se preferir rodar localmente, certifique-se de ter instalado as dependências necessárias.

O arquivo modelo_atraso_voo.ipynb contém toda a Análise Exploratória (EDA), pré-processamento, treinamento dos modelos e otimização do projeto.

📢 **Instruções adicionais 2:**

Se preferir rodar localmente, instale as dependências com pip install -r requirements.txt.

Execute o notebook modelo_atraso_voo.ipynb para visualizar o pipeline e os resultados.

# ✒️ Autor
[Filipe Silva] - https://github.com/LipeSilva83
