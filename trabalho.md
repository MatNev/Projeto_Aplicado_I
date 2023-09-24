Aqui se encontrará quaisquer conteúdos necessários para a criação do documento, tal como o mesmo : 


# Documento

O documento deve apresentar:
 - Título do trabalho.
 - Membros do grupo.
 - Contexto do estudo.
 - Referências de aquisição do dataset (origem dos dados, limitações de uso e período da coleta).
 - Descrição da origem (informações sobre a organização que gerou os dados e o contexto em que os dados foram gerados).
 - Descrição do dataset (o que ele contém, qual é a proposta, quais problemas ou fenômenos foram registrados).


link : 

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
