# MiniKartGame

Proyecto Kart Mini Game - Rene Perez - 09 08 2021

REALIZACIÓN DE LA PRUEBA

La base del desarrollo del proyecto fue la implementación del template "Karting Microgame", el cual es uno de los templates base que proporciona Unity al crear un proyecto nuevo.

No encontré la versión de Unity 2020.3.3f LTS, por lo que tuve que descargar la más reciente recomendada por el hub, que es  2020.3.15f2 LTS.

A pesar de tener varios elementos listos que me facilitaron el cumplimiento de la prueba, me tocó realizar las implementaciones y modificaciones necesarias para completar otros, como por ejemplo no había pantalla de carga, objetos para la pista, record, entre otros.

 En particular tuve dos problemas con la prueba, no entendí bien con respecto a añadir un sistema de salto, por lo que agregue una rampa, espero que este bien.

Y estuve tratando de agregar una animación al jugador cuando choca con un obstáculo, pero no sé porque en esta versión nueva de Unity no reconocía las sentencias de código, ya que he trabajado anteriormente con animaciones en versiones anteriores y con las mismas sentencias funcionaba correctamente. Luego me tocará investigar más al respecto.

 Lamentablemente no tuve oportunidad de agregar algún extra, ya no me dio tiempo, pero todos los otros aspectos principales están implementados.

EL JUEGO

El juego se encuentra ubicado en :

Assets -> Karting -> Scenes -> elegir escena “IntroMenu”

El objetivo del juego es dar una vuelta antes de que termine los 15 segundos.

Podemos controlar a nuestro jugador con las teclas de flecha o teclas WASD.

En la pista se puede encontrar relojes, que aumentan 5 segundos de tiempo.
Pero hay obstáculos que evitar que son los pinos de bolos, al chocar con estos se pierde 2 segundos de tiempo, dos reduce un poco la velocidad y provoca que nuestro giro sea muy rápido que provoque algo de descontrol por dos segundos.
También hay unas flechas , las cuales nos van a dar un pequeño turbo por 3 segundos.

Sí completamos correctamente la carrera veremos una pantalla de ganador, de lo contrario veremos una correspondiente a perder, en ambas pantallas se va poder ver el récord de la vuelta más rápida.

Busca la mejor manera para completar la vuelta a la pista lo más rápido posible.
