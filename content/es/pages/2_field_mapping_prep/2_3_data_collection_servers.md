---
title: 2.3 Servidores de recogida de datos
bookShowToC: True
---

***Nota: Esta es una versión desactualizada del material de capacitación; se harán mejoras en el futuro.***

---

Esta sección proporciona:  

* Una visión general de las opciones de almacenamiento del servidor
* Orientación sobre la selección de un servidor para las necesidades de su proyecto 
* Breve resumen de las opciones de servidor

*La siguiente sección ofrece una visión general y una guía para decidir si es necesario un servidor para su proyecto y las opciones entre las que elegir. Para obtener información detallada sobre la configuración y gestión de servidores, utilice la documentación vinculada a cada opción de servidor. 

<br>

## Visión general 
Al comenzar un proyecto de cartografía, muchas organizaciones se preguntan si necesitan disponer de un servidor. Después de recopilar los datos, necesitará obtener los datos de los dispositivos. A veces, funciona simplemente recoger y procesar los datos directamente desde los dispositivos de recogida de datos. Sin embargo, esto no se adapta bien cuando hay más personas recopilando datos, y también significa que no hay copia de seguridad de los datos: si pierdes el dispositivo, puedes perder los datos. Antes de la recogida de datos, es importante contar con una estrategia de gestión de datos que se adapte a sus operaciones. 

<br>

![](/images/management_icon_wide.PNG) 
## Elección de una opción de almacenamiento

**Servidor en la nube frente a almacenamiento físico**
El uso de un servidor de recopilación de datos permite gestionar mucho mejor los formularios y los despliegues, recopilar y agregar las respuestas, y puede ofrecer funciones adicionales de visualización, análisis y exportación de datos. El uso de un servidor puede estar restringido por los recursos disponibles (coste de un servidor) y/o la conexión a Internet (acceso a un servidor en la nube). Los servidores utilizados en los flujos de trabajo HOT incluyen:

* POSM 
* Servidor OpenMapKit
* Kobo Toolbox

Si el uso de un servidor no está a su disposición, sigue siendo posible y crucial almacenar copias de seguridad de los datos. En este caso, los datos tendrán que ser descargados o compartidos de otro modo con una ubicación central, como un ordenador portátil, y clonados en una ubicación secundaria, como un disco duro o un segundo ordenador. 

**¿Qué servidor debo utilizar?**

Si decides utilizar un servidor, utiliza la siguiente tabla para decidir cuál es el mejor para tu proyecto y tus restricciones de recursos. Estas no son las únicas opciones disponibles, sino servidores que HOT ha utilizado y probado sobre el terreno para proyectos de cartografía. 

| Quiero utilizar un servidor que...                           | Kobo Toolbox | OpenMapKit Server | POSM |
|------------------------------------------------|-----|------|-----|
| Sea físico o no requiera conexión a internet para la carga | ✔   | ✔    | ✔   | ×       | ×           | ×         |
| Está basado en la nube (carga de datos a través de Internet)            | ✔   | ✔    | ✔   | ×       | ×           | ×         |
| Acepta datos de ODK.                                    | ✔   | ✔    | ✔   | ✔       | ✔           | ×         |
| Acepta datos de KOBO Collect                 | ✔   | ✔    | ×   | ×       | ✔           | ×         |
| Acepta datos OMK                                 | ×   | ×    | ×   | ×       | ✔           | ✔         |
| Puede proporcionar visualizaciones de datos                          | ×   | ×    | ×   | ×       | ×           | ✔         |
| Proporciona una visualización de mapa de los datos GPS recogidos    | ×   | ×    | ✔   | ✔       | ×           | ×         |


### Kobo Toolbox
Kobo Toolbox es una aplicación online que permite a los usuarios construir encuestas Kobo/ODK así como almacenar, agregar y realizar análisis de datos Kobo/ODK. 

![Kobo Dashboard showing data collected in Uganda](/images/field-mapping-technical-setup/kobo_dashboard.jpeg)

**Nivel de habilidad para implementar y gestionar**.

Principiante

**Utilice Kobo Toolbox Server si:**

* NO se utiliza OpenMapKit. 
* Los datos se recogen en formato .xml, como con ODK o Kobo Collect.
* La recogida de datos geoespaciales no incluye polígonos - se aceptan puntos GPS

**Configuración y gestión de datos** <br>
Visite [kobo.humanitarianresponse.info](https://kobo.humanitarianresponse.info/)

<br>

### Servidor OpenMapKit
OpenMapKit Server es un sistema de almacenamiento basado en la nube para especialmente diseñado para almacenar y compilar datos OpenMapKit. Los datos recopilados a través de OpenDataKit también se pueden cargar en un Servidor OpenMapKit. 

![](/images/field-mapping-technical-setup/omk_server.gif)

**Nivel de habilidad para implementar y gestionar** <br>
Moderado

**Utilizar OpenMapKit Server si:**

* Recopilación de datos .osm mediante OpenMapKit. 
* Recopilación de datos .xml utilizando aplicaciones ODK y Kobo. 
* El director del proyecto necesita supervisar los datos a medida que se recopilan y cargan desde el campo. 

**Instalación** <br>
La configuración y el alojamiento son proporcionados por HOT para las comunidades locales de OSM y los proyectos con los que HOT tiene un acuerdo activo.

**Gestión de datos**

1. OpenMapKit Server permite que los formularios ODK y OMK en formato .xlsx sean cargados y convertidos a formularios .xml. En otras palabras, OpenMapKit Server puede convertir formularios de formato Excel al formato digital legible por las aplicaciones ODK, Kobo y OMK. 
2. OpenMapKit Server también permite cargar Despliegues (que contienen capas de construcción .mbtiles y .osm). 
3. Tanto los formularios como los despliegues se pueden descargar directamente a teléfonos móviles y tabletas a través de la conexión a Internet - lo que permite la configuración remota de dispositivos para la recopilación de datos. 
4. Los formularios cumplimentados y los datos pueden entonces cargarse directamente desde el terreno cuando se disponga de conexión a internet. 
5. Los administradores del servidor OpenMapKit pueden ver los datos entrantes y descargarlos en diversos formatos. 

<br>

### POSM
Portable OpenStreetMap, o POSM, es un servidor físico que contiene un conjunto de herramientas OpenStreetMap, incluyendo el servidor OpenMapKit. Los POSM permiten a varios usuarios conectarse y cargar datos desde dispositivos de recogida de datos a una ubicación central sin necesidad de acceso a Internet. A continuación, estos datos pueden agregarse mediante el servidor OMK y sincronizarse con OSM directamente o descargarse para su análisis y procesamiento.

![](/images/field-mapping-technical-setup/posm_infographic.jpeg)

**Nivel de conocimientos para implementar y gestionar** <br>
Experto

**Utilice POSM si:**

* Los directores de proyecto necesitarán adquirir hardware para ensamblar un POSM, o piezas para el autoensamblaje. Además, los equipos necesitarán tener conocimientos para configurar un servidor en el dispositivo. *Debido a estos requisitos, el POSM sólo se recomienda a equipos que dispongan de soporte técnico.
* Los encuestadores no tendrán acceso a Internet para cargar datos.
* Los topógrafos podrán reunirse para cargar los datos en el POSM (es decir, podrán reunirse para volver a un lugar donde se guarde el POSM).
* Los gestores de proyectos pueden adquirir un dispositivo POSM.

**Configuración y gestión de datos** <br>
Visite el sitio web [POSM.io](http://posm.io/docs/posm/setup/).