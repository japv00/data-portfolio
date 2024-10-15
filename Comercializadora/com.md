# Ventas Multiempresa - Dashboard

## Problem Statement

Para el proyecto, fue proporcionado acceso a la base del ERP Odoo v12 de un grupo de empresas comercializadoras (1 grupo, 6 empresas). Con una base de datos centralizada y la información de presupuestos de ventas y compras, así como la facturación a clientes y proveedores,
se tiene la necesidad de saber qué tanto de lo que se presupuesta en las ventas se cierra (llega a facturación y cobro).


## Solución Implementada

Se desarrolló una solución que muestra, para todas las empresas del grupo, la diferencia entre lo que se cotizó inicialmente y lo que se terminó  vendiendo realmente (lo efectivamente facturado).
Dichos calculos no se encuentran en el ERP, y tuvieron que realizarse mediante medidas calculadas dentro de PowerBI con DAX.


- **Resumen General**  
Se muestra la información en una sola tabla maestra categorizada por Empresa del grupo, Cliente, Vendedor, Proyecto y documento (cotizacion de venta o compra, factura de venta, factura de compra).

- **Screenshots**:  
  

Ejemplos de consultas DAX utilizadas

![5](https://github.com/user-attachments/assets/474a1ba3-adfe-48e2-9e93-8609ea3047e1)
![4](https://github.com/user-attachments/assets/e0fd23d4-bc64-4299-b6c4-e03f7d1f9542)
![3](https://github.com/user-attachments/assets/42abdc1f-a046-4255-a718-86cc8fdc73ea)  

Dashboard

![1](https://github.com/user-attachments/assets/a16d073f-c946-449f-b6c5-7c8d525836db)  

![2](https://github.com/user-attachments/assets/5926c361-47c8-4e12-a65e-509069b76732)


## Dashboard Link
#### https://app.powerbi.com/view?r=eyJrIjoiMWYwNmZhMTUtY2E4Yy00MmMyLWIzZWItNzc3MzFhM2IwOTMxIiwidCI6ImRmZTIxMGExLWVjYTYtNDQ1Yi05YzcxLWE2ODNiZDE0NTQyOCJ9
