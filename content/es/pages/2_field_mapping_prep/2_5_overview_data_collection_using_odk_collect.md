---
title: 2.5 Configuración de OpenDataKit
bookShowToC: True
---

***Nota: Esta es una versión desactualizada del material de capacitación; se harán mejoras en el futuro.***

---

Esta sección proporciona:  

* Una visión general de los pasos necesarios para configurar ODK
* Una guía paso a paso para crear formularios de encuesta ODK, incluyendo archivos de ejemplo
* Una guía paso a paso para configurar ODK en dispositivos

<br>

## Descripción general 
**OpenDataKit (ODK)** es un conjunto de herramientas gratuitas y de código abierto que ayudan a las organizaciones a crear, desplegar y gestionar soluciones móviles de recogida de datos. ODK Collect forma parte de ODK y es una aplicación para Android que sustituye a los formularios en papel utilizados en la recopilación de datos basada en encuestas. Admite una amplia gama de tipos de preguntas y respuestas, y está diseñada para funcionar bien sin conectividad de red.

¿No está seguro de si OpenDataKit es adecuado para su proyecto? Revise [Aplicaciones de recopilación de datos](https://hotosm.github.io/toolbox/pages/data-collection-and-field-mapping/4.2-data-collection-applications/)._

## Recursos y materiales de formación
En esta sección se presenta una selección de recursos dirigidos a gestores de proyectos, formadores o incluso autodidactas sobre los temas mencionados anteriormente.

![](/images/learning_icon_wide.PNG)
* La siguiente sección está diseñada para servir de guía autodidacta a los jefes de proyecto, supervisores u otras personas en la configuración de la aplicación.

**Proceso de configuración**
Para configurar OpenDataKit para dispositivos, deberá seguir los siguientes pasos:

1. 1. [Crear formularios ODK](https://hotosm.github.io/toolbox/pages/data-collection-and-field-mapping/3.2.1_setting_up_odk/#creating-odk-forms)
1. 2. [Descargar y configurar la aplicación ODK](https://hotosm.github.io/toolbox/pages/data-collection-and-field-mapping/3.2.1_setting_up_odk/#download-and-set-up-the-odk-application)

### Creación de formularios ODK
Cuando utilice las aplicaciones de encuestas ODK y OMK, necesitará crear los archivos que servirán como formularios de la encuesta. 

Los formularios pueden crearse utilizando software de hoja de cálculo (como Excel o [LibreCalc](https://www.libreoffice.org/discover/calc/)) o utilizando el [ODK Form Builder](https://build.opendatakit.org/). La documentación sobre cómo diseñar un formulario se puede encontrar [aquí](http://xlsform.org/en/).

* [Ejemplo de formulario ODK](https://drive.google.com/file/d/1HY2jsHDYnpjuGemhco_WT9Cl8PSG4b43/view?usp=sharing)
* [Formulario ODK en blanco](https://drive.google.com/file/d/1ISEYZo5C_TCfKUJFD8AvbUrlsDHxRPgK/view?usp=sharing)

**Conversión de formularios** <br>
Una vez desarrollados los formularios, es necesario convertirlos de .xlsx/.xls a .xml para que puedan ser utilizados por la aplicación ODK. Esto se puede hacer utilizando [XLSform](https://docs.opendatakit.org/xlsform/) [online](https://opendatakit.org/xlsform/) o [offline](https://docs.opendatakit.org/xlsform/). <br>
<br>
Si utiliza el servidor OpenMapKit o el servidor KoboToolBox, no necesitará completar la conversión del formulario. El servidor completará este proceso por usted. 

## Descargar y configurar la aplicación ODK.

**Descargar la aplicación** <br>

La aplicación ODK se puede encontrar en Google Play [aquí](https://play.google.com/store/apps/details?id=org.odk.collect.android&hl=en_US). 

Si se instala en varios dispositivos con pocos recursos de Internet, se recomienda descargar y compartir el apk sin conexión. El archivo APK para OpenMapKit se puede descargar [aquí](https://github.com/opendatakit/collect/releases/tag/v1.16.1).

**Cómo configurar la aplicación en los dispositivos** <br>

1. Busca el icono de la app ODK Collect en tu dispositivo móvil y toca para abrir la app.
2. Después de descargar la aplicación ODK, se creará automáticamente una carpeta odk en la memoria interna del dispositivo. Conecta tu dispositivo a un ordenador portátil para confirmar que se ha creado esta carpeta. Si no ves esta carpeta en la memoria interna de tu dispositivo, Reinicia el dispositivo.
3. Una vez reiniciado el dispositivo, conéctelo a su ordenador portátil y vaya a almacenamiento interno -> carpeta odk. Encontrarás subcarpetas dentro de la carpeta openmapkit. Es decir, las carpetas 'forms', 'instances', 'layers' y 'metadata'.

![](/images/field-mapping-technical-setup/odk_set-up.jpeg)

4. Añade tus formularios xml a la carpeta forms.
5. En la ventana del menú principal de ODK Collect, seleccione Rellenar formulario en blanco. Esto mostrará todos los formularios descargados del servidor, que utilizará para las pruebas de recopilación de datos de campo.
6. Una vez que confirme que tiene todos los formularios en su dispositivo, haga clic en el botón Atrás del dispositivo para salir de la aplicación ODK Collect.