# Challenge-Alura-Store-LATAM
Desarrollo del desafío: Challenge: Alura Store LATAM
# Alura Store Latam - Análisis de Ventas y Recomendación de Venta

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-1.3.0-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.2-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red.svg)

## 📋 Descripción del Proyecto

Este repositorio contiene un análisis completo de datos de cuatro tiendas virtuales pertenecientes a un mismo holding en Latinoamérica. El objetivo principal es **determinar cuál de estas tiendas es la más adecuada para ser vendida**, basándose en múltiples indicadores de desempeño comercial y operativo.

El análisis incluye:
- Cálculo de ingresos totales por tienda.
- Distribución de ventas por categoría de producto.
- Calificaciones promedio de los clientes.
- Identificación de productos más y menos vendidos.
- Costos de envío promedio.
- Fortalezas y debilidades de cada tienda, contextualizadas por su ciudad principal de operación.

Todo el análisis está documentado en un **notebook de Google Colab** que contiene el código, las visualizaciones y el informe final redactado.

---

## 🎯 Objetivos

- Evaluar el rendimiento económico y operativo de cada tienda.
- Identificar patrones de ventas y preferencias de los clientes.
- Comparar objetivamente las cuatro tiendas mediante KPIs relevantes.
- **Recomendar una tienda para la venta**, justificando la decisión con datos y visualizaciones.

---

> **Nota:** Los datasets se cargan directamente desde las URLs públicas proporcionadas en el notebook. No es necesario descargarlos manualmente.

---

## 🔍 Metodología

1. **Importación y exploración inicial** de los cuatro archivos CSV.
2. **Limpieza y preparación** de los datos (tipos de datos, formato de fechas, etc.).
3. **Cálculo de indicadores clave** por tienda:
   - Ingresos totales.
   - Conteo de ventas por categoría.
   - Calificación promedio.
   - Costo de envío promedio.
   - Producto más vendido / menos vendido.
4. **Identificación de la ciudad principal** de cada tienda (moda de "Lugar de Compra").
5. **Generación de gráficos** para visualizar comparaciones y distribuciones.
6. **Redacción del informe** estructurado con introducción, desarrollo, fortalezas/debilidades y conclusión.

---

## 📊 Resultados Clave

| Tienda | Ingresos Totales | Calificación Promedio | Costo Envío Promedio | Categoría Estrella       |
|-----------------|------------------|------------------------|----------------------|--------------------------|
| **Tienda 1**      | $1,150,880,400   | 3.98                    | $26,019              | Muebles                 |
| **Tienda**    | $1,116,343,500   | 4.04                    | $25,216              | Muebles                 |
| **Tienda**        | $1,098,019,600   | 4.05                    | $24,806              | Electrodomésticos       |
| **Tienda**| $1,038,375,700   | 4.0                    | $23,459             | Electrodomésticos/Muebles|

✅ **Conclusión principal:** La **Tienda Bogotá** es la más recomendada para la venta, debido a su liderazgo en ingresos, alta rotación en categorías premium y diversificación comercial. Aunque tiene oportunidades de mejora en costos logísticos y satisfacción al cliente, su posicionamiento financiero la hace la más atractiva para potenciales compradores.

---

## 🛠️ Requisitos y Ejecución

Puedes ejecutar el análisis directamente en Google Colab haciendo clic en el siguiente enlace:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU_USUARIO/AluraStoreLatam-Analysis/blob/main/AluraStoreLatam_Analisis_Final.ipynb)

**Dependencias locales (si se desea correr fuera de Colab):**
```bash
pip install pandas matplotlib numpy

**Instrucciones para personalizar:**
- Reemplaza `TU_USUARIO` en el badge de Colab con tu nombre de usuario de GitHub.
- Ajusta los valores numéricos y conclusiones si tu análisis arrojó resultados diferentes.
- Cambia "Tu Nombre" y enlaces de contacto por los tuyos.
- Si agregas más archivos (como `requirements.txt` o carpeta `data`), actualiza la estructura.
