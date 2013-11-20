---
layout: default
title: Vista de Presupuesto
---

# Vista de presupuesto
---------------------------------------
  
  Esta vista muestra todos los campos relacionadas al presupuesto en cuestión. La vista varía dependiendo si el presupuesto tiene copropietarios, unidades pre-asignadas, unidades asignadas temporalmente, descuentos, solicitudes de excepción, o solicitudes de descuento.

  El siguiente es un presupuesto simple, sólo tiene un propietario, una unidad (la principal), no posee descuentos ni solicitudes.

  >![Vista de presupuesto](/images/vistapresupuesto0.png)

  Los elementos básicos de un presupuesto son entonces:

  - Código auto-generado:
  	
  	El código del presupuesto es generado a partir del código de la unidad principal, más un número autogenerado secuencial. Servirá de identificador durante todo el proceso de adquisición.

  - Fechas de validez:

  	El presupuesto será válido desde que se crea, hasta que se cumpla el tiempo de vida prefijado en la configuración de proyecto. Para más información revise el siguiente enlace: [Configurar proyecto](configurarproyecto.html).

  - Tipo de financiamiento:

  	Definido al crear el presupuesto, es utilizado durante el proceso de adquisición para habilitar o deshabilitar la etapa de aprobación bancaria, ya que de tener un financiamiento propio o al contado no requeriría completar dicha etapa. Para más información revise el siguiente enlace: [Adquisición](adquisicion.html).

  - Plantilla seleccionada:

  	La plantilla permitirá imprimir un documento usando un formato configurado previamente, combinándolo con datos del presupuesto. El administrador del sistema podrá crear más de una plantilla para que los usuarios puedan elegirlas. Para más información revise el siguiente enlace: [Plantillas](plantillas.html).

  - Lista de precios relacionada:

  	La lista de precios relacionada es la que tiene los precios de las unidades en el presupuesto. Es importante recalcar que la lista de precios puede perder vigencia si otra lista es aprobada, sin embargo pueden manejarse excepciones para estos casos. Para más información revise el siguiente enlace: [Manejo de excepciones](excepciones.html).

  - Cliente:

  	El cliente que se muestra en esta parte es el cliente principal, con el que se hizo el primer contacto, y a quien se le entregó el presupuesto.

  - Titulares:

  	Los titulares son los copropietarios relacionados al presupuesto, por predeterminado se tendrá al cliente principal, pero puede ser retirado si así se requiere. Se pueden tener múltiples copropietarios, para más información revise el siguiente enlace: [Copropietarios](copropietarios.html). En el caso de haber copropietarios con cónyugues con régimen de comunidad de bienes, el titular puede ser cambiado desde el proceso de adquisición con la funcionalidad de titulares, para más información revise el siguiente enlace: [Manejo de titulares](titulares.html).

  - Unidad principal:

  	La unidad principal es aquella en la que parte el presupuesto, su código es utilizado para crear el código del presupuesto, y puede ser usado para ubicar al presupuesto en las listas de adquisición. Para más información revise el siguiente enlace: [Adquisición](adquisicion.html).

  - Precio total:

  	Respresenta el monto total, la suma de todos los precios de las unidades relacionadas. La moneda mostrada es la que se define en la configuración general del sistema. Para más información revise el siguiente enlace: [Configuración general](configgeneral.html).

  - Planos adjuntos:

  	Los planos adjuntos y aprobados específicos de la unidad. Estos planos están almacenados en el sistema y sus enlaces pueden ser compartidos en el envío de presupuesto al cliente. Funcionalidad explicada más adelante.

  Este sería un ejemplo de un presupuesto más complejo:

  >![Vista de presupuesto](/images/vistapresupuesto1.png)

  Un presupuesto más complejo puede tener los siguientes campos adicionales:

  - Múltiples titulares:

  	Como se explicó previamente, el presupuesto puede tener más de un titular, y puede no contener al cliente relacionado como uno de los titulares. Cada titular tiene un enlace que lleva al usuario a su correspondiente vista de cliente. Para más información revise el siguiente enlace: [Copropietarios](copropietarios.html).

  - Unidades preasignadas:

  	Las unidades preasignadas con aquellas que están "amarradas" a la unidad principal, para que sean vendidas juntas. En el presupuesto se les considerarán, como se muestra en la imagen previa. Para más información revise el siguiente enlace: [Preasignar unidades](preasignarunidades.html).

  - Unidades asignadas al presupuesto:

  	Durante la creación del presupuesto se pueden asignar unidades temporalmente a dicha venta, sin embargo dichas unidades pueden estar relacionadas a otros presupuestos. Al reservar o separar el presupuesto, las unidades asignadas temporalmente pasan a estar reservadas o separadas. Para más información revise el siguiente enlace: [Crear presupuesto](crearpresupuesto.html).

  - Descuentos:

  	Los descuentos son solicitados desde la vista de adquisición de un presupuesto, y se reflejan al ver el prespuesto, usualmente para ser aprobados o rechazados. Los descuentos se manejan por unidad o como descuentos en total. El precio total también mostrará detalles del descuento total, y el precio total con descuento. Para más información revise el siguiente enlace: [Descuentos](descuentos.html).

  - Múltiples planos adjuntos:

  	Como se explicó previamente, los planos adjuntos están dentro del sistema, y sus enlaces pueden ser enviados utilizando la funcionalidad de "Email al cliente". Cuando existen unidades pre-asignadas y asignadas temporalmente al presupuesto, los planos específicos de dichas unidades serán también consideradas en la lista. De no habler planos adjuntos, se mostrará un mensaje en cada unidad indicándolo.

  - Solicitud de excepción:

  	Las solicitudes de excepción serán mostradas en la parte superior de la vista del presupuesto, con un botón para aprobar la excepción y otro para rechazarla. Para más información revise el siguiente enlace: [Excepciones](excepciones.html).

	>![Solicitud de excepcion](/images/solicitudexcepcion.png)

  - Solicitud de descuento:

  	Las solicitudes de descuento serán mostradas en la parte superior de la vista del presupuesto, con un botón para aprobar la solictud y otro para rechazarla. Para más información revise el siguiente enlace: [Descuentos](descuentos.html).

  	>![Solicitud de descuento](/images/solicituddescuento.png)

  **Botones en la parte inferior:**

  - Email al cliente:

  	Esta funcionalidad envía un correo al cliente usando la plantilla del presupuesto. El correo envía además enlaces relacionados a los planos adjuntos, para que el cliente no tenga el correo lleno, sino que pueda acceder a ellos usando un link, y descargarlos desde ahí.

  	>![Planos adjuntos](/images/planosadjuntos.png)

  - Ver presupuesto:

  	El presionar este botón se visualiza una ventana predefinida por el navegador que permite la impresión del presupuesto. El presupuesto aparece usando la plantilla elegida en configuración, pero con los datos del prespuesto y sus elementos.	


  - Actualizar plantilla:
  
  	Si se hicieron cambios en la plantilla actual, usando la sección de configuración, y se requiere darle un vistazo o imprimir el presupuesto nuevamente, entonces conviene presionar el botón de "Actualizar Plantilla". Para más información sobre cómo editar su plantilla revise el siguiente enlace: [Plantillas](plantillas.html).


  
