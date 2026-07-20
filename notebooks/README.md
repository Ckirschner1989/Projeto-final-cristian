# Previsão de preços de imóveis 

## Sobre o projeto
Projeto que demonstra uma pipeline de regressão linear, aonde as etapas de Análise exploratória dos dados, limpeza dos dados, feature engineering, preparação para modelagem, 
modelagem e avaliação foram realizadas.

-Base de dados: Os dados utilizados foram do dataset sugerido pela avaliação, "House Sales in King County, USA".
Este conjunto de dados contém os preços de venda de casas no Condado de King, que inclui Seattle, Inclui imóveis vendidos entre maio de 2014 e maio de 2015.
Foram avaliadas as 21613 linhas de dados.

MAE: US$ 103,731 "teste"    - R2: 0.7752 "teste".
## O que o projeto analisa 
- O projeto apresenta um modelo de regressão linear utilizando como base o dataset kc_house_data.csv

## Como executar 
### 1. Instalar dependências
pip install -r requirements.txt

### 2. Abrir o notebook
jupyter notebook notebooks/dataview.ipynb
## Estrutura do projeto 
├── data/
│   ├── raw/                        
│   ├── processed/                  
│   └── final/                      
│
├── models/
│   └── v1/
│       ├── model.joblib
│       └── metrics.json       
│   
│
├── outputs/
│   └── figures/                    
│
│
├──  dataview_precos.ipynb              
│──  READMI.MD
│── License
│── gitignore
└── requirements.txt                               
  
# Melhorias futuras
Para uma possivel melhoria poderiamos utilizar a base criada no item 6a, ao qual o modelo foi treinado em 100% dos dados e não foi guardado uma cópia deste modelo
## Vídeo de demonstração 
[Inserir link do Google Drive ou YouTube aqui] 
