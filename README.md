# Ejercicios del Curso Analisís de datos

Este repositorio contiene: 2 ejercicios con notebook de Python (Google Colab) 
1. [Analiza variables aleatorias derivadas del lanzamiento de dos dados justos.](#id=1)
2. [Manipulación de DataFrames con Pandas](#id2)

## 🎲 Análisis de Variables Aleatorias con Dados <a id="id1"></a>

## 📚 Contenido

El notebook resuelve los siguientes ejercicios:

1. Documentar el análisis.
2. Calcular la ley de probabilidad de:
   - La diferencia de las caras sea mayor que 1.
   - La suma de las caras sea par.
3. Verificar que la suma de las probabilidades sea 1.
4. Subir el notebook a GitHub.

## 🛠️ Herramientas utilizadas

- Python 3
- `pandas`
- `fractions.Fraction`
- `itertools.product`
- Google Colab

## 📈 Resultados

Se construyen eventos como conjuntos de pares ordenados, se calcula su probabilidad exacta, y se verifica que las leyes de probabilidad estén correctamente normalizadas.

## 📎 Archivo

- [`Ejercicio_1.ipynb`](./Ejercicio_1.ipynb)

## 🧪 Manipulación de DataFrames con Pandas <a id="id2"></a>

## 📚 Contenido
El notebook resuelve los siguientes ejercicios:

1. Documentar el análisis.
2. Calcular una nueva columna booleana que sea True si:
   - El nombre de la ciudad contiene la palabra "San".
   - El área de la ciudad es mayor a 50 millas cuadradas.
3. Usar el método .reindex() con índices inexistentes y analizar el resultado.
4. Subir el notebook a GitHub.
5. Documentar el análisis.

## 🛠️ Herramientas utilizadas
- Python 3
- `pandas`
- Google Colab

## 📈 Resultados
- Se construye una nueva columna condicional combinando dos criterios lógicos con operadores bitwise (&).
- Se demuestra que .reindex() permite índices no existentes, rellenando las filas faltantes con NaN.

##📎 Archivo
- [`Ejercicio_2.ipynb`](./Ejercicio_2.ipynb)
