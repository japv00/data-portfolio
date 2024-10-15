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

- **Screenshots**: 
![1](https://github.com/user-attachments/assets/235df05a-77c8-4dbd-80bf-7834f578d6e5)
![2](https://github.com/user-attachments/assets/45d1055e-f41d-415e-ac5d-18401fa6e860)
![3](https://github.com/user-attachments/assets/234ffa39-7288-4889-8d49-48b81450b7c5)
![4](https://github.com/user-attachments/assets/da989b3b-73ae-4a1d-b327-dde1ece144d1)
![5](https://github.com/user-attachments/assets/671c0bd3-1223-44dc-a7a3-ca2148e8cd2c)
