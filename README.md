# Gambito

Prototipo de una plataforma de ajedrez donde los jugadores negocian una apuesta antes de cada partida.

**Demo en vivo:** https://martinezjordan115.github.io/gambito/

## Qué hace

- Ajedrez completo en el navegador: enroque, captura al paso, coronación, jaque mate, ahogado, triple repetición y material insuficiente.
- Dos modos: dos jugadores en la misma pantalla, o contra un bot de práctica (minimax con poda alfa-beta).
- Reloj de 3, 5 o 10 minutos, historial de jugadas y piezas capturadas.
- Mesa de apuesta: un jugador propone, el otro iguala, contraoferta (más alta o más baja) o rechaza. El ganador cobra el bote menos una comisión del 5%.
- Diseño adaptable a celular y modo oscuro.

## Tecnología

- HTML, CSS y JavaScript sin frameworks.
- [chess.js](https://github.com/jhlywa/chess.js) para validar las reglas.

## Estado del proyecto

Es un prototipo para validar la experiencia de juego y de apuesta. Las fichas son de práctica y no tienen valor real.

Siguientes pasos planeados:

1. Multijugador en línea con servidor autoritativo (WebSockets).
2. Análisis de partidas con Stockfish en el servidor para detección de trampas.
3. Cuentas de usuario y verificación de identidad.
4. Revisión legal antes de habilitar cualquier apuesta con dinero real.

## Cómo correrlo

Abre `index.html` en cualquier navegador. No requiere instalación.

## Autor

Jordan Martinez · [GitHub](https://github.com/martinezjordan115)
