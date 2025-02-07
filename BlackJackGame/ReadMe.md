# Juego de Black Jack en Python

¡Un juego simplificado de 21 creado para Python!

## Valores de las cartas
Los palos no afectan los valores de las cartas.

Del 2 al 10 tienen el mismo valor que el nombre de la carta.
J, Q y K valen 10.
Ases: si sumar 11 hace que la puntuación supere los 21, entonces el as vale 1. De lo contrario, vale 11.

## Jugabilidad
Simplemente ejecute el script para comenzar a jugar. La mano comienza con el jugador y el crupier recibiendo dos cartas. El jugador solo ve una de las cartas del crupier al comienzo. El jugador empieza y elige pedir carta (presione 1) o quedarse (presione 0). Si el jugador recibe más de 21 puntos, se pasará y habrá perdido la mano. Después de que el jugador seleccione quedarse, es el turno del crupier. El crupier pide carta hasta que reciba una puntuación más alta que el jugador (el jugador pierde) o se pase (el jugador gana).

## Blackjack
Un jugador obtiene un 'Blackjack' si recibe una carta con un valor de 10 y un As al comienzo de la mano. Esto automáticamente gana el juego.

**Tenga en cuenta que el propósito de este script es permitir que el usuario juegue una mano simple de Blackjack sin algunas de las partes de nivel superior del juego, como apostar o dividir dobles. Todos los empates van al jugador en esta versión del juego.

## Implementación

Para implementar este proyecto, ejecute

```bash
python BlackJackGame.py
```