# PEC2-Visualizacion-Datos
Como parte de la PEC2 de la asignatura Visualización de Datos del Máster Universitario en Ciencia de Datos de la UOC, subo tres visualizaciones de tipología distinta. Una consiste en un gráfico de barras, otra en un ridgeline chart y la última en un diagrama de red.

# Primera Visualización
Muestra la suma de la media de precipitaciones en l/m^{2} agrupada en meses, que ha habido en Chiva a lo largo de 2024, a partir de un gráfico de barras. La fuente de los datos es el [repositorio del sistema S.A.I.H. de la Confederación Hidrográfica del Júcar O.A.](https://saih.chj.es/chj/saih/glayer?t=p) Hay que tener en cuenta que debido a esta reciente DANA, el 30/10/2024 los pluviómetros dejaron de funcionar. 
La herramienta para realizar esta visualización ha sido Excel.
![visu_1_datos_lluvia_2024_Chivia](https://github.com/user-attachments/assets/e1c4313f-6806-4a58-8075-e1cf390f56e0)


# Segunda Visualización
Se trata de un Ridgeline Chart que recoge todas la media de lluvia en l/m^{2} por cada día, desde el 01/01/2024 hasta el 13/11/2024 (teniendo en cuenta que el 30/10/2024 y días sucesivos no se recogió ningún dato debido al colapso provocado por la DANA), en la estación con pluviómetro en Chiva. La fuente de los datos es el [repositorio del sistema S.A.I.H. de la Confederación Hidrográfica del Júcar O.A.](https://saih.chj.es/chj/saih/glayer?t=p)
Esta visualización se ha realizado mediante la herramienta RStudio.
![visu_2_Ridgeline_2024_Chiva](https://github.com/user-attachments/assets/85ecb907-7453-40e7-9e06-ea7a8e76f448)


# Tercera Visualización
Se trata de un Diagrama de Red, que muestra mediante un grafo formado por nodos y aristas, la relación que hay entre los autores de los artículos científicos publicados, y las citas que reciben estos autores. (Los autores son los nodos, y las aristas será cada cita que reciban). La fuente de los datos es [Kaggle](https://www.kaggle.com/datasets/mathurinache/citation-network-dataset?resource=download). Debido a la gran extensión del archivo, únicamente hemos hecho la visualización con los 200 primeros artículos de este documento. La herramienta utilizada para realizar esta visualización ha sido Python.
![visu_3_colaboracion_academica](https://github.com/user-attachments/assets/672bb55a-6ab6-49c7-a75e-c0f840b962d0)


## Instrucciones
Para ver las visualizaciones únicamente hay que descargar los tres ficheros adjuntos, si hubiera algún fallo no duden en contactar conmigo.

## Autoría
Este proyecto ha sido creado por Sofía Ramírez López

## Licencia
El proyecto está bajo la licencia Apache License 2.0. Para más detalle consultar el archivo LICENSE
