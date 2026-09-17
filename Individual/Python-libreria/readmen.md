Esta actividad tiene como objetivo familiarizarse con el ecosistema de librerías de Python utilizadas en Ciencia de Datos y comprender en qué situaciones se utiliza cada una. El trabajo deberá realizarse dentro de un notebook en Deepnote.

 Antes de arrancar, lo primero que tienen que hacer en Deepnote es:

    Crear el notebook y renombrarlo: 003 – Python Librerias
    Crear un bloque de título: TP03 – Python Librerías
    Crear un bloque de texto con su Apellido y Nombre


Ejercicio 1 – Importación de librerías

Crear un bloque de código e importar las siguientes librerías:
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

Luego crear un array de NumPy con 5 números y mostrarlo por pantalla.

Ejemplo:
datos = np.array([10, 20, 30, 40, 50])
print(datos)

Ejercicio 2 – Dataset simple con Pandas

Crear un DataFrame de Pandas con la siguiente información:
estudiante	nota
Ana	8
Juan	6
Carla	9
Pedro	5
Lucia	7


Luego realizar las siguientes operaciones:

    Mostrar el DataFrame
    Calcular el promedio de las notas
    Mostrar la nota máxima
    Mostrar la nota mínima


Ejercicio 3 – Criterio de selección de herramientas

En un  bloque de texto responder brevemente: ¿Qué librería utilizarías para cada una de las siguientes tareas?

    Leer un archivo CSV con datos de encuestas
    Crear un gráfico de distribución de datos
    Realizar un modelo de Machine Learning
    Trabajar con operaciones matemáticas sobre matrices

Escribir la librería elegida y una breve justificación.

Ejemplo:
1) pandas → porque permite leer archivos CSV y manipular datasets tabulares.