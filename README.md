## Projeto consiste de:
```
.  
├── notebooks/  
│   ├── eda.ipynb  
│   ├── ml_training.ipynb  
│   └── catboost_info
├── data/
│   ├── synthetic_delivery_requests_modified.csv
│   └── df_cleared.parquet
├── README.md
├── .gitignore
├── .python-version
├── poetry.lock
└── pyproject.toml
```
  
Na pasta notebook estão todos os notebooks de Análise Exploratória e de treinamento do modelo.  
Para entender o processo siga pelo:  
- EDA.ipynb onde estão todas as análises e transformações até a exportação dos dados limpos no formato parquet.  
- ml_training.ipynb encontrará o passo-a-passo do treinamento do modelo, comparação de TargetEncoder e sem Encoder, comparando modelo GradientBoosting, ADABoost e Catboost, grid de hiper-parâmetros e resultado final.  