# 🧠 Análisis de Sentimiento en Comentarios de Usuarios usando Inteligencia Artificial

## Descripción del Proyecto

Este proyecto fue diseñado para **Codificando** (empresa ficticia) como parte de un análisis sobre la satisfacción de los estudiantes que participaron en diferentes cursos. Utilizando técnicas de análisis de sentimiento y herramientas de visualización de datos, se buscó obtener insights clave a partir de los comentarios proporcionados por los estudiantes.

El objetivo es entender cómo los estudiantes perciben los cursos, identificando oportunidades para mejorar la calidad educativa y la lealtad hacia la institución.

## 🎯 Objetivos del Proyecto

1. **Clasificar comentarios:** Analizar y clasificar los comentarios de los estudiantes en tres categorías: positivos, negativos y neutros.
2. **Perfil demográfico:** Analizar el perfil de los estudiantes según género, edad y curso realizado.
3. **Análisis de satisfacción:** Examinar la satisfacción general y la disposición de los estudiantes para recomendar los cursos.
4. **Generar recomendaciones:** Proponer estrategias basadas en los insights obtenidos para mejorar la experiencia de los estudiantes.

## 📊 Metodología

1. **Generación del Dataset:**
   - Se crearon 100 comentarios ficticios utilizando ChatGPT, clasificados en neutros, positivos y negativos.
   - Se generó un DataFrame con datos aleatorios como edad (18 a 50 años), género (F o M), cursos realizados, si ya habían cursado antes y si recomendarían el curso.

2. **Análisis de Sentimiento:**
   - Se utilizó el modelo preentrenado `nlptown/bert-base-multilingual-uncased-sentiment` para realizar el análisis de sentimientos.
   - Los comentarios se clasificaron automáticamente y los resultados se inspeccionaron para verificar su coherencia.

3. **Visualización de Resultados en Power BI:**
   - Se creó un informe en Power BI con gráficos que representan el perfil de los estudiantes (porcentaje por género, cantidad por rango etario y curso realizado).
   - Se visualizó la distribución de sentimientos en una nube de palabras, y gráficos que muestran el porcentaje de sentimientos por curso.
   - También se analizaron las respuestas sobre si volverían a cursar y si recomendarían los cursos a otros.

## 🔍 Resultados

- **Sentimiento General:** El 50% de los estudiantes expresaron comentarios positivos, lo que sugiere una satisfacción general aceptable, pero con margen para mejorar.
- **Cursos Específicos:** Se encontró un equilibrio entre comentarios positivos y negativos en el curso de Data Analytics, indicando áreas de mejora.
- **Recomendaciones:** Solo el 53% de los estudiantes recomendarían el curso, lo que abre una oportunidad para implementar estrategias de fidelización, como descuentos o beneficios por referidos.
- **Nuevos Estudiantes:** Más de la mitad de los estudiantes eran nuevos, lo que resalta la importancia de mantener altos estándares de calidad y brindar un soporte adecuado.

## 📝 Conclusión

Este análisis de sentimiento revela importantes insights sobre la percepción de los estudiantes y su satisfacción con los cursos. Se recomienda enfocar los esfuerzos en mejorar la experiencia educativa, con especial atención a los temas más mencionados, como los profesores, tutores y el contenido de las clases. Además, se sugiere implementar estrategias para aumentar la recomendación de los cursos y fidelizar a los estudiantes actuales.

## 📂 Archivos del Proyecto

- **Colab Notebook:** Análisis de sentimientos y creación del dataset.
- **Power BI Dashboard:** Visualización de los resultados del análisis de perfil y sentimiento.
- **PDF:** Informe final con los hallazgos clave.

## 🚀 Cómo Utilizar este Repositorio

1. Clona el repositorio en tu máquina local.
2. Abre el notebook de Colab para revisar o ejecutar el análisis de sentimientos.
3. Explora el archivo de Power BI para visualizar las gráficas y el informe.
4. Consulta el informe en PDF para obtener un resumen de los resultados y conclusiones.

## 🔧 Futuras Mejoras

- Ampliar el análisis de sentimientos a un conjunto de datos más grande para obtener resultados más representativos.
- Implementar métricas de evaluación más robustas para el análisis de sentimiento.
- Incluir un análisis más detallado de los comentarios negativos para identificar áreas específicas de mejora.

---

> **Nota:** Este proyecto es parte de mis primeros pasos en el mundo del Data Analytics y  Data Science, por lo que puede contener errores. Agradezco cualquier feedback constructivo.

