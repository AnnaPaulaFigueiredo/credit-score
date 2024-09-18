#[BUILDING....]
# Projeto de Análise de Risco de Crédito dos Clientes

## Cenário Problema

No atual cenário econômico, instituições financeiras enfrentam o desafio de avaliar o risco de crédito dos clientes. A inadimplência pode levar a prejuízos significativos, e a capacidade de classificar os clientes em categorias de risco é fundamental para decisões de concessão de crédito.

Com o Banco DSA não é diferente. O banco busca expandir seus negócios e além disso, informatizar seu sistema de geração de SCORE de crédito. O desafio da vez é analisar um conjunto de dados para ajudar o Banco DSA na tomada de decisão.

## Objetivo do Projeto

O objetivo deste projeto é desenvolver um modelo preditivo que gere um score para um novo cliente. Além disso, que classifique os clientes em categorias de risco (Bom Cliente, Cliente em Risco e Mau Cliente) com base em suas características socioeconômicas e financeiras.

A análise busca entender como diferentes fatores influenciam o score de crédito e, consequentemente, a probabilidade de inadimplência. Uma vez que a empresa busca expandir seus negócios, deseja identificar quais estados têm a maior concentração de bons clientes, ajudando assim a instituição a decidir onde abrir novas filiais.

## Base de Dados

Os dados utilizados neste projeto estão disponíveis para _download_ em: [Link para Material Didático](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbUxhRGFtZzZJT0hCVGowNUhTVXlqRk4wQkZhZ3xBQ3Jtc0tubGFGSG1iUkY1ZzB2Y1NLcThXdGRqb0I5QUttM08tUnNqdnpDSUsxRnJxY1poY1dQbElNYTJIeWlsQWFzS2NDbXFFbjJET1FRdXdocHo2cEZyMThQMGZ1MU9ENEcxUl9rUjVKTVd0N3pBM09xRlZmaw&q=https%3A%2F%2Fdocs.google.com%2Fuc%3Fexport%3Ddownload%26id%3D1TRX_JpDAhk-qtXZsZM-xJc43KCN287-E&v=lK8ANM7VkNU). Esses dados e contexto foram modificados do material disponibilizado no Canal Nerd dos Dados e estão disponíveis aqui no GitHub para fins de análise.

## Características Principais

### 1. Pré-processamento de Dados

- **Verificação e Imputação de Valores Nulos:** Identifica e preenche valores ausentes com métodos como média, mediana, e outros.
- **Tratamento de Outliers:** Substitui ou remove outliers para melhorar a qualidade dos dados.

### 2. Análise e Estatísticas

- **Estatísticas Descritivas:** Fornece uma visão geral dos dados, incluindo contagem, média e desvio padrão, segmentadas por categorias relevantes.

### 3. Visualização de Dados

- **Gráficos:** Utiliza Seaborn e Plotly para criar visualizações que destacam a relação entre diferentes variáveis e o score de crédito.

### 4. Aplicação do Modelo de Aprendizado de Máquina

- **Classificação de Clientes:** Aplica técnicas de aprendizado de máquina para prever a classificação de risco dos clientes com base nas características dos dados.

## Conclusão