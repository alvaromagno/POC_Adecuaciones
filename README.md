# POC Adecuaciones Curriculares con OpenAI

## Descripción

Este **Proof of Concept (POC)** utiliza la **API de OpenAI** para generar adecuaciones curriculares para estudiantes con **Necesidades Educativas Especiales (NEE)**. Implementado en **Python** con **Jupyter Notebook**, el proyecto carga preguntas de una evaluación estándar desde un archivo `.docx`, solicita el diagnóstico de NEE del estudiante y adapta las evaluaciones conforme a las normativas educativas vigentes.

## Características

- **Carga de Evaluaciones**: Importa preguntas de evaluación desde archivos `.docx`.
- **Interacción con el Usuario**: Solicita el diagnóstico de NEE del estudiante.
- **Generación de Adecuaciones Curriculares**: Utiliza la API de OpenAI para adaptar las preguntas según el diagnóstico.
- **Visualización de Resultados**: Muestra las preguntas originales y las adecuaciones generadas para fácil comparación.
- **Manejo de Errores**: Implementa verificaciones y mensajes claros para guiar al usuario en caso de errores.

## Tecnologías Utilizadas

- **Python 3.x**
- **Jupyter Notebook**
- **Librerías de Python**:
  - `openai`: Para interactuar con la API de OpenAI.
  - `python-docx`: Para leer y manipular archivos `.docx`.
  - `python-dotenv`: Para manejar variables de entorno de forma segura.
- **Git y GitHub**: Para control de versiones y alojamiento del código.

## Requisitos

- **Python 3.x** instalado en tu sistema.
- **Cuenta de GitHub** para alojar el repositorio.
- **Clave API de OpenAI** para acceder a los modelos de lenguaje.
- **Archivo de evaluación** en formato `.docx` con las preguntas estándar.

## Instalación

1. **Clonar el Repositorio**

   ```bash
   git clone https://github.com/tu_usuario/POC_Adecuaciones.git
   cd POC_Adecuaciones

