# 📊 Análisis de Ventas de Adventure Works con Power BI

## 🏫 Institución
Proyecto desarrollado como parte del Módulo 3 de la carrera **Data Analytics**.

---

## 🧾 Introducción

**Adventure Works Cycles** es una empresa multinacional que fabrica y distribuye bicicletas, piezas y accesorios en América del Norte, Europa y Asia. Con más de 500 empleados, enfrenta desafíos para tomar decisiones informadas debido a la falta de indicadores de negocio eficientes.

Este proyecto tiene como objetivo diseñar un informe en Power BI que permita analizar las ventas, costos y rentabilidad de la empresa, brindando insights claros y visualmente atractivos para la toma de decisiones estratégicas.

---

## 🚀 Desarrollo del Proyecto

El proyecto se dividió en 4 etapas:

### 1️⃣ Limpieza y transformación de datos (Power Query)

- Se descargó la base de datos **AdventureWorksDW2019** y se restauró en **SQL Server**.
- Se conectó Power BI a esta base y a un archivo `.csv` adicional con información de clientes.
- Se realizó un proceso de limpieza en Power Query:
  - Eliminación de columnas innecesarias y filas nulas.
  - Renombramiento de columnas y normalización de datos.
  - Promoción de encabezados y transformación de tipos de datos.
  - Combinación de tablas para lograr un modelo en estrella eficiente.

### 2️⃣ Modelado de datos

- Se diseñó un modelo en **esquema estrella** optimizado para rendimiento y análisis.
- Se definieron relaciones adecuadas entre tablas evitando relaciones muchos a muchos (M:M).
- Se utilizó la tabla `DimDate` como calendario.
- Se creó un **Mockup** con base en las necesidades del negocio, organizando las visualizaciones en 3 páginas:
  - **Portada**
  - **Resumen General**
  - **Mercado USA**
- Se aplicó el **patrón de lectura en Z** para la disposición visual.

### 3️⃣ Cálculo de métricas con DAX

- Se crearon medidas y columnas calculadas para responder preguntas clave del negocio.
- Se organizaron en carpetas dentro de una tabla central llamada `Medidas_All`.
- Se agregaron jerarquías de tiempo (`Año`, `Mes`) y columnas personalizadas como `Trimestre` y `Mes Corto`.
- Se deshabilitó la carga de tablas auxiliares para mejorar el rendimiento del modelo.

### 4️⃣ Diseño del reporte en Power BI

- El reporte fue diseñado en formato 1080x1920 para facilitar la visualización.
- Se usaron visualizaciones representativas, limpias e interactivas.
- Se incluyeron botones de navegación y de reseteo de filtros.
- La experiencia de usuario fue optimizada para que los gráficos reaccionen dinámicamente según la selección del usuario.

---

## 📈 Análisis del Tablero y Principales Resultados

- Años extremos como **2010 y 2014** presentan datos incompletos y no fueron considerados para análisis concluyentes.
- **2013** fue el año con mayor cantidad de ventas, con un margen de ganancia sostenido del 40%.
- **Estados Unidos** concentra la mayor cantidad de clientes, distribuidos en distintos estados.
  
### 🔮 Recomendaciones a futuro

- Ampliar la base de clientes en otros países.
- Analizar segmentos por edad, nivel educativo y poder adquisitivo para campañas específicas.
- Evaluar rendimiento por categoría de producto.
- Incorporar análisis de costos y eficiencia de producción con enfoque ambiental.
- Analizar KPIs por sector para evaluar inversiones en maquinaria.

---

## 🔁 Líneas Futuras de Mejora

- Incluir tooltips personalizados para enriquecer visualizaciones.
- Documentar las medidas dentro del modelo.
- Usar el editor avanzado de Power Query para renombrar y comentar pasos en M.
- Implementar marcadores para cambiar entre visualizaciones dinámicas.
- Explorar variables DAX para análisis avanzados (top clientes, segmentación).
- Investigar nuevas herramientas como **Tableau**.
- Utilizar diagnósticos de rendimiento de Power BI para optimización.

---

## 💭 Reflexión Final

Este proyecto permitió comprender en profundidad el flujo completo del análisis de datos con Power BI: desde la conexión y limpieza en Power Query, hasta el modelado, cálculo de métricas y diseño visual.

Se destaca:
- La importancia del **modelado correcto** y el uso de un esquema en estrella.
- La utilidad de **medidas y columnas calculadas** para responder preguntas clave.
- El valor de los **mockups** para planificar reportes.
- El rol de la **IA como asistente**, aunque no sustituye el criterio humano.

Este trabajo consolidó habilidades fundamentales en herramientas clave del análisis de datos como **SQL Server**, **Power Query**, **DAX** y **Power BI**.

---

## 🧠 Autor

**Franco Bonavento**  
Data Analytics | SQL | Power BI | Power Query  
2025
