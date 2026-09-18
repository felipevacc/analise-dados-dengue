# Dengue em São Paulo — Mineração de Dados

Projeto acadêmico desenvolvido na disciplina **TT004 — Tópicos em Computação e Informática IV (UNICAMP)**.

Análise de casos prováveis de dengue nos **645 municípios de São Paulo**, entre **2019 e 2024**, utilizando técnicas de mineração de dados.

### Tecnologias

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Plotly

### Metodologia

Foi aplicado pré-processamento com **log1p + Z-score** e, posteriormente, o algoritmo **K-Means** para agrupar os municípios de acordo com seus padrões temporais de casos.

A análise resultou em **3 clusters**: incidência baixa, moderada e alta, utilizando também visualizações temporais, heatmap e mapa geográfico.

### Notebook

[DengueSP.ipynb](./DengueSP.ipynb)
