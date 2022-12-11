# Percepción de inseguridad de las mujeres vs cantidad de delitos cometidos con violencia machista

El presente proyecto constituye parte de la evaluación de la materia Ingienería de Características de la [Maestría de Ciencia de Datos de la UNISON](https://mcd.unison.mx/).
En él se trabajaron y analizaron datos públicos del gobierno de México relacionados con la percepción de inseguridad de las mujeres y los delitos cometidos relacionados con la violencia machista.

## Objetivos
Se quiere encontrar si existe relación entre las tasas de inseguridad que perciben las mujeres en su ciudad y los delitos como feminicidios, violencia familiar y violencia de 
género por cada 100 mil mujeres durante el año 2022.

## Fuentes de datos
Los datos utilizados se obtuvieron de dos fuentes de información diferentes

**1.** [SESNSP 2022](https://datamexico.org/es/vizbuilder?cube=sesnsp_crimes&cuts%5B0%5D=Geography.State%2C26&cuts%5B1%5D=Type.Crime+Type%2C202%2C502&cuts%5B2%5D=Date.Year%2C2022&drilldowns%5B0%5D=Date.Year&drilldowns%5B1%5D=Geography.State&drilldowns%5B2%5D=Type.Crime+Type&drilldowns%5B3%5D=Geography.Municipality&locale=es&measures%5B0%5D=Value): En formato .json

**2.** [ENSU 2022](https://www.inegi.org.mx/programas/ensu): En formato .csv

## Limpieza, análisis y visualizaciónde los datos

En [esta liga](https://github.com/Lay94/mcd-unison-proyecto_integrador/blob/main/analizando_datos.ipynb) se podrá encontrar la libreta de jupyter dónde se realiza la
limpieza y análisis de los datos, incluyendo un [análisis exploratorio automático](https://github.com/Lay94/mcd-unison-proyecto_integrador/blob/main/eda-sweetview.html) realizado con la librería ´sweetviz´ y otro donde de describen las relaciones entre las variables

Finalmente se realizó [un tablero con Tableu](https://public.tableau.com/views/PercepcindeinseguridaddemujeresVsDelitosdeviolenciamachistas/Dashboard1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link
) donde se observa:

**1.** Percepción de inseguridad por estados

**2.** Cantidad de delito reportados por estados

**3.** Relación entre la percepción de inseguridad y la cantidad de delitos





---
⌨️ con ❤️ por Elaine Grenot Castellano 😊


