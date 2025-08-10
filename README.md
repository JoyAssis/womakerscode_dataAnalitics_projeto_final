# Análise e Previsão da Evolução Global do Câncer (2015-2024)

![Python](https://img.shields.io/badge/Python-3-blue.svg) ![Pandas](https://img.shields.io/badge/Pandas-Library-green.svg) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange.svg) ![Seaborn / Plotly](https://img.shields.io/badge/Visualização-Plotly-purple.svg) ![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)

## 1. Resumo do Projeto

Este é o desafio final do **Bootcamp de Análise de Dados da WoMakersCode 2025**, realizado em equipe pela **Squad Mary Jackson**. O projeto consiste em uma análise exploratória e preditiva completa sobre a incidência de câncer no mundo entre 2015 e 2024, utilizando um dataset com 50.000 registros. O objetivo final é extrair insights que possam apoiar a criação de políticas públicas de prevenção.

O trabalho abrange desde a limpeza e tratamento dos dados, passando pela análise exploratória (EDA) e criação de visualizações interativas, até a aplicação de modelos de machine learning para prever cenários futuros e identificar os fatores de maior impacto na severidade da doença.

## 2. O Desafio Proposto

O desafio consistia em realizar uma análise completa dos dados de pacientes com câncer, seguindo quatro etapas principais:
1.  **Análise Exploratória (EDA):** Identificar padrões geográficos, temporais e demográficos.
2.  **Visualização de Dados:** Criar gráficos e mapas para comunicar os achados de forma clara.
3.  **Modelagem Preditiva:** Prever a evolução dos casos e analisar o impacto de diferentes variáveis.
4.  **Proposta de Intervenção:** Sugerir estratégias de prevenção com base nos insights gerados.

## 3. A Squad e a Metodologia de Trabalho

* **Equipe:** Squad Mary Jackson, composta por 6 integrantes: Ana Carolina Ramalho, Dâmaris Lima de Oliveira, Joyce Assis, Ludmilla Perucci dos Santos, Marina Severo Morales e Willa Regina Sena Evangelista.
* **Organização:** O trabalho foi desenvolvido de forma colaborativa, com encontros semanais aos sábados para discussão e desenvolvimento das análises. A equipe designou responsáveis pela apresentação de cada etapa do projeto e realizou sessões de treino para garantir a qualidade da entrega final.

## 4. Metodologia da Análise

O projeto seguiu um fluxo de trabalho estruturado:

1.  **Preparação e Limpeza dos Dados:** A fase inicial incluiu a importação das bibliotecas e do dataset, seguida pela análise da estrutura dos dados. Foram aplicados tratamentos específicos para garantir a consistência, como a remoção de registros incoerentes (ex: câncer de próstata em mulheres) e a amostragem para rebalancear casos de câncer de mama em homens.
2.  **Análise Exploratória (EDA):** Investigamos os dados para responder perguntas chave, como os países com maior incidência , a evolução de casos ao longo dos anos e as diferenças de incidência por gênero, faixa etária e tipo de câncer.
3. **Visualização de Dados:** Foram criadas diversas visualizações para ilustrar os achados da EDA, incluindo um mapa interativo de incidência global , séries temporais por continente e gráficos de barras comparativos.
4.  **Modelagem Preditiva:** Utilizamos modelos de séries temporais para prever o número de casos em 2025 e uma matriz de correlação para identificar as variáveis com maior impacto na severidade da doença , utilizando `Target_Severity_Score` como a variável alvo.

## 5. Principais Insights e Resultados

* **Previsão para 2025:** Utilizando modelos de séries temporais baseados na evolução histórica, o projeto previu um total de **4.344 casos** para o ano de 2025.
* **Fatores de Risco (Severidade):** A análise de correlação mostrou que `Risco Genético` (0.48) e `Tabagismo` (0.48) têm a correlação positiva mais forte com a severidade do câncer. `Poluição do Ar` (0.37) e `Consumo de Álcool` (0.36) também são fatores de impacto moderado.
* **Fator de Proteção:** Curiosamente, o `Custo do Tratamento` apresentou uma correlação negativa (-0.47) com a severidade, sugerindo que tratamentos mais caros podem estar associados a desfechos menos severos da doença.
* **Distribuição Geográfica:** A análise revelou que, entre 2015 e 2024, a **América** foi o continente com o maior número de casos reportados, com destaque para **EUA** e **Brasil**.

## 6. Proposta de Intervenção

Com base nos resultados, a equipe sugeriu que as políticas públicas de prevenção devem ser priorizadas nos países mais afetados, como os da América. As estratégias propostas incluem:
* Campanhas antitabagismo e de incentivo a hábitos saudáveis.
* Educação em saúde e programas de rastreamento precoce.
* Melhora no acesso a diagnósticos para reduzir custos e severidade.

## 7. Ferramentas e Tecnologias

* **Linguagem e Bibliotecas:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, Statsmodels.
* **Business Intelligence:** Power BI para a introdução do dashboard.
* **Ambiente:** Google Colab.

## 8. Reflexões da Squad

* **Facilidades:** O grupo teve sucesso no estabelecimento de prazos e responsabilidades e na resolução dos exercícios em geral.
* **Dificuldades:** Os principais desafios foram desenvolver a modelagem preditiva de forma mais aprofundada e manter a presença constante de todos os membros nos encontros.

## 9. Como Executar o Projeto

1.  Clone este repositório.
2.  Abra o notebook (`.ipynb`) no Google Colab ou em um ambiente Jupyter com as bibliotecas listadas instaladas.
3.  Certifique-se de que o dataset `global_cancer_patients_2015_2024.csv` esteja no mesmo diretório ou forneça o caminho correto para o arquivo.
4.  Execute as células em ordem para reproduzir a análise.
