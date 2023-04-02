[![Author](https://img.shields.io/badge/Dev-Nadi%20Duno-blueviolet%20)](https://portfolio-nadi.vercel.app/)
[![Social](https://img.shields.io/twitter/follow/nadiduno?label=%40nadiduno&style=social)](https://twitter.com/nadiduno)
[![Linkedin](https://img.shields.io/badge/in-Nadi%20Duno-blue)](https://www.linkedin.com/in/nadiduno/)
<br />
<br />

# BootCampDataScience
BootCamp com Alura 

##Importando Dados
``` py
import pandas as pd
url= 'link dos dados'
dados=pd.read_csv(url)
```


##Plotagem dos dados
```py
import matplotlib.pyplot as plt
import seaborn as sns
sns.set()
plt.figure(figsize=(10, 8))
ax = sns.histplot(data = dados_venda, x = atributo5, kde = True)
ax.set_title("Histograma Valor Imóvel")
plt.xlim((-50, 10000000))
plt.show()
```
By DevRel <💜 /> [Nadi Duno](https://www.rocketseat.com.br/) © 2023
