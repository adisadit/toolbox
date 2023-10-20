---
title: 4.1 Creando una sección de mapeo usando QGIS
bookShowToC: True
---

***Nota: Esta es una versión desactualizada del material de capacitación; se harán mejoras en el futuro.***

---

Esta sección proporciona:

* Una visión general de las herramientas y métodos para la gestión de equipos en el campo. 
* Guías paso a paso para el uso de OSMAnd y QGIS para gestionar el movimiento del equipo y la finalización de las áreas de asignación. 

<br>

## Visión general
Para que la recogida de datos sobre el terreno sea eficaz y tenga éxito, es fundamental contar con un plan de recogida de datos sobre el terreno bien elaborado. Esto asegurará que los equipos de campo se enfrenten al menor número de desafíos mientras están en el campo, reduciendo así el número de llamadas de apoyo de campo que llegan al supervisor.
 
A la hora de planificar el despliegue de un equipo, es importante que el supervisor tenga una buena idea de cuántos días de trabajo tiene frente a la mano de obra disponible para realizar el trabajo. Una vez hecho esto, creará pequeñas secciones del área de cartografía que puedan ser cubiertas en un día por un equipo de dos cartógrafos o un solo cartógrafo, dependiendo de la disposición del equipo.

De forma similar a la cuadrícula de Tasking Manager, la creación de secciones para la cartografía permite a los supervisores dividir las tareas, controlar el progreso y poder evaluar las lagunas o los problemas de calidad. 

## Recursos y materiales de formación
Esta sección presenta una selección de recursos dirigidos a gestores de proyectos, formadores o incluso autodidactas sobre los temas descritos anteriormente.

![](/images/learning_icon_wide.PNG)
*La siguiente sección está diseñada para servir como guía autodidacta para directores de proyecto, supervisores u otras personas en la creación e implementación de áreas de asignación para el mapeo de campo.*

**Habilidades y tecnología necesarias**

* Ordenador
* [QGIS Instalado](https://hotosm.github.io/toolbox/pages/data-use-and-analysis/7.1-qgis/#installing-qgis)
* [Conocimientos básicos de QGIS](https://hotosm.github.io/toolbox/pages/data-use-and-analysis/7.1-qgis/#navigating-qgis)
* [QuickMapServices](https://hotosm.github.io/toolbox/pages/data-use-and-analysis/7.1-qgis/#installing-plug-ins)

### Creación de secciones cartográficas en QGIS para mapas impresos

La siguiente actividad cubre el proceso de generación de secciones cartográficas en QGIS para impresión. Esta actividad utiliza el ejemplo de dirigir un equipo de 8 voluntarios de mapeo para mapear la ciudad de Grootfontein, en el norte de Namibia, durante un Proyecto de Eliminación de Malaria. Se proporcionan archivos de ejemplo para esta actividad, pero puede seguirse con archivos proporcionados por el usuario.

Para empezar, abra QGIS en su ordenador e inicie un nuevo proyecto. Usando [QuickMapServices](https://hotosm.github.io/toolbox/pages/data-use-and-analysis/7.1-qgis/#installing-plug-ins) como mapa base, navegue a Grootfontein Town, Norte de Namibia. 

![](/images/advanced_qgis/management1.gif)

Cree un shapefile vacío seleccionando 'Capa' > 'Crear Capa' > 'Nueva Capa Shapefile'. Después de seleccionar la ubicación y el nombre del archivo, asegúrese de asignar el archivo como 'Polígono'.

![](/images/advanced_qgis/management2.gif)

Habilite la edición, seleccione también la 'Nueva característica'. Cree secciones de la ciudad, dándoles números. Estas secciones deben seguir características naturales o puntos de referencia prominentes como pantanos o carreteras. Esto es para asegurar la facilidad de localización de estas secciones por los maperos.

![](/images/advanced_qgis/management3.gif)

Una vez que todas las secciones se crean, el estilo para la visibilidad. 

![](/images/advanced_qgis/management4.PNG)

Crea mapas que muestren estas secciones. Estos mapas pueden imprimirse para compartirlos con los voluntarios de cartografía. Los equipos pueden ahora dirigirse a sus secciones asignadas para realizar el mapeo de campo.

### Creación e importación de secciones cartográficas a OSMAnd
 
La siguiente actividad cubre el proceso de importación de archivos a OSMAnd basado en la actividad anterior (generación de secciones de mapeo en QGIS). Esta actividad utiliza el ejemplo de dirigir un equipo de 8 voluntarios de mapeo para mapear Grootfontein Town, en el norte de Namibia, durante un Proyecto de Eliminación de Malaria. 

![](/images/area_of_focus.jpg)
 
**OSMAnd** proporciona una gran alternativa a la impresión de estos mapas de secciones. Con OSMAnd, el Supervisor puede utilizar los siguientes pasos para dar secciones a los miembros del equipo para su uso en el campo directamente en sus dispositivos móviles.

1. Cree centroides de sección desde *grootfontein_sections.shp* obteniendo *grootfontein_sections_centroids.shp*. Cree los centroides seleccionando el menú 'Vector' > 'Geometry Tools' > 'Centroids'. En el submenú, seleccione el archivo *grootfontein_sections.shp* como capa de Entrada, haga clic en 'Ejecutar.'
2. Exporte los archivos shapefile de secciones (_grootfontein_sections.shp_) y el archivo shapefile de centroides (_grootfontein_sections_centroids.shp_) como .gpx obteniendo un _grootfontein_sections.gpx_ y un _grootfontein_sections_centroids.gpx._.
3. 3. Transfiera estos dos archivos .gpx desde su ordenador a la carpeta _/Phone/Android/data/net.osmand/files/tracks _.
4. Abra la aplicación OSMAnd y cargue estos dos archivos a través de _Botón de menú -> Mis sitios -> Pistas -> Examinar hasta donde se encuentran los archivos_.

El archivo gpx de secciones le mostrará los límites de las secciones y el archivo gpx de centroides le mostrará los números de sección una vez seleccionado un punto centroide. Con estos dos, los voluntarios pueden moverse por el campo utilizando la aplicación OSMAnd, localizando sus posiciones cada vez, así como las secciones en las que se encuentran.