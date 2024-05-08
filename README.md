
# Laboratorio de Machine Learning con Python

## Introducción
Este conjunto de laboratorios está diseñado para introducir a los estudiantes a los conceptos fundamentales de Python y su aplicación en Machine Learning. Aprenderán a usar bibliotecas como **Pandas** para manipulación de datos y **Scikit-Learn** para crear y evaluar modelos de aprendizaje automático. Los tres laboratorios cubren:

1. **Conceptos Básicos de Python y Pandas**: Estructuras de datos, control de flujo y uso de pandas para manipulación de datos.
2. **Laboratorio de Machine Learning con Python y Scikit-Learn**: Entrenamiento y evaluación de un modelo de regresión lineal utilizando un conjunto de datos de viviendas en California.
3. **Laboratorio de Machine Learning con Matriz de Confusión**: Entrenamiento y evaluación de un modelo de clasificación usando un conjunto de datos de cáncer de mama y análisis con matriz de confusión.

## Requisitos
- Python 3.x
- Bibliotecas requeridas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Puedes instalar las bibliotecas necesarias usando el siguiente comando:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Laboratorio 1: Introducción a Python y Pandas
1. **Objetivos**:
   - Comprender estructuras de datos como listas, tuplas, diccionarios y conjuntos.
   - Realizar operaciones básicas con bucles y condicionales.
   - Introducir el uso de la biblioteca pandas para trabajar con conjuntos de datos.

2. **Pasos Clave**:
   - Crear estructuras de datos y entender cómo utilizarlas.
   - Manipular datos tabulares con pandas (seleccionar columnas, filtrar filas).
   - Aplicar técnicas básicas de programación como condicionales y bucles.

3. **Resultado Esperado**:
   - Familiaridad con los conceptos básicos de programación en Python y pandas.

## Laboratorio 2: Machine Learning con Scikit-Learn (Regresión Lineal)
1. **Objetivos**:
   - Entrenar un modelo de regresión lineal con datos de California Housing.
   - Evaluar el modelo con métricas como RMSE (Raíz Cuadrada del Error Cuadrático Medio) y coeficiente R².

2. **Pasos Clave**:
   - Cargar el conjunto de datos usando Scikit-Learn.
   - Normalizar las características para que estén en una escala consistente.
   - Dividir los datos en entrenamiento y prueba.
   - Entrenar un modelo de regresión lineal y evaluar su rendimiento.

3. **Resultado Esperado**:
   - Comprender cómo se construye y evalúa un modelo de regresión con Scikit-Learn.

## Laboratorio 3: Machine Learning con Matriz de Confusión (Clasificación)
1. **Objetivos**:
   - Entrenar un modelo de clasificación usando un conjunto de datos de cáncer de mama.
   - Evaluar el rendimiento utilizando una matriz de confusión.

2. **Pasos Clave**:
   - Cargar el conjunto de datos Breast Cancer y dividirlo en datos de entrenamiento y prueba.
   - Normalizar las características para que estén en la misma escala.
   - Entrenar un modelo de clasificación (RandomForestClassifier).
   - Evaluar el modelo usando una matriz de confusión y un informe de clasificación.

3. **Resultado Esperado**:
   - Entender cómo se desarrolla un modelo de clasificación y cómo interpretar una matriz de confusión.
