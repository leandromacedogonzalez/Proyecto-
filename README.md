🥊 Juego de Pelea 1 vs 1
🎮 Nombre del juego

Pelea Definitiva

Justificación del nombre

El nombre “Pelea Definitiva” representa la intensidad del combate entre dos jugadores que se enfrentan cara a cara hasta que solo uno quede en pie. Es simple, directo y refleja la esencia del juego: un duelo decisivo.

📖 Descripción

Este es un juego de pelea 1 vs 1 desarrollado en GameMaker Studio 2, donde dos jugadores pueden elegir sus personajes y enfrentarse usando movimientos y ataques básicos.

Cada jugador tiene una barra de vida y debe intentar reducir la del oponente a cero para ganar la partida.
Incluye también un selector de personajes y un tutorial interactivo que enseña los controles paso a paso.

🕹️ Controles
Jugador 1

Mover izquierda: A

Mover derecha: D

Golpear (puño): Q

Jugador 2

Mover izquierda: Flecha izquierda (←)

Mover derecha: Flecha derecha (→)

Golpear (puño): Flecha arriba (↑)

⚔️ Mecánica de juego

Cada jugador comienza con 100 puntos de vida (HP).

Cada golpe que conecta quita 10 puntos de vida al oponente.

La barra de vida se muestra en la parte superior de la pantalla.

Los jugadores no pueden salirse de los límites de la pantalla.

Cuando un jugador llega a 0 de vida, aparece un mensaje con el ganador y el juego vuelve a la pantalla de inicio (rm_inicio).

👥 Selector de personaje

Antes del combate, cada jugador selecciona su personaje en el objeto obj_selector.
El obj_controller crea los personajes elegidos para la pelea.
Cada personaje tiene su propio sprite y animaciones de movimiento y ataque.

📘 Tutorial (rm_tutorial)

Muestra los controles paso a paso.

Cada paso avanza al presionar la tecla correspondiente.

Incluye imágenes que representan cada acción.

Al finalizar, vuelve automáticamente a la pantalla de inicio.

💻 Requisitos técnicos

Recurso necesario: GameMaker Studio 2 (para abrir o ejecutar el archivo .yyz y .exe).

Sistema operativo recomendado: Windows 10 o superior.

Resolución recomendada: 480x480 px.

Espacio mínimo requerido en disco: 30 MB.

🧩 Autoría y créditos

Desarrollado por: Leandro Macedo, Pablo Mecoll, Tiziano Fernandez y Jean Ortiz.

Motor de desarrollo: GameMaker Studio 2.

Inspiración: Creado originalmente como un proyecto educativo de pelea 1 vs 1.

Recursos gráficos: Diseñados por el equipo (sin fuentes externas).

👨‍💻 Integrantes y roles
Integrante	Rol	Tareas realizadas
Leandro Macedo	Programador principal	Programación del sistema de combate, controladores y colisiones.
Pablo Mecoll	Diseñador de niveles	Creación de escenarios y diseño del room principal.
Tiziano Fernandez	Artista y animador	Creación de sprites y animaciones de personajes.
Jean Ortiz	Coordinador y tester	Integración del contenido y pruebas de jugabilidad.
