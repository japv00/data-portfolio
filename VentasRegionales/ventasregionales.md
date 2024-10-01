# Ventas Regionales - Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiZDFiNTYwYTEtZTBjOS00OGY4LThhNDktYTZlODdjYmQ2ZjdlIiwidCI6ImRmZTIxMGExLWVjYTYtNDQ1Yi05YzcxLWE2ODNiZDE0NTQyOCJ9

## Problem Statement

Se proporcionó una base de datos en formato CSV que contenía información sobre empresas y los ingresos de ventas. Algunos ejemplos de la información: 

- **Nombre de la empresa**
- **Industria**
- **Estado y municipio**
- **Dirección completa**
- **Número de empleados (en rango)**
- **Ingresos de venta**

La tarea consistió en crear un dashboard que permitiera visualizar y analizar esta información de manera efectiva. 

## Solución Implementada

Se desarrolló un dashboard interactivo que incluye:

- **Resumen General**: Visualiza el número total de industrias y empresas, así como los ingresos totales y promedio por empresa y operación.
  
- **Gráficas**: Incluye gráficos que muestran los ingresos en función del tipo de empresa (micro, pequeña, mediana o grande).
  
- **Análisis Demográfico**: Presenta un top 5 de los estados con mayores ingresos.

- **Mapa Coroplético**: Un mapa que utiliza un esquema de colores para resaltar los estados de México con mayores ingresos, además de un botón que permite cambiar a un mapa de calor.

- **Funcionalidades de Descarga**: 
  - Un botón para descargar los primeros mil registros de la base.
  - Un botón que permite descargar todos los registros utilizando una lógica avanzada en Power BI.
  - Un botón que ofrece la opción de descargar un archivo mediante una conexión a Excel para poblar la tabla.
