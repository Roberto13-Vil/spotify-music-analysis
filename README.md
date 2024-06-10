# Identificación de Patrones de Éxito Musical en Spotify mediante Análisis de Datos y Clasificación Predictiva

Este proyecto tiene como objetivo identificar características que influyen en el éxito de las canciones en plataformas de streaming como Spotify, Apple Music, Shazam y Deezer. Utiliza técnicas de análisis de datos y machine learning para predecir la popularidad de las canciones.

## Tabla de Contenidos
- [Descripción del Proyecto](#descripción-del-proyecto)
- [Objetivos](#objetivos)
- [Metodología](#metodología)
- [Resultados](#resultados)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Conclusiones](#conclusiones)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Descripción del Proyecto
Este proyecto aborda el análisis de datos de canciones en plataformas de streaming para identificar patrones que predicen el éxito musical. Se utilizaron datos de diversas fuentes, incluyendo Spotify, Apple Music, Shazam y Deezer, y se aplicaron técnicas de análisis exploratorio de datos, reducción de dimensionalidad, clustering y clasificación supervisada.

## Objetivos
- Identificar características clave que determinan el éxito de una canción.
- Desarrollar modelos predictivos para evaluar la popularidad de las canciones.
- Proporcionar recomendaciones basadas en datos para productores musicales y plataformas de streaming.

## Metodología
1. **Análisis Exploratorio de Datos (EDA)**: Visualización y análisis de los datos para identificar patrones y relaciones.
2. **Reducción de Dimensionalidad**: Uso de PCA para simplificar los datos manteniendo la mayor información posible.
3. **Clustering**: Agrupación de canciones en clusters basados en características similares.
4. **Modelos de Clasificación**: Entrenamiento y evaluación de modelos como Regresión Logística, Random Forest, Redes Neuronales, SVM, entre otros.
5. **Evaluación de Modelos**: Uso de métricas como precisión, recall, F1-score para evaluar el desempeño de los modelos.

## Resultados
- Los modelos lograron identificar características significativas que influyen en el éxito de las canciones.
- El modelo de Redes Neuronales obtuvo el mejor desempeño con una precisión de 72%, recall de 67%, y F1-score de 69%.
- Los resultados sugieren que el modelos mejor apto para los datos es de Redes Neuronales.

## Requisitos
- Python 3.12.2
- Librerías: pandas, numpy, scikit-learn, matplotlib, seaborn, etc.
- Archivos de datos (https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/data).

## Instalación
1. Clonar el repositorio:
    ```sh
    git clone https://github.com/Roberto13-Vil/spotify-music-analysis.git
    cd spotify-music-analysis
    ```
2. Crear un entorno virtual e instalar las dependencias:
    ```sh
    python -m venv env
    source env/bin/activate  # en Windows usa `env\Scripts\activate`
    pip install -r requirements.txt
    ```

## Uso
1. Ejecutar el notebook Jupyter:
    ```sh
    jupyter notebook Proyecto.ipynb
    ```
2. Seguir las instrucciones dentro del notebook para reproducir el análisis y los resultados.

## Conclusiones
El proyecto demuestra que es posible predecir el éxito de las canciones en plataformas de streaming utilizando técnicas avanzadas de análisis de datos y machine learning. Aunque el modelado es complejo y requiere un enfoque cuidadoso, los resultados obtenidos proporcionan insights valiosos para la industria musical.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir, por favor crea un fork del repositorio, realiza tus cambios y envía un pull request.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.
