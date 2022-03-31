=============
Administrador
=============

Distribución del Menú
=====================
.. _graficote:
Cómo primer punto, se va a encontrar la interfaz principal, la cual es
el **panel de control**, esta se visualizara automaticamente al iniciar
sesion en la plataforma.

.. figure:: /images/index-administrador.png
   :alt: image0

Chat de ayuda
-------------

Al ingresar a la plataforma nos mostrará un icono para utilizar el chat
de ayuda que se encuentra del lado inferior derecho de la pantalla.

.. image:: /images/icono-chat.png
   :width: 150px
   :alt: chat
   :align: center  

   
Si se selecciona la opción de ayuda, nos mostrará un chat donde el
usuario podrá interactuar con soporte técnico para dudas, aclaraciones o
problemas con la plataforma, para iniciar chat se deberá seleccionar la
opción de *“Nueva conversación”*, o bien seleccionar el campo de *Buscar
respuestas* para verificar si esa pregunta ya se había realizado con
anterioridad.  


.. image:: /images/chat.png
   :width: 230px
   :alt: chat
   :align: center  

Tenemos del lado izquiero el menú principal, el cuál se conforma por la
sección **Panel de control**, **Usuarios**, **Alumnos**, **Sede**,
**Control escolar**, **Pagos**, **Aplicación**, **Académicos**,
**Desarrollo**.

Menú Superior
-------------

.. figure:: /images/dashboard-administrador.png
   :alt: 

1. **Home:** Muestra el tipo de moneda que se está manejando, en este
   caso MXN son pesos mexicanos, así mismo el icono *home* tiene la
   función de regresar a la pantalla principal.
2. **Notificación:** Muestra las notificaciones pendientes.
3. **Usuario:** Muestra el nombre de usuario con el que se inició la
   sesión y el nombre de la Sede, en este caso *PRUEBAS*, al seleccionar
   el nombre del usuario nos desglosará un menú con estas opciones:

.. image:: /images/opcionesdeperfil-ce.png   
   :width: 200px
   :alt: alternate text
   :align: center  

.. _perfilusuario:
| Si seleccionamos cualquiera de las dos primeras opciones, ya sea,
  *Perfil ó Configuración* nos mostrará un formulario tanto para
  modificar el nombre y datos del usuario así cómo su contraseña.

.. figure:: /images/configuracion-usuario-admin.png
   :alt: 

Panel de control
================

Cómo se mencionó anteriormente, el panel de control es la vista
principal que se nos presenta al iniciar sesión en nuestro usuario, por
lo que se explicará cada sección:

.. figure:: /images/interfaz-admin.png
   :alt: image6

1. Conciliaciones pendientes
----------------------------
Muestra el número de pagos pendientes a conciliar, los datos se reflejan en :ref:`esta tabla <#conciliaciones-pendientes-1>`.

2. Conciliaciones realizadas
----------------------------

| Se mostrará el total de conciliaciones realizadas,al hacer click en
  “*Historial*” nos mostrará la siguiente tabla:

.. _historialconciliacion:

Historial de conciliaciones
~~~~~~~~~~~~~~~~~~~~~~~~~~~

| Cómo su nombre lo indica, mostrará una tabla con el historial de
  conciliaciones realizadas, en esta se podrá ver desde el folio,
  sede,concepto,fecha de conciliación,etc. 
  
 .. image:: /images/historial-conciliaciones-adm.png
    :width: 100%
    :alt: alternate text
    :align: center  

.. _conceptos:  

1. Concepto
~~~~~~~~~~~

| Al hacer clic sobre algún concepto, abrirá otra ventana con
  información más específica cómo, datos de conciliación, pagos adjuntos
  y acciones del administrador. A continuación se explicará cada sección
  a detalle:

1.1 Conciliación
~~~~~~~~~~~~~~~~

| Se muestra el nombre de la Sede, Fecha de creación,Periodo,Recaudación
  total tanto de materias cómo de requerimientos,elementos ó número de
  pagos, requerimientos y la rentabilidad.

.. image:: /images/conciliacion-admin.png
   :width: 100%
   :alt: alternate text
   :align: center  

| También podemos ver una tabla de la distribución del total de la
  rentabilidad, indicandonos el monto, notaremos que tenemos la opción
  de **Permitir Sede**, esto quiere decir que podemos ocultar o mostrar
  cierto concepto a las sedes con tan solo seleccionar *Mostrar* u
  *Ocultar* con un clic. Así mismo tenemos la opción de búsqueda dónde
  podremos realizar búsquedas tanto por nombre de concepto, cómo por
  monto y mostrados u ocultos, así como podemos imprimir o guardar esta
  información en cualquiera de los formatos que se muestran, cómo CSV,
  Excel o PDF.  

.. figure:: /images/distribucion-rentabilidad.png
   :alt:

1.2 Pagos adjuntos
~~~~~~~~~~~~~~~~~~

| Se muestra la lista de los pagos realizados por los alumnos, también
  tendremos la opción de imprimir o guardar la lista de pagos.  
  
.. image:: /images/pagos-adjuntos1.png
   :width: 100%
   :alt: alternate text
   :align: center  

| Podremos visualizar información específica del pago y del alumno,
  desde el monto, cantidad de pagos, matrícula y nombre del alumno,
  fechas y comprobantes hasta conceptos de pago.  

.. image:: /images/pagos-adjuntos-tabla1.png
   :width: 100%
   :alt: alternate text
   :align: center  

.. figure:: /images/pagos-adjuntos-tabla2.png
   :alt:  

Al hacer clic sobre cualquier nombre del alumno en la columna *Alumno*,
nos dirigirá a otra vista con la información general del alumno.

.. _infoalumno:
                                                              
1.2.1 Información de alumno
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Se divide en 3 secciones, la primera es la información escolar del
alumno, en que sede se encuentra, nombre, matrícula,carrera, el último
pago que realizó y su grupo. Únicamente los campos marcados en verde son
modificables, si se altera alguno de los datos, para guardalos se deberá
presionar el botón *Guardar*.

.. image:: /images/informacion-alumno-admin.png
   :width: 70%
   :alt: alternate text
   :align: center  

1.2.2 Comentarios y acciones  
~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

| La segunda sección es la de comentarios y acciones, en el área de
  *Comentarios* se puede agregar alguna nota para un alumno en
  específico y en *Acciones* veremos que tenemos varias opciones cómo se
  explicará a continuación:

.. image:: /images/comentarios-acciones-admin.png
   :width: 100%
   :alt: alternate text
   :align: center  

.. _credencial:  

1.2.2.1 Credencial de estudiante
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

Si la credencial ya fue previamente **pagada** nos dará la posibilidad de subir la foto del alumno, al posicionar el cursor sobre la leyenda **1. Seleccione la separación** nos aparecerá una pequeña descripción 
*Indica la cantidad de caracteres del título (El nombre del alumno) de la carrera para partir el texto en dos lineas*, en este caso su valor es de **40**.  

Al seleccionar la opción de **Seleccionar archivo** nos abrirá una ventana para elegir la foto del alumno correspondiente, de preferencia las dimensiones 
de la foto deben ser de **250 x 300**:

.. image:: /images/credencial1.png
   :width: 500px
   :alt: credencial
   :align: center  

Posteriormente nos mostrará una tabla con los pagos de credencial realizados, al hacer clic en la columna **Validez** vigente nos abrirá la siguiente vista:  

.. image:: /images/credencial2.png
   :alt: image52  

.. image:: /images/validezcredencial.png
   :width: 600px
   :alt: credencial
   :align: center  

Pos último del lado derecho nos mostrará la vista previa de cómo quedaría el diseño de la credencial:

.. image:: /images/credencial3.png
   :width: 300px
   :alt: texto
   :align: center  


| En la parte superior tendremos dos opciones:

.. image:: /images/credencial4.png
   :alt: alternate text
   :align: center  


| - *Remanofacturar*: Al seleccionar ésta opción, la vista previa cambiará su apariencia con la foto que hayamos seleccionado.  

.. image:: /images/remanofacturar.png
   :width: 500px
   :alt: texto
   :align: center

| - *Descargar*: Nos descargará la credencial en formato PNG de imágen con los cambios realizados.  

.. image:: /images/credencialconfoto.png
   :width: 500px
   :alt: texto
   :align: center  


1.2.2.1.1 Pago de credencial de estudiante
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

En caso de que el alumno aún no haya realizado el pago, la vista que nos mostrará al seleccionar :ref:`Credencial de estudiante <#credencial>` será la siguiente:  

.. image:: /images/credencialsinpago.png
   :width: 100%
   :alt: texto
   :align: center 

Al seleccionar el botón verde **Subir pago de credencial** nos dirigirá a un formulario el cuál se debe llenar con forme a los datos requeridos:  
De lado izquierdo ingresaremos el *monto,descuento (en caso de que haya uno),fecha, folio y nota:   

.. image:: /images/nuevopagocredencial.png
   :width: 100%
   :alt: texto
   :align: center  

De lado derecho tendremos que *subir el comprobante del pago (en caso de que haya alguno), elegir el método de pago, el tipo de pago, y el concepto*:   

.. image:: /images/nuevopagocredencial2.png
   :width: 100%
   :alt: texto
   :align: center  

Después de haber llenado el formulario correctamente, seleccionaremos el botón **Guardar** y nos dirigirá a la sección de la *Información del alumno* 
donde se nos reflejará el pago en la parte inferior de la página :ref:`estados de pago <#estados>`.  
Una vez realizado el pago, se puede continuar con :ref:`esta parte <#credencial>`.  

1.2.2.2 Planes de pago
~~~~~~~~~~~~~~~~~~~~~~  

.. image:: /images/planes-pago-admin.png
   :width: 500px
   :alt: alternate text
   :align: center  


   
   Seleccionamos esa opción y nos mostrara los planes locales
   del alumno, si hacemos clic sobre *Seleccionar plan de pagos* nos
   desglosará una lista de plan de pagos, donde se eligirá la que el
   usuario considere conveniente, posteriormente al elegir el plan,
   seleccionamos la opción de **Añadir Plan**. 
   
.. image:: /images/planes-pago-lista.png
   :width: 100%
   :alt: alternate text
   :align: center

| En caso de que en la lista de planes desglosada no se encuentre el
  plan adecuado, se puede generar uno seleccionando:

.. image:: /images/elaborarplan.png
   :width: 300px
   :alt: alternate text
   :align: center  

.. image:: /images/nuevoplandepagos.png
   :width: 100%
   :alt: alternate text
   :align: center  

| Seleccionamos el tipo de **concepto** que vamos a agregar.   

.. image:: /images/conceptonuevoplan.png
   :width: 350px
   :alt: alternate text
   :align: center  

Una vez completados los datos requeridos seleccionamos el botón de **CREAR PLAN DE PAGO** y notaremos que en la parte inferior se mostrará el plan agregado dentro de la misma ventana. En la parte superior se visualiza el plan de pagos del alumno y sus abonos realizados , tanto los pagados cómo los pendientes.  

.. image:: /images/plan-local.png
   :width: 100%
   :alt: alternate text
   :align: center  

1 . Notaremos que en la parte superior derecha se encuentran las
opciones *Eliminar / Imprimir*, si seleccionamos *Imprimir* nos
descargará la información del estado de cuenta que estamos visualizando
pero en formato PDF de la siguiente manera:  

.. figure:: /images/estado-cuenta.png
   :alt: image22

2 . Se puede agregar la fecha de inicio y la periodicidad del día en el
que se estará haciendo el cobro de colegiatura, si se hace clic sobre la
opcion Nº 2 se mostrará una ventana de ayuda cómo la siguiente:

.. image:: /images/cada.png
   :width: 350px
   :align: center
   :alt: image23

3 . Se muestra el porcentaje obtenido en caso de que se cuente con una
beca, de igual manera si se selecciona esa opcion mostrará una ventana
de ayuda cómo la siguiente:  

.. image:: /images/cada.png
   :width: 350px
   :align: center
   :alt: image24

4 . En caso de que se hayan modificado los datos de periodicidad, para
guardar los cambios se seleccionará el botón *Actualizar*.

1.2.2.3 Eliminar  
~~~~~~~~~~~~~~~~

Nos dá dos opciones para eliminar.

.. _estados:  
1.2.3 Estados de pago  
~~~~~~~~~~~~~~~~~~~~~  

En la última columna de la tabla se visualizará el estado del pago según el color que corresponda: 

.. image:: /images/estadosdelpago.png
   :width: 100%
   :alt: alternate text
   :align: center  

| A continuación se muestran las columnas sobre las cuales se puede modificar los datos:  

.. image:: /images/estadosdelpago-admin.png
   :width: 100%
   :alt: alternate text
   :align: center  

| 1. **Plan** Se muestra en color negro, ya que ya hay un plan asignado,
  en caso que no hubiera , éste seria color naranja.
| 2. **Comprobante** En caso de que no se haya subido un recibo de pago,
  se podrá hacer dando doble clic sobre la leyenda *Sin comprobante*,
  inmediatamente aparecerá un botón llamado **Seleccionar archivo** para
  adjuntar el recibo. En este caso si existe un comprobante, al darle
  clic en **Ver comprobante** y nos mostrará la siguiente imagen:

.. image:: /images/comprobante-ingreso-admin.png
   :width: 100%
   :alt: alternate text
   :align: center  

| 3.\ **Concepto/Nota:** Al hacer clic sobre esta opción desglosará una
  ventana con el concepto que se le asignó al pago (*No es
  modificable*).

.. image:: /images/concepto-pago-ce.png
   :width: 350px
   :alt: alternate text
   :align: center  

| 4. **Generar recibo de pago** Al hacer clic nos descargará el recibo
  del pago seleccionado en formato PDF:

.. image:: /images/recibo-pago.png
   :width: 100%
   :alt: alternate text
   :align: center  

| **NOTA** Si hacemos clic sobre el URL o escaneamos el código QR nos
  enviará a una liga con la información del recibo anterior donde se
  podrán ingresar datos del alumno para solicitar facturación,en la
  parte inferior tenemos dos opciones, la primera es el botón para
  *Solicitar facturación* si el alumno así lo requiere ó la opción de
  *Hablar con mi asesor de sede* la cuál dirigirá al alumno al correo
  institucional. 
  
.. image:: /images/factura-uno.png
   :width: 100%
   :alt: alternate text
   :align: center  

| **Facturación y aclaración:**

.. image:: /images/factura-dos.png
   :width: 100%
   :alt: alternate text
   :align: center  

| 5.\ **Devolver:** Solamente aparecerá esta opción si el pago no se ha
  conciliado, al seleccionar esta opción aparecerá la siguiente ventana
  indicando la leyenda siguiente:

.. image:: /images/devolucion.png
   :width: 350px
   :alt: alternate text
   :align: center

| 6.\ **Estado** Cómo se puede observar está marcado en color *Verde* lo
  que quiere decir que este pago ya ha sido conciliado y no se pueden
  realizar modificaciones.

1.3 Acciones de administrador
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

2. Acciones
~~~~~~~~~~~

Al hacer clic en **Detalles de la conciliación** nos mostrará la misma
información que en la columna de :ref:`Conceptos <#conceptos>`.

.. _facturaspendientes: 

3. Facturas pendientes
----------------------

.. figure:: /images/solicitud-facturas.png
   :alt: image26

1. Detalles
~~~~~~~~~~~

| Muestra información general del alumno, tanto escolar cómo datos
  personales y acerca de su facturación e historial de pagos:  

.. image:: /images/informacion-alumno-detallada.png
   :width: 100%
   :alt: alternate text
   :align: center  

.. image:: /images/informacion-alumno-detallada2.png
   :width: 100%
   :alt: alternate text
   :align: center  

1.1 Información detallada del alumno
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

| En esta primer sección nos muestra datos del alumno, cómo se mencionó
  en anteriormente, sólo los campos marcados en color verde pueden
  modificarse.  

.. image:: /images/info-parte1.png
   :width: 500px
   :alt: alternate text
   :align: center  

| 1. Al hacer clic en el sobre nos dirigirá a otra pestaña en
  el navegador, para enviar un e-mail al alumno, la vista será cómo
  esta:  

.. image:: /images/info-parte1-mail.png
   :width: 500px
   :alt: alternate text
   :align: center  

| 2. Desglosará una lista de sedes en donde se seleccionará la
  correspondiente.  
  
.. image:: /images/info-parte2.png
   :width: 400px
   :alt: alternate text
   :align: center  

| En la parte derecha se mostrará los datos cómo CURP, fecha de
  nacimiento,así cómo también fecha de registro, periodo, etc.  

.. image:: /images/info-parte3.png
   :width: 100%
   :alt: alternate text
   :align: center  

.. _programaseducativos:  

1.1.1 Programas educativos  
~~~~~~~~~~~~~~~~~~~~~~~~~~

| 1. Posteriormente está la parte de *Programas educativos* al dar clic
  en **Inspeccionar** nos dirigirá a una sección donde nos dará la
  opción de agregar *Materias*, *Generar un Kardex* y *Mostrar las
  materias agregadas*.  

.. _materias:
1.1.1.1 Añadir materias 
~~~~~~~~~~~~~~~~~~~~~~

Esta sección es para agregar materias al alumno para crear un kardex de calificaciones.  
  
.. image:: /images/agregar-materia-ce.png
   :width: 100%
   :alt: alternate text
   :align: center  

| Se deberá seleccionar la materia de la lista, el periodo y finalmente
  insertar la calificación correspondiente, para finalizar se selecciona
  el botón naranja **Añadir materias**.  

.. image:: /images/lista-materias.png
   :width: 400px
   :alt: alternate text
   :align: center  

| Las materias añadidas se mostrarán en una tabla en la parte superior
  de la :ref:`siguiente manera <#tablamaterias>`.

1.1.1.2 Kardex
~~~~~~~~~~~~~~

| También se puede generar un documento de Kardex con las materias
  aprobadas disponibles, en caso de que existan materias.  

.. image:: /images/kardex-materias.png
   :width: 100%
   :alt: alternate text
   :align: center  

| 1.Se seleccionan las materias que aparecerán en el kardex.
| 2.Se introduce la fecha de expedición si se requiere modificar.  

.. image:: /images/kardex-materias2.png
   :width: 100%
   :alt: alternate text
   :align: center  

| 3.Por último se selecciona el botón de *Generar documento*.  

.. image:: /images/kardexp1.png
   :width: 500px
   :alt: alternate text
   :align: center  

.. image:: /images/kardexp2.png
   :width: 500px
   :alt: alternate text
   :align: center  


| 2.En la parte superior de `Programas educativos <#programaseducativos>`__,
  tendremos la opción **Agregar**, la cuál al hacer clic nos desglosará
  una liste de programas educativos para agregar al alumno:  

.. image:: /images/programaseducativoslista.png
   :width: 350px
   :alt: alternate text
   :align: center  

| Se seleccionará un programa de la lista y se dará clic sobre el botón
  *Agregar programa*, notaremos que aparecerá en la lista de programas
  del alumno.   
  
.. image:: /images/agregarprograma.png
   :width: 350px
   :alt: alternate text
   :align: center  

.. image:: /images/programaseducativosagregados.png
   :width: 500px
   :alt: alternate text
   :align: center  

| En la parte superior de la información del alumno también tendremos la
  opción de modificar o agregar el estado en que se encuentra el alumno
  en una lista, pago o grupo:  

.. image:: /images/estado-pago-grupo.png
   :width: 500px
   :alt: alternate text
   :align: center  

| Se selecciona el tipo de estado y para guardar los cambios
  seleccionamos el botón *Guardar*.  

.. image:: /images/estado-alumno.png
   :width: 400px
   :alt: alternate text
   :align: center  

.. _tablamaterias:
1.1.1.3 Materias  
~~~~~~~~~~~~~~~~  

.. image:: /images/tablamaterias.png
   :width: 100%
   :alt: alternate text
   :align: center  

| En la columna de **Calificación** tenemos la opción de modificarla
  dandole clic sobre la calificación, nos aparecerá la siguiente
  ventana, donde podremos modificar tanto la calificación cómo el
  periodo ó tipo de reprobatoria en caso que se requiera:  

.. image:: /images/editarcalificacion-adm.png
   :width: 350px
   :alt: alternate text
   :align: center  

| En la columna **Eliminar** en caso que se deseé eliminar la materia,
  aparecerá la siguiente ventana.  

.. image:: /images/eliminarmateria.png
   :width: 350px
   :alt: alternate text
   :align: center  

1.2 Puntos
~~~~~~~~~~

.. image:: /images/puntos.png
   :width: 100%
   :alt: alternate text
   :align: center  

| **1.** Se inserta la cantidad de puntos que se desea agregar.
| **2.** En caso de que los puntos se resten se marca esta casilla.
| **3.** Para añadir el puntaje, seleccionar ese botón.
| **4.** Para ver el historial de los puntos insertados se selecciona
  ésta opción y nos muestra la siguiente tabla indicando el nombre del
  usuario que los insertó, la cantidad, matricula del alumno al que se
  le agregaron los puntos y la fecha, así mismo tenemos la opción de
  búsqueda:  

.. image:: /images/historialpuntos.png
   :width: 100%
   :alt: alternate text
   :align: center  

1.3 Comentarios y acciones
~~~~~~~~~~~~~~~~~~~~~~~~~~  
1.3.1 Comentarios
~~~~~~~~~~~~~~~~~  

Esta sección tiene un área para escribir algún comentario y al presionar
el botón verde se mostrará en la parte superior.

.. image:: /images/comentarios1-admin.png
   :width: 500px
   :align: center  
   :alt: image48

El comentario insertado se mostrará de la siguiente manera:

.. image:: /images/comentarios2-admin.png
   :width: 500px
   :alt: 49
   :align: center  

.. _acciones-1:

1.3.2 Acciones
~~~~~~~~~~~~~~

Esta sección tiene distintas opciones para manipular los datos escolares
del alumno, se irá especificando cada una de acuerdo al número que le
corresponga:

.. image:: /images/acciones-admin.png
   :width: 500px
   :alt: acciones
   :align: center

1.3.2.1 Credencial del estudiante
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

Esta información fue previamente explicada en :ref:`esta sección <#credencial>`.

.. _informacionadicional:  

1.3.2.2 Editar información adicional
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Esta opción nos mostrará un formulario para introducir información
personal, laboral y escolar más específica del alumno. Al terminar el
correcto llenado de los campos seleccionar el botón *Actualizar* en caso
que se quieran conservar los cambios.

.. figure:: /images/informacion-adicional-estatal-ce.png
   :alt: image55  

1.3.2.3 Materias
~~~~~~~~~~~~~~~~

Esta sección es para agregar materias al alumno y para crear un kardex
de calificaciones, ésta opción ya fue previamente explicada en :ref:`esta sección <#materias>`.

1.3.2.4 Datos académicos
~~~~~~~~~~~~~~~~~~~~~~

En caso de que el alumno se registre para maestría o licenciatura se
deberá llenar los campos de la fecha de antecedente y el número de
cédula profesional. En el área de **Grado de estudios** se eligirá
*Posgrado* ó *Licenciatura*.

.. figure:: /images/datos-academicos-admin.png
   :alt: image56

En la parte inferior hay un apartado para subir los documentos oficiales
del alumno que requiera la institución, tales cómo: CURP, acta de
nacimiento, etc. Se pueden subir dando clic sobre la flecha ó
arrastrando los archivos con el mouse, del equipo al area marcada.

.. figure:: /images/documentos-estatal.png
   :alt: image57  


   Notaremos que hay 3 opciones del proceso de validación:  

| **1. En validación:** significa que está en validación, es decir, aún
  está en espera de revisión por el personal institucional.
| **2. Necesita correción:** Una vez revisado cada documento la marca
  cambiará a éste color si se tiene que modificar algún documento.
| **3. Válidado:** Quiere decir que ya están correctos y/o validados.  

.. image:: /images/documentos-estatal1.png
   :width: 100%
   :alt: alternate text
   :align: center  
.. image:: /images/documentos-estatal2.png
   :width: 100%
   :alt: alternate text
   :align: center  


| **1.** Cada documento tendrá una flecha al lado derecho del título, la
  cuál al seleccionarla desglosará una lista para elegir el nombre
  estándar que debe llevar cada uno.
| **2.** De igual manera notaremos que del lado superior derecho tendrá
  una marca color **naranja** por lo que indica que necesita corrección.

1.3.2.5 Planes de pago
~~~~~~~~~~~~~~~~~~~~~~  

| Seleccionamos esa opción y nos mostrara los planes locales del alumno
  generados por el usuario SEDE. Se visualizará el plan de pagos del
  alumno y sus abonos realizados , tanto los pagados cómo los
  pendientes, siempre se mostrará un plan de pago por defecto, cómo el
  siguiente:   

.. image:: /images/plan-defecto.png
   :width: 100%
   :alt: alternate text
   :align: center   

Para crear un nuevo plan se selecciona el que se requiera de la lista de
*Plan de pagos* y elegimos el botón de *Añadir plan*.  

.. figure:: /images/planes-pago.png
   :alt: image61  

En caso de que en la lista de planes desglosada no se encuentre el plan
adecuado, se puede generar uno seleccionando:  

.. figure:: /images/nuevo-plan-admin.png
   :alt: image62  

Seleccionamos el tipo de **concepto** que vamos a agregar.  

.. image:: /images/concepto-pago-admin.png
   :width: 350px
   :alt: 61
   :align: center  

Una vez completados los datos requeridos seleccionamos el botón de
**CREAR PLAN DE PAGO** y notaremos que en la parte inferior se mostrará
el plan agregado dentro de la misma ventana. En la parte sueprior se
visualiza el plan de pagos del alumno y sus abonos realizados , tanto
los pagados cómo los pendientes.  

.. figure:: /images/plan-local-plazos.png
   :alt: image62

**1. Eliminar/Imprimir**: Al seleccionar \*Imprimir nos descargará la
información del estado de cuenta que estamos visualizando pero en
formato PDF de la siguiente manera:  

.. figure:: /images/estado-cuenta-admin.png
   :alt: image63  

**2. Fecha de inicio**: Se puede modificar la fecha dando clic sobre
ella y así nos dará la posibilidad de elegir la fecha que se requiera.  

**3. Cada(periodo)**: Se añade el día ó periodicidad en el que se estará
haciendo el cobro de colegiatura haciendo doble clic sobre la palabra
*Mes*, al seleccionar el signo **?** nos mostrará una ventana de ayuda
como la siguiente:   

.. image:: /images/cada.png
   :width: 350px
   :alt: 63
   :align: center  

**4. Beca**: Se muestra el porcentaje obtenido en caso de que se cuente
con una beca, para agregar un nuevo porcentaje se tendrá que hacer doble
clic sobre **0%**, de igual manera si se selecciona esa opcion mostrará
una ventana de ayuda cómo la siguiente:  

.. image:: /images/beca.png
   :width: 350px
   :alt: 64
   :align: center

**5. Detener plan**:   

1.3.2.6 Eliminar  
~~~~~~~~~~~~~~~~  

En ésta sección tendremos dos botones *Eliminar del sistema* y *Eliminar
alumno*.  

1.4 Datos académicos(documentación)  
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

.. figure:: /images/datos-academicos-info.png
   :alt: image65  

1.5 Información adicional
~~~~~~~~~~~~~~~~~~~~~~~~~  

Se muestran los datos insertados en la sección de **Acciones**\ `/Editar
información adicional <#informacionadicional>`, en este caso aquí ya
no son modificables.  

.. figure:: /images/informacion-adiciona-info.png
   :alt: image66  

1.6 Facturación
~~~~~~~~~~~~~~~  

En caso de que se haya solicitado facturación al realizar un pago, se
mostrará la información introducida en el recibo de pago:  

.. figure:: /images/datos-factura.png
   :alt: image67

Los datos generales mostrados aquí ya no son modificables en ésta
sección.  

.. figure:: /images/facturacion-admin.png
   :alt: image68  

1.7 Estados de pagos  
~~~~~~~~~~~~~~~~~~~~    

Cómo última sección del área de *Facturas pendientes* se encuentran los
estados de pagos que ya han sido explicados en :ref:`esta parte <#estados>`.   

2. Solicitud  
~~~~~~~~~~~~   

Al seleccionar la opción de **Ver solicitud** nos abrirá una nueva
ventana mostrandonos la información del recibo de facturación
solicitado, estos datos no son modificables:   

.. image:: /images/factura1.png
   :width: 500px
   :alt: alternate text
   :align: center  

.. image:: /images/factura2.png
   :width: 500px
   :alt: alternate text
   :align: center  

.. _acciones-2:

3. Acciones
~~~~~~~~~~~  

.. image:: /images/marcarnoentregada.png
   :width: auto
   :alt: alternate text
   :align: center

NOTAS
-----

CREAR NUEVO
-----------  

4. Obligaciones crediticias
---------------------------  

.. image:: /images/obligaciones-crediticias.png
   :width: 500px
   :alt: alternate text
   :align: center   

.. image:: /images/deuda-alumno1.png
   :width: 100%
   :alt: alternate text
   :align: center  

.. image:: /images/deuda-alumno2.png
   :width: 100%
   :alt: alternate text
   :align: center  

5. Barra de ingresos
--------------------  

Se muestran los ingresos totales obtenidos por Sedes en el mes que nos
encontremos en una barra de porcentaje, en éste caso Marzo.

.. image:: /images/ingresos.png
   :width: 500px
   :alt: ingresos
   :align: center

6. Pagos recibidos
------------------  

.. figure:: /images/pagos-recibidos.png
   :alt: image75

.. _conciliaciones-pendientes-1:

7. Conciliaciones pendientes
----------------------------  

Muestra en color naranja (link) las que ya estan conciliadas desde sedes, las conciliaciones pasan por el robot cada 5 minutos, si hay unas que falten compilar, las intenta compilar, si lo hace con éxito el concepto se pondrá en color naranja, si no, seguirá mostrándose de color negro, **FEBRERO 2022** se ha intentado compilar,es por eso que en la columna **Compilando** está en estado *Compilando* pero no fue posible ya que la terminología es menor a el número de pagos.

.. image:: /images/conciliaciones-pendientes.png
   :width: 100%
   :alt: alternate text
   :align: center  

Se pueden acceder a los datos de los conceptos en color *negro*, aunque no haya pasado el robot, dando clic derecho sobre el concepto que se deseé y desglosará 
un menú con 2 opciones de compilación, *Compilación manual* y *Compilación rápida*:  

.. image:: /images/compilaciones.png
   :width: 300px
   :alt: alternate text
   :align: center   

1. Compilación manual  
~~~~~~~~~~~~~~~~~~~~~  

Utilizaremos cómo ejemplo el siguiente concepto para explicar la compilación manual, notaremos que aún no está Compilando
y por ende aún se muestra en color *negro*.

.. image:: /images/encabezado-febrero.png
   :width: 100%
   :alt: alternate text
   :align: center 

.. image:: /images/febrero.png
   :width: 100%
   :alt: alternate text
   :align: center 

Se va a intentar buscar que la terminología sea igual al número de pagos, dependiendo la cantidad de pagos será el tiempo que tardará el proceso.  

1.1 Conciliación
~~~~~~~~~~~~~~~~

Cómo podemos observar nos muestra el total, descuentos ,recargos, etc, notaremos que en la parte superior aparecerá un reloj en color **Naranja**,
lo que significa que la conciliación está en **Espera**.  

.. image:: /images/febrero1.png
   :width: 100%
   :alt: alternate text
   :align: center  

.. image:: /images/febrero1.png
   :width: 100%
   :alt: alternate text
   :align: center  

1.2 Pagos adjuntos
~~~~~~~~~~~~~~~~~~  

Se muestra una tabla con todos los datos respecto a los pagos realizados, montos, información del alumno,
fechas,terminología ,comprobantes, etc.   

.. image:: /images/febrero2.png
   :width: 80%
   :alt: alternate text
   :align: center  

.. image:: /images/febrero3.png
   :width: 100%
   :alt: alternate text
   :align: center   


La terminología dice **NORMAL** ya que es un pago que se hizo al corriente y toda la información del pago, 
de acuerdo al grupo en el  que viene realizará cálculos los cuáles tienen base en el catálogo de 
**Distribuciones**.   

1.2.1 Debug  
~~~~~~~~~~~  

.. image:: /images/debug.png
   :width: 100%
   :alt: alternate text
   :align: center 

El botón rojo es de **‘Debug’** el cuál sirve para ver cómo se va a repartir los ingresos pago por pago, al 
presionarlo cambiará a color verde y mostrará una columna extra llamada **Valores** antes del Folio.

1.3 Distribución
~~~~~~~~~~~~~~~~ 

Relacionan como se va a distribuir el dinero de los pagos con los grupos, si hay dos grupos es posible 
que el dinero no se distribuya igual para ambos grupos. Los grupos además de ayudar a agrupar los alumnos 
también ayudan a distribuir ese ingreso, si entran una serie de pagos y sus grupos no están definidos 
aparecerá un recuadro **naranja** en la parte inferior con la leyenda **“Sin distribución”**, quiere decir que hay un pago el cuál su grupo de distribución no se encuentra.  

.. image:: /images/febrero5.png
   :width: 100%
   :alt: alternate text
   :align: center   


.. _resultadosdistribucion:
1.4 Resultados de distribución
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Resultados de distribución: son los cálculos de cómo es que se va a distribuir el dinero, si no tiene grupo 
todo se irá a **“Sin distribución asignada”**.

.. image:: /images/febrero4.png
   :width: 100%
   :alt: alternate text
   :align: center   


1.5 Añadir nuevo requerimiento   
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~   

Los requerimientos son pagos realizados por la Sede y que tienen que ser repartidos.  

.. image:: /images/añadirnuevorequerimiento-compilacionmanual.png
   :width: 400px
   :alt: alternate text
   :align: center 

Después de seleccionar algún concepto de la lista y haber agregado el monto seleccionamos 
*Añadir requerimiento* y mostrará una tabla cómo la siguiente:   

.. image:: /images/requerimientoincluido.png
   :width: 100%
   :alt: alternate text
   :align: center   

Estos datos también se toman en cuenta al momento de repartir los pagos, por lo que se 
mostrará el concepto de **Requerimientos** en la tabla de :ref:`Resultados de distribución <#resultadosdistribucion>`. 
Estos requerimientos son agregados por Contador o Sede.  

1.6 Acciones de administrador  
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

.. image:: /images/accionesadministrador-compilacionmanual.png
   :width: 400px
   :alt: alternate text
   :align: center  

1.6.1 Deshacer  
~~~~~~~~~~~~~~
Le regresa todos los pagos a la universidad en caso de que haya algo mal con ellos.  

1.6.2 Conciliar
~~~~~~~~~~~~~~~   

En caso de que se hayan revisado todos los pagos y todo esté correcto con la 
distribución, al haber conciliado muestra una vista mas general con una tabla de **(rentabilidad)**. 
Esta conciliación pasará a ser parte del :ref:`Historial de conciliación <#historialconciliacion>`.   

2. Compilación rápida
~~~~~~~~~~~~~~~~~~~~~    

Ignora la terminología de pagos y mostrará los datos con sus cálculos.   
Utilizaremos cómo ejemplo el siguiente concepto para explicar la compilación manual, notaremos que aún no está Compilando
y por ende aún se muestra en color *negro*.  

.. image:: /images/encabezado-febrero.png
   :width: 100%
   :alt: alternate text
   :align: center 

.. image:: /images/febrerorapida.png
   :width: 100%
   :alt: alternate text
   :align: center   

.. _desconciliado: 

2.1 Conciliación
~~~~~~~~~~~~~~~~

Cómo podemos observar nos muestra el total, descuentos ,recargos, etc, notaremos que en la parte superior aparecerá un reloj en color **Naranja**,
lo que significa que la conciliación está en **Espera**.   

.. image:: /images/conciliacionrapida.png
   :width: 100%
   :alt: alternate text
   :align: center     

2.2 Pagos adjuntos 
~~~~~~~~~~~~~~~~~~  

Muestra todos los pagos que se están enviando, montos, si los pagos están bien o pendientes de 
devolución, si existen cargos extra o cargos en contra, matricula y nombre del alumno, grupo de 
distribución (cómo se van a repartir los montos y agrupar alumnos), fecha en que se pagó y la 
fecha cubierta, ésta muestra **“No definido”** porque hicimos una compilación rápida y este método 
se salta el cálculo de la fecha cubierta para acelerar el proceso.  

.. image:: /images/pagosrapida.png
   :width: 100%
   :alt: alternate text
   :align: center   

2.2.1 Debug  
~~~~~~~~~~~  

.. image:: /images/pagossindebug.png
   :width: 100%
   :alt: alternate text
   :align: center   

El botón rojo es de **‘Debug’** el cuál sirve para ver cómo se va a repartir los ingresos pago por pago, 
al presionarlo cambiará a color verde y mostrará una columna extra llamada **Valores** antes del Folio.   

.. image:: /images/pagosconvalores.png
   :width: 100%
   :alt: alternate text
   :align: center   

El primer valor **350** se refiere a que por cada pago de colegiaturas a sede Orizaba descontará $350 
y una pasarela la cuál es **122.625**, el restante lo va a repartir 70-30.
Al seleccionar un valor de color naranja, por ejemplo **122.625** mostrará una ventana con la formula 
que se utilizó para realizar el cálculo para ese valor.   

.. image:: /images/formula.png
   :width: 350px
   :alt: alternate text
   :align: center   

Al hacer clic sobre la matrícula del alumno que se requiera, nos dirigirá a su :ref:`información general <#infoalumno>`.   


2.2.2 Distribución  
~~~~~~~~~~~~~~~~  

Relacionan como se va a distribuir el dinero de los pagos con los grupos, si hay dos grupos es posible 
que el dinero no se distribuya igual para ambos grupos. Los grupos además de ayudar a agrupar los alumnos 
también ayudan a distribuir ese ingreso, si entran una serie de pagos y sus grupos no están definidos 
aparecerá un recuadro **naranja** en la parte inferior con la leyenda **“Sin distribución”**, quiere decir que hay un pago el cuál su grupo de distribución no se encuentra.   

.. image:: /images/sindistribucion-compilacionmanual.png
   :width: 600px
   :alt: alternate text
   :align: center   

2.2.3 Conceptos opcionales a descontar
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~    

.. image:: /images/conceptosadescontar-compilacionmanual.png
   :width: 100%
   :alt: alternate text
   :align: center   

2.3 Resultados de distribución  
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~   

.. image:: /images/resultadosdistribucion-compilacionmanual.png
   :width: 100%
   :alt: alternate text
   :align: center   

2.4 Añadir nuevo requerimiento  
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~     

.. image:: /images/añadirnuevorequerimiento-compilacionmanual.png
   :width: 80%
   :alt: alternate text
   :align: center   

2.5 Acciones de administrador   
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

.. image:: /images/accionesadministrador-compilacionmanual.png
   :width: 100%
   :alt: alternate text
   :align: center   

2.5.1 Deshacer  
~~~~~~~~~~~~~~    

Le regresa todos los pagos a la universidad en caso de que haya algo mal con ellos.   

2.5.2 Conciliar
~~~~~~~~~~~~~~~     

En caso de que se hayan revisado todos los pagos y todo esté correcto con la 
distribución, al haber conciliado muestra una vista mas general con una tabla de (rentabilidad). 
Esta conciliación pasará a ser parte del :ref:`Historial de conciliación <#historialconciliacion>`.   

8. Historial de conciliaciones y facturas  
-----------------------------------------   

.. image:: /images/historial-conciliaciones-pendientes.png
   :width: 400px
   :alt: 77
   :align: center    

8.1 Historial de conciliaciones  
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~     

Al hacer clic sobre cualquier concepto nos mostrará los siguientes contenidos:    

8.1.1 Conciliación  
~~~~~~~~~~~~~~~~~~   

Notaremos que se muestra un icono verde indicando que el estatus de ese concepto ya está conciliado.   

.. image:: /images/conciliacion.png
   :width: 100%
   :alt: conciliacion
   :align: center  

Nos muestra la cantidad bruta, descuentos, recargos, neto, cuantos elementos hay y cuantos requeridos.    
 

8.1.2 Distribución de rentabilidad
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~   

En ésta tabla se mostrará la distribución del total de los pagos, seccionada en las siguientes columnas:      

1. Distribución: Muestra los conceptos en los que se distribuyeron los montos y el total(rentabilidad).  
2. Monto: Es la cantidad que se le asignará a cada concepto ya sea de utilidad o extras.  
3. Permitir en sede: Todos los datos sobre distribución y conciliaciones que estaremos visualizando la Sede no las estará viendo, la Sede únicamente podrá ver los datos correspondientes a los que se le dé clic 
sobre **Mostrar**, en este caso de ejemplo a “UTILIDAD_-_Esteban_Garcia, notaremos que ahora cambió a **Ocultar** y este será el único dato que podrán ver:    

.. image:: /images/distribucion.png
   :width: 100%
   :alt: distribucion
   :align: center     

8.1.3 Pagos adjuntos
~~~~~~~~~~~~~~~~~~~~    

Notaremos que ahora la tabla de pagos ya no nos muestra el botón de **Debug** debido a que éste solo aparece
cuando aún no ha sido conciliado.   

.. image:: /images/pagosconciliados.png
   :width: 100%
   :alt: distribucion
   :align: center   

De igual manera al seleccionar cualquier alumno en color **Rojo** nos dirigirá a la :ref:`información general <#infoalumno>`.    

8.1.4 Acciones de administrador
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~   

Nos encontraremos con una sola opción **Desconciliar**, al seleccionar ese botón nos mostrará una ventana de advertencia cómo esta:   

.. image:: /images/advertenciadesconciliar.png
   :width: 350px
   :alt: distribucion
   :align: center   

Y al darle **Continuar** volverá a mostrar los datos :ref:`de ésta manera <#desconciliado>`.   

8.2 Historial de factuación
~~~~~~~~~~~~~~~~~~~~~~~~~~~   

Al seleccionar ésta opción nos dirigirá a la misma información explicada en :ref:`Facturas pendientes <#facturaspendientes>`.   

Usuarios
========   

Ésta opción está úbicada en el menú de la parte izquiera de la pantalla.  

1. Perfil de usuario
--------------------  

Nos mostrará un formulario tanto para modificar el nombre y datos del
usuario así cómo su contraseña, se mostrará :ref:`este formulario <#perfilusuario>`.


2. Lista de usuarios
--------------------  

Cómo su nombre lo índica, mostrará la lista general de usuarios
registrados en la plataforma de todas las sedes, muestra desde el nombre
del usuario hasta la última vez que inició sesión. Se pueden realizar
búsquedas para encontrar un usuario en específico ya sea por nombre del
usuario, sede, nivel, etc.  

.. figure:: /images/lista-usuarios.png
   :alt: image79

.. _acciones-3:

Acciones
~~~~~~~~  

En ésta columna nos mostrará 3 diferentes opciones para cada usuario:  

2.1 Información de usuario
~~~~~~~~~~~~~~~~~~~~~~~~~~  

.. image:: /images/accion2.png
   :width: 30px
   :alt: alternate text
Se utiliza para modificar la información del usuario,
mostrandonos un formulario cómo el siguiente:  

.. figure:: /images/info-usuarios.png
   :alt: image82  

2.2 Agregar acceso a sedes
~~~~~~~~~~~~~~~~~~~~~~~~~~    

.. image:: /images/accion1.png
   :width: 30px
   :alt: alternate text
Aquí se controla el acceso a sedes para los usuarios, pueden
tener acceso a más de una, solo con seleccionar la sede a la que se
quiere dar acceso y presionando el botón **Agregar acceso a sede**.  

.. figure:: /images/accesoasedes.png
   :alt: image84  

2.2.1 Accesos concedidos
~~~~~~~~~~~~~~~~~~~~~~~~  

En la siguiente parte se muestra una tabla con la lista de sedes a las
que se le dió acceso al usuario, incluyendo fecha en que se dió de alta
y la opción para eliminar el acceso a alguna sede en específico, también
incluye la opción *Búscar* para listas mas largas, ya sea por nombre de
sede ó fólio:  

.. figure:: /images/accesosconcedidos.png
   :alt: image85  

2.2.2 Copiar accesos
~~~~~~~~~~~~~~~~~~~~  

.. figure:: /images/copiaraccesos.png
   :alt: image86  

2.2.3 Eliminar accesos
~~~~~~~~~~~~~~~~~~~~~~  

| Tenemos ésta opción para eliminar todas las sedes a las que se le dió
  acceso al usuario:   

.. image:: /images/eliminartodas.png
   :width: 100%
   :alt: alternate text
   :align: center   

2.3 Acceder a sedes
~~~~~~~~~~~~~~~~~~~  

.. image:: /images/accion3.png
   :width: 30px
   :alt: alternate text   

Al seleccionar este botón nos iniciará en la sesión del usuario que se seleccionó, éste puede ser de nivel *Sede, Control escolar ó Administrador* y nos mostrará la interfaz segun el nivel que corresponda.   

.. _listausuarios:  

| En este caso iniciaremos con este usuario que como nos muestra en la
  siguiente imágen es de tipo *Sede*:  

.. figure:: /images/perlausuario.png
   :alt: image89   

Cómo se mencionó anteriormente nos mostrará la interfaz de acuerdo al
nivel con el que se inició sesión, en éste caso **Sede**:  

.. figure:: /images/perlausuario-interfaz.png
   :alt: image90   

En la parte superior izquierda muestra el tipo de usuario que es, en la
parte derecha al seleccionar el nombre del usuario nos desglosará una
lista en donde tenemos la opción de elegir **Quedarme aquí** en caso de
que quiera permanecer en este usuario.  

En caso de que se deseé regresar a la interfaz de su usuario original
deberá presionar clic derecho sobre cualquier parte de la pantalla y nos
mostrará un menú en donde seleccionaremos **Salir de este usuario**
regresandonos a `Lista de usuarios <#listausuarios>`__.  

.. image:: /images/salirdeesteusuario.png
   :width: 300px
   :alt: salir de usuario
   :align: center   

Nuevo usuario
~~~~~~~~~~~~~  

Al seleccionar este botón nos mostrará un formulario con los campos
requeridos cómo nombre,correo electrónico,sede, nivel de usuario ya sea
*Sede, Control escolar, Administrador ó Administrador escolar*, clave y
guardando los cambios seleccionando el botó **Guardar**.  

.. figure:: /images/nuevousuario.png
   :alt: image92   

3. Historial
------------  

Muestra una lista con el nombre del usuario, la acción y fecha en que lo
realizó, se puede realizar búsquedas por nombre de usuario, fólio o
acción.  

.. figure:: /images/historial-usuarios.png
   :alt: image93  

Las acciones que mencionen a algun alumno por su **matrícula**, se podrá
dar clic sobre ella y nos mostrará la información general del alumno,
datos escolares, pagos, etc.  

3.1 Gráfico de uso del sistema
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  

Muestra gráficamente el porcentaje que cáda usuario realizó acciones
sobre el sistema:  

.. figure:: /images/grafico-usosistema.png
   :alt: image94  

4. Credenciales generadas
-------------------------      

4.1 Historial  
~~~~~~~~~~~~~  

Muestra una tabla con el historial para saber quién generó y descargó una credencial, así mismo aparecerá gráficamente en la parte superior en base al porcentaje del número 
de personas que hayan realizado ésta acción:  

.. image:: /images/historialcredencial.png
   :width: 100%
   :alt: historial
   :align: center


Alumnos
=======  
