# TFG
Generación automática de síntesis científicas mediante la adaptación de modelos de lenguaje

Descripción

Este proyecto de Trabajo de Fin de Grado (TFG) se centra en la exploración y aplicación de modelos de lenguaje basados en arquitecturas Transformer, específicamente T5 y Pegasus, para la generación automática de resúmenes de textos científicos. Se han implementado técnicas de fine-tuning y preprocesamiento adaptadas al dominio científico, utilizando un corpus especializado para entrenar y evaluar los modelos.

Estructura del repositorio

- Dataset.zip: Conjunto de datos utilizado para el entrenamiento y evaluación de los modelos.
- MultiLevelRichCorpus.zip: Corpus enriquecido con múltiples niveles de información para mejorar la calidad de los resúmenes generados.
- train_pegasus.py: Script en Python para el entrenamiento del modelo Pegasus.
- train_t5.py: Script en Python para el entrenamiento del modelo T5.
- test_multilevelrichcorpus.py: Script para la evaluación de los modelos utilizando el corpus enriquecido.
- estadísticas_bbdd.py: Script para el análisis estadístico de la base de datos utilizada.
- modelos_sin_entrenar.py: Script para la inicialización y configuración de los modelos antes del entrenamiento.
- README.md: Este archivo, que proporciona una visión general del proyecto.

Requisitos del sistema

Para ejecutar este proyecto, se recomienda tener instalado:
- Python 3.8 o superior
- Jupyter Notebook
Las siguientes bibliotecas de Python:
- transformers
- datasets
- torch
- numpy
- pandas

Para cualquier consulta o sugerencia, puedes contactar a la autora:
María Gómez
Correo electrónico: mariiagoomez5@gmail.com
