---
title : 2.1 Diseñar el modelo de datos
bookShowToC: True
---

***Nota: Esta es una versión desactualizada del material de capacitación; se harán mejoras en el futuro.***

---

Esta sección proporciona:  

* Una visión general de los modelos de datos y el etiquetado de OpenStreetMap, incluyendo diapositivas de presentación.
* Instrucciones paso a paso sobre las herramientas que le ayudarán a crear su modelo de datos.
* Instrucciones paso a paso para crear su modelo de datos

<br>

## Visión general
Al comenzar un proyecto de cartografía, será necesario crear un modelo de datos para determinar qué características se cartografían y los detalles recogidos para cada una de ellas. Un **modelo de datos** define qué elementos se van a cartografiar y qué atributos se van a recopilar para cada uno de ellos. Si un proyecto va a cargar datos en OpenStreetMap, el modelo de datos debe diseñarse para que coincida con el etiquetado de OSM. 

Ejemplos de modelos de datos:

- [Crisis de refugiados en Uganda](https://wiki.openstreetmap.org/wiki/WikiProject_Uganda/Uganda_Crowdsourcing_Non-Camp_Refugee_Data)
- [Ramani Huria](https://wiki.openstreetmap.org/wiki/Dar_es_Salaam/Ramani_Huria)

OSM no trabaja con capas o tablas de atributos, sino con etiquetas. **Las etiquetas** se utilizan en OSM para categorizar las características, y para añadir información que es útil para la comprensión del mapa, la planificación, el enrutamiento y la consulta. Cada etiqueta consiste en una clave y un valor. Cada característica del mapa debe tener una o más etiquetas como:

* building=residential
* highway=primary
* amenity=school

Además, cada una de estas características puede tener un número ilimitado de atributos relacionados añadidos en OSM como etiquetas. Por ejemplo, un edificio puede tener las siguientes etiquetas: 

* building=commercial
* building:material=brick
* roof:material=metal
* shop=tailor

La creación de un modelo de datos debe realizarse en colaboración con todas las partes interesadas para garantizar que se recopila toda la información necesaria: es mucho más difícil volver a visitar un lugar para cartografiarlo y recopilar información adicional.  Al mismo tiempo, a la hora de diseñar un modelo de datos hay que tener en cuenta cuánto tiempo necesitará un topógrafo para completar la recopilación de datos: cada tipo de característica, atributo o pregunta añadirá el tiempo adicional necesario. 

## Recursos y material de formación
En esta sección se presenta una selección de recursos dirigidos a directores de proyectos, formadores o incluso autodidactas sobre los temas mencionados anteriormente.

![](/images/training_presentations_wide.PNG)
* Las siguientes presentaciones pueden utilizarse para impartir formación o talleres.

* [Modelos de datos y etiquetado](https://docs.google.com/presentation/d/1CU6cBtu9ZAeCWKIz6xLVN4fBrdsN7R5tFELPXbepilI/edit#slide=id.g5c7d19429e_0_225)


![](/images/learning_icon_wide.PNG)
*La siguiente sección está diseñada como material autodidáctico que puede ser utilizado tanto en cursos de formación como por alumnos autodidactas.

* Herramientas para crear un modelo de datos
### Creación de su modelo de datos

### Herramientas para crear su modelo de datos
HOT recomienda el uso de TagInfo y OSM Wiki para buscar características OSM existentes cuando desarrolle su modelo de datos. Los siguientes pasos proporcionarán una introducción a cómo utilizar estas herramientas. 

**Habilidades y Tecnología Necesaria**

* Ordenador con 
* Conexión a Internet
* [Cuenta OpenStreetMap](https://hotosm.github.io/toolbox/pages/digitization-and-editing/3.1.1-opening_osm_accounts/)
* Recomendado: ratón de ordenador

**Cómo usar OSM Wiki

![osm_wiki_map_features](/images/field-mapping-technical-setup/osm_wiki_map_features.gif)

1. Navegue hasta [https://wiki.openstreetmap.org/wiki/Map_Features](https://wiki.openstreetmap.org/wiki/Map_Features) en un navegador de Internet Google Chrome o Mozilla Firefox.
2. Esta página proporciona documentación sobre características OSM comunes y existentes categorizadas por tipo. Estas tablas contienen claves y valores, junto con comentarios y a veces imágenes para ayudar a definir la etiqueta.  Desplázate por las tablas para explorar las etiquetas descritas. 
3. Busque una etiqueta en particular utilizando 'Ctrl+F' en su teclado. Por ejemplo, busque la etiqueta que debe utilizarse para los hospitales. Para ello, pulse "Ctrl+F" en su teclado, escriba "hospital" en la barra de búsqueda y pulse Intro. Esto le llevará a la etiqueta adecuada para hospitales. *Nota: puede haber más de una etiqueta adecuada para un elemento de búsqueda. Desplácese por los resultados hasta encontrar la etiqueta adecuada.*
4. 4. Las claves y valores de las tablas también enlazan con las páginas wiki correspondientes. Por ejemplo, si hace clic en "hospital" en el apartado de servicios, se le redirigirá a [https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dhospital](https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dhospital). Esta página proporciona detalles en profundidad sobre la etiqueta, así como etiquetas relacionadas y consejos sobre cómo mapear una característica en particular. 
5. Para practicar, busque otras palabras clave relacionadas con las características que desee asignar para descubrir claves y valores relacionados con esa característica. 

**Cómo utilizar TagInfo**

![taginfo](/images/field-mapping-technical-setup/taginfo.gif)

1. Navegue hasta [https://taginfo.openstreetmap.org](https://taginfo.openstreetmap.org) en un navegador de Internet Google Chrome o Mozilla Firefox.
2. 2. En la esquina superior izquierda, utilice la barra de búsqueda para encontrar una etiqueta. Para esta actividad, busca "techo".
3. La siguiente ventana te permitirá seleccionar entre las claves, valores y relaciones existentes que contengan "techo". 
4. 4. Al seleccionar una de estas opciones, accederá a una página de información sobre esa clave, valor o relación. Para esta actividad, busque y haga clic en "tejado:material". 
5. Ahora verás una página de información sobre la etiqueta "tejado:material" incluyendo valores que se han utilizado con la clave "tejado:material", combinaciones de otras etiquetas que se han utilizado con la clave, un mapa de la distribución de uso global de la clave si hay suficientes casos de uso, y enlaces a cualquier página OSM Wiki relacionada existente. 
6. Para practicar, busque otras palabras clave relacionadas con las características que desea mapear para descubrir claves y valores relacionados con esa característica. 



### Creación de su modelo de datos 
La siguiente actividad le guiará a través del proceso de creación de un modelo de datos. Aunque este proceso se puede hacer a mano o en un software de documentos (como Google Docs o Microsoft Word), el software de hoja de cálculo es el método recomendado para documentar su modelo de datos. 

**Habilidades y tecnología necesarias**

* Ordenador con 
* Conexión a Internet (recomendado para acceder a TagInfo y OSM Wiki)
* [Cuenta OpenStreetMap](https://hotosm.github.io/toolbox/pages/digitization-and-editing/3.1.1-opening_osm_accounts/)
* Recomendado: ratón de ordenador
* Software de hoja de cálculo, como LibreCalc, Google Sheets o Excel (recomendado para estructurar el modelo de datos)

**Flujo de trabajo del modelo de datos**

El diseño de un **modelo de datos** basado en el **etiquetado OSM** se define típicamente por las siguientes preguntas y flujo de trabajo:

1. ¿Cuál es el objetivo de la recogida de datos? Considere cómo se utilizarán los datos. 
1. ¿Qué características desea recopilar? Identifique el objetivo de la recogida de datos. 
1. ¿Dónde va a recoger los datos? Los modelos de datos pueden diferir en función de su ubicación.
1. ¿Qué se ha hecho antes? Elabore un modelo de datos aprovechando modelos similares. 
1. ¿Qué etiquetas existen para las características? 
   1. Verificar el estado de las etiquetas a través de OSM Wiki
   1. Verificar el uso de la etiqueta a través de TagInfo
1. Utilizar etiquetas aprobadas siempre que sea posible en el modelo de datos
1. ¿Están todas las partes interesadas de acuerdo con el modelo de datos? Revise el modelo de datos e incorpore los comentarios de los socios del proyecto (añadir, eliminar o cambiar características del modelo de datos puede retrasar la recogida de datos sobre el terreno y disminuir la calidad de los datos).


Elabore una lista de todas las características que desea recopilar. Por ejemplo: edificios, puntos de agua, carreteras. 

| Características                          |
|------------------------------------------------|
|Edificios | 
|Puntos de agua  | 
|Carreteras  | 

Vaya a [OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Map_Features) para buscar la clave adecuada para cada característica, y el valor si sólo hay una opción de valor. 



| característica                           |  Clave                           | Valor                           |
|------------------------------------------------|------------------------------------------------| ------------------------------------------------|
|Edificios | building |  | 
|Puntos de suministro de agua | amenity | water_point |
|Carretera | highway |  |

Para las características con múltiples valores, tales como edificios, utilice la página OSM Wiki para esa clave, así como TagInfo para encontrar los valores apropiados. Estos valores deben ser sólo lo que es razonable para su recopilación de datos. Si bien sería ideal recoger todos los tipos de edificios en una ciudad, su proyecto sólo podría ser capaz de recoger todos los edificios de escuelas y hospitales. Nota: los valores de su modelo de datos deben tener sentido para el contexto de su geografía. Por ejemplo: hut es un valor apropiado para edificios en Liberia, pero no es probable que lo sea en Alemania. Además, puede que tenga que interpretar un tipo de valor existente para que coincida mejor con el valor apropiado para su región. 



| Característica                           |  Clave                           | Valor                           |
|------------------------------------------------|------------------------------------------------| ------------------------------------------------|
|Edificio | building | residential, school, civic | 
|Puntos de suministro de aguas | amenity | water_point |
|Carretera | highway | primary, secondary, residential |

Una vez que tenga las etiquetas base para sus características, puede decidir qué atributos quiere o puede recoger para cada característica. 


| Característica                           |  Clave                           | Valor                           |
|------------------------------------------------|------------------------------------------------| ------------------------------------------------|
|Edificio | building | residential, school, civic | 
| | building:material |  | 
| | building:levels | |
| | roof:material | |
|Puntos de suministro de aguas | amenity | water_point |
| | status |  |
|Carretera | highway | primary, secondary, residential |
| | name | |
| | condition | |
| | surface | |
| | width | |

A continuación, también se pueden determinar valores para cada clave de atributo. Estas opciones pueden ser determinadas usando el OSM Wiki y TagInfo, o en algunos casos pueden ser definidas por el mapeador - como para respuestas numéricas o nombres.


| Característica                           |  Clave                           | Valor                           |
|------------------------------------------------|------------------------------------------------| ------------------------------------------------|
|Edificio | building | residential, school, civic | 
| | building:material | cement_block, brick, wood, mud | 
| | building:levels | *numeric* |
| | roof:material | thatch, metal, concrete, plastic, tile |
|Puntos de suministro de agua | amenity | water_point |
| | drinking_water | yes, no |
|Carretera | highway | primary, secondary, residential |
| | name | *user defined* |
| | condition | excellent, good, poor |
| | surface | gravel, paved, dirt |
| | width | *numeric* |

Una vez completado el modelo de datos, las partes interesadas deberán comprobarlo para detectar posibles lagunas. Además, el plan del proyecto debe ser flexible para que este modelo de datos pueda ajustarse mediante pruebas sobre el terreno y consultas a los cartógrafos. 

**Recopilación de datos privados**
<br>
Los datos privados nunca deben cargarse en OSM. Sin embargo, algunos proyectos requieren que se recopile información personal. Cuando este es el caso, el modelo de datos puede incluir etiquetas únicas no OSM para los datos privados que deben ser recogidos. Al limpiar los datos después de la recogida, estos datos privados pueden mantenerse en un conjunto de datos completo antes de ser eliminados. Una vez eliminados los datos privados, el conjunto de datos puede cargarse en OSM.