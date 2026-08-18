# A-B-Testing
# 🧪 Experimento A/B: Evaluación de Desempeño en Landing Page

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)](https://scipy.org/)

## 📌 Resumen del Proyecto
Evaluación e interpretación estadística de un **Experimento A/B** aplicado a una página de inicio (*Landing Page*) con dos variantes (**A** y **B**) sobre una muestra de **40,000 usuarios**. El objetivo principal es respaldar la toma de decisiones estratégicas mediante el análisis de la **tasa de conversión**, el **gasto promedio por cliente** y la relación con variables demográficas y canales de adquisición.

---

## 🎯 Objetivos de Negocio
1. **Analizar la Tasa de Conversión:** Determinar si la versión B incrementa significativamente el número de usuarios que realizan una compra/acción.
2. **Evaluar el Monetización:** Verificar si el gasto promedio por usuario convertido difiere según la versión expuesta.
3. **Segmentación de Audiencia:** Identificar el impacto de las fuentes de tráfico (*Organic, Ads, Email, Referral*) y el tipo de usuario (*Nuevo vs Recurrente*) en la conversión.

---

## 📊 Hallazgos Principales & Pruebas Estadísticas

### 1. Tasa de Conversión (Prueba Z de Proporciones)
* **Versión A:** Tasa de conversión del **12.57%** (2,512 convertidos de 19,982 usuarios).
* **Versión B:** Tasa de conversión del **15.96%** (3,194 convertidos de 20,018 usuarios).
* **Resultado:** Se rechaza la hipótesis nula ($p < 0.001$). **La variante B incrementa significativamente la tasa de conversión.**

### 2. Gasto Promedio por Cliente (Prueba T de Student)
* **Versión A:** Gasto promedio de **$61.09**.
* **Versión B:** Gasto promedio de **$68.75**.
* **Resultado:** Se rechaza la hipótesis nula ($p < 0.001$). **Los usuarios expuestos a la Versión B generan un gasto superior.**

### 3. Fuentes de Tráfico (Prueba Chi-Cuadrada)
* **Canal con mayor tasa de conversión:** Email (**14.99%**) y Ads (**14.74%**).
* **Tráfico Orgánico:** Representa el mayor volumen absoluto de usuarios y conversiones, con una tasa del **13.79%**.

---

## 💡 Recomendación Final de Negocio
Se recomienda **implementar la Versión B de la Landing Page de forma definitiva**. Los datos comprueban que no solo atrae a una proporción mayor de compradores (un incremento de +3.39% en conversión), sino que también genera un gasto promedio más alto por cliente.

---

## 🛠️ Tecnologías y Librerías Utilizadas
* **Python 3.x**
* **Pandas / NumPy:** Limpieza, filtrado y estructuración de datos.
* **SciPy / Statsmodels:** Pruebas estadísticas hipótesis (T-Test, Z-Test de Proporciones, Chi-Cuadrada, Prueba Exacta de Fisher).
* **Matplotlib / Seaborn:** Visualización de resultados.

---

## 🚀 Cómo ejecutar este repositorio
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/JorgeCeronDA/A-B-Testing.git]
