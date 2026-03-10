# lithium-exports-argentina-bi
Proyecto de BI que analiza las exportaciones de litio de Argentina utilizando Power BI, Power Query y modelado de datos.

## Resumen del Proyecto

Este proyecto de Business Intelligence analiza las exportaciones de litio de Argentina.
El objetivo es explorar las tendencias de exportación, identificar las provincias con mayor valor de exportación y evaluar la evolución de los mercados internacionales.

El proyecto se desarrolló con Power BI, incluyendo la transformación de datos (ETL), el modelado de datos con un esquema en estrella y la creación de indicadores analíticos con DAX.

## Objetivos del Proyecto

- Identificar las provincias que concentran las mayores exportaciones de litio.
- Analizar la evolución del valor de las exportaciones a lo largo del tiempo.
- Identificar los destinos internacionales con mayor crecimiento.
- Evaluar la relación entre el precio internacional y el valor de las exportaciones.

## Herramientas utilizadas

- Microsoft Power BI
- Power Query (ETL)
- DAX
- Excel / CSV dataset

## Modelo de datos

El modelo de datos sigue un diseño de esquema en estrella:

Tabla de hechos:
- Exportación

Tablas de dimensiones:
-Calendario
- Provincia
- Destino
- Empresa
- Producto_Litio

Transformación de datos (ETL)

La transformación de datos se realizó mediante Power Query:

- Eliminación de valores nulos
- Corrección de tipos de datos
- Creación de una tabla de calendario
- Normalización de datos para tablas de dimensiones

## Visualización de datos

(en proceso)
