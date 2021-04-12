# APAGADO PROGRAMADO EN LA IMPRESORA 3D

Muchas impresoras no tienen una función de apagado programado, y en algunas piezas complejas, la impresión dura mucho por lo que no podemos estar al tanto de apagarlas, sobre todo si cuando va a acabar la pieza va a ser a horas no católicas.

Una solución fácil es incorporar un temporizador en el enchufe, esto se puede hacer fácilmente pues en el slice nos dice el tiempo que va a durar:

![](/assets/cura9.jpg)

Podemos programar el temporizador con un tiempo **superior** al marcado :

![](/assets/cura11.jpg)

## SI LA IMPRESORA ESTÁ EN EL CENTRO EDUCATIVO: Una solución sofisticada:

Consiste en hacer streaming, utilizando una webcam de vigilancia comercial o en este caso una rasperry con webcam. Para ello se ha seguido los pasos del capítulo 8 de este [tutorial](https://catedu.github.io/rover-marciano-alphabot/8-camara/81-que-vamos-a-hacer.html)

![](/assets/cura12.jpg)

De esta manera vamos controlando si se está realizando correctamente la impresión, incluso desde el móvil, es una URL y los alumnos pueden participar en vigilarlo. Cuando acaba o se ha producido un desastre, podemos apagar remotamente la impresora y/o la rasperry con un enchufe wifi inteligente :

![](/assets/cura13.jpg)
