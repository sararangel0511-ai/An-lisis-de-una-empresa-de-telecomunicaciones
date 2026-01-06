# 📊 Análisis de Datos ConnectaTel: México & Colombia

## 🎯 Objetivo del Proyecto
Transformar datos crudos de consumo y perfiles de usuarios en conclusiones accionables para optimizar la oferta comercial y mejorar la retención de clientes de **ConnectaTel**. El enfoque principal es la segmentación estratégica y la limpieza de datos técnicos.

## 📁 Datasets Utilizados
* `plans.csv`: Catálogo de precios y beneficios.
* `users_latam.csv`: Datos demográficos y contractuales.
* `usage.csv`: Detalle técnico de llamadas y mensajes.

## 🛠️ Etapas del Análisis
1.  **Carga y Exploración:** Diagnóstico inicial de la estructura.
2.  **Calidad de Datos:** Limpieza de nulos y corrección de errores (ej. edad -999).
3.  **Estadística Descriptiva:** Análisis de medidas de tendencia central y dispersión.
4.  **Visualización:** Identificación de sesgos y outliers mediante histogramas y boxplots.
5.  **Segmentación:** Clasificación de usuarios por edad y nivel de consumo (Bajo, Medio, Alto).
6.  **Insights:** Generación de recomendaciones estratégicas.

## 🚀 Ejecución y Reproducción

### Opción A: Google Colab (Recomendado)
1.  Carga los archivos `.csv` en la carpeta `content` de Colab o conéctalo con Google Drive.
2.  Copia el código del notebook y ejecútalo celda por celda.

### Opción B: Local (Jupyter Notebook)
1.  **Clonar repositorio:** `git clone https://github.com/tu-usuario/nombre-repo.git`
2.  **Instalar dependencias:** `pip install pandas numpy matplotlib seaborn`
3.  **Abrir notebook:** Ejecuta `jupyter notebook` y abre el archivo `.ipynb`.

---
**Tecnologías:** Python 🐍 (Pandas, Numpy, Seaborn, Matplotlib).
