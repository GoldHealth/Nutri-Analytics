# Nutri-Analytics
Es un sofware que nos permite analizar datos de peso y talla para correlacionarlos al IMC
## Integrantes
1.- Sebastian Salvatierra Saavedra 24278  
2.- Francis Rios 24174  
3.- Roberto Minuche 24051  
4.- Sara Mach 24167  
5.- Izza Moreira 24151  
6.- Victor Posadas 24215  
7.- Melissa Flor de Maria Gonzalez Zuleta 24253  
8.- Kimberly Aragón 24210  
9.- Jorge Mendez 24283  
10.- Gabriela Peinado 24137  
11.- Valeria Araujo 24277
## Problema
En la actualidad se utilizan múltiples métodos de recolección de información en el ámbito nutricional para evaluar el estado de una población con el fin de tomar acciones preventivas y correctivas sobre su situación. Sin embargo, estos métodos exponen carencias tecnológicas que dificultan el análisis de los datos. Aunado a ello, este es un tema tratado a nivel internacional, puesto que, existen grandes afecciones relacionadas con la alimentación y actividad física de la población estudiantil de Zamorano, destacándose entre ellas la desnutrición, malnutrición, sobrepeso y obesidad, es por ello, que el objetivo principal de este proyecto es la creación de gráficos mediante el uso de Jupiter-Python y Matplotlib sobre el índice de masa corporal y correlacionar los datos de estatura con el peso esto con el objetivo de determinar el estado nutricional en que se encuentran los estudiantes. 
## Solución propuesta
Para este proyecto, se realizó el uso del lenguaje de programación Python, el cual fue de ayuda para automatizar la inspección de datos sobre los diferentes IMC’S de las diferentes poblaciones de Zamorano, que fueron recolectados mediante el software de administración de encuestas, Google Forms, además se empleó el editor de código fuente de Jupiter-Python, mediante el uso de la librería Matplotlib. Lo anteriormente mencionado, es un todo que nos permitieron desarrollar un programa que aprovechó los datos obtenidos de la población estudiantil y los interpretó darles el enfoque estadístico.
## Objetivos
El proyecto incluye los siguientes objetivos:  

• Crear un repositorio público de código fuente para el proyecto: Nutri-Analytics. 

• Automatizar la ingestión de una fuente de datos CSV de datos de peso, edad y estatura de la población estudiantil de Zamorano mediante el software Python.

• Digitalizar de manera automática la subida a memoria de los datos en un formato consistente para facilitar el análisis de los datos recolectados.  

• Analizar gráficas que faciliten la interpretación del índice de masa corporal de la población estudiantil de Zamorano. 

• Correlacionar el Índice de Masa Corporal de la población con respecto a su estatura y la estatura con el peso. 
## Herramientas y Métodos

i.	Herramientas: 
-	Jupyter
-	Github
-	Encuesta de google forms
-	Lenguaje de programación Python
-	Microsoft Excel 365

ii.	Librerías:
-	Pandas
-	Matplolib
-	Numpy 
-	Statistics 
-	Sklearn

iii.	Métodos:

Para la resolución del problema, primeramente, se realizó una encuesta de Google Forms a los estudiantes de primero, segundo y tercer año, en la cual, se les preguntó los siguientes rubros: edad, peso (lb), estatura (m) y año de carrera. 

Los datos obtenidos de la encuesta se tabularon en Microsoft Excel para ordenar los datos y poder analizarlos posteriormente. Se utilizó en formato csv.

Python: Se importaron librerías, las cuales son:

Sklearns: es una librería para modelo de regresión lineal. 

Pandas: es una herramienta de manipulación y análisis de datos de código abierto rápida, potente y flexible de usar, construida sobre el lenguaje de programación Python.

Matplotlib: es una biblioteca completa para crear visualizaciones estáticas, animadas e interactivas en Python. Se utilizó para realizar las gráficas de los datos analizados. 

Numpy: en la biblioteca de Python que se utilizó para trabajar las operaciones matemáticas. 

Estadístico: se utilizó para el análisis estadístico y con el uso del programa Survey Monkey se estimó el tamaño de la muestra https://es.surveymonkey.com/mp/sample-size-calculator/

Por último, se realizará una presentación donde se plasmé el contenido del proyecto para el Pitch y reporte final, mostrando los resultados obtenidos.
## Fuentes de datos
Se recopilarán datos vía Google Forms.  
El formato de Datos sera .CSV  
Se logró recolectar 259  muestras o registros
Propiedades de la Fuente de Datos:  
Edad, Estatura, Peso (lbs), (Año)
Discusión/Analisis: Se tiene planeado, mostrar graficamente el comportamiento del IMC mediante graficas, para asi, mostrar el comportamiento de una curva acorde al año y/o edad que se encuentran los individuos.  
El link de acceso al formulario es el siguiente: https://forms.gle/ZJAKQo5J5HXdr1h27  
El subdirectorio correspondiente se encuentra en el siguiente link: https://github.com/GoldHealth/Nutri-Analytics/tree/main/data
## Resultados
Correlacion Peso vs IMC
https://github.com/GoldHealth/Nutri-Analytics/blob/main/pesoimc.png
Correlacion Estatura vs Peso
https://github.com/GoldHealth/Nutri-Analytics/blob/main/estpeso.png
## Referencias
Bisong, E. (2019). Matplotlib and seaborn. In Building machine learning and deep learning models on google cloud platform (pp. 151-165). Apress, Berkeley, CA.
OMS. (2021, 9 junio). Malnutrición. Recuperado 12 de septiembre de 2022, de https://www.who.int/es/news-room/fact-sheets/detail/malnutrition
Reback, J., McKinney, W., Van Den Bossche, J., Augspurger, T., Cloud, P., Klein, A., ... & Seabold, S. (2020). pandas-dev/pandas: Pandas 1.0. 5. Zenodo.
Universidad de Alcalá. (2019). Pandas: herramienta básica para el Data Science. https://www.master data-scientist.com/pandas-herramienta-data-science/
