# CLASE 1 CONCEPTOS SOBRE RAG

## 📚 Lo que aprendimos

En este proyecto aprendimos a construir un sistema de recuperación de información utilizando **LangChain** y modelos de lenguaje.

💻 **Entorno de trabajo**

* Configuramos un entorno de desarrollo en Google Colab e instalamos las bibliotecas necesarias.

🦜 **LangChain**

* Utilizamos LangChain para integrar y simplificar el uso de modelos de lenguaje (LLMs).

🔐 **Variables de entorno**

* Configuramos credenciales de API de forma segura mediante variables de entorno.

✂️ **Chunking**

* Aplicamos técnicas de segmentación de documentos con **TextSplitter** para mejorar la recuperación de información.

🧠 **Embeddings y base vectorial**

* Generamos embeddings de texto y los almacenamos en una base de datos vectorial para realizar búsquedas semánticas.

🔍 **Recuperación y prompts**

* Configuramos un recuperador (Retriever) y diseñamos prompts optimizados para obtener respuestas precisas y basadas en el contexto.

✅ **Resultado**

* Construimos una base sólida para desarrollar aplicaciones de IA capaces de recuperar información relevante y generar respuestas más precisas.

# CLASE 2 CHUNKING Y VECTORIZACIÓN


## 📚 Lo que aprendimos

En este proyecto aprendimos a construir el proceso de **indexación de documentos** para sistemas **RAG**, optimizando la búsqueda de información mediante bases de datos vectoriales.

📄 **Carga de documentos**

* Utilizamos diferentes loaders de LangChain para importar información desde archivos de texto, PDF y páginas web.

✂️ **Chunking**

* Dividimos los documentos en fragmentos (chunks), ajustando su tamaño para mejorar el rendimiento de los modelos de embeddings.

🧠 **Embeddings**

* Exploramos distintos modelos de embeddings, incluyendo opciones locales con Hugging Face, comprendiendo la importancia de los tokenizadores en la representación del texto.

🗂️ **Bases de datos vectoriales**

* Aprendimos el funcionamiento de las VectorStore y exploramos soluciones como **Pinecone**, comprendiendo cómo crear índices, almacenar embeddings y realizar búsquedas semánticas.

🔍 **Búsqueda por similitud**

* Implementamos un pipeline de indexación y recuperación utilizando búsquedas por similitud para encontrar los documentos más relevantes.

💾 **Implementación del proyecto**

* Aunque estudiamos la integración con **Pinecone** y su forma de crear y administrar índices, **el proyecto final se desarrolló utilizando FAISS como base de datos vectorial local**, permitiendo crear el índice, almacenar los embeddings y realizar consultas semánticas sin depender de un servicio en la nube.

🏷️ **Metadatos y ranking**

* Utilizamos metadatos para filtrar resultados y comprender cómo los scores de similitud ayudan a mejorar la relevancia de las respuestas.

✅ **Resultado**

* Construimos un pipeline de indexación basado en **FAISS**, capaz de organizar, almacenar y recuperar información de forma eficiente para aplicaciones RAG, aplicando los mismos conceptos utilizados en bases de datos vectoriales como Pinecone.


# CLASE E RAG CON OLLAMA

## 📚 Lo que aprendimos

En este proyecto aprendimos a construir un sistema **RAG (Retrieval-Augmented Generation)** utilizando herramientas de código abierto para ejecutar modelos de lenguaje de forma local.

🔗 **Cadena RAG**

* Implementamos una cadena completa con LangChain para conectar la recuperación de información y la generación de respuestas.

🤖 **Modelos locales con OLLAMA**

* Ejecutamos modelos de lenguaje y de embeddings de forma local mediante **OLLAMA**, utilizando el modelo **BGE-M3** de Baidu para generar representaciones vectoriales del texto.

📄 **Procesamiento de documentos**

* Creamos un pipeline para cargar y procesar documentos PDF, preparándolos para su indexación y consulta.

🗂️ **Base de datos vectorial con FAISS**

* Generamos embeddings y construimos un índice local utilizando **FAISS**, permitiendo realizar búsquedas semánticas de forma rápida y eficiente.

🐍 **Entorno virtual**

* Configuramos un entorno virtual para gestionar las dependencias del proyecto y garantizar un entorno de desarrollo aislado y reproducible.

✅ **Resultado**

* Construimos un sistema RAG completamente funcional que procesa documentos, genera embeddings con modelos locales y recupera información mediante **FAISS**, sin depender de servicios en la nube.


# CLASE 4 FINETUNING CON RAG

## 📚 Lo que aprendimos

En este proyecto aprendimos a optimizar la recuperación de información en sistemas **RAG**, mejorando la precisión de las consultas y las respuestas generadas.

🔍 **Retrievers con LangChain**

* Integramos retrievers para realizar búsquedas eficientes dentro de bases de datos vectoriales y recuperar la información más relevante.

⚡ **Optimización de consultas**

* Aplicamos estrategias para mejorar las consultas y diseñamos prompts más efectivos, aumentando la calidad de las respuestas del sistema RAG.

✍️ **Rewrite Retrieval Read (RRR)**

* Implementamos la técnica **Rewrite Retrieval Read**, utilizando un modelo de lenguaje más pequeño para reescribir las consultas del usuario antes de realizar la búsqueda, obteniendo resultados más precisos y relevantes.

✅ **Resultado**

* Construimos un pipeline RAG optimizado, capaz de interpretar mejor las preguntas del usuario, recuperar información de manera más eficiente y generar respuestas con mayor precisión.
