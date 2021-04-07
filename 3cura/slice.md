# SLICE
## ¿Qué es?

La impresora 3D lee ficheros **gcode** que lo que contiene es información de cómo se tiene que mover el cabezal en cada capa o rebanada (Slice = rebanada)

## Antes de dar a Slice
Tenemos que ver que no quede nada importante "en el aire", para ello nos ponemos en un punto de vista mirando de abajo a arriba y CURA nos destaca en rojo lo que queda "al aire" :

![](/assets/cura6.jpg)

NO es relevante y esos pequeños trozos los puede hacer sin problema

La parte azul indica que está pegado a la base (importante para que la pieza no se nos despegue durante el proceso de impresión), pero vemos que las puntas redondeadas no, acercándonos vemos que no he sido preciso en el diseño (a lo mejor tú sí)

![](/assets/cura5.jpg)

Esto pasa por no usar la herramienta **Alinear** en Tinkercad, seleccionando los dos objetos la U y los semicilindros :

![](/assets/cura7.jpg)

Esto de las "partes en el aire" lo trataremos en el tema de **SOPORTES**.

Como es una pieza que no tendrá problemas de adhesión yo suelo quitar el [Skirt Brime o Raft](https://filament2print.com/es/blog/23_skirt-brim-raft.html) que sale por defecto.

![](/assets/cura14.jpg)

## Procedemos a Slice

Ponemos una tarjeta microSD en nuestro ordenador, seguramente necesitaremos un adaptador :

![](/assets/sd-card.png)

Icono de [Flaticon](https://www.flaticon.com/)

Procedemos a pulsar en el botón Slice :

![](/assets/cura8.jpg)

Y nos dice luego cuanto va a tardar, pulsamos en grabar en la tarjeta (Removable)

![](/assets/cura9.jpg)

Podemos pues a pulsar a Expulsar (Eject) pues ya ha grabado el fichero "CE3-Taca-camara-web.gcode"

![](/assets/cura10.jpg)
