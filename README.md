📌 Introducción del Proyecto

Este proyecto nace con el objetivo de crear un Storytelling de Retail interactivo utilizando Python y la librería PyNarrative para visualizar de manera clara la evolución de ventas, utilidades y clientes en el tiempo.

🔹 Fase 1 – Desarrollo local en Spyder
El punto de partida fue la construcción del script en Spyder (IDE de Python). Allí se diseñó la lógica para:

Cargar archivos de entrada (CSV o Excel).

Procesar los datos con pandas.

Generar narrativas visuales mediante PyNarrative (gráficas con contexto, títulos y storytelling).

Este desarrollo inicial permitió validar la funcionalidad en entorno local.

🔹 Fase 2 – Integración con Streamlit
Posteriormente, se integró la solución con Streamlit, una herramienta que permite crear aplicaciones web interactivas directamente desde Python. Con ello, el Storytelling pasó de ser un script local a una aplicación con interfaz gráfica que:

Permite subir archivos de datos.

Ofrece selección de distintos tipos de historias (Ventas, Utilidades, Clientes).

Muestra gráficas dinámicas y contextualizadas listas para interpretación.

🔹 Fase 3 – Despliegue en la nube con GitHub + Streamlit Cloud
Para facilitar el acceso público, se creó un repositorio en GitHub con:

El archivo principal Ejemplo_1_Storytelling.py.

El archivo requirements.txt para instalar las dependencias necesarias.

Luego, el repositorio fue conectado con Streamlit Community Cloud, lo que genera automáticamente una URL pública para que cualquier persona pueda ejecutar la aplicación desde su navegador, sin necesidad de instalar nada.

🚀 Beneficios del proyecto

Democratiza el acceso al análisis de datos retail mediante una interfaz web.

Integra storytelling con visualizaciones interactivas.

Reduce la dependencia de entornos locales, migrando hacia soluciones compartidas en la nube.

👉 Este flujo (Spyder → Streamlit → GitHub → Streamlit Cloud) refleja un caso práctico de cómo llevar un análisis de datos desde el desarrollo inicial hasta su despliegue web accesible públicamente.
