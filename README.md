# Encuesta de Presupuestos de Tiempo en Euskadi (1993-2023)

## Descripción del proyecto

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre la Encuesta de Presupuestos de Tiempo (EPT) en Euskadi, utilizando datos desde 1993 hasta 2023, con respuestas recolectadas cada 5 años. La encuesta ofrece información detallada sobre los hábitos sociales y la vida cotidiana de la población desde la perspectiva del uso del tiempo diario, analizando su distribución entre diversas actividades.

El objetivo principal de este estudio es analizar tendencias y diferencias sociales relacionadas con el uso del tiempo a lo largo de 30 años, considerando factores como el género, la edad y las preferencias personales. Los datos utilizados se obtuvieron de la página oficial de Eustat: [Encuesta de Presupuestos de Tiempo](https://www.eustat.eus/estadisticas/tema_173/opt_0/tipo_11/temas.html).

---

## Datos utilizados

Se han utilizado 7 datasets correspondientes a los años:
- 1993
- 1998
- 2003
- 2008
- 2013
- 2018
- 2023

Cada dataset contiene información sobre las actividades realizadas por la población y el tiempo dedicado a cada una de ellas. Los datos incluyen variables relacionadas con:
- Tareas del hogar
- Actividades religiosas
- Vida social
- Género
- Grupo de edad
- Nivel de estudios

---

## Hipótesis analizadas

1. **Brecha de género en las tareas del hogar**: La brecha de tiempo dedicada a las tareas del hogar entre hombres y mujeres se ha reducido a lo largo de los años.

2. **Disminución del tiempo dedicado a la religión**: El tiempo que las personas dedican a actividades religiosas ha disminuido con el paso de los años.

3. **Vida social y edad**: Los jóvenes dedican más tiempo a la vida social en comparación con los grupos de edad más avanzada.

---

## Estructura del repositorio

El repositorio contiene los siguientes archivos:

- `EDA_Presupuestos_Tiempo.ipynb`: Notebook de Jupyter con el análisis exploratorio de datos, visualizaciones y resultados.
- `data/`: Carpeta que contiene los 7 datasets utilizados para el análisis.
- `img/`: Carpeta conimagenes utilizadas en el Notebook
- `README.md`: Archivo de documentación con información sobre el proyecto.

---

## Resultados clave

1. **Brecha de género en tareas del hogar**: La diferencia en el tiempo dedicado a las tareas del hogar entre hombres y mujeres muestra una tendencia decreciente, aunque persiste una brecha significativa.

2. **Disminución del tiempo dedicado a la religión**: El tiempo invertido en actividades religiosas ha disminuido considerablemente desde 1993.

3. **Vida social y edad**: Los jóvenes dedican consistentemente más tiempo a la vida social en comparación con los grupos de mayor edad, aunque esta tendencia ha variado ligeramente en función de los períodos estudiados.

---

## Tecnologías utilizadas

- Python (pandas, matplotlib, seaborn, numpy)
- Jupyter Notebook

---

## Fuentes de datos

Los datos fueron obtenidos de la página oficial de Eustat:
[Encuesta de Presupuestos de Tiempo](https://www.eustat.eus/estadisticas/tema_173/opt_0/tipo_11/temas.html)


