# Movilidad CDMX (2021–2025)

Este proyecto analiza la afluencia en los principales sistemas de transporte público de la Ciudad de México: **Metro, Metrobús, Trolebús, Cablebús y Tren Ligero**, utilizando datos abiertos actualizados hasta agosto de 2025.

## 🎯 Objetivo
Identificar patrones de movilidad, tendencias temporales y diferencias entre líneas, estaciones y tipos de pago.  
Los resultados se presentarán en un **dashboard en Power BI**, con:
- Una hoja dedicada a cada transporte.
- Una visión general comparativa.
- Un **chatbot integrado en Power BI** para responder preguntas de negocio de forma interactiva.


## 🧹 Proceso en Python (EDA completado ✅)

### 🔹 EDA Parte 1
- Revisión de estructura inicial, valores nulos y duplicados.  
- Primeras visualizaciones exploratorias.  

### 🔹 EDA Parte 2
- Limpieza y estandarización de columnas (minúsculas, sin acentos, nombres consistentes).  
- Conversión de tipos de datos (`fecha`, `anio`, `mes`, `afluencia`).  
- Unificación de datasets en un único DataFrame con 9 columnas estándar.  
- Resumen exploratorio consolidado (volumen, fechas, sistemas, líneas y estaciones).  

### 🔹 EDA Parte 3
- Análisis temporal: evolución mensual, participación relativa y patrones estacionales.  
- Análisis por líneas y estaciones (Top 10 de mayor afluencia).  
- Distribuciones y outliers (histogramas, boxplots).  
- Correlaciones básicas entre `anio`, `mes` y `afluencia`.  
- **Exportación del dataset final limpio** → `movilidad_cdmx_2021_2025.csv` (solo en local, no en repo por tamaño).  

## 📂 Estructura (en progreso)
- `data/` → datasets de afluencia.
- `README.md` → descripción general del proyecto.
- `notebooks/` → análisis exploratorio en Python 
- `reports/` → figuras y hallazgos (pendiente).
- `powerbi/` → archivo del dashboard (pendiente).


---
📌 *Proyecto en desarrollo *
