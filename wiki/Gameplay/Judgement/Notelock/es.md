---
tags:
  - note lock
  - jittering notes
  - shaking notes
  - notas bloqueadas
  - notas temblorosas
  - agitando notas
---

# Notelock

![](img/notelock.gif "Un ejemplo del notelock: la segunda nota es inaccesible")

El **notelock**, o **bloqueo de nota**, es un término informal para la mecánica del juego [osu!](/wiki/Game_mode/osu!), el cual puede evitar que un jugador elimine un objeto. Esto pasa si **dos** condiciones se cumplen al mismo tiempo:

1. Las [ventanas de tiempo](/wiki/Beatmap/Overall_difficulty#tiempo) de dos objetos se superponen.
2. El primer objeto de los dos aún no ha sido juzgado (acertado o fallado).

En este caso, se dice que el segundo objeto está *bloqueado* ante el primero, lo que hace que osu! ignore los golpes del jugador hasta que haya pasado la ventana de golpeo del primer objeto. El notelock solo es un problema si el jugador no puede volver al objeto anterior e interactuar con él correctamente, así se quita el bloqueo. En ese caso, una nota bloqueada puede causar un fallo en cascada, forzando al jugador a fallar más y más objetos posteriores, hasta quedar sin [salud](/wiki/Gameplay/Health) y fallar el beatmap.

Cuando se produce el notelock, el círculo se sacudirá. Esto no sucede con deslizadores o ruletas.

## Causa

El notelock es parte del sistema de la ventana de tempo de osu!, y sucede cuando la ventana de tiempo de dos objetos se superponen. Esto ocurre con mayor frecuencia en beatmaps con valores bajos de [OD](/wiki/Beatmap/Overall_difficulty) o valores altos de [PPM](/wiki/Music_theory/Tempo), ya que en estos casos son más frecuentes la superposición en la ventana de tiempo.

Dado que regularmente los objetos en los beatmaps de osu! están destinados a borrarse en orden cronológico, el rechazo de golpes causados por el notelock, generalmente juega un papel positivo como:

- Evitar que los jugadores ignoren partes de un beatmap
- En las dificultades más grandes y rápidas, evita que los jugadores pierdan el ritmo y se desincronicen

## Prevención

Desde la perspectiva de un mapper, el notelock se puede evitar, si se elige cuidadosamente el valor del OD de una [dificultad](/wiki/Beatmap/Difficulty) de acuerdo a su densidad y PPM. En beatmaps con PPM de 200 o más, es recomendable usar un OD de 5 o más. Para un desglose más detallado, consulta la guía «[Avoiding notelock at high BPM](https://osu.ppy.sh/community/forums/topics/334458)».
