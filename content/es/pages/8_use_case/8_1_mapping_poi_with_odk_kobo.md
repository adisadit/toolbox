---
title : 8.1 Mapear POI con ODK + Servidor KoboToolbox
bookShowToC: True
---

*El siguiente flujo de trabajo muestra las herramientas y procesos utilizados en un sencillo proyecto de mapeo de campo durante el cual HOT formó a ONGs locales para integrar el mapeo en programas existentes utilizando OpenDataKit y KoboToolBox Server.* 



## Descripción general del proyecto

**Colmar las lagunas en materia de desarrollo y emergencia para la crisis de los refugiados en África Oriental**.

África Oriental (y Uganda en concreto) sigue siendo el centro de una de las mayores y más rápidas crisis de refugiados del mundo. La progresiva política de puertas abiertas de Uganda ha provocado por sí sola una afluencia de aproximadamente 1,4 millones de refugiados al país. La gran movilidad de los refugiados hace que la distribución y el tamaño de los asentamientos cambien constantemente, y la necesidad de disponer de información estandarizada y accesible para tomar decisiones oportunas sobre dónde deben planificarse y construirse los servicios es más crucial que nunca. Mediante el uso de herramientas técnicas de código abierto combinadas con una metodología basada en la comunidad, HOT ha sido capaz de abordar la crítica carencia de datos en estos contextos aumentando la producción de datos exhaustivos en tiempo real sobre infraestructuras y servicios donde residen los refugiados y las comunidades de acogida. Para garantizar que el gobierno y las organizaciones implicadas en la respuesta a los refugiados sepan, en primer lugar, que estos datos existen y, en segundo lugar, cómo utilizarlos eficazmente, HOT ha trabajado intensamente para apoyar y formar a los actores sobre cómo incorporar sistemáticamente los datos generados por los ciudadanos en sus programas para abordar y llenar las lagunas existentes.

**Página del proyecto:** [BRIDGING DATA GAPS: MAPPING REFUGEE CONTEXTS IN EAST AFRICA](https://www.hotosm.org/projects/bridging-data-gaps-mapping-refugee-contexts-in-east-africa/)

**Fechas:** junio de 2018 - mayo de 2019

**Estado:** Completo 

<br>

#### Herramientas utilizadas:
* **Recopilación de datos sobre el terreno y a distancia:** OpenDataKit (ODK) Collect, servidor Kobo, HOT Tasking Manager (ID Editor, JOSM).
* **Supervisión de datos sobre el terreno:** OSMand y Maps.me
* **Limpieza de datos:** OpenRefine, Excel, JOSM, scripts Python 
* **Extracción y visualización de datos:** Herramienta de exportación HOT, OSM Analytics, QGIS, Overpass Turbo, Umap, HDX

<br>

## Flujo de trabajo de mapeo de campo

#### 1. 1. Identificación de las necesidades de los socios y de su área de interés/operación
A través de interacciones regulares y reuniones planificadas con varias partes interesadas y socios - incluyendo ACNUR, OPM, FLM, etc. - el Director del Proyecto y/o el Director Nacional trabajarían para comprender las carencias técnicas y las necesidades a las que se enfrentan las instituciones a la hora de reforzar sus contribuciones a la respuesta nacional a los refugiados. A partir de este punto, identificaríamos las lagunas de datos y las competencias institucionales necesarias para cubrir estas áreas e idearíamos conjuntamente un plan de ejecución para formar al grupo/organización durante varios días con el fin de lograr los resultados previstos. 

Pasos utilizados en esta fase:

* [Definición de necesidades y requisitos](https://hotosm.github.io/toolbox/pages/running-a-mapping-project/1.1_defining_needs_and_requirements/)

<br>

#### 2. Formación y ejercicios de capacitación
Tras el amplio proceso de consulta, se planificarán e impartirán cursos de formación en las propias instalaciones o en las de los socios. El objetivo principal de estas formaciones sería introducir -e intentar inculcar- herramientas SIG y apoyar el desarrollo de capacidades con socios de respuesta a refugiados a través de lecciones personalizadas durante un corto número de días. Todos estos materiales de formación se diseñaron específicamente para cada organización asociada, con el fin de garantizar que los recursos se ajustaran a su nivel de destreza/comprensión y les permitieran mejorar adecuadamente sus conocimientos prácticos. Por lo general, la formación duró entre 2 y 5 días y abarcó temas como la recopilación, el almacenamiento, la extracción, el análisis y la visualización de datos. 

Pasos utilizados en esta fase:

* [Formaciones y talleres](https://hotosm.github.io/toolbox/pages/running-a-mapping-project/1.4-trainings-and-workshops/)

Las formaciones impartidas a los socios incluyeron: 

* [Introducción a OSM](https://docs.google.com/presentation/d/1QneNbichunhVjyN4RPRyPuYV3Q7QMJctp50_90FpMpc/edit#slide=id.g526e73601c_0_1163)
* [Cartografía con JOSM](https://docs.google.com/presentation/d/1nLs1JA-nlmqWA2vIr9ZsoDcg8wjsoc5nv1QMK9GT8KI/edit?usp=sharing)
* [Cartografía con el editor ID](https://docs.google.com/presentation/d/1sbTZp5B7sQlEM-RzDU-33JlJnUUUGDkeOchhC6srK20/edit#slide=id.g51d3d58777_0_0)
* [Herramientas móviles de recogida de datos](https://hotosm.github.io/toolbox/pages/data-collection-and-field-mapping/3.2-data-collection-applications/)
* [Introducción a QGIS](https://docs.google.com/presentation/d/1EA63n-jEjgEYVGzfdW8dispZpqvkbGDYx7ZtuayxZnQ/edit?usp=sharing)
* [Descarga de datos de OSM (Hot Export Tool y Quick OSM)](https://docs.google.com/presentation/d/1RyHYVPZU5d4xJ1cpWga4QRdfohpEs-t9ylJ_HTJ7wm8/edit?usp=sharing)

<br>

#### 3. 3. Recogida de datos
Las actividades de recopilación de datos fueron de naturaleza consultiva y participativa, donde los recopiladores de datos fueron elegidos de las comunidades locales que nos interesaba generar datos para apoyar la respuesta a los refugiados. Los recopiladores de datos utilizaron sus smartphones personales y aquellos que no disponían de smartphones que funcionaran correctamente fueron equipados con uno por HOT. OpenDatakit fue la principal herramienta/aplicación de recopilación de datos utilizada y los encuestadores aplicaron 6 formularios únicos -incluidos los de salud, educación, agua y saneamiento- y los utilizaron para elaborar mapas en todas las aldeas visitadas, tanto en los asentamientos de refugiados como en sus alrededores. 

Pasos utilizados en esta fase: 

* [Elección de una aplicación de recopilación de datos: OpenDataKit (ODK)](https://hotosm.github.io/toolbox/pages/data-collection-and-field-mapping/3.2-data-collection-applications/#open-data-kit-odk)
* [Configuración de OpenDataKit](https://hotosm.github.io/toolbox/pages/data-collection-and-field-mapping/3.2.1_setting_up_odk/)
* [Uso de ODK Collect](https://hotosm.github.io/toolbox/pages/field-mapping-management/5.1_using_odk_collect/)

<br>

#### 4. Almacenamiento y supervisión de datos
Los datos obtenidos sobre el terreno se almacenaron en el espacio en línea del servidor kobo del ACNUR. Esto permitió a los diferentes socios implementadores de ACNUR y OPM acceder a los datos de forma fácil y efectiva. El recopilador de datos sobre el terreno cargaba los datos al final de cada jornada laboral. La carga de ODK requiere una conexión de tan sólo 2G para enviar los archivos al servidor. Los encuestadores siempre disponían de al menos 50 MB de datos para realizar estas tareas. El servidor Kobo también se utilizó como herramienta de seguimiento para determinar el número de puntos de datos recogidos y evaluar rápidamente cualquier laguna en la calidad de los datos sobre el terreno.

Pasos utilizados en esta fase: 

* [Servidores de recogida de datos](https://hotosm.github.io/toolbox/pages/data-collection-and-field-mapping/3.4-data-collection-servers/)

<br>

#### 5. Limpieza y análisis de datos
Después de almacenar los datos en Kobo, los datos se descargarían, se limpiarían y se cargarían utilizando JOSM. 

Pasos utilizados en esta fase: 

* [Limpieza de datos con JOSM](https://hotosm.github.io/toolbox/pages/data-cleaning-upload-and-quality-assurance/5.1-data-cleaning-with-josm/)

<br>

#### 6. Visualización de datos
Para este proyecto, HOT utilizó varios métodos para visualizar los datos; desde el uso de QGIS para crear mapas estáticos y atlas hasta el uso de herramientas como Overpass turbo, Umap y Mapbox Studio para crear productos cartográficos dinámicos e informativos. Los tipos de visualizaciones que se desarrollaron principalmente incluyeron matrices de distancias, identificadores de lagunas de recursos, mapas de localización y navegación y mapas de indicadores de proximidad.

Pasos utilizados en esta fase:

* [Descarga de datos con la herramienta de exportación HOT](https://hotosm.github.io/toolbox/pages/data-export/6.1-hot-export-tool/)
* [Creación de mapas y atlas en QGIS](https://hotosm.github.io/toolbox/pages/data-use-and-analysis/7.2-creating-an-atlas-in-qgis/)
* [Mapas web e interactivos](https://hotosm.github.io/toolbox/pages/data-use-and-analysis/7.3_web_and_interactive_maps/)