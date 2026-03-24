# ETL_PROYECTO_BI
## Descripción General
Este proyecto implementa un flujo completo de Business Intelligence (BI) enfocado en la automatización del proceso de extracción, transformación y carga de datos (ETL) usando SQL Server Integration Services (SSIS).  
El objetivo es centralizar la información de distintas fuentes en un Data Warehouse (DWH) y visualizarla mediante Power BI para mejorar la toma de decisiones.
## Arquitectura de la Solución
Fuentes de datos (archivos CSV, Excel, etc.)
│
[SSIS - ETL]
Extracción, Transformación y Carga
│
[SQL Server DWH]
Tablas Dimensión y Hechos
│
[SSAS Tabular Model]
│
[Power BI Dashboard]

# Tecnologías Utilizadas
- SQL Server 2022
- SSIS (SQL Server Integration Services)
- SSAS (SQL Server Analysis Services)
- Power BI Desktop
- Visual Studio 2022
- Lenguaje SQL

# Extracción y Transformación (SSIS)
- Se configuraron conexiones a fuentes externas en formato `.csv` y `.xlsx`.  
- Se realizaron transformaciones (limpieza, tipificación, conversión de tipos y control de nulos).  
- Se implementó manejo de errores y logs de ejecución.  

# Carga de Datos (DWH)
- Los datos transformados fueron cargados en tablas **Dimensión** y **Hechos**.  
- Se diseñó la estructura **DWH_ProyectoBI** con claves primarias y foráneas para análisis relacional.  

# Modelo Tabular (SSAS)
- Creación de modelo tabular para consultas de alto rendimiento.  
- Definición de jerarquías y medidas DAX.  

# Visualización (Power BI)
- Dashboard con métricas de ventas, desempeño y comparativos por categoría.  
- Uso de segmentadores, gráficos dinámicos y KPIs.
  
# Panel de control general
<img width="1436" height="804" alt="Dashboard general" src="https://github.com/user-attachments/assets/4b3511b2-c929-4903-b866-94cd9096a48c" />

# Panel de evoluciòn de ventas
<img width="1264" height="802" alt="Dashboard Evolucion ventas" src="https://github.com/user-attachments/assets/400ed246-9809-4702-972f-f9d777e5ef5d" />

# Panel de control metas
<img width="1413" height="792" alt="Dashboard metas" src="https://github.com/user-attachments/assets/e28f822c-4aa7-4d29-803b-bffa24618a29" />


# Panel de indicadores clave de rendimiento
<img width="1101" height="796" alt="KPIs ventas" src="https://github.com/user-attachments/assets/0698eb7f-e01d-4d51-b116-ff9990bf4670" />

