# Detección de Jugadores de Fútbol

## Descripción

Este proyecto se centra en la detección de jugadores de fútbol en videos utilizando el modelo YOLOv8, combinado con la API de Roboflow para obtener un conjunto de datos específico de detección de jugadores de fútbol.

## Objetivo

El objetivo principal del proyecto es identificar y etiquetar automáticamente a los jugadores de fútbol y árbitros en videos, dibujando elipses alrededor de ellos y diferenciándolos por colores.

## Herramientas y Librerías Utilizadas

- **YOLOv8**: Un modelo de detección de objetos de última generación proporcionado por Ultralytics.
- **Roboflow**: Una plataforma que proporciona herramientas para la preparación y gestión de conjuntos de datos de visión por computadora.
- **OpenCV**: Una librería de visión por computadora que permite manipular y procesar imágenes y videos.
- **Matplotlib**: Utilizada para la visualización de imágenes.
- **Keras**: Utilizada para construir y entrenar modelos de aprendizaje profundo.
- **Google Colab**: Ambiente de desarrollo utilizado para ejecutar el notebook, que proporciona acceso a recursos de GPU.

## Pasos del Proyecto

1. **Instalación de dependencias**: Instalación de las librerías necesarias, incluyendo `ultralytics`, `requests`, `opencv-python-headless` y `roboflow`.
2. **Configuración de YOLOv8**: Importación y configuración del modelo YOLOv8 para la detección de objetos.
3. **Descarga de datos**: Uso de la API de Roboflow para descargar el conjunto de datos de detección de jugadores de fútbol.
4. **Procesamiento de videos**: Lectura de un video de fútbol, aplicación del modelo de detección y dibujo de elipses alrededor de los jugadores y árbitros detectados.
5. **Generación de resultados**: Guardado del video procesado con las detecciones realizadas por el modelo.

## Cómo Utilizar

1. **Ejecutar el notebook**: Subir y ejecutar el notebook en Google Colab o en cualquier otro entorno compatible con Jupyter.
2. **Proporcionar el video de entrada**: Asegurarse de que el video de fútbol esté disponible en la ruta especificada en el notebook.
3. **Obtener la salida**: El notebook generará un video con las detecciones realizadas, dibujando elipses alrededor de los jugadores y diferenciando a los árbitros con un color distinto.

## Consideraciones

- Es necesario tener una clave de API de Roboflow para poder descargar el conjunto de datos.
- Asegurarse de tener suficiente espacio de almacenamiento y recursos de procesamiento, especialmente si se trabaja con videos largos y de alta resolución.
- Verificar la compatibilidad de las versiones de las librerías utilizadas con el entorno de ejecución.
