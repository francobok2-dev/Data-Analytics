# Portafolio de Data Analytics – Franco Bokhdjalian

Repositorio que contiene proyectos prácticos enfocados en análisis de datos, visualización y exploración con Excel, Power BI y Tableau.

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



## 🔹 Proyecto 2. Dashboard de Análisis Financiero y Transaccional (Excel)

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

📁 **Archivo:** `Dashboard_Transacciones.xlsx`



## 🔹 Proyecto 3. Dashboard Comercial y Análisis de Ventas con Promociones (Power BI)

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


## 🔹 Proyecto 4. Dashboard de Análisis de Seguros

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

📁 Archivo: `Dashboard_Seguros.pbix`
