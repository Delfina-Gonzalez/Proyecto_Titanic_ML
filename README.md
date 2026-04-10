# 🚀 Minería de Datos con Python / Trabajo Final / Abril 2026

## 📈 Student Performance

## 📌 Clonar el repositorio

Para descargar este proyecto, ejecutar:

```bash
git clone https://github.com/Delfina-Gonzalez/Students_Performance_ML.git
cd Students_Performance_ML


📊 Descripción de la problemática

En este ejercicio, el objetivo es obtener modelos de regresión que describan el comportamiento de los datos en el archivo student_performance.csv (data tomada de Kaggle).

En este archivo se registra la calificación obtenida por estudiantes (Performance Index, escala 0-100), en relación con las siguientes variables:

Horas de estudio (Hours Studied)
Calificación previa (Previous Score)
Actividades extracurriculares (Extracurricular Activities)
Horas de sueño (Sleep Hours)
Número de exámenes practicados (Sample Question Papers Practiced)


⚙️ Metodología

El flujo de trabajo implementado incluye:

Carga de datos en un DataFrame de Pandas
Transformación de variables categóricas
Normalización de datos con StandardScaler
División en conjunto de entrenamiento y prueba (train_test_split)
Implementación de modelos:
Regresión Lineal
Red Neuronal (TensorFlow/Keras)
Evaluación mediante métricas:
MAE
MSE
R²
Varianza explicada
Visualización de resultados


📊 Resultados
| Modelo             | MAE | MSE  | Varianza Explicada | R²   | 
|--------------------|-----|------|--------------------|------| 
| Regresión Lineal | 1.60 | 4.03 | 0.99 | 0.99 | 
| Red Neuronal | 1.61 | 4.33 | 0.99 | 0.99 |


🧠 Conclusiones

Los resultados obtenidos evidencian que ambos modelos de regresión logran un desempeño excelente en la predicción del Performance Index, alcanzando valores de R² de 0.99.

Se observa que ambos modelos presentan errores muy bajos y un ajuste casi perfecto a los datos. Sin embargo, la red neuronal no logra mejorar significativamente el rendimiento de la regresión lineal, lo que sugiere que la relación entre las variables del problema es principalmente lineal.

En términos de resolución del problema, esto implica que un modelo simple como la regresión lineal es suficiente para capturar la dinámica del rendimiento estudiantil, sin necesidad de recurrir a modelos más complejos.

Esto reduce el costo computacional y mejora la interpretabilidad de los resultados.

En conclusión, ambos modelos cumplen con los objetivos planteados, pero la regresión lineal se posiciona como la alternativa más adecuada.


▶️ Cómo ejecutar
Instalar dependencias:
pip install -r requirements.txt
Ejecutar el notebook:
jupyter notebook


🛠️ Tecnologías utilizadas
Python
Pandas
NumPy
Scikit-learn
TensorFlow / Keras
Matplotlib
