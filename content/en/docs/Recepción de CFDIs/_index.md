---
title: "Recepción de CFDI's"
linkTitle: "Recepción de CFDI's"
weight: 3
---

Por cualquier medio que se haga la recepción de cfdis en bóveda, ya sea bajar del SAT, subir archivo ZIP, jalar de correos electrónicos.

* Se validará que los archivos sean tipo cfdi y que corresponda el rfc de la cuenta al emisor o receptor
* Se guardará y se marcara con status “Pendiente”, el archivo pasa a una cola para posterior validación y resguardo.
* Se validará integridad por medio del sello y validez ante el SAT.

**Estatus CFDI**

* **Pendiente:** Aún está pendiente validar CFDI (sello & sat) y resguardar.
* **Vigente:** El comprobante se encuentra en el SAT y no está alterado.
* **Cancelado:** El comprobante se encuentra cancelado en el SAT y no está alterado.
* **Invalido:** El comprobante aun no llega al SAT tiene 72hrs a partir de la fecha de certificación, si no manda alerta a contacto de bóveda.
* **Alterado:** El comprobante está corrupto en su estructura, se manda alerta a contacto de bóveda.

* CFDIs con status Vigente y Cancelado. Se muestran en Catálogo Emitidos o Recibidos.
* CFDIs con status Pendiente, Invalido o Alterado. Se muestran en Catálogo de Inhabilitados.

> **Siga los enlaces para entrar en detalle de la configuración.**



