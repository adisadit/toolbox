---
title: 4.2 Uso de ODK Collect
bookShowToC: True
---

***Nota: Esta es una versión desactualizada del material de capacitación; se harán mejoras en el futuro.***

---

Esta guía proporciona **a los topógrafos, cartografistas y supervisores de campo** los conocimientos necesarios para:

* Completar la configuración inicial de ODK Collect 
* Utilizar ODK Collect para encuestas de recopilación de datos

<br>

## Descripción general
**Open Data Kit Collect (ODK Collect)** es una aplicación de recogida de datos en Android. ODK Collect puede reemplazar la encuesta de formulario de papel a digital. Por lo tanto, esta aplicación ayudará a las actividades de mapeo y recopilación de datos en el campo que también permiten guardar la ubicación y la información de la foto a la vez.

## Recursos y materiales de formación
En esta sección se presenta una selección de recursos dirigidos a gestores de proyectos, formadores o incluso autodidactas sobre el tema o los temas expuestos anteriormente.

![](/images/learning_icon_wide.PNG)
*La siguiente sección está diseñada para servir de guía autodidacta para gestores de proyectos, supervisores u otras personas en la configuración de la aplicación.

### Configuración inicial para ODK Collect

**1. Configurar el servidor URL** <br>
*Si no utiliza un servidor, vaya al paso 2. Establezca el tamaño de la imagen*

Para realizar la encuesta de formulario desde el servidor por primera vez, el usuario necesita configurar el servidor URL. Estos son los pasos:

* Abra ODK Collect y pulse el botón de tres puntos en la esquina superior derecha, seleccione **Configuración general → Servidor**.

![Opción para rellenar el menú de direcciones URL en ODK Collect](/images/using-odk-collect/0201_Option_to_fill_the_URL_address_menu_in_ODK_Collect.png)
<p align="center"><i>Opción para rellenar el menú de direcciones URL en ODK Collect</i><p align="center">


* Escribe la dirección URL del servidor en **URL → OK**.

![Paso para rellenar la dirección URL en ODK Collect](/images/using-odk-collect/0202_Step_to_fill_the_URL_address_in_ODK_Collect.png)
<p align="center"><i>Paso para rellenar la dirección URL en ODK Collect</i><p align="center">.


**2. Establecer el tamaño de la imagen**

Además del punto de localización, también puedes tomar una imagen como información adicional. Si va a recopilar imágenes como parte de sus encuestas de recopilación de datos, puede establecer la resolución de la imagen como desee. Sin embargo, la resolución de la imagen también afectará a la cantidad de memoria del teléfono o al archivo que se cargará posteriormente en el servidor. Se recomienda elegir la resolución más pequeña de la imagen durante la configuración inicial. Puede seguir este paso: 

* Abra ODK Collect y pulse el botón de tres puntos en la esquina superior derecha, seleccione **Configuración general → Gestión de formularios**.

![Menú de opciones para establecer la resolución de la imagen](/images/using-odk-collect/0203_Option_menu_to_set_image_resolution.png)
<p align="center"><i>Menú de opciones para ajustar la resolución de la imagen</i><p align="center">

* Seleccione **Tamaño de imagen** y luego seleccione la **opción **Muy pequeña (640px)**.

![Menú Tamaño de imagen para ajustar la resolución de la imagen](/images/using-odk-collect/0204_Image_size_menu_to_set_the_image_resolution.png)
<p align="center"><i>Menú de tamaño de imagen para establecer la resolución de la imagen</i><p align="center">


### ODK Collect operaciones básicas

**1. Cómo obtener una encuesta de formulario en blanco del servidor** <br>
*Si no utilizas un servidor y las encuestas se subieron manualmente al dispositivo, salta al paso 2. Rellene el formulario de la encuesta*

Antes de rellenar el formulario de encuesta que hizo antes, necesita descargar el formulario de encuesta en blanco del servidor especificado. Puede seguir este paso para obtener una encuesta en blanco del servidor:

* Pulse **Obtener formulario en blanco**, espere a que el formulario se descargue del servidor y asegúrese de que su conexión a Internet está activa.

![Obtener opciones de formulario en blanco para realizar un formulario en un servidor](/images/using-odk-collect/0205_Get_blank_form_options_to_take_form_on_a_server.png)
<p align="center"><i>Obtener opciones de formulario en blanco para tomar formulario en un servidor</i><p align="center">

* Seleccione el formulario disponible, marque la casilla de verificación o si desea seleccionar todo el formulario, puede **Seleccionar todo**. Si su formulario no aparece, puede pulsar **Refrescar** para recargar la página.

![Visualización de la página en el menú Obtener formulario en blanco](/images/using-odk-collect/0206_Page_display_on_Get_Blank_Form_menu.png)
<p align="center"><i>Visualización de página en el menú Obtener formulario en blanco</i><p align="center">

* Después de seleccionar el formulario, puede pulsar **Get Selected** para descargar el formulario seleccionado.

![](/images/using-odk-collect/0207_Page_display_on_the_Get_Blank_Form_to_get_the_survey_form.png)
<p align="center"><i>Page display on the Get Blank Form to get the survey form</i><p align="center">.


**2. Rellenar el formulario de la encuesta**
* Para rellenar el formulario, vuelva a la página de inicio y seleccione el menú **Rellenar formulario en blanco**. A continuación, seleccione un formulario en blanco que desee rellenar en la lista de formularios de encuesta.

![Opciones para rellenar el formulario de encuesta y lista de formularios en blanco](/images/using-odk-collect/0208_Fill_Blank_Form_options_for_filling_out_the_survey_form_and_blank_survey_form_list.png)
<p align="center"><i>Opciones del formulario en blanco para rellenar el formulario de encuesta y la lista de formularios de encuesta en blanco</i><p align="center">.


* Desliza el dedo hacia la derecha o hacia la izquierda en la pantalla para pasar a la página siguiente/anterior. Las preguntas que tienen una estrella roja en la parte superior izquierda son obligatorias y no se puede pasar a la siguiente pregunta si la respuesta está vacía.

![Ejemplos de pregunta obligatoria (estrella roja)](/images/using-odk-collect/0209_Examples_of_mandatory_question_red_star.png)
<p align="center"><i>Ejemplos de pregunta obligatoria (estrella roja)</i><p align="center">


* Puede tomar fotos directamente seleccionando la opción **Hacer foto** o seleccionar una foto de su galería de fotos seleccionando **_Elegir imagen_**.

![Tomar foto mostrar en ODK Form](/images/using-odk-collect/0210_Take_photo_display_in_ODK_Form.png)
<p align="center"><i>Visualización de la foto en el formulario ODK</i><p align="center">


* Para añadir puntos de localización de objetos incluyen etiqueta de objeto OSM, puede utilizar la aplicación adicional, que es OpenMapKit (OMK). Puedes cambiar inmediatamente a la aplicación OMK pulsando **Lanzar OpenMapKit** en el formulario. Puede obtener más información sobre el uso de la aplicación OMK en la sección [4.3 Uso de OpenMapKit](https://hotosm.github.io/toolbox/pages/field-mapping-management/4.3_using_openmapkit/). 

Botón [Lanzar OpenMapKit en el formulario de la encuesta](/images/using-odk-collect/0211_Launch_OpenMapKit_button_on_the_survey_form.png)
<p align="center"><i>Botón de lanzamiento de OpenMapKit en el formulario de la encuesta</i><p align="center">.


* Al final, puede asignar un nombre al formulario, marcar **Marcar formulario como finalizado** y al final elegir **Guardar formulario y salir** para finalizar la encuesta del formulario final.

![Finalización de las páginas vistas en el formulario de la encuesta](/images/using-odk-collect/0212_Finalization_of_page_views_on_the_survey_form.png)
<p align="center"><i>Finalización de páginas vistas en el formulario de encuesta</i><p align="center">


**3. Editar el formulario de encuesta completado**
El formulario guardado se guarda automáticamente en ODK Collect. (*Nota: no recomendamos editar los formularios recopilados a través de OpenMapKit debido a posibles errores en los datos.*) Si desea editar el formulario completado, puede seguir este paso:

* Puede volver a la página de inicio y elegir **Editar formulario guardado**.

![Editar formulario guardado para editar el formulario guardado](/images/using-odk-collect/0213_Edit_Saved_Form_for_edit_the_saved_form.png)
<p align="center"><i>Editar Formulario Guardado para editar el formulario guardado</i><p align="center">


* Seleccione el formulario que desea editar pulsando el formulario y puede editar el formulario.

![Editar página de formulario guardado para seleccionar el formulario que desea editar](/images/using-odk-collect/0214_Edit_save_form_page_to_select_the_form_that_you_want_to_edit.png)
<p align="center"><i>Edita la página de guardar formulario para seleccionar el formulario que quieres editar</i><p align="center">.


* A continuación, pulse el icono del disquete  

![Edite la página de guardar formulario para seleccionar el formulario que desea editar](/images/using-odk-collect/0215_A_completed_survey_form_and_icon_to_save_changes.png)
<p align="center"><i>Edita la página de guardar formulario para seleccionar el formulario que quieres editar</i><p align="center">


### Transferencia de formularios completados
Una vez finalizada la recogida de datos, será necesario transferir todos los formularios desde el dispositivo de recogida de datos a una ubicación de almacenamiento central para la limpieza y el procesamiento de los datos. 

**1. Descarga manual**

Si no tiene acceso a un servidor, los formularios pueden descargarse manualmente desde los dispositivos. Para ello, conecte el dispositivo a un ordenador. 

* Vaya al Administrador de archivos o al Explorador de archivos de su smartphone y abra el almacenamiento interno. A continuación, abra la carpeta ODK. Esta carpeta contiene todos los archivos de resultados de encuestas almacenados en la aplicación ODK Collect. A continuación, seleccione la carpeta "instances" que contiene los archivos de los resultados de la encuesta.

![Carpeta de instancias en la carpeta ODK y el resultado de la encuesta en la carpeta de instancias](/images/using-odk-collect/0222_Instances_folder_in_ODK_folder_and_the_survey_result_in_instances_folder.png)
<p align="center"><i>Carpeta instancias en carpeta ODK y el resultado de la encuesta en carpeta instancias</i><p align="center">.

* Copie la carpeta 'instances' en su ordenador. Renombra la carpeta por fecha y encuestador. 

**2. Suba los formularios de encuesta al servidor**

Después de rellenar y guardar el formulario, el siguiente paso es subir el formulario de encuesta al servidor.  Puede seguir estos pasos para subir el formulario al servidor:

* Para subir el formulario de vuelta al servidor, puede elegir **Enviar Formulario Finalizado**.

![Enviar Formulario Finalizado para subir un formulario de encuesta al servidor](/images/using-odk-collect/0216_Send_Finalized_Form_to_upload_a_survey_form_to_the_server.png)
<p align="center"><i>Enviar Formulario Finalizado para subir un formulario de encuesta al servidor</i><p align="center">


* La encuesta del formulario se guarda en esa página y está lista para enviar. Puede elegir **Seleccionar todo** para seleccionar primero todos los formularios. 
* Asegúrese de que está conectado a Internet. A continuación, pulse **Enviar seleccionados** y espere a que finalice el proceso_ de carga_ del formulario.

![Formularios de encuesta que están listos para enviar en el Formulario Enviar Finalizado](/images/using-odk-collect/0217_Survey_forms_that_are_ready_to_send_in_the_Send_Finalized_Form.png)
<p align="center"><i>Formularios de encuesta que están listos para enviar en el Formulario Enviar Finalizado</i><p align="center">


* Todos los formularios que se hayan cargado correctamente se almacenarán en el menú **Ver formulario enviado** y el icono se volverá verde.

![Ver formulario enviado y formulario de encuesta que se han cargado con éxito en el servidor](/images/using-odk-collect/0218_View_Sent_Form_and_survey_form_that_have_been_successfully_uploaded_to_the_server.png)
<p align="center"><i>Ver formulario enviado y formulario de encuesta que se han subido correctamente al servidor</i><p align="center">


* Después de subir el formulario, puede eliminar el formulario en **_Eliminar formulario guardado _**menú.

![Eliminar formulario guardado menú para eliminar el formulario](/images/using-odk-collect/0219_Delete_Saved_Form_menu_for_delete_the_form.png)
<p align="center"><i>Eliminar formulario guardado menú para eliminar el formulario</i><p align="center">


* Puede eliminar el formulario rellenado en la opción **Formularios guardados** y eliminar el formulario en blanco en la opción **Formularios en blanco**. Debe elegir el formulario que desea eliminar o **Seleccionar todo** para eliminar todos los formularios.

![Eliminar formulario guardado](/images/using-odk-collect/0220_Delete_Saved_Form_option.png)
<p align="center"><i>Opción Eliminar Formulario Guardado</i><p align="center">


* Debe confirmar la eliminación del formulario de encuesta seleccionando **Borrar formularios**.

![Cuadro de diálogo de confirmación de eliminación](/images/using-odk-collect/0221_Delete_confirmation_dialog_box.png)
<p align="center"><i>Borrar cuadro de diálogo de confirmación</i><p align="center">.


**3. Subir el formulario de la encuesta a Google Drive**

Después de cargar todo el formulario de la encuesta en el servidor, es posible que desee guardar y cargar el archivo de resultados de la encuesta en formato .zip en la carpeta de Google Drive que fue creada por su supervisor de mapeo. Este es el paso:

* Vaya al Administrador de archivos o al Explorador de archivos de su smartphone y abra el almacenamiento interno. A continuación, abra la carpeta ODK. Esta carpeta contiene todos los archivos de resultados de encuestas almacenados en la aplicación ODK Collect. A continuación, seleccione la carpeta "instances" que contiene los archivos de los resultados de la encuesta.

![Carpeta de instancias en la carpeta ODK y el resultado de la encuesta en la carpeta de instancias](/images/using-odk-collect/0222_Instances_folder_in_ODK_folder_and_the_survey_result_in_instances_folder.png)
<p align="center"><i>Carpeta de instancias en la carpeta ODK y el resultado de la encuesta en la carpeta de instancias</i><p align="center">.


* Antes de mover la carpeta **instances** a tu ordenador, necesitas convertir la carpeta a formato .zip pulsando la carpeta **instances** y seleccionando **Compress**. Puedes cambiar el nombre del archivo .zip.

![El paso para convertir a formato .zip](/images/using-odk-collect/0223_The_step_for_convert_to_zip_format.png)
<p align="center"><i>El paso para convertir a formato .zip</i><p align="center">


* Después de mover el archivo .zip a su ordenador, puede subir el archivo a Google Drive que ya se ha establecido por su supervisor de mapeo.

![El archivo .zip listo para mover al ordenador](/images/using-odk-collect/0224_The_zip_file_that_ready_to_move_to_computer.png)
<p align="center"><i>El archivo .zip que listo para mover a la computadora</i><p align="center">


* Puedes subir el archivo a la carpeta Survey Result (u otro nombre que haya puesto tu supervisor de mapeo) haciendo clic con el botón derecho del ratón y luego eligiendo **Upload Files** y eligiendo el archivo que quieres subir.

![La carpeta de Google Drive para subir el archivo .zip](/images/using-odk-collect/0225_The_folder_on_Google_Drive_for_upload_zip_file.png)
<p align="center"><i>La carpeta en Google Drive para subir el archivo .zip</i><p align="center">