# 📊 Adventure Works Sales Dashboard | Power BI

Dashboard interactivo desarrollado en **Microsoft Power BI** utilizando el conjunto de datos **Adventure Works**. El proyecto presenta un análisis ejecutivo de ventas mediante un modelo dimensional en estrella, medidas DAX avanzadas y visualizaciones interactivas.

---

# 📷 Dashboard

## Página 1 – Análisis de ventas

<img width="1202" height="681" alt="dashboard_01" src="https://github.com/user-attachments/assets/033d27cf-76de-41e8-b473-feb27d8459ac" />


## Página 2 – Análisis avanzado DAX

<img width="1202" height="666" alt="image" src="https://github.com/user-attachments/assets/a7d3b074-96b9-4279-94cf-3b2c16a0e1b5" />


---

# 🎯 Objetivos

- Construir un modelo dimensional en estrella.
- Analizar la evolución de las ventas.
- Evaluar la rentabilidad por categoría.
- Analizar el rendimiento comercial.
- Implementar medidas DAX avanzadas.
- Crear un dashboard ejecutivo e interactivo.

---

# 🏗 Modelo de datos

El proyecto utiliza un **modelo en estrella** compuesto por:

### Tabla de hechos

- FactSales

### Tablas de dimensiones

- DimCalendar
- DimProduct
- DimSalesperson
- DimRegion
- DimReseller

Se han establecido relaciones uno-a-muchos siguiendo las buenas prácticas de modelado en Power BI.

---

# 📈 Dashboard ejecutivo

La primera página incluye:

- Segmentadores por Año, Región, Categoría y Vendedor.
- KPIs principales:
  - Total Ventas
  - Beneficio
  - Margen de beneficio
  - Cumplimiento del objetivo
  - Pedidos
  - Objetivo total
- Evolución mensual de ventas.
- Ventas por categoría.
- Distribución por tipo de distribuidor.
- Rentabilidad por categoría.
- Top productos por ventas.

---

# 📊 Análisis avanzado DAX

La segunda página muestra la aplicación práctica de distintas funciones DAX para el análisis de contexto de filtros.

Funciones implementadas:

- ALL()
- ALLSELECTED()
- ALLEXCEPT()
- KEEPFILTERS()
- FILTER()

---

# 📚 Medidas DAX destacadas

### Total Sales

Calcula las ventas totales.

### Profit

Obtiene el beneficio restando el coste total a las ventas.

### Profit Margin %

Calcula el margen de beneficio porcentual.

### % Sales All Products

Calcula el porcentaje de ventas respecto al total de productos utilizando ALL().

### % Sales Selected Products

Calcula el porcentaje respecto a los productos seleccionados mediante ALLSELECTED().

### Sales by Category

Ejemplo de utilización de ALLEXCEPT().

### Bike Sales KeepFilters

Ejemplo práctico de KEEPFILTERS().

### High Value Sales

Filtrado mediante FILTER() para ventas superiores a un umbral determinado.

---

# 🛠 Tecnologías utilizadas

- Microsoft Power BI Desktop
- DAX
- Modelo dimensional
- Power Query

---

# 📌 Características

- Modelo en estrella
- Dashboard interactivo
- Segmentadores dinámicos
- KPIs
- Medidas DAX avanzadas
- Diseño responsive
- Navegación intuitiva

---

# 📁 Estructura del proyecto

```
AdventureWorks-PowerBI/
│
├── AdventureWorks.pbix
├── README.md
├── images/
│   ├── dashboard_01.png
│   └── dashboard_02.png
└── docs/
```

---

# 🚀 Posibles mejoras

- Incorporación de parámetros What-if.
- Tooltips personalizados.
- Navegación mediante botones.
- Tema corporativo personalizado.
- Publicación en Power BI Service.

---

# 👤 Autor

**Jon Gorritxo**

Data Analyst | Business Intelligence | Power BI | SQL | Python

GitHub:
https://github.com/jagoher
