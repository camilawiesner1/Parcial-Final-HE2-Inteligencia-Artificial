#### 🐦
# Parcial Final HE2 Inteligencia-Artificial: Descifrando a Trump

Bienvenidos! Quisimos crear una aplicación que ayude a categorizar los tweets de el presidente de los Estados Unidos. Los quisimos categorizar con tres diferentes etiquetas: 1.Proteccionista 2. Anti-migratorio 3. Pro-empresa
#### Link de acceso
Para visitar nuestro categorizador, hacer click aquí:  https://698fb45d7248d240b8.gradio.live/
🐦
#### Demo del funcionamiento:
# 
 ### Caracteristicas de la app:
- Categoriza cualquier tweet de trump en segundos!
- Está entrenado con tweets antiguos de Trump, lo que le agrega veracidad.
- Usa como herramienta gradio, para que sea amigable con el usuario.
- Ayuda a entender las posturas de el presidente Trump.
### Entendiendo el codigo: 
- Primero, se debe correr el primer codigo en Colab, el cual por medio de la inteligencia artificial, clasifica la base original de tweets de trump que fue sacada de Hugging Face. Este archivo con el codigo se denomina "App_Final.ipynb" y está en la carpeta del proyecto.
 -- la base es de Kaggle Fuente: Preda, G. (2020). Trump Tweets: Preliminary EDA [Conjunto de datos]. Kaggle. Recuperado de https://www.kaggle.com/code/gpreda/trump-tweets-preliminary-eda/input

- Después se debe correr el codigo que contiene la augmentación, el FineTunning y el Gradio. Insertando el archivo de excel titulado "dt_clean.xlsx" que tambíen está en la carpeta del proyecto (la salida del anterior codigo). Para correr este codigo, remitase al archivo llamado "Final_de_IA.ipynb"

🐦
## Instalaciones
- Para el primer codigo / colab :
##### Instalar los paquetes necesarios para el entrenamiento del modelo
!pip install fsspec==2024.10.0
!pip install gcsfs==2024.10.0 fsspec==2024.10.0
##### Instalar paquetes transformers y datasets
!pip install transformers datasets -q 
##### Instalar transformers con soporte para PyTorch
!pip install accelerate -q # Instalar accelerate
##### Instalar evaluate
!pip install evaluate -q  # Instalar evaluate
##### Instalar Gemini
pip install -q -U google-generativeai
# 
- Para el segundo codigo /Colab
##### Instalar paquetes transformers y datasets
!pip install transformers datasets  
##### Instalar transformers con soporte para PyTorch
!pip install transformers[torch]  
##### Instalar accelerate
!pip install accelerate  
##### Instalar evaluate
!pip install evaluate 
##### Instalar evaluate
!pip install gradio as gr
##### Instalar textaugment
!pip install textaugment nlpaug

🐦
## 

🐦
## Video de muestra 

# 
### Creadores: 
Alejandra Lopez
Camila Wiesner
Felipe Castillo
Stefania Alvarez
Valentina González

