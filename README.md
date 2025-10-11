========================
JUEGO DE PELEA 1 VS 1
========================

DESCRIPCIÓN
------------
Este es un juego de pelea 1 vs 1 hecho en GameMaker.
Dos jugadores pueden elegir sus personajes y enfrentarse usando movimientos y ataques básicos.

CONTROLES

Jugador 1:
- Mover izquierda: A
- Mover derecha : D
- Golpear (puño) : Q

Jugador 2:
- Mover izquierda: Flecha izquierda (←)
- Mover derecha : Flecha derecha (→)
- Golpear (puño) : Flecha arriba (↑)

MECÁNICA DE JUEGO
-----------------
1. Cada jugador tiene 100 puntos de vida (hp).
2. Cada puño que conecta le quita 10 de vida al oponente.
3. La vida se muestra con una barra de vida en la parte superior de la pantalla.
4. Los jugadores no pueden salirse de los límites de la pantalla.
5. Cuando la vida de un jugador llega a 0, se muestra un mensaje indicando quién ganó y el juego vuelve a la pantalla de inicio (rm_inicio).

SELECTOR DE PERSONAJE
---------------------
- Antes de pelear, cada jugador selecciona su personaje en el objeto obj_selector.
- El obj_controller instancia los personajes seleccionados para la pelea.
- Cada personaje tiene su propio sprite y animaciones de movimiento y ataque.

TUTORIAL (rm_tutorial)
----------------------
- Al iniciar el tutorial, se muestran los controles paso a paso.
- Debes presionar la tecla correspondiente para avanzar al siguiente paso.
- El tutorial incluye representación visual de cada acción para aprender fácilmente.
- Al finalizar, vuelve automáticamente a la pantalla de inicio.

RECOMENDACIONES
---------------
- Jugar en pantalla de 480x480 px para que los personajes y barras de vida se vean correctamente.
- Asegurarse de que los sprites de los personajes estén asignados correctamente en el obj_selector y en los objetos de jugador.
- Revisar que las variables hp y max_hp estén definidas en cada objeto jugador para que la barra de vida funcione.

CRÉDITOS
--------
- Desarrollado por: [Leandro Macedo, Pablo Mecoll, Tiziano Fernandez y Jean Ortiz]
- GameMaker Studio 2
