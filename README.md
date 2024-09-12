# Projeto de Predição de Score de Clientes

## Objetivo do Projeto

O objetivo deste projeto é prever o score dos clientes utilizando regressão linear. O modelo é treinado com dados obtidos de um vídeo no YouTube, disponível em [este link](https://www.youtube.com/watch?v=lK8ANM7VkNU). O projeto explora várias técnicas de pré-processamento de dados e análise para garantir a precisão e a robustez das previsões.


## Base de Dados

Os dados utilizados neste projeto estão disponíveis para _download_ em: [Link para Material Didático](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbUxhRGFtZzZJT0hCVGowNUhTVXlqRk4wQkZhZ3xBQ3Jtc0tubGFGSG1iUkY1ZzB2Y1NLcThXdGRqb0I5QUttM08tUnNqdnpDSUsxRnJxY1poY1dQbElNYTJIeWlsQWFzS2NDbXFFbjJET1FRdXdocHo2cEZyMThQMGZ1MU9ENEcxUl9rUjVKTVd0N3pBM09xRlZmaw&q=https%3A%2F%2Fdocs.google.com%2Fuc%3Fexport%3Ddownload%26id%3D1TRX_JpDAhk-qtXZsZM-xJc43KCN287-E&v=lK8ANM7VkNU). Esse material não é de minha autoria é do Canal Nerd dos Dados e foi utilizado somente para fins de inspiração. Caso os links saiam do ar, não me reponsabilizo. Entretanto subirei uma cópia da base de dados aqui no github.


## Características Principais

### 1. Pré-processamento de Dados

- **Verificação de Valores Nulos:** Identifica e calcula a porcentagem de valores nulos em cada coluna do DataFrame.
- **Imputação de Valores Nulos:** Imputa valores ausentes em uma coluna usando diferentes métodos, incluindo média, mediana, moda, e métodos mais avançados como k-NN e regressão.
- **Tratamento de Outliers:** Substitui outliers em uma coluna com base em métodos como média, mediana ou moda.

### 2. Análise e Estatísticas

- **Contagem e Porcentagem de Valores Únicos:** Calcula a contagem e a porcentagem de valores únicos em uma coluna.
- **Estatísticas Detalhadas por Grupo:** Fornece estatísticas descritivas detalhadas para uma coluna, agrupadas por outra coluna. Inclui contagem, porcentagem, valores máximos e mínimos, média, mediana, desvio padrão, assimetria, kurtosis e intervalo interquartílico.

### 3. Visualização de Dados

- **Paleta de Cores Consistente:** Utiliza uma paleta de cores consistente em visualizações feitas com Seaborn e Plotly.
- **Gráficos com Seaborn e Plotly:**
  - **Boxplot:** Visualiza a distribuição dos dados e identifica potenciais outliers.
  - **Histograma:** Plota a distribuição de uma variável.
  - **Distribuição:** Plota a densidade de uma variável, com opções para visualização simples ou agrupada.

### 4. Pré-processamento dos Dados

- **Formatação essencial para Modelagem Computacional:** 

### 5. Aplicação do Modelo de Regressão Linear

- **Previsão do Score dos Clientes:** Utiliza a técnica de regressão linear para prever o score dos clientes com base nas características dos dados.
