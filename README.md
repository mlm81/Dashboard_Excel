# Proyecto Dashboard con Excel 📊

## Descripción
Este proyecto corresponde al ejercicio final del módulo de Dashboard & Análisis de Datos del Máster en Data Analytics.  
El objetivo del proyecto es la creación de un dashboard interactivo en Excel para la compañía IberFarma, analizando el cierre del año 2025 y el mercado de Rinitis Alérgica en el que compite.

---

## Objetivo del proyecto
Aplicar los conceptos aprendidos en el módulo de Dashboard & Análisis de Datos

---

## Estructura del proyecto
El repositorio contiene un archivo de Excel que incluye el dashboard, organizado en las siguientes pestañas:

- Datos → base de datos original y transformada
- Mapeos → tablas maestras y correspondencias
- Tablas Dinámicas → cálculos y métricas necesarias para el análisis
- Dashboard → visualización final e interactiva de los resultados

---

## Contenidos trabajados
Durante la realización de este proyecto se han trabajado los siguientes conceptos:

- Limpieza y transformación de datos en Excel
- Conversión de datos a tablas para un manejo eficiente
- Creación de variables calculadas
- Uso de tablas dinámicas
- Cálculo de métricas de negocio (crecimiento, cuotas de mercado)
- Análisis de ventas en euros y unidades
- Diseño de dashboards interactivos
- Análisis de mercado y competencia

---

## Limpieza y transformación de datos
Para llevar a cabo el análisis fue necesario realizar un proceso previo de depuración y transformación de los datos:

- Transformación de los datos originales en tablas
- Creación de nuevas variables (identificadas con el sufijo _Final) para corregir valores incompletos
- Asignación del Principio Activo_Final a partir de la pestaña maestro cuando el campo original estaba vacío
- Completado de valores faltantes en euros y unidades:
  - Cálculo de unidades dividiendo las ventas en euros entre el precio
  - Cálculo de ventas en euros multiplicando el precio por las unidades
- Creación de nuevas métricas en las tablas dinámicas:
  - Porcentaje de crecimiento (% Crec)
  - Cuota de mercado (% MS)

---

## Resultados y conclusiones
En la pestaña Dashboard se presenta un informe dinámico que permite analizar la información tanto en euros como en unidades.

- La primera parte del dashboard muestra la información específica de la compañía, disponible únicamente en euros
- La segunda parte analiza el mercado, incluyendo:
  - Competidores
  - Productos
  - Canales de venta
  - Moléculas
  - Presentaciones

Toda la información del mercado puede filtrarse por compañía, región y molécula, permitiendo un análisis más detallado.

Como principales conclusiones:
- IberFarma cierra el año 2025 con un crecimiento del 7,0%, por encima del mercado
- El mercado presenta una fuerte estacionalidad entre los meses de marzo y junio
- El canal farmacia es el predominante, aunque el canal online muestra un ligero crecimiento en 2025

---

## Requisitos
Para revisar y utilizar el proyecto es necesario disponer de:

- Microsoft Excel
- GitHub

---

## Autor
Lourdes Martínez Díaz


