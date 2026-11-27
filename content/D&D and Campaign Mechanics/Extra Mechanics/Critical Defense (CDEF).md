# Critical Defense (CDEF)

La **defensa crítica (CDEF)** ofrece una reducción de daño y permite convertir algunos golpes críticos en golpes normales.

| CDEF | Reducción por instancia de daño | Negaciones de crítico por Descanso Largo |
| --- | --- | --- |
| 1 | 1 | 1 |
| 2 | 2 | 2 |
| 3 | 3 | 3 |
## Reducción de daño

Cada vez que recibes daño, reduce el daño de esa instancia en una cantidad igual a tus acumulaciones de CDEF. La reducción se aplica **una sola vez por instancia de daño** y solo al daño al que no se le hayan aplicado **Resistencias o Inmunidades**. Se aplica después de la Resistencia, la Vulnerabilidad y los demás modificadores aplicables, y antes de descontar puntos de golpe temporales o puntos de golpe.

Si una misma instancia incluye varios tipos de daño, resuelve primero las defensas aplicables a cada tipo. Luego *suma el daño que no se haya reducido por Resistencia ni anulado por Inmunidad* y *aplica CDEF una sola vez a ese total*. La reducción no puede exceder ese daño: cualquier reducción sobrante no se aplica al daño que sí fue resistido o anulado por Inmunidad.

**Mínimo de 1.** Si, después de aplicar las demás defensas y modificadores, la instancia infligiría al menos 1 de daño, CDEF no puede reducir su ***daño total*** por debajo de 1.

**Ejemplos.** Cada fila representa una instancia de daño y el objetivo tiene CDEF(2).

| Daño inicial            | Defensa del objetivo         |                                                                     Daño final |
| ----------------------- | ---------------------------- | -----------------------------------------------------------------------------: |
| 10 de fuego             | Ninguna                      |                                                                              8 |
| 10 cortante             | Resistencia al daño cortante |                                                                              5 |
| 6 cortante y 4 de fuego | Resistencia al daño cortante |   5: el daño cortante se reduce a 3 por Resistencia y el de fuego a 2 por CDEF |
| 6 cortante y 1 de fuego | Resistencia al daño cortante | 3: CDEF reduce a 0 el daño de fuego, pero no reduce el daño cortante resistido |
| 1 de fuego              | Ninguna                      |                          1: CDEF no puede reducir la instancia por debajo de 1 |
| 3 de fuego              | Inmunidad al daño de fuego   |                                                                              0 |
|                         |                              |                                                                                |
***El DM decide los casos dudosos sobre si el daño forma una sola instancia o varias.***

## Negar un golpe crítico

Cuando recibes un [[Critical Hits|golpe crítico]], puedes convertirlo en un golpe normal. Debes decidirlo después de saber que el ataque es un crítico y antes de tirar el daño.

El ataque sigue impactando, y el daño se resuelve como un golpe normal y no se aplican los beneficios o efectos que dependan de que el golpe sea crítico.

CDEF ***no reduce el daño de un ataque cuyo crítico hayas convertido en un golpe normal***.

Puedes usar este beneficio un número de veces igual a tus acumulaciones de CDEF. Recuperas todos los usos gastados cuando terminas un Descanso Largo.

**Ejemplo.** Un ataque inflige normalmente 1d4 + 3 y el objetivo tiene CDEF(2) y no tiene Resistencia ni Inmunidad al daño del ataque.
- Si el atacante no tiene CDMG, el crítico maximizado inflige 7, reducido a 5 por CDEF.
- Si el objetivo niega el crítico, el ataque inflige 1d4 + 3 antes de las demás defensas y sin reducción de CDEF.

**Cambios de equipamiento** Los usos gastados pertenecen al personaje y no se recuperan al cambiar de arma o equipamiento. Si tu CDEF cambia, tus usos disponibles son tu CDEF actual menos los usos que has gastado desde tu último Descanso Largo.

CDEF no puede superar 3 acumulaciones efectivas.