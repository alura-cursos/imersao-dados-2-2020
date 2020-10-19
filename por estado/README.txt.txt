# Script para o collab

```
# defina aqui a sigla do teu estado
estado = "sp"


uri = f"https://github.com/alura-cursos/imersao-dados-2-2020/blob/master/por%20estado/{estado}.csv.zip?raw=true"
!wget -O estado.zip $uri


import pandas as pd

dados = pd.read_csv("estado.zip", sep=";")
dados.head()```

Arquivos já separados por Antônio Salvador Neto
Fonte: https://www.kaggle.com/dataset/eeebf2b4e3352e5ae3bbc7f985dd1edd7e11904a687431737859b3bd8f93cc64?select=Selec_AC.txt
