Aqui se va a a consignar toda la información perteneciente al proyecto desarrollado para la materia Electrónica digital 3

##ZoneX

##Daniel Cano Restrepo - 1193558626 ##Valentina Jaramillo Raquejo - 1000207036 ##Jhon Eduar García Ortiz - 1152471164 ##Luis Fernando Torres - 1061820239

##PROPUESTA

Se desea implementar un sistema de control de acceso orientado a las zonas residenciales o espacios compartidos donde se manejan roles de administrador del interior y usuario de una habitación interna de dicho interior. El objetivo es permitir el ingreso a dichos espacios por medio de tags de radio frecuencia que sólo tiene el administrador(todos los espacios) y el usuario(1 espacio).

Para administrar el espacio del anfitrión se disponen de acciones de conrol sobre el sistema que permitirán retirar un suario del sistema, agregar usuarios al sistema y modificar las contraseñas de los espacios interiores para mayor seguridad.

#DESCRIPCION DEL SISTEMA:

#USUARIO: -yo como usuario puedo ingresar a la zona controlada por la puerta principal y puedo ingresar a la zona principal y una habitación que temporalmente estoy habitando o usando.

-Yo como usuario puedo cambiar la contraseña de mi espacio asignado por el sistema

#ADMINISTRADOR:

-Yo como administrador puedo ingresar al area principal y a cada uno de los espacios interiores -Yo como administrador puedo ingresar nuevos usuarios al sistema -Yo como administrador puedo eliminar usuarios del sistema -Yo como administrador puedo cambiar la contraseña de todos los espacios cubiertos por el sistema

##ENTRADA PRINCIPAL:

-teclado + lcd + lectorRF + modulo bluetooth

##ESTACION INTERIOR:

-teclado + leds + lectorRF + modulo bluetooth

##Requisitos funcionales

-Comandos de control: el sistema debe permitir el ingreso de una secuencia de teclas asociada a un comando, registrarlo en el sistema y ejecutarlo.

-Control de ingreso: el sistema debe permitir el ingreso a las zonas controladas por medio de una contraseña o de un tag de radiofrecuencia. El sistema tambien debe registrar la operación y permitir el acceso

-Vinculo entre estaciones: las etaciones del sistema deben notificarse entre sí los cambios ocurridos en el sistema, por ejemplo los usuarios nuevos.

##Requisitos no funcionales

-Alimentación: El sistema debe funcionar con baterías para cada una de las estaciones

-El sistema debe se debe refrescar su estado en menos de un minuto

-El sistema cuenta con un máximo de 10 usuarios activos al tiempo

##Componentes -4 Raspberry Pi pico x $30000 -4 Módulo RFID-RC522 x $15000 -4 módulos bluetooth HC05 x $20000 -4 Llavero de acceso RFID x $3000 -3 Bombillos LED para alarma x $3000 -1 pantalla lcd x $10000 -4 Fuente de alimentación (Baterías) x $10000
