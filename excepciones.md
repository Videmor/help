---
layout: default
title: Manejo de excepciones
---

# Manejo de excepciones
---------------------------------------
  
  Se le llama excepciones a aquellas situaciones específicas en las que se trabaja con un presupuesto que no tiene las unidades asignadas o el precio definido, tal como los asignó el gerente de proyecto u otra persona con permisos de edición de unidades y precios.

  Cuando se estas situaciones, el usuario no podrá efectuar una reserva o una separación del presupuesto en cuestión, y por ende no podrá proseguir con el proceso de adquisición.

  Sin embargo el usuario tiene la opción de enviar una solicitud de excepción. Al intentar realizar la reserva o separación, le aparecerá un mensaje indicando la razón por la cual no podrá continuar haciéndolo, pero además le aparecerá la opción de enviar una solicitud de excepción a los supervisores del proyecto relacionado.

  Las tres situaciones en las que se darían estas circunstacias son las siguientes:

  - Se crea un presupuesto, y en un momento posterior se aprueba una nueva lista de precios que tiene un precio diferente para las unidades relacionadas a dicho presupuesto. Para más información sobre las listas de precios, consulte el siguiente enlace: [Listas de precios](listasdeprecios.html).

  >![Mensaje de excepcion](/images/mensajeexcepcion1.png)

  - Se crea un presupuesto, y en un momento posterior se pre-asigna una unidad a una de las unidades relacionadas a dicho presupuesto. Para más información acerca de la pre-asignación de unidades, consulte el siguiente enlace: [Pre-asignar unidades](preasignarunidades.html).

  >![Mensaje de excepcion](/images/mensajeexcepcion2.png)

  - Si se dan las dos situaciones anteriores juntas.

  >![Mensaje de excepcion](/images/mensajeexcepcion3.png)
  
  Al enviar la solicitud de excepción, los supervisores serán notificados con un mensaje interno. Si el proyecto no tuviese un supervisor, aparecerá un mensaje indicándolo, el usuario deberá solicitar que el administrador asigne uno para manejar este tipo de excepciones.

  >![Sin supervisor](/images/sinsupervisor.png)

  Al tener un presupuesto con una solicitud pendiente de excepción, se tendrá una pequeña marca en dicho presupuesto, en la lista de presupuestos, como lo muestra la siguiente imagen:

  >![Excepcion pendiente](/images/excepcionpendiente.png)

  El mensaje interno que le llega al supervisor contiene un enlace directo al presupuesto. El supervisor podrá hacer click en el enlace y visitar el presupuesto. Una vez en el presupuesto, el supervisor tendrá la opción de aceptar o rechazar la solicitud de excepción.

  >![Solicitud de excepcion](/images/solicitudexcepcion.png)  

  Cuando el supervisor apruebe o rechace la solicitud de excepción, le llegará un mensaje al usuario que solicitó dicha excepción, indicando el resultado.

  Si la excepción fue aprobada, se le verá con una marca en la lista de presupuestos, tal como lo muestra la siguiente imagen:
	
  >![Excepcion aprobada](/images/excepcionaprobada.png)

  En ese momento el usuario podrá efectuar la reserva o separación de dicho presupuesto. Si el supervisor hubiera rechazado la excepción, el usuario seguiría sin poder efectuar la reserva o separación.



  