## Contenido:
Este directorio incluye cuatro carpetas y un archivo .txt, cada uno con componentes clave para la ejecución de scripts de procesamiento y análisis de datos.

1. `requirements.txt`:
   - Contiene una lista detallada de las bibliotecas y versiones de los lenguajes de programación necesarios para ejecutar los scripts incluidos en las carpetas.

2. Carpetas:
   - `/Datos`:
     - `TRAIN.csv`: Conjunto de datos de entrenamiento.
     - `frases.csv`: Colección de frases proporcionadas por Accenture.
   - `/Método Árbol de decisión y Naïve Bayes`:
     - Notebook `.ipynb` que documenta los pasos para la generación de modelos Árbol de Decisión y Naïve Bayes, incluyendo comentarios explicativos.
   - `/Red Neuronal`:
     - `Solución con Red Neuronal.ipynb`: Notebook para el entrenamiento y evaluación de la red neuronal.
     - `modelo_red_neuronal.keras`: Modelo de red neuronal entrenado y exportado para el uso en interfaz.
     - `tokenizer.json`: Tokenizador necesario para la implementación de la red neuronal en la interfaz.
     - `SBW-vectors-300-min5.txt.bz2`: Archivo de word embedding para la capa de entrada de la red neuronal, creado por [Cristian Cardellino](https://github.com/crscardellino). No incluido en este repositorio. Se puede descargar directamente en el siguiente [enlace](https://cs.famaf.unc.edu.ar/~ccardellino/SBWCE/SBW-vectors-300-min5.txt.bz2) y añadir manualmente a la carpeta `/Red Neuronal`.
   - `/Interfaz`:
     - Notebook `.ipynb` que, al ejecutarse, permite la visualización de la interfaz de usuario descrita en la documentación del proyecto.
   - `/Memoria`:
     - `Memoria.pdf`: Documento con la memoria de prácticas detallando el proyecto.

## Instrucciones de Uso:
Para garantizar el correcto funcionamiento de los scripts, siga las instrucciones de instalación y ejecución detalladas en el archivo `requirements.txt`.

Nota: Al ejecutar Solución con `Red Neuronal.ipynb` se sobreescriben los archivos de `modelo_red_neuronal.keras` y `tokenizer.json`. Se puede hacer si se desea comprobar el funcionamiento completo del script.

## Referencias
Cristian Cardellino: Spanish Billion Words Corpus and Embeddings (March 2016), https://crscardellino.github.io/SBWCE/.

--------------------------------------------------

## What is this about?

This repo is a project developed by four students of the Universidad Complutense of Madrid for a university contest, in which different enterprises proposed real-world-problems for the students to solve. We agreed to solve the one proposed by `Accenture`, and so we did! 

The problem we faced was triying to discriminate between texts produced by AI and human texts. We approched the problem from diffenrent perpectives. If you are interested you can read the `Memoria.pdf`.

## Content:

This directory includes four folders and a .txt file, each containing key components for running data processing and analysis scripts.

1. `requirements.txt`:
   - Contains a detailed list of the libraries and programming language versions needed to run the scripts included in the folders.

3. Folders:
   - `/Datos`:
     - `TRAIN.csv`: Training dataset.
     - `sentences.csv`: Collection of sentences provided by Accenture.
   - `/Método Árbol de decisión y Naïve Bayes`:
     - `.ipynb` notebook that documents the steps for generating Decision Tree and Naïve Bayes models, including explanatory comments.
   - `/Red Neuronal`:
     - `Neural Network Solution.ipynb`: Notebook for training and evaluating the neural network.
     - `neural_network_model.keras`: Trained and exported neural network model for use in the interface.
     - `tokenizer.json`: Tokenizer required for the implementation of the neural network in the interface.
     - `SBW-vectors-300-min5.txt.bz2`: Word embedding file for the input layer of the neural network, created by [Cristian Cardellino](https://github.com/crscardellino). Not included in this repository. It can be downloaded on the following [link](https://cs.famaf.unc.edu.ar/~ccardellino/SBWCE/SBW-vectors-300-min5.txt.bz2) and manually added to the `/Red Neuronal` folder.
   - `/Interfaz`:
     - `.ipynb` notebook that, when executed, allows the visualization of the user interface described in the project documentation.
   - `/Memoria`:
     - `Memory.pdf`: Document with the internship report detailing the project.

## Instructions for Use:

To ensure the correct operation of the scripts, follow the installation and execution instructions detailed in the `requirements.txt` file.

Note: When executing `Neural Network Solution.ipynb` the `model_red_neuronal.keras` and `tokenizer.json` files are overwritten. This can be done if you want to check the complete functionality of the script.

## References
Cristian Cardellino: Spanish Billion Words Corpus and Embeddings (March 2016), https://crscardellino.github.io/SBWCE/.
