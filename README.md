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
<img width="804" height="604" alt="Dashboard general" src="https://github.com/user-attachments/assets/82369802-abae-4b90-9175-b760ca638be1" />

# Panel de evoluciòn de ventas
<img width="804" height="602" alt="Dashboard Evolucion ventas" src="https://github.com/user-attachments/assets/8bb0b7db-6e65-4176-a8d8-ea550b4b765b" />

# Panel de control de metas
<img width="804" height="602" alt="Dashboard metas" src="https://github.com/user-attachments/assets/191df1b0-bcf7-43d0-96da-6035b16c872a" />

# Indicadores de rendimiento
<img width="804" height="796" alt="KPIs ventas" src="https://github.com/user-attachments/assets/46b5093a-1a43-4d0a-a3c5-9ef471b22e5a" />

