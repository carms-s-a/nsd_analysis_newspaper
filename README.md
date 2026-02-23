## ¡Proyecto en curso!
# nsd_analysis_newspaper

DISCLAIMER: Este repositorio utiliza información accesible de los materiales descargables del libro en cuestión tras su compra. Los derechos pertenecen al autor. Este repositorio tiene fines exclusivamente académicos.

## Descripción
Un ejercicio de análisis de datos no estructurados para un repositorio de textos extraídos de periódicos del libro "Analítica textual" de John Atkinson-Abutridy. Introducción a la ciencia y aplicación del análisis de información no estructurada"

### Estructura del repositorio

/corpus/        → textos originales  
/notebooks/     → análisis exploratorio y modelado  
/data/          → datos procesados (si aplica)

# ¿Cómo reproducir este análisis?
1. Abre el archivo que desees observar en el directorio '/notebooks/' de este repositorio
2. A continuación, haz clic en **Open in Colab**
3. El dataframe se podrá cargar desde el directorio '/corpus/', almacenado en este mismo repositorio. 
4. A continuación podrás ejecutar las celdas en órden.

# Objetivo del análisis
Utilizar herramientas de la minería de datos y la analítica textual para realizar labores de agrupación de textos, extracción de información categorización de textos e inferencia de relaciones por medio de una metodología que incluye: 
1. Preprocesamiento del texto por medio de metodologías como lematización, stemming y POS tagging
2. Generación y selección de características
3. Descubrimiento e interpretación de patrones

#Librerías de python utilizadas: 
1. SnowballStemmer para la realización del stemming
2. es_core_news para modelos de lenguaje en español específicos a notas periodísticas
3. from spacy.lang.es.stop_words: STOP_WORDS para el uso de stop words
4. from string: punctuation para la definición de puntuación 
