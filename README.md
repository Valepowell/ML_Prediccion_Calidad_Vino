Proyecto de Clasificación de Calidad de Vino
Descripción
Este proyecto tiene como objetivo clasificar la calidad de los vinos utilizando diferentes algoritmos de aprendizaje automático. Se exploran y preprocesan los datos, se entrenan y evalúan modelos de clasificación (KNN, Random Forest y Regresión Logística), y se comparan sus rendimientos para identificar el mejor modelo.

Estructura del Proyecto
El proyecto se basa en un notebook de Colab que contiene los siguientes pasos:

Carga y Exploración de Datos: Carga del dataset, revisión de su estructura, descripción de variables, identificación y tratamiento de valores nulos y outliers.
Preprocesamiento de Datos: Selección de características, transformación de variables (si es necesario), división de datos en conjuntos de entrenamiento y prueba, y escalado de características.
Entrenamiento de Modelos de Clasificación: Entrenamiento de al menos tres modelos diferentes con validación cruzada para la selección de hiperparámetros.
Evaluación de Modelos: Evaluación de los modelos utilizando métricas como exactitud, precisión, recall, F1-Score y matriz de confusión.
Análisis y Comparación de Resultados: Comparación del rendimiento de los modelos, discusión del mejor modelo y análisis de fortalezas y debilidades.
Configuración y Uso
Abre el notebook en Google Colab.
Monta tu Google Drive para acceder al dataset WineQT.csv. Asegúrate de que la ruta al archivo sea correcta en la celda de carga de datos.
Ejecuta cada celda del notebook secuencialmente.
Resultados
El análisis de los resultados se presenta en la sección "Análisis y Comparación de Resultados" del notebook, donde se detallan las métricas de rendimiento de cada modelo y se discute cuál ofrece el mejor desempeño para este problema de clasificación.

Dataset
El dataset utilizado en este proyecto es WineQT.csv. Contiene diversas características físico-químicas de vinos y su calidad asociada.

Dependencias
Las principales bibliotecas utilizadas son:

pandas
seaborn
matplotlib
sklearn
Estas bibliotecas suelen estar preinstaladas en el entorno de Google Colab.

Autor
Valeska Powell.
# ML_Prediccion_Calidad_Vino
