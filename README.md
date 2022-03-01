<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>

# __ih_datamadpt1121_project_m2__ ALVARO

## Librerías:
```
import pandas as pd 
```
```
import numpy as np 
```
```
from sqlalchemy import create_engine
```
```
import seaborn as sns
```


## Datasets: Obtenemos dos datasets finales:

1. Usando sqlite como bbdd local establecemos una conexión con ella gracias a SQLAlchemy. 
2. Realizamos una única query para obtener el dataframe final
3. Añadimos dos columnas para obtener medidas europeas “mg y gr” (que al final no se han utilizado en el dashboard) y obtener el oriimer data frame final con el que empezar a crear os dashboards
4. Creamos el coeficiente de correlación para obtener el segundo data frame con el que estudiar las relaciones entre los atributos numéricos.
5. Exportamos los dos dataframes en csv a una carpeta llamada “output_dataset”


## Visualización: 

El proyecto consiste en 3 pestañas (dos “dashboards” y una “story”)

### 1 - PRICE SEARCHER TOOL: DASHBOARD
Objetivo: tienes un diamante y no sabes que precio ponerle. Usando los filtros seleccionas las características de tus diamantes y te devuelve el precio de mercado de un diamante similar. 
Si hay múltiples diamantes te puedes fijar en las medias.
Si quieres un rango te puedes fijar en las medias también.
![Image](https://raw.githubusercontent.com/alvaro-saez/ih_datamadpt1121_project_m2/main/images/price_searcher_tool.png)

### 2 - CUT, COLOR, CLARITY: STORY (dos pestañas)
PESTAÑA 1 - HEATMAP: Objetivo: ver de un solo vistazo la distribución de los diamantes en torno a las 3 principales categorías cualitativas (cut, color, clarity) y en base a los principales KPIs (ventas - ingresos, precio medio y kilates medios)

![Image](https://github.com/alvaro-saez/ih_datamadpt1121_project_m2/blob/main/images/heatmap.png)

PESTAÑA 2 - TABLA: Objetivo: poder descargarse los datos analizados y visualizados en el heatmap

![Image](https://github.com/alvaro-saez/ih_datamadpt1121_project_m2/blob/main/images/table.png)


### 3 - PRICE INFORMATION (main KPIs): DASHBOARD
Objetivo: estudiar las ventas, ingresos y precios (precio como KPI principal) de un solo vistazo del conjunto de diamantes en base a cut, color, clarity y carat
![Image](https://github.com/alvaro-saez/ih_datamadpt1121_project_m2/blob/main/images/KPIs.png)



## **References:**

- [SQLite](https://www.sqlite.org/index.html)

- [SQLAlchemy](https://docs.sqlalchemy.org/en/14/core/engines.html)

- [Visual Analysis Best Practices](https://github.com/ih-datapt-mad/ih_datamadpt1121_project_m2/blob/main/images/visual-analysis-guidebook.pdf)

- [Financial Times Visual Vocabulary](https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary)

- [Matplotlib](https://matplotlib.org/stable/api/index)

- [Pandas Visualization](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html)

- [Seaborn](https://seaborn.pydata.org/api.html)

- [Plotly](https://plotly.com/graphing-libraries/)

- [Cufflinks](https://coderzcolumn.com/tutorials/data-science/cufflinks-how-to-create-plotly-charts-from-pandas-dataframe-with-one-line-of-code)

- [Tableau](https://github.com/ih-datapt-mad/dataptmad1121_lessons/blob/main/module-2/visualization_tableau.md)

- [Power BI](https://github.com/potacho/power_bi_workshop)
