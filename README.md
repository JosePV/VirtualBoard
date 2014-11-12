VirtualBoard
============

La pizarra virtual es una forma de trabajar en remoto con un equipo de trabajo de manera colaborativa, mantener reuniones virtuales y compartir la información como si estubiesemos en el mismo espacio de trabajo físico.

1- Funcionalidades de pizarra:

La idea es crear una pantalla donde se pueda escribir o pintar. La escritura se haría con el teclado del dispositivo. A la hora de pintar hay que conseguir una experiencia de usuario lo más realista posible, eso implica:

A- Que los trazos sean lo más fluido posible.
B- Que el grosor del trazo sea sensible a la presión. 
C- Que el grosor del trazo sea sensible a la velocidad de este.
D- Que el feedback de la pantalla sea lo más rápido posible, es decir, que no haya lag entre el momento en que se pinta y el momento en que el trazo aparece en la pantalla.

2- Almacenaje/Sincronización de trazos

La idea es poder almacenar y comunicar los trazos que se hagan en el canvas. Para ello creemos que la mejor opción es convertir los diferentes trazos a SVG. El que los trazos sean vectoriales es importante ya que cada dispositivo puede tener una resolución de pantalla diferente.

Por un lado habría que almacenar toda la información de trazos en un servidor y por otro ver la mejor forma de mantener sincronizados los dispositivos entre si para que todos muestren los contenidos que se vayan dibujando.

3- Proyección en pantalla wifi.

Con pantalla wifi nos referimos a un dispositivo con soporte airplay, chromecast o miracast.  

La idea es que, al igual que se ven los contenidos en los diferentes dispositivos, además se vean en una pantalla principal como puede ser una TV o un proyector.
