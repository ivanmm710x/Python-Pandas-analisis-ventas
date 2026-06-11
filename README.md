# Análisis de Ventas de Negocio con Pandas 🛒📊

Este proyecto forma parte de mi portfolio como Analista de Datos Junior. He utilizado Python y la librería Pandas para procesar, limpiar y extraer conclusiones de negocio a partir de un dataset de registros de ventas en bruto.

## 🎯 Objetivo del Proyecto

El objetivo principal de este Notebook no es solo manipular datos, sino responder a preguntas reales que cualquier departamento de ventas o dirección necesitaría saber para tomar decisiones estratégicas. 

## 💡 Preguntas de Negocio Resueltas

Durante el análisis, he aplicado técnicas de agrupación y ordenación para dar respuesta a las siguientes métricas clave:

1. **El Producto Estrella:** Identificación del producto individual con mayor volumen de unidades vendidas.
2. **Estacionalidad (El Mejor Mes):** Análisis temporal para descubrir en qué mes se generó el mayor pico de ingresos. Para ello, se transformaron los datos de texto plano a formato `datetime` internacional, extrayendo el mes exacto de cada transacción.
3. **Rentabilidad por Categoría:** Un paso atrás en la granularidad para agrupar las ventas por familias de productos, identificando qué categoría general aporta más valor económico a la empresa.

## 🛠️ Herramientas y Técnicas Aplicadas

* **Python & Pandas:** Como motor principal del análisis.
* **Limpieza y Transformación:** Conversión de formatos de fecha americanos (`MM/DD/YYYY`) al estándar de objetos de tiempo de Pandas para poder operar matemáticamente con ellos.
* **Agrupaciones (`groupby`):** Uso intensivo del método de separación y aplicación de cálculos (`.sum()`) para resumir miles de filas en tablas de impacto visual directo.
* **Optimización de Código:** Creación de variables al vuelo (como la extracción de `.dt.month`) para mantener el rendimiento y la legibilidad sin saturar el DataFrame con columnas innecesarias.

## 🚀 Cómo ver el proyecto

Puedes explorar el código, la lógica paso a paso y las tablas de resultados haciendo clic en el archivo `.ipynb` de este mismo repositorio. El Notebook está documentado para explicar el "por qué" de cada decisión técnica.
