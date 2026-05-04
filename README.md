# Portafolio de Data Analytics – Franco Bokhdjalian

Repositorio que contiene proyectos prácticos enfocados en análisis de datos, visualización y exploración con Excel, Power BI y Tableau.

<!--## 🔹 Proyecto 1. Pipeline de Datos Bancarios: SQL + Power BI + IA Generativa

**Objetivo:**  
Desarrollar un flujo completo de procesamiento y análisis de datos bancarios utilizando SQL y Power BI. El proyecto incluye generación de datos simulados, corrección de inconsistencias, integración de múltiples tablas y análisis visual mediante dashboards interactivos.

## 📂 Proceso del proyecto

El proyecto se desarrolló en cuatro etapas principales:

1️⃣ **Generación de datos**  
Se utilizó **IA (Perplexity)** para generar código SQL que crea tres tablas iniciales:
- Clientes (ID Cliente, Nombre, Género, Fecha de nacimiento, Dirección, Email, Teléfono, ID cuenta)
- Cuentas (ID Cuenta, ID Cliente, Tipo, Fecha apertura, Balance)
- Transacciones (ID Transacción, ID Cuenta, Fecha, Tipo, Monto, Descripción, Divisa)

Estas tablas contienen **inconsistencias intencionales** para simular escenarios reales de calidad de datos.

2️⃣ **Limpieza y corrección de datos**  
Se generó código SQL adicional para identificar y corregir inconsistencias en los datos.

3️⃣ **Integración de tablas**  
Se creó una consulta SQL que realiza joins entre las tres tablas originales para generar una **tabla consolidada única**.

4️⃣ **Análisis y visualización**  
La tabla final fue utilizada en **Power BI** para construir un dashboard con múltiples métricas financieras y operativas.


## 🗄 Estructura de la tabla final

Se combinaron los campos de las tres tablas creadas en una tabla nueva única, que se usó como fuente de datos en Power BI.

La tabla consolidada contiene información de transacciones, cuentas y clientes.

Esta estructura permite analizar el comportamiento financiero combinando información de clientes, cuentas y transacciones.

## 🛠 Herramientas utilizadas

- **SQL Server**
- **Power BI**
- **DAX**
- **IA Perplexity**

## 📊 Métricas y análisis desarrollados

### 🏦 Análisis de cuentas
- **Cantidad de cuentas por tipo**
- **Cuentas inactivas por año y mes**
- **Saldo total por cliente**

### 💰 Análisis financiero
- **Sueldo total por tipo de cuenta**
- **Monto total de transacciones por mes**
- **Monto total por cliente**  
  (Top 2 clientes con mayor monto mediante filtros)

### 🔄 Actividad transaccional
- **Cantidad de transacciones por tipo**

### 👥 Perfil de clientes
- **Clientes por grupo etario**
- **Cantidad de clientes por género**

## 📊 Principales insights obtenibles

- Identificación de clientes con mayor volumen de transacciones.
- Análisis del comportamiento financiero según tipo de cuenta.
- Detección de cuentas inactivas en el tiempo.
- Segmentación demográfica de clientes por edad y género.
- Evaluación del volumen transaccional mensual.

## 🚀 Valor agregado

Este proyecto demuestra la capacidad de construir un pipeline completo de análisis de datos, incluyendo generación de datos, limpieza, integración mediante SQL y visualización con Power BI. Además, incorpora el uso de IA como herramienta de asistencia para desarrollo de consultas y modelado de datos, simulando un flujo de trabajo en análisis de datos.

📁 Archivos incluidos: `Proyecto Transacciones-Cuentas-Clientes.pbix`

<img width="785" height="503" alt="Captura de pantalla (520)" src="https://github.com/user-attachments/assets/1bcdefca-2995-4d01-8890-7476bac3506c" />

<img width="783" height="496" alt="Captura de pantalla (521)" src="https://github.com/user-attachments/assets/59bfdbd3-c7db-4815-99fe-0b37bf2fec44" />
-->

## 🔹 Proyecto 1. Análisis de Producción (Excel)

**Objetivo**:
Desarrollar un dashboard interactivo en Excel para analizar la eficiencia productiva, los costos asociados y la distribución operativa por categoría, manager y período temporal.

**Dataset**:
Base de datos productiva con las siguientes variables:
- ProductionID
- Fecha de producción
- Region
- Manager
- Tipo de producto
- Cantidad de unidades producidas
- Costo total
- Costo de producción por unidad
- Variables demográficas complementarias

**Herramientas utilizadas**:
- Microsoft Excel  
- Tablas dinámicas  
- Segmentación de datos  
- Gráficos 3D (circular, barras, líneas y columnas)  
- Cálculo de KPIs productivos

**Métricas analizadas**:

- 📊 Costo promedio de producción por unidad por categoría  

- 📈 Cantidad de tareas por manager  

- 📅 Cantidad de unidades producidas por mes y año  

- 💰 Costo total por categoría

**Principales insights obtenibles**:
- Identificación de categorías con mayor costo unitario.
- Detección de variaciones productivas mensuales.
- Comparación de carga operativa entre managers.
- Análisis de concentración de costos por tipo de producto.

📁 **Archivo**: `Dashboard Produccion.xlsx`

<img width="1039" height="563" alt="Captura de pantalla (522)" src="https://github.com/user-attachments/assets/f41b2894-ae3b-437e-a440-6f90b10be0d1" />

<img width="1014" height="572" alt="Captura de pantalla (523)" src="https://github.com/user-attachments/assets/e91f4de5-d2a6-4b05-ad49-65fddbaad641" />

## 🔹 Proyecto 2. Análisis de Ventas y Rentabilidad (Tableau)

**Objetivo:**  
Desarrollar un dashboard interactivo en Tableau para analizar el desempeño comercial de una empresa, identificando patrones de ventas, rentabilidad y comportamiento de clientes a través de diferentes regiones, segmentos y categorías de productos.

## 📂 Estructura del dataset

El dataset contiene información detallada sobre pedidos, clientes, productos y logística de envíos.

Variables incluidas:

- ID fila
- ID Orden
- Fecha Orden
- Prioridad de la orden
- Cantidad
- Monto
- Descuento
- Modo de envío
- Ganancia
- Precio unitario
- Costo de envío
- Nombre del cliente
- Ciudad
- Código postal
- Estado
- Región
- Segmento del cliente
- Categoría del producto
- Subcategoría del producto
- Nombre del producto
- Envase del producto
- Márgen de beneficio
- Fecha de envío

Esta estructura permite analizar el rendimiento comercial desde múltiples perspectivas: geográfica, demográfica y operativa.

## 🛠 Herramientas utilizadas

**Tableau**
- Visualización interactiva de datos
- Creación de dashboards analíticos
- Exploración de datos comerciales
**Excel** como fuente de datos.

## 📊 Métricas y análisis desarrollados

### 🌍 Desempeño regional
- **Ganancias por región y segmento de clientes**

### 📊 Participación de mercado
- **Porcentaje de contribución de ventas por región**

### 💰 Análisis de rentabilidad
- **Relación entre ventas y ganancias**  
  (Análisis de correlación entre volumen de ventas y margen de beneficio)

### 📦 Actividad comercial
- **Cantidad de productos vendidos por mes**  
  (Análisis temporal del volumen de ventas)

## 📊 Principales insights obtenibles

- Identificación de regiones con mayor rentabilidad.
- Comparación del desempeño entre segmentos de clientes.
- Análisis de la relación entre volumen de ventas y margen de ganancia.
- Detección de tendencias estacionales en el volumen de productos vendidos.

## 🚀 Valor agregado

El dashboard permite explorar el desempeño comercial desde diferentes perspectivas (regional, temporal y por segmento de cliente), facilitando la identificación de oportunidades de mejora en ventas y rentabilidad.

📁 Archivos incluidos: `Dashboard Ventas-Productos-Clientes - Tableau.twb`

<img width="1131" height="675" alt="Captura de pantalla (519)" src="https://github.com/user-attachments/assets/9f6c4b6b-4aa8-4e24-804d-83ab2a610a34" />

## Proyecto 3. 📊 Análisis de Rentabilidad de un Negocio con Excel

¿Cómo impactan los descuentos, los clientes y las decisiones operativas en la rentabilidad de un negocio?

A partir de un dataset de transacciones, desarrollé un dashboard en Excel enfocado en identificar los principales drivers de rentabilidad y detectar oportunidades de mejora.

## 🎯 Objetivo del proyecto

Analizar los factores que influyen en la rentabilidad del negocio y transformar datos transaccionales en información útil para la toma de decisiones.

## 📌 Análisis realizados

El proyecto incluye el análisis de variables clave como:

- Rentabilidad por línea de producto
- Impacto de los descuentos en el margen
- Performance por región
- Margen de ganancia por método de pago
- Segmentación de clientes y su rentabilidad
- Evolución temporal de la rentabilidad (mes/año)
- Porcentaje de transacciones que generan pérdidas

## 🔍 Principales insights obtenidos
- África se posiciona como la región más rentable, mientras que Asia-Oceanía presenta el menor margen y el mayor porcentaje de transacciones con pérdida, lo que sugiere una oportunidad clara de mejora.
- La línea de Salud combina alto volumen de ingresos con una rentabilidad elevada, mientras que Muebles, a pesar de generar menor volumen, mantiene un margen alto. En contraste, Ropa presenta el peor desempeño relativo.
- El segmento PyME concentra la mayor cantidad de transacciones, pero con menor rentabilidad promedio. Por el contrario, los consumidores finales, con menor volumen, muestran un margen significativamente superior.
- Se identifican caídas marcadas en la rentabilidad a lo largo del tiempo, siendo julio 2022 el punto más crítico. Un análisis adicional sugiere que esto podría estar vinculado a cambios en la composición de las transacciones, particularmente un mayor peso de regiones con menor rentabilidad como Asia-Oceanía.
- El análisis por método de pago muestra diferencias en el margen, lo que puede estar asociado a costos operativos o estrategias comerciales diferenciadas.

## 🛠️ Proceso de trabajo
- Limpieza y transformación de datos
- Creación de variables derivadas (margen por transacción, rangos de descuento)
- Construcción de tablas dinámicas
- Diseño de dashboards enfocados en la toma de decisiones

## 🚀 Valor del proyecto

Este análisis permite:

Comprender qué factores impactan la rentabilidad
Detectar segmentos, productos y regiones críticas
Identificar oportunidades de mejora en la operación
Transformar datos en insights accionables

📁 Archivos incluidos: `Dashboard Transacciones 2026.xlsx`

<img width="1385" height="573" alt="Captura de pantalla (546)" src="https://github.com/user-attachments/assets/d3a2dde3-af41-46df-bfdf-9db6e4a19cf0" />

<img width="1382" height="577" alt="Captura de pantalla (547)" src="https://github.com/user-attachments/assets/2f47e72b-decb-49d3-9373-5636480b322b" />



## 🔹 Proyecto 4. Dashboard Comercial y Análisis de Ventas con Promociones (Power BI)

**Objetivo:**  
Desarrollar un dashboard para analizar el rendimiento de ventas, rentabilidad de productos y efectividad de campañas promocionales, utilizando datos de clientes, productos y promociones.

**Estructura del dataset:**

El proyecto integra tres tablas principales:

**1️⃣ Clientes**
- ID Cliente
- Nombre
- Ciudad
- Estado
- Pincode
- Email
- Teléfono

**2️⃣ Productos**
- ID Producto
- Nombre Producto
- Categoria Producto
- Precio

**3️⃣ Promociones**
- ID Promocion
- Nombre Promocion
- Tipo de anuncio
- Código de cupón
- Porcentaje descuento

*Nota:* Los datos se encuentran en estado preliminar (sin limpieza)

### 🛠 Herramientas utilizadas

- Power BI Desktop
- Power Query Editor (limpieza y transformación de datos)
- Segmentación de datos
- Gráficos avanzados (barras apiladas, línea, dispersión, mapa geográfico)  
- Integración de múltiples tablas

### 📊 Métricas y análisis desarrollados

#### 📦 Performance de productos
- Top 5 y Bottom 5 productos por:
  - Ingresos
  - Unidades vendidas
  - Ganancia 

#### 📈 Tendencia de ventas
- Evolución de ventas por período  

#### 💰 Análisis de rentabilidad
- Ganancia vs monto neto de ventas  

#### 🎯 Análisis de promociones
- Descuento promedio por categoría de promoción  

#### 🌍 Distribución geográfica
- Ventas por ciudad  

#### 📌 KPIs generales
- Número total de órdenes
- Total de ventas
- Total de ganancia
- Cantidad total de unidades

#### 📋 Vista detallada
- Tabla dinámica con todos los campos y filtros interactivos

### 📊 Principales insights obtenibles

- Identificación de productos más y menos rentables.
- Evaluación del impacto de promociones en el volumen de ventas.
- Detección de concentración geográfica de ingresos.
- Relación entre volumen de ventas y margen de ganancia.
- Análisis comparativo de desempeño por período.

El dashboard integra datos de clientes, productos y promociones en una sola vista, permitiendo evaluar simultáneamente performance comercial, impacto promocional y comportamiento geográfico de ventas.

📁 Archivo: `Dashboard Ventas-Ganancia.pbix`


## 🔹 Proyecto 5. Dashboard de Análisis de Seguros

### 🎯 Objetivo
Desarrollar un dashboard interactivo en Power BI orientado al análisis del negocio asegurador, con foco en la evaluación de rentabilidad, comportamiento de clientes y gestión de reclamos.

El objetivo principal es transformar datos operativos en información útil para la toma de decisiones, mediante el análisis de métricas clave como primas, cobertura, siniestralidad y comportamiento de siniestros.

---

## 📂 Estructura del dataset

El dataset integra información de pólizas, clientes y reclamos, permitiendo un análisis integral del ciclo de vida del seguro.

### 📑 Pólizas
- Número de póliza  
- Tipo de póliza  
- Fecha de inicio  
- Fecha de fin  
- Monto de prima  
- Monto de cobertura  

### 👥 Clientes
- ID Cliente  
- Género  
- Edad  

### 📊 Reclamos
- Número de reclamo  
- Fecha del reclamo  
- Monto del reclamo  
- Estado del reclamo (aprobado, rechazado, pendiente)  

---

## 🛠 Herramientas utilizadas

- **Power BI** → Visualización y desarrollo del dashboard  
- **SQL Server** → Extracción y modelado de datos  
- **Power Query** → Limpieza y transformación de datos  
- **DAX** → Creación de métricas y KPIs  

---

## 📊 Métricas y análisis desarrollados

Se construyeron indicadores clave orientados a evaluar el desempeño del negocio desde distintas perspectivas:

### 💰 Primas y cobertura
- Monto total de primas  
- Monto total de cobertura  

### 📈 Reclamos
- Cantidad total de reclamos  
- Monto total reclamado  
- Reclamos por estado (aprobado / rechazado / pendiente)  

### 🛡 Rentabilidad y riesgo
- Índice de siniestralidad  
  *(Relación entre el monto reclamado y el monto de primas)*  
- Costo promedio por reclamo  

### 👥 Segmentación de clientes
- Distribución por género  
- Distribución por rango etario  
- Análisis por tipo de póliza  

### ⏱ Análisis temporal
- Monto reclamado por año  
- Distribución del tiempo hasta el reclamo *(días desde inicio de póliza)*  

---

## 📊 Principales insights obtenidos

- El índice de siniestralidad (2,83) evidencia un escenario de baja rentabilidad, con costos de siniestros significativamente superiores a las primas.  
- Las pólizas de tipo Viajes presentan el mayor nivel de pérdida, posicionándose como el segmento de mayor riesgo dentro del portfolio.  
- En 2024 se registra el mayor volumen de montos reclamados, lo que sugiere un incremento en la siniestralidad durante ese período.  
- Se observa una proporción elevada de reclamos rechazados, lo que podría indicar oportunidades de mejora en los procesos de validación o en la suscripción de pólizas.  
- La siniestralidad se mantiene alta y relativamente homogénea entre los distintos tipos de póliza, lo que sugiere un problema estructural del negocio.  
- La distribución del tiempo hasta el reclamo es uniforme, sin concentraciones marcadas, lo que indica un comportamiento de riesgo estable a lo largo del ciclo de vida de la póliza.  

---

## 🚀 Valor del proyecto

Este dashboard permite:

- Evaluar la rentabilidad del negocio asegurador  
- Identificar segmentos de mayor riesgo  
- Analizar el comportamiento de los reclamos  
- Detectar oportunidades de mejora en procesos operativos  
- Transformar datos en insights accionables para la toma de decisiones 

---

📁 **Archivo:** `Dashboard Empresa Seguros.pbix`

---

## 🖼 Vista del dashboard

<img width="1007" height="577" alt="Captura de pantalla (536)" src="https://github.com/user-attachments/assets/7260e69d-be1d-401f-9b70-b739a196cd72" />

## Proyecto 6: Análisis de Eficiencia Comercial

### 🎯 Objetivo

Analizar el impacto de los descuentos, el volumen de ventas y las características de productos y clientes sobre la eficiencia comercial de un negocio.

El proyecto busca identificar qué factores impulsan o deterioran el rendimiento comercial, detectando oportunidades de optimización en la estrategia de precios, promociones y segmentación.

### 📂 Estructura del dataset

El modelo de datos está basado en un esquema estrella, con una tabla de hechos central y tres dimensiones:

- Ventas: Fecha, ID Cliente, ID Producto, ID Promoción, Importe Total, Importe Neto, Porcentaje de Descuento, Unidades, Precio Unitario, Valor de Descuento
- Clientes: ID, Nombre, Ciudad, Provincia, Email
- Productos: ID, Nombre, Precio, Categoría
- Promociones: ID, Nombre, % Descuento, Código de Cupón, Tipo de Anuncio

Se realizaron procesos de limpieza, transformación y enriquecimiento de datos para garantizar consistencia y permitir análisis más profundos.

### 🛠 Herramientas utilizadas
Power BI (modelado de datos y visualización)
DAX (creación de métricas y KPIs)
Power Query (limpieza y transformación de datos)

### 📊 Métricas y análisis desarrollados
Ventas Netas y Ventas Brutas
Eficiencia comercial por categoría
Ventas netas para cada promoción
Descuento promedio para cada categoría
Análisis de ventas netas y eficiencia en ciudades, clientes y productos
Relación entre unidades vendidas y facturación
Relación entre eficiencia y facturación por producto


### Análisis principales:

Evolución temporal de ventas y eficiencia
Relación entre ventas, volumen y eficiencia (análisis multivariable)
Impacto de los descuentos en el rendimiento comercial
Performance por categoría de producto
Análisis por promociones
Segmentación geográfica
Análisis de clientes (top por ventas y eficiencia)
Identificación de productos con baja eficiencia

📊 Principales insights obtenidos
- La ciudad de Resistencia presenta la menor eficiencia comercial, asociada a un alto nivel de descuentos sin un incremento significativo en el volumen de ventas, lo que evidencia una estrategia promocional poco efectiva.

- En contraste, ciudades como Paraná muestran altos niveles de eficiencia pero bajo volumen de ventas, lo que sugiere potencial de crecimiento mediante estrategias comerciales controladas.

- Los clientes con mayor volumen de compra no necesariamente son los más eficientes, lo que indica que el ingreso generado no siempre está alineado con la rentabilidad operativa.

- A nivel producto, la olla a presión se posiciona como uno de los menos eficientes, con bajo volumen de ventas y alto impacto de descuentos, lo que sugiere la necesidad de revisar su estrategia comercial.

- Se observa una relación clara entre volumen, ventas y eficiencia: no siempre vender más implica ser más eficiente, lo que refuerza la importancia de analizar múltiples variables en conjunto.

🚀 Valor del proyecto

Este dashboard permite:

- Identificar productos y categorías que generan valor real vs aquellos dependientes de descuentos
- Optimizar estrategias de precios y promociones
- Detectar oportunidades de mejora en mercados específicos
- Analizar el comportamiento de clientes en términos de eficiencia
- Tomar decisiones basadas en datos para mejorar el rendimiento comercial

📁 **Archivo:** `Analisis Eficiencia Comercial.pbix`

### 🖼 Vista del dashboard

<img width="1112" height="619" alt="Captura de pantalla (563)" src="https://github.com/user-attachments/assets/ae70ae7f-ea59-48e4-8945-de30561ae189" />
<img width="1112" height="622" alt="Captura de pantalla (564)" src="https://github.com/user-attachments/assets/76bfbdd5-4f3a-40c9-8f49-22edffc8e3f3" />
<img width="1111" height="612" alt="Captura de pantalla (572)" src="https://github.com/user-attachments/assets/be92b45d-8ff3-4356-a153-726257ec941f" />
<img width="1111" height="612" alt="Captura de pantalla (571)" src="https://github.com/user-attachments/assets/1db5a81a-4619-4e03-b863-7223092ff486" />
