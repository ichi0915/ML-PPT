# ML-PPT
Machine Learning Piedra, Papel y Tijera

Este Programa tiene 3 Modos:
  -Easy: La computadora elige entre una de las 3 opciones de manera random.
  -Hard: La computadora predice que vas a elegir dependiendo de otros patrones ya guardados.
  -Impossible!: La computadora elige aquella opcion que te va a vencer.

Futuras Actualizaciones:
  -Conectar Hard.txt a un servidor para cuando mas gente juegue se actualize la informacion.
  -Analizar el patron del jugador actual mas el de otros jugadores.

El Codigo:
  -Modo Hard se basa en la ronda anterior.
  -Checa que han elegido la mayoria de los jugadores y luego considera lo que el jugador eligio en su ultimo movimiento y el resultado de dicha eleccion.
  -Ejem Cual es el siguiente movimiento de la mayoria de los jugadores si acaban de perder contra las Tijeras.

Explicacion de Hard.txt:
  -El primer digito despues de "move:" representa lo que el jugador eligio la ultima ronda (1-rock, 2-paper, 3-scissors)
  -El segundo digito despues de "move:" representa lo que la computadora eligio la ultima ronda (1-rock, 2-paper, 3-scissors)
  -Las lineas "r,p,s" representan el numero de veces que cada jugador a elegido cada opcion
  
