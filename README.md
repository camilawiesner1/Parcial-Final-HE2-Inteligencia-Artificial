# Parcial-Final-HE2-Inteligencia-Artificial
Bienvenidos! Quisimos crear una aplicación que ayude a predecir cómo afecta la canasta familiar estadounidense y la tasa de cambio los resultados de las elecciones precidenciales de Estados Unidos del 2024.  

## Tabla de contenidos 
- [Descripción](#descripción)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Technologies](#technologies)
- [License](#license)
## Descripción
Este modelo busca ayudar a clasificar los tweets de trump en tres diferentes categorías: Anti-migratorio, Pro-empresa y proteccionista. 
## Setup
#### Importar librerias
import numpy as np
import pandas as pd
import matplotlib
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
from wordcloud import WordCloud, STOPWORDS
from google.colab import files
#### Subir archivo
uploaded = files.upload()
#### Leer el archivo Excel
df = pd.read_excel("X.xlsx", engine="openpyxl")

## Usage 
## Technologies
## license
