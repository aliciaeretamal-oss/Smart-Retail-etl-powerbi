# Smart Retail — ETL y Visualización en Power BI

## Objetivo
Consolidar datos de ventas e inventario de una cadena de tiendas ("Sucursal A/B/C")
provenientes de dos fuentes distintas, transformarlos con Power Query y construir
un modelo de datos con una métrica calculada (DAX) para su visualización en Power BI.

## Contenido del repositorio
- `ventas.csv` — registros de ventas por sucursal, categoría y producto.
- `inventario.xlsx` — stock actual por producto y sucursal.
- `Smart_retail_ETL.pbix` — archivo de Power BI con el modelo y las visualizaciones.
- `Paso a paso ETL y visualizacion Smart Retail.pptx` — documentación del proceso paso a paso.
- `dashboard.png` — captura del dashboard final.

## Proceso (ETL)
1. Carga de `ventas.csv` en Power BI Desktop vía Inicio → Obtener datos → CSV,
   verificando que el delimitador fuera coma.
2. Carga de `inventario.xlsx` como segundo origen en Power Query.
3. Estandarización y renombrado de columnas en ambas tablas (incluyendo el
   renombrado de la hoja "Sheet1" a "Inventario").
4. Verificación y corrección del formato de cada columna (texto, número, moneda)
   para asegurar cálculos correctos aguas abajo.
5. Cierre y aplicación de las transformaciones en Power Query.
6. Creación de una columna calculada con DAX sobre la tabla de ventas.
7. Construcción de las visualizaciones finales en el lienzo de reporte.

## Tecnologías
Power BI Desktop (Power Query, modelo de datos, DAX), CSV, Excel.

## Cómo revisarlo
- Abrir `Smart_retail_ETL.pbix` con Power BI Desktop (gratuito), o
- Revisar directamente `dashboard.png` para ver el resultado sin instalar nada.

## Autora
Alicia Retamal Durán — [GitHub](https://github.com/aliciaeretamal-oss) ·
[LinkedIn](https://www.linkedin.com/in/alicia-retamal-mechanicalengineer)
