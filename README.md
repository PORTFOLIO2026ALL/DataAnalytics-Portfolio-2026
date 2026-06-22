# DataAnalytics-Portfolio-2026
En este portafolio que se inicia con fecha 19-06-2026 a las 8 am cuyo nombre es DataAnalytics-Portfolio-2026 pretendo compilar todos los proyectos concretados en relación solamente al análisis de datos.


# 📊 Portafolio de Análisis de Datos 2026

Bienvenido a mi espacio de proyectos de análisis de Datos. Este repositorio recopila soluciones analíticas de extremo a extremo, aplicando metodologías estandarizadas desde la ingesta e imputación de fuentes primarias hasta el despliegue de cuadros de mando estratégicos.

---

## ☕ Proyecto #1: Análisis de Datos - Coffee Sales

Este proyecto analiza el comportamiento transaccional del consumidor, simulaciones de empaquetamiento de productos (*bundling*) y fugas de valor para optimizar la rentabilidad de una cadena de café. El objetivo es mostrar el proceso completo aplicando la metodología KDD.

> **Estrategia comercial y de Business Intelligence para incrementar la rentabilidad por transacción a través de ingeniería de datos y simulaciones financieras.**

---

## 📊 Vista Rápida del Impacto (Resumen Ejecutivo)
Tras auditar y modelar un histórico de **10,000 transacciones reales**, estos son los resultados financieros del proyecto:
* **📈 Incremento Potencial de Ingresos:** `+10.1%` (+$8,987 USD netos adicionales).
* **💸 Optimización de Ticket Promedio:** Proyección de incremento de `$8.89 USD` a `$9.79 USD`.
* **🚨 Fuga de Monetización Detectada:** Un `99.99%` de compras se realizan de manera aislada (sin productos complementarios).
* **👥 Segmento Clave de Alto Valor:** Clientes en "Grupo" con un ticket medio de `$10.34 USD`.

---

## 🚨 El Problema (¿Qué dolor del mundo real resuelve?)
El negocio experimenta una **subexplotación del potencial de ingresos por cliente**, lo que se traduce en niveles moderados y estancados de ticket promedio. Al procesar el histórico de ventas, se identificó un patrón de consumo críticamente simple y lineal:

* **Dominio absoluto de un solo producto:** Las bebidas concentran el mayor volumen de ventas (**54.90%** de todas las transacciones).
* **Baja venta cruzada (*Cross-selling*):** Existe una mínima combinación o adopción de productos complementarios. La repostería representa apenas el **22.31%** y la comida el **22.79%** de la participación total.
* **Estructura de consumo aislada:** El **99.99%** de las transacciones se realizan bajo un esquema de "consumo simple" (el cliente compra un único producto, sin combos ni agregados adicionales en el punto de venta).

> 📌 **Diagnóstico de Negocio:** La empresa **no enfrenta un problema de baja demanda**, sino una falta de **optimización del valor monetario por cada transacción** efectuada.

---

## 💡 La Solución (¿Qué se construyó y por qué?)
Se diseñó y construyó un **Dashboard e Infraestructura Analítica de Negocios de extremo a extremo (End-to-End)** orientado a la monetización ágil y a la toma de decisiones comerciales de la gerencia. La solución técnica abarca tres componentes clave:

1.  **Ingeniería y Transformación de Datos (*Data Cleansing*):** Procesamiento, limpieza profunda e imputación del set de datos bruto (`dirty_cafe_sales`), estructurando tablas matrices íntegras para eliminar duplicados o registros corruptos y erradicar sesgos analíticos.
2.  **Modelado de Comportamiento Comercial:** Creación de tablas dinámicas avanzadas y segmentadores cruzados para clasificar el consumo por tipos de cliente (**Individual, Pareja, Grupo**) y auditar con precisión su comportamiento de gasto asociado.
3.  **Simulador de Escenarios Financieros:** Desarrollo de un bloque interactivo e inteligente de simulación bajo la estructura **Input-Calculus-Output**, diseñado para evaluar de forma automatizada y segura el impacto económico de implementar estrategias de empaquetamiento (*bundling*) antes de arriesgar capital en el mundo real.

---

## 📈 El Impacto y Resultados Comerciales (Métricas de Negocio)
A través del uso del cuadro de mando interactivo, la dirección puede proyectar e implementar decisiones estratégicas respaldadas por certezas matemáticas:

* **Incremento del 10.1% en Ingresos Totales:** La simulación demuestra que bajo un escenario conservador donde el **30%** de los clientes adopte una estrategia de *bundling* (adición de un producto complementario de **$3 USD**), el negocio captura **$8,987 USD** en ingresos adicionales netos sobre el escenario base.
* **Maximización del Ticket Promedio:** Permite calcular de manera inmediata la transición y el impacto del ticket promedio actual de **$8.89 USD** hacia un nuevo ticket optimizado de **$9.79 USD**.
* **Segmentación de Clientes con 1 Clic:** Facilita la toma de decisiones diferenciadas, revelando instantáneamente que el segmento **"Group"** genera el mayor ticket promedio (**$10.34 USD** frente a los **$2.97 USD** de compras individuales), guiando al negocio a priorizar paquetes familiares o de volumen.

---

## 🛠️ Tecnologías y Metodologías
* **Análisis y Procesamiento de Datos:** Estructuración matricial de datos, lógica de negocio avanzada y fórmulas analíticas complejas para la creación de bases de datos analíticas sólidas.
* **Inteligencia de Negocios (BI) & Modelado Financiero:** Tablas dinámicas cruzadas, segmentadores interactivos de comportamiento, KPI dashboards y bloques analíticos predictivos en **Google Sheets / Excel**.
* **Metodología:** Transformación técnica de datos crudos (*Data Cleansing*) enfocada 100% en la extracción e interpretación de *Insights* comerciales de alto impacto.

---

### 📸 Interfaz del Cuadro de Mando e Impacto Financiero

(https://docs.google.com/spreadsheets/d/1vMq1q4CoxJVqDkVejIEylh8QQ6xfzBIWlZP6dE9btuI/edit?gid=1137595256#gid=1137595256&fvid=961458355) 
En la hoja Pivot Table 12 en el bloque Oportunidad.

### 📑 Presentación del Proyecto
* 🎥 **[Diapositivas Resumen](https://docs.google.com/presentation/d/19_nWRm0_zapuBiCeAzJsQNZde0cLUvTenAIGy-R3OH0/present?slide=id.g3a87eabab9d_2_75)**: Presentación ejecutiva del modelo de negocio.
* 📊 **[Dashboard Interactivo](https://docs.google.com/spreadsheets/d/1GHb4md2lzgrpl4_0_IHoRx8YSRSE-3C17VNMTxsYT5k/edit?gid=1137595256#gid=1137595256&fvid=961458355)**: Reporte analítico automatizado (Dirigirse a la hoja *"Pivot Table 12"* y presionar *"Utilizar Plantilla"*).

### 🛠️ Metodología Aplicada
* 🧠 **[KDD](https://docs.google.com/presentation/d/19_nWRm0_zapuBiCeAzJsQNZde0cLUvTenAIGy-R3OH0/present?slide=id.g3a87eabab9d_4_16)**: Fases de selección, preprocesamiento y transformación del histórico de transacciones.
* 💾 **[Dataset Raíz](https://docs.google.com/spreadsheets/d/1iPTQq2u4AXH7E_DAIlQHkyMdYQfEBwzKbyc2mFyJry8/preview?gid=528103202&single=true#gid=528103202)**: Conjunto de datos íntegro utilizado como base analítica.
* 📈 **Métricas de Control (KPIs)**: Ticket promedio, Ingresos brutos, % Penetración de Bebidas, % Consumo simple, Beneficio cesante total y Beneficio cesante por cliente.
* 🖥️ **[Visualización Dinámica](https://docs.google.com/spreadsheets/d/1GHb4md2lzgrpl4_0_IHoRx8YSRSE-3C17VNMTxsYT5k/edit?gid=1137595256#gid=1137595256&fvid=961458355)**: Cuadros de mando dinámicos con segmentadores de datos en Google Sheets.

### 📂 Contenido de la Sección
* `README.md` → Portada descriptiva y navegación.
* `Presentacion.pptx` → Soporte visual corporativo.
* `Dataset.xlsx` → Matriz de datos de las transacciones evaluadas.

---

## ⚡ Proyecto #2: Análisis de Datos - Electric Vehicle Population

Análisis enfocado en la evolución tecnológica y demográfica del parque automotor de vehículos eléctricos. Aborda el tratamiento de grandes volúmenes de registros mediante técnicas de imputación y mapeo extensivo de autonomía.

### 📑 Presentación del Proyecto
* 🎥 **[Diapositivas Resumen](https://docs.google.com/presentation/d/1xLVPenyxkJSBubEAozLAKsx7nURbJ_hQ_j2tMJI-JtM/present?slide=id.p1)**: Enfoque estratégico del mercado y ciclos de maduración.
* 📊 **[Dashboard Interactivo](https://docs.google.com/spreadsheets/d/1J1W3T0qi6Vj5dF8m0PgaviXEoukTEoRt90hfmq5HcMs/edit?gid=1811363385#gid=1811363385)**: Panel ejecutivo centralizado para la toma de decisiones.

### 🛠️ Metodología Aplicada
* 🧠 **[KDD](https://docs.google.com/presentation/d/1xLVPenyxkJSBubEAozLAKsx7nURbJ_hQ_j2tMJI-JtM/present?slide=id.p4)**: Estrategia de ingeniería de datos e imputación basada en medianas estadísticas para registros faltantes.
* 💾 **[Dataset Tratado](https://docs.google.com/spreadsheets/d/1cVYNUtC4UAro4kVg-5yRTBH_CsiUVn8E8y13QoNZgh8/edit?gid=595707311#gid=595707311)**: Base de datos depurada con filtros y diccionarios de mapeo expandidos.
* 📈 **Métricas de Control (KPIs)**: Censo total de vehículos, Tasa global BEV (Battery Electric Vehicle) y Autonomía máxima promedio por fabricante.
* 🖥️ **[Visualización Dinámica](https://docs.google.com/spreadsheets/d/1xyBNrkLq3oWuBRUqqLhB4dPD_cmGW-WCF3l55pb4A5M/preview?gid=1811363385&single=true#gid=1811363385)**: Interfaz de usuario final interactiva sin elementos secundarios de edición.

### 📂 Contenido de la Sección
* `README.md` → Portada descriptiva y navegación.
* `Presentacion.pptx` → Diapositivas de soporte técnico.
* `Dataset.xlsx` → Registro depurado de la población de vehículos eléctricos.

---
*Diseño y desarrollo de portafolio orientado a la consultoría analítica.*
---
*Portafolio desarrollado por Leonardo Fabio Usta Villa.*
