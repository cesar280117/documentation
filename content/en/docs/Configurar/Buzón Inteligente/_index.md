---
title: "Buzón Inteligente"
linkTitle: "Buzón Inteligente"
weight: 3
description: >
  La pestaña de configuración de Buzón inteligente permite activar o desactivar el rechazo automático de CFDIS de Cancelación, así como establecer reglas para cancelar de forma automática.
---

### ° Rechazo automático

* En este switch de **Rechazo automático** Activamos o desactivamos el buzón inteligente, Este tendra diferentes funcionalidades dependiendo si esa activado o descativado.
![IMG](principal.png)

### ° Estado activo de buzón inteligente

* **Activado**:
  ![IMG](activo.png)

* Se Rechaza de forma automática los CFDIs que lleguen al buzón siguiendo las reglas.
	*	Rechazar con antigüedad en ## días .
	*	Rechazar todo antes del mes actual .
	*	Rechazar por monto mayor a $ ###,###.##.
	*	Rechazar todas las solicitudes.
	*	Aceptar todas donde el emisor esté en lista blanca.
<br><br>
*	Se envía correo a contacto de bóveda notificando la acción & acuse.
*	Si, no entra a ninguna regla se acepta automático
*	Cuando se rechaza, se puede marcar como pre-aprobada de manera manual.
* Las solicitudes posterior a un rechazo:
	*	Si se encuentra pre-aprobada, se acepta la cancelación de forma automática.
 	*	Si no se encuentra pre-aprobada se vuelve a rechazar
	*	Se envía correo a contacto de bóveda notificando la acción & acuse.
  <br><br>
*	En catálogo o listado de buzón se muestran por defecto las solicitudes procesadas ya sean aceptadas o rechazadas.

#### ° Reglas de rechazo automatico
con esta sección Podemos rechazar todas las solicitudes.
![](shi.gif) 

O podemos establecer **reglas que rechazaran los cfdis** que cumplan esos requisitos, los cfdis que no cumplan podemos verlos en el buzón inteligente, para ello dar clic en el siguiente campo y seleccionar **Algunas Solicitudes**.

![](selec.gif) 

Se mostra un menú en donde se podra elegir **Las reglas que rechazaran los cfdis**

![](shi2.png) 

#### ° Lista de aceptación
Por ultimo podemos **establecer una lista de RFCs de emisores** a los cuales siempre aceptaremos sus solicitudes de cancelación.
Para ello nos dirigiremos a la sección de **Lista de Aceptación** y agregarmos dichos **RFCs** emisores deseados.

![](lista.gif) 

<br><br><br><br>


### ° Estado inactivo del buzón inteligente
* **Desactivado**:
![IMG](desactivado.png) 

*	Solicitudes esperan aceptación o rechazo de forma manual
*	Se envía correo a contacto de bóveda notificando la solicitud de cancelación (El correo contendrá dos link únicos uno para aceptación y otro para rechazó con un api key temporal única, para no tener que ingresar a sitio de bóveda)
*	Se envía correo a contacto de bóveda notificando la acción & acuse.

	*	Si no se recibe acción manual, el SAT aplica las reglas previamente establecidas en DOF.
	*	Se envía correo a contacto de bóveda notificando el estatus cancelación de su solicitud no atendida. 
	*	En el catálogo o listado de buzón se muestran por defecto las solicitudes pendientes de aceptación-rechazo.

