# Covid-19 en CABA y PBA durante el año 2021

En este proyecto se estudia la evolución del COVID-19 en la Ciudad Autónoma de Buenos Aires (CABA) y la Provincia de Buenos Aires (PBA) durante parte del año 2021 con el fin de comparar la situación epidemiológica en ambas jurisdicciones. En particular, se trata de contrastar la dinámica temporal y la magnitud de la tasa de incidencia en ambas regiones para luego tratar de explicar las diferencias encontradas.

## Link

Para visitar la página del repositorio, haga clic en [este enlace]().

## Contexto

Este proyecto fue realizado en el marco del trabajo final para el módulo de **Introducción al Análisis Epidemiológico** del curso de posgrado [Introducción a la Ciencia de Datos en Salud](https://www.fmed.uba.ar/innovacion/hacemos) de la Facultad de Medicina de la Universidad de Buenos Aires.

## Objetivo

La intención de este proyecto es aplicar lo aprendido en el curso sobre introducción al análisis epidemiológico. Con este fin, debíamos describir la situación epidemiológica respecto del COVID-19 utilizando variables de tiempo, lugar y persona. 

## Resumen

1. En primer lugar, este trabajo compara la curva epidémica de COVID-19 de CABA y PBA para determinar si éstas poseen la misma dinámica. A continuación, contrasta los casos de COVID-19 confirmados entre ambas jurisdicciones y la magnitud de la tasa de incidencia.

2. Luego, compara la positividad en el testeo de COVID-19 y la tasa de notificación entre CABA y PBA. ¿Son similares entre ambas jurisdicciones? ¿Podrían explicar las diferencias observadas en cuanto a la tasa de incidencia?

3. A continuación, analiza la distribución de la población por rango etario en CABA y PBA y la relación entre ésta y la tasa de notificación.

4. Por último, utiliza tasas de incidencia estandarizadas para examinar el efecto de la distribución etaria de la población en este indicador y compara el indicador estandarizado entre jurisdicciones.

## Datos

Para este trabajo, se utilizó la [base de datos de casos registrados de COVID-19 en la República Argentina](https://www.datos.gob.ar/dataset/salud-covid-19-casos-registrados-republica-argentina) (Covid19Casos.csv) mantenida por la Dirección Nacional de Epidemiología y Análisis de Situación de Salud del Ministerio de Salud de la República Argentina descargada el día 28 de agosto de 2022.

Además, se utilizaron las [proyecciones provinciales de población por sexo y grupo de edad 2010-2040](https://www.indec.gob.ar/ftp/cuadros/publicaciones/proyecciones_prov_2010_2040.pdf) para el año 2021 calculadas por el INDEC a partir de datos del Censo Nacional de Población, Hogares y Viviendas 2010. En particular, los datos correspondientes a la población total de CABA y PBA.

Para estudiar la distribución territorial de uno de los indicadores analizados en este trabajo, usamos la [base geográfica que contiene los departamentos de las distintas jurisdicciones de la República Argentina](https://www.indec.gob.ar/indec/web/Institucional-Indec-Codgeo), elaborada en base a datos del INDEC, a partir del Censo Nacional de Población, Hogares y Viviendas 2010 y geografía y códigos geográficos del Sistema Estadístico Nacional.

Por último, para estudiar la distribución etaria de la población de CABA y PBA, utilizamos los datos correspondientes a las [proyecciones provinciales de población por sexo y grupo de edad 2010-2040](https://www.indec.gob.ar/ftp/cuadros/publicaciones/proyecciones_prov_2010_2040.pdf) para el año 2021 calculadas por el INDEC a partir de datos del Censo Nacional de Población, Hogares y Viviendas 2010. Esta vez, utilizamos los datos correspondientes a la población agrupada en rangos quinquenales de edad.
