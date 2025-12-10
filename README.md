## Clasificación Automática de Textos Literarios

**Descripción Breve:** Desarrollo y evaluación de modelos de Machine Learning para clasificar textos literarios en inglés (poesía, ensayo, cuento y novela) utilizando características de vocabulario y estructura.


### Planteamiento del Problema

La creciente disponibilidad de textos en formato digital ha impulsado la necesidad de desarrollar sistemas automáticos capaces de organizar y clasificar grandes volúmenes de información escrita. Sin embargo, la clasificación de obras literarias representa un reto particular debido a su diversidad estilística, su complejidad estructural y la variación natural entre autores, épocas y formas de escritura. A diferencia de otros tipos de clasificación textual, identificar correctamente el tipo de texto, requiere modelos capaces de detectar tanto patrones lingüísticos como características estructurales propias de cada forma literaria.

En este proyecto se aborda el problema de diseñar un sistema capaz de clasificar automáticamente textos literarios en inglés, asignándolos a una de cuatro categorías: `poetry`, `essays`, `short stories` y `novels`. Dado que estos tipos de texto presentan longitudes muy variables, estilos heterogéneos y estructuras altamente diferenciadas, la tarea exige explorar modelos de aprendizaje automático que permitan capturar no solo el contenido semántico, sino también propiedades formales y estructurales de los documentos. El reto consiste en desarrollar un modelo que logre un desempeño robusto aun ante diferencias de extensión, compilaciones de obras múltiples y variación entre autores.

### Objetivo

Desarrollar y evaluar un modelo de clasificación automática capaz de identificar con la mayor precisión posible el tipo de texto literario al que pertenece un documento en inglés, utilizando técnicas de procesamiento de lenguaje natural (NLP) y modelos de aprendizaje automático basados en características tanto lingüísticas como estructurales.

### Descripción del Dataset

El conjunto de datos utilizado en este proyecto fue construido manualmente a partir de textos descargados del repositorio digital **Project Gutenberg**, una plataforma que ofrece obras literarias de dominio público. Para garantizar una correcta representación de cada categoría, se realizó una selección cuidadosa mediante filtros de búsqueda que permitieran obtener textos acordes a las cuatro clases definidas: `poetry`, `essays`, `short stories` y `novels`.
