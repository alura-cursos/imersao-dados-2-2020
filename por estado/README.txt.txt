Arquivos já separados pelo Antônio Salvador Neto
Fonte: https://www.kaggle.com/dataset/eeebf2b4e3352e5ae3bbc7f985dd1edd7e11904a687431737859b3bd8f93cc64?select=Selec_AC.txt

Script para baixar o arquivo e abrir no collab:
```
import pandas as pd
import zipfile

estado = "sp"

!wget '$estado.csv.zip'
zip = zipfile.ZipFile(f'{estado}.csv')
dados = pd.read_csv(zip)
dados.head()```