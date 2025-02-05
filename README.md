🎗️ Proyecto: Clasificación de Cáncer de Mama en Wisconsin 🧬
Este proyecto tiene como objetivo clasificar tumores de cáncer de mama en benignos (B) o malignos (M) utilizando un conjunto de datos de características de núcleos celulares. Se implementaron varios modelos de Machine Learning para predecir el diagnóstico con alta precisión.

📌 Descripción
El conjunto de datos contiene 30 características calculadas a partir de imágenes digitalizadas de tumores de mama, como el radio, textura, perímetro, área, suavidad, compacidad, concavidad, simetría y dimensión fractal. El objetivo es predecir si un tumor es benigno o maligno.

🛠️ Herramientas y Tecnologías
Lenguaje de programación: Python 🐍

Bibliotecas principales:

Pandas 🐼: Para manipulación de datos.

Scikit-learn 🔧: Para preprocesamiento, entrenamiento y evaluación de modelos.

TensorFlow/Keras 🤖: Para implementar redes neuronales.

Matplotlib/Seaborn 📊: Para visualización de datos.
: ![descarga](https://github.com/user-attachments/assets/7d7bb47b-868c-4124-8016-9b7648bea54c)


Algoritmos utilizados:

Regresión Logística 📈

Redes Neuronales 🧠

Bosques Aleatorios 🌳

Máquinas de Soporte Vectorial (SVM) 🚀

📂 Estructura del Proyecto
Preprocesamiento de datos:

Estandarización de características.

División de datos en conjuntos de entrenamiento y prueba.

Entrenamiento de modelos:

Regresión Logística.

Redes Neuronales.

Bosques Aleatorios.

Máquinas de Soporte Vectorial (SVM).

Evaluación de modelos:

Cálculo de métricas como accuracy, precision, recall y F1-score.

Generación de matrices de confusión y curvas ROC.

Predicción con nuevos datos:

Clasificación de tumores nuevos como benignos o malignos.

📊 Resultados
Regresión Logística:

Precisión en entrenamiento: 94.7%

Precisión en prueba: 92.9%

Redes Neuronales:

Precisión en prueba: 96.5%

Bosques Aleatorios:

Precisión en prueba: 96.5%

Máquinas de Soporte Vectorial (SVM):

Precisión en prueba: 95.6%

🚀 Cómo usar el proyecto
Clona el repositorio:

bash
Copy
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
Instala las dependencias:

bash
Copy
pip install -r requirements.txt
Ejecuta el código:

Abre el notebook Cancer_Mama_Wisconsin.ipynb y ejecuta las celdas para entrenar y probar los modelos.

Prueba con nuevos datos:

Modifica la lista de input_data en el notebook para predecir el diagnóstico de nuevos tumores.
