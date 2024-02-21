## Contenido:
Este directorio incluye cuatro carpetas y un archivo .txt, cada uno con componentes clave para la ejecución de scripts de procesamiento y análisis de datos.

1. `requirements.txt`:
   - Contiene una lista detallada de las bibliotecas y versiones de los lenguajes de programación necesarios para ejecutar los scripts incluidos en las carpetas.

2. Carpetas:
   - `/Datos':
     - `TRAIN.csv`: Conjunto de datos de entrenamiento.
     - `frases.csv`: Colección de frases proporcionadas por Accenture.
   - `/Método Árbol de decisión y Naïve Bayes`:
     - Notebook `.ipynb` que documenta los pasos para la generación de modelos Árbol de Decisión y Naïve Bayes, incluyendo comentarios explicativos.
   - `/Red Neuronal`:
     - `Solución con Red Neuronal.ipynb`: Notebook para el entrenamiento y evaluación de la red neuronal.
     - `modelo_red_neuronal.keras`: Modelo de red neuronal entrenado y exportado para el uso en interfaz.
     - `tokenizer.json`: Tokenizador necesario para la implementación de la red neuronal en la interfaz.
     - `SBW-vectors-300-min5.txt.bz2`: Archivo de word embedding para la capa de entrada de la red neuronal.
   - `/Interfaz`:
     - Notebook `.ipynb` que, al ejecutarse, permite la visualización de la interfaz de usuario descrita en la documentación del proyecto.
   - `/Memoria`:
     - `Memoria.pdf`: Documento con la memoria de prácticas detallando el proyecto.

## Instrucciones de Uso:
Para garantizar el correcto funcionamiento de los scripts, siga las instrucciones de instalación y ejecución detalladas en el archivo `requirements.txt`.

Nota: Al ejecutar Solución con Red Neuronal.ipynb se sobreescriben los archivos de modelo_red_neuronal.keras y tokenizer.json. Se puede hacer si se desea comprobar el funcionamiento completo del script.
