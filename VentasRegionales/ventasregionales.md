# Ventas Regionales

## Descripción del proyecto

Se proporcionó una base de datos en formato CSV que contenía información sobre empresas y los ingresos de ventas. Algunos ejemplos de la información: 

- **Nombre de la empresa**
- **Industria**
- **Estado y municipio**
- **Dirección completa**
- **Número de empleados (en rango)**
- **Ingresos de venta**

La tarea consistió en crear un dashboard que permitiera visualizar y analizar esta información de manera efectiva. 

## Solución Implementada

Se desarrolló un flujo en un paquete de SSIS para limpieza de los datos y carga de la información a una base de datos local de SQL Server. Después se desarrolló un dashboard interactivo que incluye:

- **Resumen General**: Visualiza el número total de industrias y empresas, así como los ingresos totales y promedio por empresa y operación.
  
- **Gráficas**: Incluye gráficos que muestran los ingresos en función del tipo de empresa (micro, pequeña, mediana o grande).
  
- **Análisis Demográfico**: Presenta un top 5 de los estados con mayores ingresos.

- **Mapa Coroplético**: Un mapa que utiliza un esquema de colores para resaltar los estados de México con mayores ingresos, además de un botón que permite cambiar a un mapa de calor.

- **Funcionalidades de Descarga**: 
  - Un botón para descargar los primeros mil registros de la base.
  - Un botón que permite descargar todos los registros utilizando una lógica avanzada en Power BI.
  - Un botón que ofrece la opción de descargar un archivo mediante una conexión a Excel para poblar la tabla.

## Screenshots
#### **ETL con SSIS**
![1](https://github.com/user-attachments/assets/abb9dfce-7442-4b74-9530-7af00c912a64)
![2](https://github.com/user-attachments/assets/22d70e31-86fe-452f-8728-3bcc9a154e41)

#### **Funcionalidad de descarga con PowerFlows**
#### Se creó una tabla con DAX en el modelo de PowerBI, la cual es iterable en un flujo dentro de la aplicación de PowerFlows. El flujo de PowerFlows se ejecuta con un botón dentro del Dashboard. El resultado final es un archivo de Excel con la información de la tabla en cuestión. Esta aproximación se hizo para intentar solventar el problema del limite de registros que el servicio de PowerBi permite exportar a archivos de Excel.

https://github.com/user-attachments/assets/647f1429-da07-4119-955f-7d9c4521abdb

#### **Dashboard**
![3](https://github.com/user-attachments/assets/a660b65c-271c-4bb1-8c68-bd8ef92d3a78)


## Dashboard Power BI
#### https://app.powerbi.com/view?r=eyJrIjoiZDFiNTYwYTEtZTBjOS00OGY4LThhNDktYTZlODdjYmQ2ZjdlIiwidCI6ImRmZTIxMGExLWVjYTYtNDQ1Yi05YzcxLWE2ODNiZDE0NTQyOCJ9

**NOTA: LA FUNCIONALIDAD DE DESCARGAR LOS ARCHIVOS NO ESTÁ DISPONIBLE AL COMPARTIR EN LA WEB (NO SOPORTADA POR MICROSOFT)**



