# Portafolio de Data Analytics – Franco Bokhdjalian

Repositorio que contiene proyectos prácticos enfocados en análisis de datos, visualización y exploración con Excel, Power BI y Tableau.

## 🔹 Proyecto 1. Pipeline de Datos Bancarios: SQL + Power BI + IA Generativa

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



## 🔹 Proyecto 2. Análisis de Producción (Excel)

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



## 🔹 Proyecto 3. Dashboard de Análisis Financiero y Transaccional (Excel)

**Objetivo**:
Desarrollar un dashboard en Excel para analizar el rendimiento financiero de una empresa a través del estudio de ingresos, gastos, ganancias y comportamiento transaccional por diferentes dimensiones de negocio.

**Dataset**:
Base de datos transaccional con las siguientes variables:
- Transaction_ID
- Fecha de transacción
- Ingresos
- Gastos
- Ganancia
- Categoría
- Región
- Departamento
- Tipo de producto
- Grupo de clientes
- Método de pago
- Descuento

**Herramientas utilizadas:**
- Microsoft Excel  
- Tablas dinámicas  
- Gráficos dinámicos (columnas, barras, líneas, circular y área)  
- Cálculo de métricas financieras  

**Métricas analizadas:**

- 💳 Ganancia total por método de pago  

- 📦 Ingresos totales por tipo de producto  

- 📈 Ingresos, gastos y ganancia total por categoría  

- 🏢 Gastos totales por departamento

- 🌎 Cantidad de transacciones por región

**Principales insights obtenibles:**
- Identificación de métodos de pago más rentables.
- Detección de líneas de producto con mayor generación de ingresos.
- Comparación de desempeño financiero entre categorías.
- Análisis de concentración de gastos por departamento.
- Evaluación de distribución geográfica de la actividad comercial.

El dashboard permite analizar el desempeño financiero desde múltiples perspectivas (producto, región, departamento y método de pago), facilitando la toma de decisiones estratégicas basadas en datos.

📁 **Archivo:** `Dashboard Transacciones.xlsx`



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

**Objetivo:**  
Desarrollar un dashboard interactivo en Power BI para analizar el desempeño de pólizas de seguros, comportamiento de clientes y gestión de reclamos, permitiendo identificar patrones en primas, cobertura y estado de reclamos.

## 📂 Estructura del dataset

El dataset contiene información relacionada con pólizas de seguros, clientes y reclamos asociados.

Variables principales:

- Número de póliza
- ID Cliente
- Género
- Edad
- Tipo de póliza
- Fecha de comienzo de póliza
- Fecha de fin de póliza
- Monto de prima
- Monto de cobertura
- Número del reclamo
- Fecha del reclamo
- Monto del reclamo
- Estado del reclamo

## 🛠 Herramientas utilizadas

- Power BI
- SQL Server
- Power Query Editor

## 📊 Métricas y análisis desarrollados

### 💰 Análisis de primas
- **Monto de prima por tipo de póliza**  

### 📑 Estado de pólizas
- **Cantidad de pólizas activas e inactivas**  

### 👥 Perfil de clientes
- **Cantidad de clientes por género**  

### 📈 Análisis de reclamos
- **Monto de reclamación por grupo etario**  

### 🛡 Cobertura y estado de reclamos
- **Monto de cobertura por tipo de póliza y estado del reclamo**  

### 📌 Gestión de reclamos
- **Cantidad de reclamos por estado del reclamo**

## 📊 Principales insights obtenibles

- Identificación de tipos de póliza con mayor volumen de primas.
- Distribución demográfica de clientes asegurados.
- Análisis del comportamiento de reclamaciones según edad.
- Evaluación de la relación entre cobertura y estado de los reclamos.
- Detección de tendencias en el procesamiento de reclamaciones.

## 🚀 Valor agregado

El dashboard permite analizar simultáneamente la información de pólizas, clientes y reclamos, facilitando la evaluación del desempeño del negocio asegurador y la identificación de patrones de riesgo y comportamiento de los asegurados.

📁 Archivo: `Dashboard Empresa Seguros.pbix`



## 🔹 7. Análisis de Ventas y Rentabilidad (Tableau)

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
