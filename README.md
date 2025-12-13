# 📊 Análisis de Datos de una Aplicación de Libros para la Generación de una Propuesta de Valor
Este proyecto realiza un análisis exploratorio y descriptivo de la base de datos de una aplicación de libros mediante consultas SQL, con el objetivo de transformar datos operativos en insights estratégicos. El análisis se enfoca en el comportamiento de los usuarios, el desempeño de los libros, autores y editoriales, y su relación con reseñas y calificaciones, proporcionando información clave para mejorar la oferta de contenido y la experiencia del usuario.

## 🎯 Objetivos

* Analizar el catálogo de libros para identificar tendencias relevantes posteriores al año 2000.
* Evaluar el desempeño de los libros a partir del número de reseñas y calificaciones promedio.
* Identificar editoriales y autores con mayor impacto y aceptación entre los usuarios.
* Generar recomendaciones orientadas a mejorar la visibilidad del catálogo y la participación de los usuarios.
* Proponer acciones estratégicas basadas en datos para fortalecer el sistema de recomendaciones

## 📈 Hallazgos Clave

* Se identificó el volumen de libros publicados después del 1 de enero de 2000, reflejando la evolución reciente del catálogo.
* Existe una variabilidad significativa en el número de reseñas entre libros, lo que impacta directamente en la confiabilidad de la calificación promedio.
* Determinadas editoriales concentran una mayor cantidad de libros con más de 50 páginas, lo que indica un mayor peso dentro del catálogo relevante.
* Al considerar únicamente libros con al menos 50 calificaciones, se logró identificar a los autores con mejor desempeño promedio.
* Los usuarios más activos en calificaciones y reseñas concentran una parte importante del feedback disponible en la plataforma.

## 🔍 Conclusiones Estratégicas
Para rankings como “Top 10 mejores libros”, es clave considerar tanto la calificación promedio como el volumen de reseñas para evitar sesgos. Los libros con altas calificaciones pero pocas reseñas representan oportunidades estratégicas para ser promovidos como “Libros por descubrir”.

Incrementar la participación de los usuarios mediante recordatorios contextuales (correo o notificaciones in-app) puede mejorar la calidad y cantidad de datos disponibles, al igual que, identificar autores y editoriales mejor calificados permite detectar patrones por género y optimizar el algoritmo de recomendaciones.

## 🧪 Herramientas y Tecnología
* SQL
* Python
* SQLAlchemy (create_engine)
* python-dotenv (load_dotenv) y variables de entorno (os)
* Pandas
* Jupyter Notebook