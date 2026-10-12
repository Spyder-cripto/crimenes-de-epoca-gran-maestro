# Crímenes de época: Gran Maestro

Un solo caso, el más difícil de la colección: **Los idus de marzo**, en casa de un senador romano. Un sudoku de asesinatos en
un tablero de 10x10 con diez sospechosos: coloca a cada uno en su sitio, uno por fila y por columna, y descubre quién se quedó
a solas con la víctima. Juego web autónomo en un único `index.html`.

**Jugar:** https://spyder-cripto.github.io/crimenes-de-epoca-gran-maestro/ · Para calentar antes:
[cinco crímenes en cinco mundos](https://spyder-cripto.github.io/crimenes-de-epoca/) y
[cinco en la Edad Media](https://spyder-cripto.github.io/crimenes-de-epoca-edad-media/).

![Crímenes de época: Gran Maestro](captura.png)

## Qué tiene de especial un Gran Maestro
En los niveles de fácil a maestro basta con deducir y, como mucho, con suposiciones sencillas: «¿y si estuviera aquí?».
Siguiendo las consecuencias, algo deja de cuadrar y esa casilla se descarta. Aquí llega un momento en que eso **no basta**,
aunque se cuenten las zonas. Para seguir, hay dos caminos:
- suponer algo y, **dentro de esa suposición**, suponer otra cosa;
- dar con un razonamiento de conjunto muy bien escondido.

Lo hemos comprobado por ordenador: los diez casos de las otras dos webs, maestros incluidos, salen con suposiciones sencillas,
y este no. Además, en una prueba a ciegas, un solucionador experto lo resolvió sin ver la solución. Las pistas enseñan el
camino de la doble suposición, paso a paso.

## Cómo se juega
- En cada **fila** y en cada **columna** hay exactamente **una persona**.
- Coloca a los sospechosos según sus pistas; la víctima va en la casilla que queda libre.
- El **asesino** es la única persona que estaba en la misma zona que la víctima.
- **Ninguna zona se quedó vacía.**
- No se puede estar en una casilla con un objeto, salvo los que se ocupan (lechos, la silla curul, bancos…).
- «Al lado de» es arriba, abajo, a la izquierda o a la derecha; «al este de», en cualquier columna a su derecha; «al norte de»,
  en cualquier fila más arriba.
- **La conjura**, la regla especial de Roma: los **patricios** siempre están sobre **mosaico**, los **esclavos** nunca, y dos
  **conjurados** nunca están en la misma zona.
- **Colocar**, **notas** (las iniciales de quien podría estar en cada casilla) y **tachar**; deshacer, comprobar y pistas
  opcionales.

El caso tiene una sola solución, comprobada por ordenador con programas escritos por separado. Hacen falta las dos partes de
la regla especial y «ninguna zona vacía», y no sobra ninguna pista.

## Créditos
- Caso, regla especial, arte y textos: **Spider** (Fali + Claude), 2026.
- Inspirado en los *Murdoku* de Manuel Garand.
