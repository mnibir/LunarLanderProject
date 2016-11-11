# LunarLanderProject

## DAW1. LENGUAJE DE MARCAS. LUNAR LANDER

Codificación de la propuesta del grupo formado por: D. Aranda Hevia, F.M. Estelrich Cánaves, D. Rodríguez Cardell y J.S. Vera Fernando.

### Componentes

1	Fondo estrellado repetitivo en la parte superior y central de la pantalla. Hecho a partir de la imagen que me pasaron y estableciendo un tamaño de imagen de 300px x 300px.
2	Suelo lunar en la parte inferior de la pantalla. Hecho a partir de la imagen que me pasaron y coloreando la parte superior de dicha imagen (previamente transparente) del mismo color del cielo estrellado de fondo (usando GIMP).
o	Botón "pausa" en esquina superior derecha con menú desplegable con las opciones del juego (i.e. controles, cambio nave, sonido/silencio, reiniciar y salir). Hecho.
o	Panel de control en la esquina superior izquierda (i.e. landing time, speed y fuel). Hecho, creando la barra de fuel.
o	Nave centrada en la parte superior. Hecho.
o	Plataforma centrada en la parte inferior. Hecho, creando la plataforma y colocándola entre cielo-suelo.
o	Pinchos a ambos lados de la plataforma en caso de que la nave también pudiera moverse horizontalmente, pero, al descartarse dicha opción, la presencia de pinchos ya no tenía sentido por lo que éstos no se han incluido.


### Parte técnica. Propuesta horizontal vs. propuesta vertical

o	Tamaño del suelo lunar: 100% x 15% en pantalla horizontal vs. 100% x 5% en pantalla vertical. Hecho, modificando entonces el tamaño relativo asignado a todo el fondo estrellado y el tamaño y la localización de la plataforma.
o	Tamaño del menú desplegable: height = 35% en pantalla horizontal vs. height = 25% en pantalla vertical. Hecho, habiendo de adaptar el margen entre sus elementos de manera que éstos se distribuyan adecuadamente y recolocando la posición del menú en la pantalla según la localización del botón "pausa".
o	Tamaño de la nave: height = 15% en pantalla horizontal vs. height = 7% en pantalla vertical. Hecho, manteniendo un tamaño horizontal proporcional al tamaño vertical establecido para no deformar la imagen.
o	La nave colocarla bajo el panel de control, incluyendo una redistribución de elementos del propio panel de control, en función del espacio horizontal disponible de manera que no se superpongan entre sí.
