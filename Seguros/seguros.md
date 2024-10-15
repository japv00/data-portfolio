# Operación de empresa de seguros - Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiMGJlNTQ0OTEtMDU1Mi00NjY1LTkyNDUtMzQ4NDhjOTViYjFlIiwidCI6ImRmZTIxMGExLWVjYTYtNDQ1Yi05YzcxLWE2ODNiZDE0NTQyOCJ9

## Problem Statement

Con base en la base de datos de la empresa, la solicitud fue poder visualizar información de las partes más importantes del flujo operativo como : 

- **Emisiones**
- **Cancelaciones**
- **Siniestros**
- **Envíos**



## Solución Implementada

Con una fuente de datos en una base de datos de MSSQL, se desarrólló una vista en t-sql que sirve como fuente para el dashboard. 

- **Resumen General**
Información de emisiones correctas, emisiones rechazadas, cancelaciones y siniestros.


- **Funcionalidades**: 
  - Menú de navegación para explorar los distintos paneles mediante el uso de botones y marcadores.
  - Funcionalidad de Drilltrough para explorar a detalle algunas de las métricas.
  - Tooltips personalizados en algunas visualizaciones.
  - Uso del algoritmo de predicción de PowerBI para proyectar ventas en meses futuros (Panel de emisiones).


