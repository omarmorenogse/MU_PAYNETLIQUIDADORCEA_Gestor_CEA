
.. autosummary::
   :toctree: generated


5.	HEALTH CHECKER
=================

Health Checker es una solución diseñada y centralizada para proporcionar una visión completa y actualizada del estado real de los productos de Gse. Esta herramienta se encarga de monitorear y evaluar de manera continua el rendimiento, la disponibilidad y la integridad de los productos.

5.1	INICIO DE SESIÓN
----------------------------

•	Para acceder a la plataforma se debe iniciar sesión en https://estatus.gse.com.co/login
•	Para iniciar el proceso de ingreso, se utilizarán las credenciales de email y contraseña.
•	Una vez haya cargado la página, podrá visualizar un recuadro donde solicita ingresar las credenciales de usuario:


.. image:: ../images/1.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 1**. Login Aplicativo Web


**Importante:**


Al momento de ingresar sus credenciales se deben respetar las mayúsculas y minúsculas según haya sido creado para su usuario/contraseña. Además, podrá dar clic en el cuadro de “recuérdame”   para que el próximo inicio de sesión las credenciales se carguen automáticamente. 

•	Si las credenciales de usuario son correctas, al pulsar el botón “Iniciar sesión”, la aplicación le redirigirá hacia la vista de inicio obteniendo un resultado similar al siguiente:

.. image:: ../images/2.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 2**. Sección Home

**Importante:** Podrá visualizar la fecha y hora de la última actualización de los servicios ej. 

.. image:: ../images/3.png
   :width: 30%
   :alt: Ejemplo JSON de respuesta 


5.2	ESTADO PRODUCTO O SERVICIO
----------------------------

El sistema mostrará una vista general de todos los servicios GSE que están siendo monitoreados. Cada servicio tendrá un estado asignado, el cual puede ser uno de los siguientes:

•	Alive (En funcionamiento): El servicio está operativo y no presenta problemas.
•	Die (Caído): El servicio no está disponible y requiere atención.
•	Warning (Advertencia): El servicio está experimentando problemas potenciales que deben ser revisados.



.. image:: ../images/4.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 3**. Estado servicio

•	Podrá ingresar a cada producto o servicio y ver el estado de los diferentes módulos que tiene.

.. image:: ../images/5.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 4**. Estado detallado


5.2.1	Proceso de Monitoreo notificación 
****************************

Estado: Alive
Si el estado de un servicio es Alive, significa que el servicio está funcionando correctamente. No se requiere ninguna acción adicional. El proceso de monitoreo finaliza y puede continuar monitoreando otros servicios.

Estado: Die o Warning

Si el estado de un servicio es Die o Warning, el sistema tomará medidas automáticas:

•	Notificación automática: Se enviará un correo electrónico a los responsables de la gestión del servicio indicando que hay un problema, la notificación incluirá detalles sobre el servicio afectado y el tipo de problema Die o Warning.



.. image:: ../images/6.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 5**. Estado Warning

.. image:: ../images/6.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 6**. Estado Die

•	Deberá dar clic en el botón de "Verificar Estado del Servicio" para obtener más información y realizar una verificación manual del estado actual del servicio afectado.
•	Después de enviar la notificación y verificar el estado, el sistema regresará automáticamente a la página principal de Estado de Servicios GSE, donde podrá continuar revisando el estado de los servicios.


5.3	CAMBIO DE CONTRASEÑA
----------------------------

Si ha olvidado su contraseña deberá dirigirse a la sección de login en la opción 
"¿Olvidaste tu contraseña?"como se muestra a continuación:

.. image:: ../images/8.png
   :width: 40%
   :alt: Ejemplo JSON de respuesta 

**Imagen 7**. ¿Olvidaste tu contraseña?

Luego de hacer clic, será redireccionado a la siguiente sección, en esta deberá ingresar el correo electrónico asociado a los productos de GSE.

.. image:: ../images/9.png
   :width: 40%
   :alt: Ejemplo JSON de respuesta 

**Imagen 8**. Ingresar correo

Luego le llegara al correo el enlace para que establezca la nueva contraseña:


.. image:: ../images/10.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 9**. Correo enviado

.. image:: ../images/11.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 10**. Cuerpo del correo recibido

Deberá hacer clic en "Restablecer contraseña", lo cual lo redirigirá a una nueva ventana donde deberá crear una contraseña de mínimo 8 caracteres.

.. image:: ../images/12.png
   :width: 40%
   :alt: Ejemplo JSON de respuesta

**Imagen 11**. Nueva contraseña

Al dar clic en "Continuar", deberá aparecer un mensaje indicando que el cambio de contraseña fue exitoso.

.. image:: ../images/13.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 12**. Cambio de contraseña correctamente



5.4 BÚSQUEDA RÁPIDA
----------------------------

El sistema le permitirá hacer una “búsqueda rápida” donde podrá escribir por producto o servicio. 

.. image:: ../images/14.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 13**. Búsqueda rápida


5.5 CERRAR SESIÓN
----------------------------

Para un uso adecuado de la página, se solicita que, al terminar de consultar el estado de los servicios, cierre sesión. Al hacerlo, se mostrará la interfaz de inicio de sesión.

.. image:: ../images/14.png
   :width: 80%
   :alt: Ejemplo JSON de respuesta 

**Imagen 14**. Cerrar sesión

Para un uso adecuado de la página, se solicita que, al terminar de consultar el estado de los servicios, cierre sesión. Al hacerlo, se mostrará la interfaz de inicio de sesión.
