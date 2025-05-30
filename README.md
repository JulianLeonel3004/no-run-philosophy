# No run philosophy

**Este manifiesto NO es de programación.**

## Introducción

En general los programadores avanzamos en la carrera leyendo documentación, viendo tutoriales y unos cuantos yendo a la universidad. Avanzamos de jr a semi y por último a sr, no contabilizo el resto porque ya hablaríamos de liderazgo. A pesar de esto, hay unos conceptos que solemos ignorar. Esto intenté encontrarlos en distintos libros, videos, documentos… pero nunca encontré nada. 

Los aspectos ignorados son los que vamos a tratar en el siguiente texto: el entendimiento del dominio (negocio), los conceptos de organización personal y de la iniciativa que llevás, y el trabajo en equipo.

Todo esto es parte de lo que decidí llamar la filosofía del **“No run”**. Porque el aprender y seguir estos conceptos, te evitará los dolores de cabeza de correr detrás de tareas e iniciativas. Te permitirá empezar a tener una claridad sobre lo que se debe hacer y qué no. Haciendo que pares de correr y empieces a crear un valor real, sin necesidad de pasar por el estrés y los tiempos de codeo fuera de horario laboral. 

Ojalá esto te ayude como a mí. Y que tengas un camino profesional mucho más sano.

---

## Entiende el dominio

### ¿Qué es el dominio?

Vamos a empezar con el punto más difícil, y el más abstracto. ¿Qué es entender el negocio?

Recuerdo cuando era jr recién iniciado en la programación, y un líder me dijo que encontré un bug rápido porque entendía el negocio. Mi reacción fue preguntarme ¿Qué entendí del negocio? Mi proceso mental para encontrar el bug fue pensar en qué línea podría estar, yo lo había programado y recordaba por donde estaba. Pero tengo que decir que mi habilidad para reconocer el negocio era nula. Aunque hoy entiendo por qué aparenté conocerlo en esa situación.

El negocio, podríamos definirlo como la respuesta a la pregunta:  
**¿A qué se dedica la empresa a la cual le resolvés el problema?**  
En un ecommerce, es maximizar las ventas; en un banco, mantener la confianza de los clientes; en un hospital, tener una reputación de curar a los pacientes, etc.

Entonces, el negocio es un objetivo muy genérico, que es bueno tenerlo en cuenta pero no va a hacer la diferencia. El punto de quiebre es el dominio, *tú dominio*.

El **dominio** es un sector del negocio, un subnegocio, por así decirlo.  
Si volvemos a los ejemplos anteriores:

- En un ecommerce, puede ser el monitoreo de las entregas de los productos.
- En un hospital, uno podría ser el sistema de turnos, que debería brindar opciones asequibles para los pacientes objetivos.

Por lo tanto, el conocer el dominio te ayuda a ponerte en la piel del usuario y saber qué necesita, aunque este no lo sepa. Esto te ayuda a tomar decisiones certeras, formando un criterio que otorga un valor real al usuario, la empresa y al sistema que estás creando. Sumando una cuota de propósito personal y no caer en la alienación.

### ¿Cómo entendemos el dominio?

Una forma de entenderlo es ponerse en la piel del usuario:

- ¿Qué quiere?
- ¿Qué necesita?
- ¿Lo que hacemos lo ayuda?

**Ejemplo**:  
Volvamos con un hospital, suponiendo que estamos desarrollando un sistema de monitoreo de signos vitales. Uno de ellos es la presión arterial. Cuando sube usamos una flecha hacía arriba verde, y cuando baja una flecha hacía abajo roja.

**¿Cuál es el objetivo?**  
Si lo que buscamos es distinguir cuando sube y baja, podríamos decir que está bien. Pero si nuestro objetivo es visualizar **cuando es un riesgo**, esto no nos dice nada.

- Si la presión estaba alta y procede a bajar, no sería un riesgo, sino algo bueno.
- Bajo ese concepto podríamos plantear conservar las flechas, pero que tengan un color neutro (ejemplo: gris).
  - Si oscila entre subir y bajar pero conserva rangos saludables, no tendrá cambio de color.
  - Si sube o baja fuera de esos rangos, cambia a rojo.
  - Si luego se estabiliza, cambia a verde.
  - Y finalmente, si vuelve a rangos normales, vuelve al color neutro.

Esto daría una información más concreta y muchos más datos de forma visual.

Este es un ejemplo visual, pero pueden ser **números** también:

- ¿Qué número quiere saber el médico?
- ¿Un número constante de presión o solo cuando sale de los rangos?

**No caigamos en decir que esto es solo responsabilidad de UX/UI.**  
Esto es responsabilidad de todo el equipo. El conocer el dominio te permite debatir decisiones de diseño, o de qué número se debe calcular, validar, mostrar. 

Un dev que tenga un nivel técnico excepcional puede darse cuenta si una solución es poco escalable, lenta o inviable.  
Un dev que entienda su dominio puede darse cuenta de que ese feature **no es una solución**, sino que sería un problema implementarlo porque el usuario querrá iterarlo a algo mucho más complejo.

---

## Trabajo en equipo

Perdí la cuenta de la cantidad de veces que me dijeron que hay que trabajar en equipo. Seguramente te pasó igual.  
Te invito a olvidar todo lo que crees saber sobre *trabajo en equipo*. Esto no es un discurso corporativo, es la diferencia entre un grupo de devs estresados y uno que trabaja en sinergia.

Este manuscrito está estructurado de forma incremental, entonces cada concepto importa mucho con el anterior.  
Por lo tanto, el trabajo en equipo va de la mano con el dominio.

Primero hablemos de qué **NO** es trabajar en equipo:

- Trabajar en equipo **no es** separar tareas y repartírselas.
  - Eso es como decir que jugar al fútbol es que haya jugadores que sean arqueros, defensores, centrales y atacantes.
  - Eso no te garantiza el juego en equipo, solo que cada uno sabe sus posiciones.
- Si completás tareas en Jira, reaccionás en el channel de Slack, asistís a las dailys, retro y cumplís todo lo que dice el método Scrum…  
  **Amigo mío, no estás trabajando en equipo, estás siendo un bot.**  
  Y todos fuimos ese bot. Es momento de dejar de serlo.

**¿Por qué debería importarte trabajar en equipo?**  
Porque si no aprendés a hacerlo estás condenado a correr. Tus compañeros deberían ser tu equipo porque tu bienestar laboral también depende de ellos.  
Si conseguís la sinergia, conseguís el “no run”, conseguís la tranquilidad.

### ¿Cómo trabajar en equipo?

Cualquiera pensaría que la respuesta está en preocuparse por lo que hace tu compañero…  
**Pero, ¿y si te digo que no?**

Durante mucho tiempo esa fue mi respuesta, y no pude estar más errado.

Una vez, en un feedback, me dijeron que “vea el producto completo y no solo mis tareas”.  
Eso me hizo un *click*.

La respuesta tiene mucha relación con eso: **tenés que preocuparte por el producto**; y por consecuencia, te preocupás por lo que hacen tus compañeros.

Más arriba había aclarado que era necesario entender el dominio antes de hablar de trabajo en equipo. Era por esto.  
Cuando entendés el dominio y te preocupás por el producto que TODOS están desarrollando, comenzás a escuchar a tus compañeros y empezás a entender ¿qué están haciendo?

Cuando llegás a ese punto, podés conectarlo con tus tareas y entender si:

- Se comete un error.
- Una tarea choca con la tuya.
- Incluso si podrías dar una mano a alguien de tu equipo.

**Entendé el dominio y vas a conocer el trabajo en equipo.**

---

## Divide y vencerás

*Pido perdón por este título, sé que es algo muy quemado, pero no encuentro una mejor forma de decirlo.*

Al organizar una iniciativa, no podemos ver el todo y decir “me lleva 3 semanas” o peor:  
Suponiendo que somos 3 devs y no solo uno, decir “a los 3 nos lleva una semana”.

La **estimación es muy importante**, pero es muy fácil errarle. Tenemos que tener conciencia de eso.

Hay métodos conocidos como la *Planning Poker*, pero si la usamos para estimar features enteros sin desmenuzarlos, no van a ser efectivos.

Para saber cuánto te va a llevar una tarea, primero **lo que estimás debe ser una tarea**.  
Si lo que estás estimando es tan grande que no podés ver un norte, es porque vas a correr.

Cada tarea debe ser una clase, un archivo o una muy pequeña parte de una capa bien dividida.  
Si tenés que estimar un ABM, las tareas van más allá de esto:

- crear alta
- crear baja
- crear modificación

**Rotundamente NO.**  
Cada uno de estos es, prácticamente, un feature.

**Ejemplo: Crear alta significa hacer lo siguiente:**

- Crear `repository` con método `save`.
- Crear `servicio` que, según unos parámetros, llame al método `save` del repository.
- Crear `controller` que valide los posibles `bad_request` y llame al servicio para ejecutar el `save`.

Cada una de las tareas, dependiendo de la persona, el proyecto, el código, puede llevar más o menos tiempo.  
**Pero dividirlo da una verdadera visión de qué hacer, cómo hacerlo y quién pudiera tomar cada una.**

Porque la ventaja de esto es que se pueden **paralelizar** muchos features, para aumentar la velocidad del equipo.

---

## Final

Si llegaste hasta acá, muchas gracias por hacerlo.  
Y ojalá esto te sirva como me sirvió a mí.

Intenté hacer un resumen de lo que me parece más importante para que dejen de correr y empiecen a disfrutar de su trabajo plenamente.

Sé que no todos están en un entorno donde puedan gozar de tranquilidad y la libertad de empezar a aplicar estos principios, pero si lo están, no tengo dudas de que al menos un consejo les va a servir.

Y si no están en ese lugar, cuando puedan **HUYAN** de ahí, y vayan a buscar la paz mental que merecen.

**Mucha suerte en la carrera.**
