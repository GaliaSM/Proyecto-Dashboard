# PROYECTO-DASHBOARD-ANALISIS-DE-DATOS
En este repositorio podrá encontrar un análisis del datset Superstore, donde encontrar un archivo de Excel con las distintas hojas de trabajo y su Dashboard final.

## Descripción del proyecto

La idea de este proyecto es aplicar los conocimientos que se han adquirido en el módulo “ Dashboard & Análisis de Datos”.
Tenemos que seleccionar un base de datos, con un numero mínimo de 10 columnas y al menos 2000 filas,y seleccionar una de estas dos herramientas  Excel o Google Sheets.

## Objetivo

EL objetivo es realizar un análisis de un conjunto de datos de elección propia y reflejarlos en un dashboard. Por tanto, vamos a aplicar las técnicas de limpieza y transformación de los datos, hacer un análisis descriptivo de los datos reflejar esa información en el dashboard y finalmente hacer el informe explicativo.

## Dataset utilizado

Fuente: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/data.
Descripción: Datos de ventas de una tienda minorista en EE.UU.
Tamaño: 9.995 filas y 21 columna .
Variables Principales:
           Order ID, Order Date, Ship Date, Ship Mode.
           Customer ID, Customer Name, Segment, Region, City, State, Country.
           Product ID, Category, Sub-Category, Product Name.
           Sales, Quantity, Discount, Profit.

## Proceso realizado

Este proyecto se desarrolló siguiendo los pasos siguientes importación del archivo CSV en excel, se procedió a realizar la revisión de las columnas y tipos de datos, corrección del formato numérico de Sales, Profit, Discount esto se tuvo q realizarse en el proceso de la importación, transformación de fechas, revisión de duplicados, comprobación de valores nulos, creación de columnas auxiliares como Month, Trimestre, Year, Take to, creación de las tablas dinámicas, análisis descriptivo, informe explicativo y diseño del dashboard final.

## Análisis realizado

En este proyecto se analizaron diferentes aspectos del negocio:
       Ventas por año, trimestre, categoría,subcategoría, region y tipo de cliente
       Beneficio por categoría, subcategoría,producto,region y tipo de envío
       Cantidad vendida por categoría,subcategoría,producto, regio y cliente
       Tiempos de envíos

## Principales conclusiones

Superstore muestra una empresa con una evolución positiva de las ventas durante el periodo 2014 al 2017. Las ventas presentan una tendencia de creciente especialmente en los dos ultimos años, hay una clara estacionalidad  en las ventas en el cuarto trimestre de cada año.La categoría Technology destaca en cuanto a ventas y rentabilidad ,Officde Supplies sobresale en cuanto volumen lo que es razonable ppr le tipo de producto. Sin embargo Furniture se encuentra en la segunda posición de ventas pero en cambio su rentabilidad es baja e incluso la mayor parte de las perdidas viene de esta categoría.Consumer es el cliente principal y las regiones West y East concentran mejores resultados.Finalmente el tipo de envio mas utlizado es el Standard pero el mas rentable es First Class.

## Archivos del proyecto

Superstore.xlsx: archivo principal del proyecto.Incluye Datos originales sin limpiar, datos limpios, análisis de ventas, análisis de los beneficios y pérdidas , análisis cantidad, análisis tipo de envío, tablas dashboard, dashboard y notas.
Informe_Analisis_superstore: Informe explicativo  del análisis realizado  así como el problema  encontrado en la importación del archivo csv.
Sample-Superstore.csv : Archivo descargado de la página Kaggle.


## Autor
Proyecto realizado por Galia Sidahmed Merino
