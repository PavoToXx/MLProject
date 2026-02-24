# ⚽ Predicción de Partidos de Fútbol (EPL 24/25) - ML & Power BI

Este proyecto es una solución integral de análisis de datos y Machine Learning (End-to-End) diseñada para predecir resultados de partidos de fútbol. Abarca desde la extracción de datos hasta la visualización de las predicciones en un entorno de Business Intelligence.

## 🏗️ Arquitectura del Proyecto (Pipeline)

1. **Extracción de Datos:** Dataset obtenido de Kaggle (Estadísticas de equipos y datos de jugadores de FIFA).
2. **Procesamiento y Feature Engineering (Python/Colab):** Limpieza de datos iterativa, cruce de tablas y generación de la `megatabla_features.csv` para entrenar el modelo.
3. **Machine Learning:** Entrenamiento de modelos predictivos en Jupyter Notebook (`ProyectoFinal.ipynb`) para clasificar resultados.
4. **Exportación:** Generación del archivo `datos_predichos_powerbi.csv` con los resultados del modelo.
5. **Visualización (Power BI):** Creación de un dashboard interactivo (`proyecto_finalv3.pbix`) para analizar la precisión del modelo y estadísticas clave.

## 📂 Estructura del Repositorio

- `/notebooks`: Contiene el código fuente en Python (`ProyectoFinal.ipynb`) con el EDA, preprocesamiento y entrenamiento del modelo.
- `/dashboards`: Contiene el reporte final en PDF (`PFinalvM.pdf`) y el archivo de Power BI.
- *Nota: Por buenas prácticas, el dataset original y los archivos `.csv` intermedios no están subidos a este repositorio.* ## 🛠️ Tecnologías Utilizadas
- **Lenguaje:** Python (Pandas, Scikit-Learn, Matplotlib/Seaborn)
- **Entorno:** Google Colab / Jupyter Notebook
- **Visualización:** Microsoft Power BI
- **Fuente de Datos:** Kaggle

## 📊 Resultados Visuales
*(Te sugiero reemplazar este texto con una captura de pantalla de tu dashboard de Power BI para que sea visible de inmediato en GitHub).*
