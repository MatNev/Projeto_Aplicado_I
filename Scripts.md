# Scripts (Python)

### Domicílios : 
```
import pandas as pd

excel = pd.read_excel (r"C:\Users\dante\Downloads\Projeto Aplicado\Aula 02\Folder\Domiciliosatendidos.xlsx")

# Carregue os dados do arquivo Excel em um DataFrame do pandas
df = pd.read_excel (r"C:\Users\dante\Downloads\Projeto Aplicado\Aula 02\Folder\Domiciliosatendidos.xlsx")

# Calcule as medidas de posição (média, moda, mediana)
media = df["Domicilios"].mean()
moda = df["Domicilios"].mode().iloc[0]
mediana = df["Domicilios"].median()

# Calcule as medidas de dispersão (variância, desvio padrão, amplitude)
variancia = df["Domicilios"].var()
desvio_padrao = df["Domicilios"].std()
amplitude = df["Domicilios"].max() - df["Domicilios"].min()

# Imprima os resultados
print("Média:", media)
print("Moda:", moda)
print("Mediana:", mediana)
print("Variância:", variancia)
print("Desvio Padrão:", desvio_padrao)
print("Amplitude:", amplitude)
```
### Ano :
```
import pandas as pd

excel = pd.read_excel (r"C:\Users\dante\Downloads\Projeto Aplicado\Aula 02\Folder\Domiciliosatendidos.xlsx")

# Carregue os dados do arquivo Excel em um DataFrame do pandas
df = pd.read_excel (r"C:\Users\dante\Downloads\Projeto Aplicado\Aula 02\Folder\Domiciliosatendidos.xlsx")

# Calcule as medidas de posição (média, moda, mediana)
media = df["Ano"].mean()
moda = df["Ano"].mode().iloc[0]
mediana = df["Ano"].median()

# Calcule as medidas de dispersão (variância, desvio padrão, amplitude)
variancia = df["Ano"].var()
desvio_padrao = df["Ano"].std()
amplitude = df["Ano"].max() - df["Ano"].min()

# Imprima os resultados
print("Média:", media)
print("Moda:", moda)
print("Mediana:", mediana)
print("Variância:", variancia)
print("Desvio Padrão:", desvio_padrao)
print("Amplitude:", amplitude)
```
