# 🎓 Desempeño de estudiantes 📊

Este proyecto tiene como objetivo predecir el desempeño de los estudiantes en matemáticas a partir de
un conjunto de datos que contiene información demográfica y académica de los estudiantes.

## 📝 Selección del Proyecto

El dataset fue extraído de Kaggle y contiene información sobre el rendimiento de los estudiantes en matemáticas,
además de características demográficas como el género, la raza, la educación de los padres, el tipo de almuerzo y la preparación para los exámenes.
El objetivo es predecir las calificaciones en matemáticas usando diferentes modelos de machine learning y comparar sus desempeños.

## ⚙️ Data Cleaning y Feature Engineering

- 🔍 Exploración y análisis inicial del dataset.
- 🛠️ Tratamiento de valores faltantes 
- 🔢 Conversión de variables categóricas en variables numéricas mediante técnicas como One-Hot Encoding.
- ✨ Creación de nuevas características útiles, como combinaciones de características o características derivadas.

## 🤖 Construcción y Evaluación de Modelos
Se entrenaron diferentes modelos para predecir las calificaciones en matemáticas:

- **📈 Regresión Lineal**: Modelo de regresión simple.
  ![image](https://github.com/user-attachments/assets/d852ca2d-da6b-4d70-a10f-13b9c75b228f)
- **🌲 Random Forest**: Un modelo de ensamble basado en árboles de decisión.
  ![image](https://github.com/user-attachments/assets/002a7467-133e-432b-abd4-d350faecbe4f)
- Para la evaluación se utilizaron las siguientes métricas:
- 📉 **Mean Absolute Error (MAE)**: Media del valor absoluto de los errores de predicción.
- 📊 **R² Score**: Proporción de la varianza explicada por el modelo.

## 🏅 Comparación de los Modelos

  ![image](https://github.com/user-attachments/assets/59caf780-d84b-41ae-8b7d-b2bc8996f1d7)
- **📈 Regresión Lineal**: Proporcionó el mejor desempeño en términos de R² y MAE.
- MAE: 3.59
- R2 Score: 0.89
- **🌲 Random Forest**: Aunque mejoró ligeramente en términos de reducción de error, no superó a la regresión lineal en este dataset.
- MAE: 4.22
- R2 Score: 0.86

## 🔚 Conclusiones

- La **📈 Regresión Lineal** fue el mejor modelo para predecir el desempeño de los estudiantes en matemáticas, logrando una mayor precisión con un MAE más bajo y un R² mayor.
- Los modelos más complejos no mejoraron el desempeño de manera significativa, lo que indica que un modelo más simple puede ser más adecuado para este tipo de datos.
