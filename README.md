# Análisis de Debate Electoral
Este repositorio contiene el código y los datos utilizados para analizar los transcritos de los debates electorales. A continuación, se describen los pasos clave del proceso:

## 1. Obtención del Texto del Debate
Para obtener los transcritos de los debates, descargué los archivos desde la página del INE (Instituto Nacional Electoral) utilizando la biblioteca de Python requests. Luego, limpié el texto para eliminar cualquier “residuo” del formato HTML y asegurarme de que solo se incluyeran las intervenciones de los candidatos.

## 2. Procesamiento con NLTK
Utilicé la biblioteca NLTK para procesar el texto. En primer lugar, eliminé las palabras comunes (stop words) y los signos de puntuación. A continuación, calculé la frecuencia de cada palabra en el texto resultante.

## 3. Visualización de Resultados
Para visualizar los datos, empleé las bibliotecas pandas y seaborn. Estas herramientas permitieron crear gráficos y tablas que presentan de manera clara y concisa los resultados del análisis.

¡No dudes en explorar el código y los datos en este repositorio! Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue o ponerte en contacto conmigo.
