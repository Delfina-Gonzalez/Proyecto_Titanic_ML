
# 🚀 Minería de Datos con Python / Trabajo Final / Abril 2026

## 🚢 Titanic - Machine Learning

## 📌 Clonar el repositorio

Para descargar este proyecto, ejecutar:

```bash
git clone https://github.com/Delfina-Gonzalez/Proyecto_Titanic_ML.git
cd Proyecto_Titanic_ML

📊 Descripción de la problemática

El objetivo es obtener modelos de clasificación sobre el archivo titanic_processed.csv, el cual contiene datos previamente procesados del dataset Titanic.

Cada registro indica si un pasajero sobrevivió (Survived = 1) o no (Survived = 0), en función de:

Clase (Pclass)
Sexo (Sex)
Edad (Age)
Familiares a bordo (SibSp, Parch)
Tarifa pagada (Fare)
Puerto de embarque (one-hot encoding)


⚙️ Metodología

El flujo de trabajo incluye:

Carga de datos en Pandas
División en entrenamiento y prueba
Modelos implementados:
Regresión Logística
Árbol de Decisión
Evaluación mediante:
Accuracy
Matriz de confusión
Interpretación de resultados


📊 Resultados
Regresión Logística → Accuracy: 82.5%
Árbol de Decisión → Accuracy: 80%


🧠 Conclusiones

La regresión logística mostró un mejor desempeño general, mientras que el árbol de decisión permitió interpretar las reglas de decisión.

Se observó que el modelo tiene dificultades en valores cercanos al umbral de decisión (0.5), pero presenta alta confianza en predicciones extremas.

🔍 Variables más influyentes
Variable	Coeficiente	Influencia
Sex	-1.164	Muy alta
Pclass	-0.885	Alta
Age	-0.568	Media
SibSp	-0.306	Baja
Embarked_Q	-0.096	Muy baja
Parch	-0.045	Muy baja
Embarked_S	-0.042	Muy baja
Fare	-0.060	Muy baja
Embarked_C	0.093	Baja


🧾 Conclusión general

El análisis confirma patrones históricos:

El sexo fue el factor más determinante
La clase social influyó fuertemente en la supervivencia
La edad tuvo impacto significativo
Viajar acompañado también influyó

El evento no fue aleatorio: múltiples factores estructurales determinaron la supervivencia.

▶️ Cómo ejecutar
Instalar dependencias:
pip install -r requirements.txt
Ejecutar:
jupyter notebook
Abrir el notebook correspondiente.


🛠️ Tecnologías utilizadas
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
