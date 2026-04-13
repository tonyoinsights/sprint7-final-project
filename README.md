# sprint7-final-project

Análisis de Clientes y Rentabilidad: ConnectaTel 📊

Este proyecto consiste en un análisis integral de los datos de consumo de la empresa de telecomunicaciones ConnectaTel. El objetivo es evaluar el comportamiento de los usuarios en dos planes distintos (Surf y Ultimate) para identificar patrones de uso, detectar anomalías y proponer estrategias que optimicen la rentabilidad y la retención de clientes.

🎯 Objetivo del Proyecto
Analizar el comportamiento de consumo (llamadas, mensajes y datos) de 500 usuarios para determinar cuál de los planes genera mayores ingresos y proponer una segmentación estratégica que permita personalizar las ofertas comerciales de la compañía.

📂 Datasets Utilizados
El análisis se basa en tres fuentes de datos principales:

users.csv: Información demográfica de los usuarios (nombre, edad, ciudad, fecha de registro y plan).

calls.csv: Registro detallado de cada llamada realizada (duración y fecha).

messages.csv: Registro de los mensajes de texto enviados.

Nota: También se utilizó información técnica sobre las tarifas de los planes Surf y Ultimate.

⚙️ Etapas del Análisis
El proyecto se desarrolló siguiendo un flujo de trabajo de ciencia de datos:

Preprocesamiento de Datos: Limpieza de valores nulos, corrección de tipos de datos y manejo de registros sin actividad.

Análisis Exploratorio de Datos (EDA): Identificación de tendencias centrales y dispersión en el consumo de minutos, mensajes y volumen de datos.

Detección de Outliers: Uso de Boxplots para identificar usuarios con consumos extremos ("Heavy Users").

Segmentación de Clientes: Clasificación de usuarios por rangos de edad (Joven, Adulto, Adulto Mayor) y niveles de uso (Bajo, Medio, Alto).

Cálculo de Ingresos: Aplicación de lógica de negocio para calcular cargos básicos y excedentes por plan.

Insights Ejecutivos: Generación de recomendaciones estratégicas basadas en los hallazgos.

🚀 Cómo ejecutar el notebook
Para revisar y ejecutar este análisis, sigue estos pasos:

Abrir en Google Colab:

Sube el archivo .ipynb a tu cuenta de Google Drive.

Haz clic derecho sobre el archivo y selecciona "Abrir con" -> "Google Colab".

Cargar los datos:

Asegúrate de subir los archivos .csv (users, calls, messages) al entorno de ejecución de Colab (icono de carpeta en el panel izquierdo).

Ejecutar celdas:

Ejecuta las celdas en orden secuencial (Shift + Enter).

## 🛠️ Guía de Reproducción

1. **Clona este repositorio** en tu máquina local o terminal:
   ```bash
   git clone [https://github.com/tonyoinsights/sprint7-final-project.git](https://github.com/tonyoinsights/sprint7-final-project.git)

   Acceso directo: También puedes ver el código y los archivos directamente en la página principal del repositorio.
Asegúrate de tener instaladas las librerías necesarias:

Bash
pip install pandas numpy seaborn matplotlib
Coloca los archivos CSV en la misma carpeta que el notebook para que las rutas de lectura funcionen correctamente.

Ejecuta el script para generar los gráficos y las tablas de segmentación.

✍️ Autor
Tony - Senior Accountant & Data Analyst
