# Script por estado para o collab

1. Defina o estado

```
estado = "sp"
```

2. Baixe o arquivo

```
uri = f"https://github.com/alura-cursos/imersao-dados-2-2020/blob/master/por%20estado/{estado}.csv.zip?raw=true"
arquivo = f'{estado}.csv.zip'
!wget -O $arquivo $uri
```

3. Lendo o arquivo:

```
import pandas as pd
dados = pd.read_csv(arquivo)
dados.head()```

Arquivos csv foram separados por Antônio Salvador Neto
Fonte: https://www.kaggle.com/dataset/eeebf2b4e3352e5ae3bbc7f985dd1edd7e11904a687431737859b3bd8f93cc64?select=Selec_AC.txt
