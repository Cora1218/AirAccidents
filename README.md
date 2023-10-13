![header](https://github.com/Cora1218/AirAccidents/blob/master/Imgs/header.png)

## Indice
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Contenido</summary>
  <ol>
    <li><a href="#Introducción">Introducción</a></li>
    <li><a href="#Objetivo">Objetivo</a></li>
    <li><a href="#Alcance">Alcance</a></li>
    <li><a href="#Tecnologías">Tecnologías Utilizadas</a></li>
    <li><a href="#ETL-EDA">ETL-EDA</a></li>
    <li><a href="#Conclusiones relevantes">Conclusiones relevantes</a></li>
    <li><a href="#KPIs">KPIs</a></li>
    <li><a href="#PowerBI">PowerBI</a></li>
    <li><a href="#Desarrollador">Desarrollador</a></li>
  </ol>
</details>

## Introducción
Proyecto de Data Analytics para la carrera de Data Science en la academia Soy Henry. 

El presente proyecto consta de un análisis de una base de datos histórica de accidentes aéreos para identificar patrones y tendencias en la seguridad de la aviación civil, así como los insights más relevantes a través de un dashboard interactivo con 4 KPIs. 

## Objetivo
Diseñar un dashboard interactivo que permita explorar los datos y obtener información sobre accidentes, incluyendo la visualización de 4 KPIs (1 solicitado, 3 propuestos). 

Objetivos especificos:
- Hacer un análisis exploratorio de datos para poder identificar los diferentes patrones y tendencias. 
- Sacar conclusiones a partir del ánalisis hecho.
- Crear KPIs relevantes para la seguridad de la aviación civil.

## Alcance
El proyecto fue desarrollado siguiendo los pasos a continuación:
1. Pre-procesamiento de datos
2. Extracción, Transformación y Carga de datos [ETL_Link](https://github.com/Cora1218/AirAccidents/blob/master/ETL.ipynb) 
3. Análisis exploratorio de datos (EDA) [EDA Link](https://github.com/Cora1218/AirAccidents/blob/master/EDA.ipynb)
4. Desarrollo de dashboard con PowerBI

![proceso](https://github.com/Cora1218/Imgs/blob/master/proceso.png)
    
- Link de descarga dashboard Google Drive: 

## Tecnologías
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)

- seaborn
- ydata_profiling

## ETL-EDA
1. Transformación de datos paso a paso. 
2. Exportación de datos a formato csv.
3. Uso de ydata_profiling, matplotlib y seaborn para la generación de gráficos.
4. Análisis de gráficos, relación entre datos y detección de anomalías.
5. Generación de conclusiones.
6. Generación de KPIs de acuerdo al análisis.

## Conclusiones relevantes
1. La mayor concentración de accidentes aéreos se encuentra entre los años 1940 y 2000, con el máximo en 1946 donde hubo un total de 87 accidentes. Esto se puede deber al hecho de que alrededor de 1950 la aviación comercial empezó a tener un auge en popularidad, años en los que también coincide la producción de las primeras generación de jets, las cuales tenían una alta tasa de accidentalidad e inadecuadas práticas de mantenimiento. 
2. La mayor cantidad de accidentes se ha dado en la ruta de Moscú, Rusia, lo cual concuerda con los datos de los operadores, dentro de los cuales, la aerolínea rusa Aeroflot tiene el mayor número de accidentes y mayor número de fatalidades. Esto apoya a los registros históricos, que constatan que Aeroflot ha tenido cinco veces más accidentes que cualquier otra aerolínea. 
3. Los accidentes aéreos militares superaron a los civiles en los tiempos de las guerras mundiales, lo cual tiene sentido ya que las fuerzas aéreas, como la Luftwaffe, tuvieron una incidencia significativa en estos conflictos. 
4. El modelo Douglas DC-3 que más ha tenido accidentes historicamente. Este modelo tuvo un alto impacto en la industria aérea durante las decadas de 1930, 1940 y la segunda guerra mundial (se vendió mucho). Estos aviones fueron acogidos tanto por industría aérea civíl, como por la militar. Se adaptaron varias versiones dependiendo el uso. Esto concuerda con las gráficas analizadas anteriormente, donde se pudo evidenciar una alta incidencia de accidentes después de 1940.
5. No suele haber muchas muertes en tierra a causa de accidentes aéreos, en comparación a las muertes de las personas a bordo. Sin embargo, se evidenció un pico máximo de fatalidades en tierra en el 2001, superando con creces a las muertes de personas a bordo, el cual corresponde al ataque terrorista al World Trade Center (9/11) en la ciudad de Nueva York, lo cual le da total sentido a este outlier. 
6. El año con mayor número de fatalidades parece ser 1972, lo cual tiene sentido porque en 1972 ya estaba operando la nueva generación de jets, que hasta el día de hoy siguen en uso y en producción, como el Boeing 737. Estos aviones son mucho más grandes que los de la primera generación y admiten muchos más pasajeros, por ende, en el caso de accidentes, lo más probable es que haya una mayor tasa de mortalidad, aunque no necesariamente haya una mayor tasa de accidentalidad.

## KPIs
1. `KPI 1`: Tasa de mortalidad 
- Métrica: Número de muertes a bordo/Número total de personal a bordo 
- Objetivo: Reducción del 5% anualmente
2. `KPI 2`: Tasa de fatalidades por accidentes
- Métrica: Número de muertes a bordo/Número total de accidentes
- Objetivo: Reducción de un 10% anualmente
3. `KPI 3`: Tasa de accidentes fatales
- Métrica: Número de accidentes donde no hubo sobrevivientes a bordo/Número total de accidentes
- Objetivo: Tasa de accidentes fatales por debajo del 50% anualmente
4. `KPI 4`: Tasa de accidentes sin fatalidades
- Métrica: Número de accidentes sin fatalidades a bordo/Número total de accidentes
- Objetivo: Aumento de un 10% en un periodo de 3 años

## PowerBI
Links de acceso para descarga del dashboard:

- Link Google Drive: 

## Desarrollador
<div align="center">
 
| [<img src="https://github.com/Cora1218/AirAccidents/blob/master/Imgs/yo.png" width=115><br><sub>María  Martínez</sub>](https://github.com/Cora1218) |
| :---: | 

Mi Linkedin para ponerte en contacto conmigo: </br>

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mar%C3%ADa-guadalupe-mart%C3%ADnez-1a489173?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BfHtKttkUTGW0GMtwRy3KkA%3D%3D)

</div>
