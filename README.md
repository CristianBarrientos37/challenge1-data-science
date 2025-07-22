# prompt: genera el README.md

# Análisis de Datos de Tiendas

Este repositorio contiene un análisis exploratorio de datos de ventas de cuatro tiendas diferentes. El análisis incluye métricas clave como ingresos totales, número de facturas, promedio de ingreso por factura, ventas por categoría, calificación promedio de la tienda, productos más y menos vendidos, y costo de envío promedio.

## Contenido

El análisis se realizó utilizando un Jupyter Notebook que carga y procesa datos de cuatro archivos CSV remotos.

## Estructura del Notebook

El notebook está organizado en las siguientes secciones:

1.  **Importación de datos:** Carga los datos de las cuatro tiendas desde sus respectivas URLs.
2.  **Análisis de facturación:** Calcula y presenta el ingreso total, número de facturas y promedio de ingreso por factura para cada tienda.
3.  **Ventas por categoría:** Analiza las ventas totales por categoría para todas las tiendas juntas y también por cada tienda individualmente.
4.  **Calificación promedio de la tienda:** Calcula la calificación promedio para cada tienda y la calificación promedio general de todas las tiendas.
5.  **Productos más y menos vendidos:** Identifica los productos más y menos vendidos tanto a nivel de tienda individual como a nivel general en todas las tiendas.
6.  **Envío promedio por tienda:** Calcula el costo de envío promedio para cada tienda (si la columna 'Costo de envío' está presente).

## Datos

Los datos utilizados en este análisis provienen de los siguientes archivos CSV remotos:

-   `tienda_1.csv`: [https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
-   `tienda_2.csv`: [https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
-   `tienda_3.csv`: [https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
-   `tienda_4.csv`: [https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

## Cómo ejecutar el Notebook

Puedes ejecutar este notebook en un entorno como Google Colab o Jupyter Notebook con las siguientes dependencias instaladas:

-   pandas

Simplemente abre el notebook y ejecuta las celdas secuencialmente.

## Resultados Clave

El notebook produce las siguientes métricas y análisis:

-   Desglose de facturación (ingreso total, número de facturas, promedio por factura) por tienda.
-   Ranking de categorías de productos por ventas totales.
-   Ranking de categorías de productos por ventas en cada tienda.
-   Calificación promedio para cada tienda y la calificación promedio general.
-   Identificación de los productos más y menos vendidos por tienda y en total.
-   Costo de envío promedio por tienda.

Estos resultados proporcionan una visión general del rendimiento de cada tienda y de las tendencias de ventas en general.
