---
layout: default
title: Configurar proyecto
---

# Configurar Proyecto
---------------------------------------
  Para entrar a esta vista el usuario debe hacer click en el ícono en forma de tuerca, ubicado en la vista de proyecto, o en la lista de proyectos. Además el usuario deberá tener permisos para editar proyectos.

  >![Configurar proyecto](/images/configurarproyecto.png)
  
  El formulario de configuración de proyecto cuenta con los siguientes opciones:

  - **Tiempo de vida de un presupuesto**  

  	Si un presupuesto vence, ya no puede ser utilizado para reservas o separaciones. Es necesario crear un nuevo presupuesto, pero es probable que el precio pueda haber cambiado si se aprobó una nueva lista de precios. Un presupuesto vencido se verá de color rojo en la lista de presupuestos en la unidad, tal como la imagen lo muestra:

  	>![Presupuesto vencido](/images/presupuestovencido.png)	

  - **Acción a tomar cuando una reserva vence**
  	
  	Algunas inmobiliarias podrán elegir que las unidades estén disponibles de manera automática cuando la reserva haya vencido, y otras preferirán quitar la reserva manualmente.
  	
  	Es importante recordar que si hay reservas en cola, estas entrarán automáticamente una vez que se haya vencido la reserva anterior de manera independiente a este campo de configuración, y esto seguirá sucediendo hasta que ya no queden reservas en esa cola, en ese caso la última reserva se mantendrá o se quitará automáticamente al vencer dependiendo de este campo de configuración.

  - **Tiempo predeterminado para la duración de una reserva**

  	Es el tiempo que el sistema sugiere o define para la reserva en el momento en que se está creando la misma. Al configurar se puede elegir entre 1,2,3,4,5,6 y 7 días o puede dejarlo en Ninguno. El usuario al crear una reserva en dicho proyecto podrá cambiar ese tiempo dependiendo de la siguiente opción de configuración.

  - **Permitir que el usuario defina la duración de la reserva**

  	Si se habilita al usuario para definir la duración de la reserva, al crear la reserva el sistema le sugerirá un tiempo predeterminado para la misma, pero el usuario podrá cambiarla por otro.

 	>![Creando reserva](/images/creareserva.png)	

  - **Tiempo de vida de procesos**

  	El sistema permite colocar un tiempo de vida para los procesos de separación, aprobación, venta y cancelación.

  	Esta opción permite definir un tiempo máximo de cuánto duraría cada tipo de proceso en el proyecto. En cada tipo de proceso, al finalizar este tiempo sin que un proceso haya terminado, se prenderá una alerta que informará a los usuarios que el proceso está demorado, y les permita tomar acciones correctivas. Estos tiempos son sólo informativos, no bloquean ninguna acción en el sistema.

