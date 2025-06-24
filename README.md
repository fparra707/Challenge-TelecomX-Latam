# 📊 Análisis de Retiro de Clientes - TelecomX LATAM

Este proyecto analiza los factores que influyen en el retiro (churn) de clientes en una empresa de telecomunicaciones, utilizando visualizaciones y estadísticas descriptivas. 
Se trabaja sobre un conjunto de datos proporcionado en la URL:
- url ='https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json'


## 📁 Contenido

- `Challenge_TelecomX_LATAM_Final.ipynb`: Notebook principal con todo el análisis, visualizaciones y hallazgos.
- Gráficas de comparación de acuerdo a:
  - Género
  - Edad (Clientes senior mayores de 60 años)
  - Meses de contrato (tenure)
  - Tipo de contrato
  - Formas de pago
  - Tipo de servicio de internet
- Estadísticas generales del conjunto de datos
- Recomendaciones estratégicas para reducir la tasa de retiro


## 🛠 Herramientas y Tecnologías

- Python
- Pandas
- Plotly Express
- Google Colab / Jupyter Notebook


## 🎯 Objetivos

- Identificar patrones en el retiro de clientes.
- Determinar variables clave que predicen abandono.
- Proponer recomendaciones basadas en los hallazgos.


## 📌 Principales Hallazgos

- Clientes con **contratos mensuales**, **pagos manuales** y **menor antigüedad** presentan mayor riesgo de abandono (retiro).
- Los **clientes mayores de 60 años** muestran una tasa de retiro elevada.
- La **fibra óptica** tiene más retiros que otros servicios, lo cual puede estar ligado a la calidad, precio o espectativa.
- No se encontraron diferencias significativas basadas en el género.


## ✅ Recomendaciones

- Fomentar **contratos a largo plazo**.
- Incentivar el uso de **pagos automáticos**.
- Fortalecer el **soporte a nuevos clientes** y **clientes senior**.
- Mejorar la calidad percibida del **servicio de fibra óptica**.


## 🚀 Cómo usar

1. Abre el archivo `.ipynb` en Google Colab o Jupyter.
2. Asegúrate de tener instaladas las siguientes librerías:
- Pandas
- Numpy
- Plotly


## 🧑‍💻 Autor

Proyecto desarrollado en el marco del Challenge de Data Science (TelecomX) de Alura LATAM.
