# Previsão de preços de imóveis 

## Sobre o projeto
Projeto que demonstra uma pipeline de regressão linear, aonde as etapas de Análise exploratória dos dados, limpeza dos dados, feature engineering, preparação para modelagem, 
modelagem e avaliação foram realizadas.

-Base de dados: Os dados utilizados foram do dataset sugerido pela avaliação, "House Sales in King County, USA".
Este conjunto de dados contém os preços de venda de casas no Condado de King, que inclui Seattle, Inclui imóveis vendidos entre maio de 2014 e maio de 2015.
Foram avaliadas as 21613 linhas de dados.
## O que o projeto analisa 
- Receita total e volume de vendas por mês
- Top produtos em venda, receita por categoria
- Desempenho por estado "EUA"- Segmentação de clientes por nível de gasto (Bronze, Prata, Ouro)
- Comparação entre os dados com e sem tratamento de outliers (v1 e v2)
- Exportação de relatórios em CSV e JSON 
## Objetivo 
Praticar os principais conceitos: 
- Lógica de programação com Python
- Variáveis, tipos de dados e operadores
- Condicionais (if, elif, else) e repetição (for, while)
- Funções com parâmetros, retorno e funções lambda
- Funções reutilizáveis
- Leitura e escrita de arquivos CSV e JSON
- Módulo datetime para manipulação de datas
- Expressões regulares com o módulo re
- Pandas: DataFrames, limpeza, groupby, filtros e transformações
- NumPy: arrays, operações vetorizadas, broadcasting
- Detecção e tratamento de outliers (IQR ou z-score)
- Matplotlib e Seaborn: gráficos, customização e exportação em PNG
- Uso básico do GitHub 
## Como executar 
### No Google Colab (recomendado) 
1. Faça upload do notebook Projeto.ipynb 
2. Abra o arquivo carregado no Colab 
3. Execute as células na ordem, de cima para baixo 
## Estrutura do projeto 
projeto
- data 

           dataset bruto
  
           V_1 com outliers
  
           V2 outliers tratado
  
- Notebook

          Projeto.ipynb  
 
- outputs
  
          Gráficos 

          US Superstore data (1)_v2_clientes.csv

          US Superstore data (1)_v2_por_mes.csv

          US Superstore data (1)_v2_stats.json 

- final                   
                  
# Dataset bruto gerado/baixado 
"US Superstore data" retirado do site 
"https://www.kaggle.com/datasets/juhi1994/superstore/data"
no dia 18/06/2026
# Dados de limpeza geral, outliers mantidos 
- v2_outliers_tratado
- Limpeza v1 + tratamento de outliers 
# Dataset escolhido para uso futuro 
  - dataview.ipynb           
  - outputs
  - metricas_por_mes.csv 
  - segmentacao_clientes.csv 
  - estatisticas_gerais.json 
  - graficos
  -  README.md   
## Ferramentas utilizadas 
- Python 3.10+ 
# Notebook principal de EDA 
- Google Colab 
- Bibliotecas: pandas, numpy, matplotlib, seaborn, re, datetime, os, random
- GitHub para versionamento 
## Vídeo de demonstração 
[Inserir link do Google Drive ou YouTube aqui] 
