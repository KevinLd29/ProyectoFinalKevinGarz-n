# Proyecto Final de «Print("Los gatos de Schrodinger")» 
# Kevin Garzón

Hasta que por fin, llegamos a lo último
En este proyecto final, despues de unas trasnochadas, por fin tenemos el código funcional, afortunadamente si ejecuta.
La historia es una tragedia, empecé con mi grupo que eran de 3, primero canceló una compañera, entonces eramos mi compañero y yo guerreando, haciendo el taller 1 y trabajando en los retos, pero inafortunadamente, cuando más necesitaba ayuda, mi compañero se desaparece, me tocó iniciar con el proyecto a mi solito, pero bueno, no es tiempo de penas. Avancé con la idea, el planteamiento del código en lo cual fui libre porque al ser yo solo, no tenía que contentar a otra persona, entoces me decanté por el lado de mi carrera, de hecho, este tema en la hora de resolución se torna un poco abstracto, lo cual hace que sea beneficioso crear este tipo de programa.

El programa se basa en un tema que causa cierto complique en la química como medio mencioné anteriormente, tiene que ver con la espontaneidad en una reacción, en otras palabras, que tan fácil es que se de o no una reacción
Para que se entienda de una mejor manera, hay que tener los conceptos claros, en este programa hay que tener en cuenta muchas cosas, variables en muchos casos cómo lo son la Entropía, Entalpía y energía libre de Gibbs, que para etender mejor el código y entender para que sirve, aquí algunas definiciones sencillas, por decirlo así, de los temas tratados:

 **Entropía:**
   - La entropía mide el grado de desorden o caos en un sistema.
   - Es como una forma de cuantificar cuán organizado o desorganizado está un sistema.
   - Los sistemas tienden a volverse más desordenados con el tiempo, ya que la entropía tiende a aumentar.

 **Entalpía:**
   - La entalpía es una medida de la cantidad total de energía en un sistema.
   - Incluye la energía interna y la asociada con la presión y el volumen del sistema.
   - En reacciones químicas, los cambios en entalpía indican cuánta energía se absorbe o libera durante la reacción.

 **Energía Libre de Gibbs:**
   - La energía libre de Gibbs (G) mide cuánta energía está disponible para realizar trabajo en un sistema.
   - Predice si una reacción o proceso será espontáneo.
   - Si la energía libre de Gibbs es negativa, la reacción tiende a ocurrir espontáneamente; si es positiva, la reacción no es espontánea.
   - Se relaciona con la entalpía y la entropía mediante la ecuación: ΔG = ΔH - TΔS, donde ΔG es el cambio en la energía libre de Gibbs, ΔH es el cambio en entalpía, ΔS es el cambio en entropía, y T es la temperatura en kelvins.

Entonces, para resumir, la entropía se vincula con el desorden, la entalpía con la energía total, y la energía libre de Gibbs con la disponibilidad de energía para realizar trabajo. Estos conceptos son muy importantes para entender el comportamiento y los cambios en los sistemas químicos.

# Desarollo del código
Para desarrollar el código, fue un complique tambíen, aprovechando la clase de diccionarios, usé la biblioteca matplotlib, estaba entre varias, como por ejemplo Sympy que es compatible con ecuaciones y simbología química, estaba tambien math, pero para mi beneficio, decidí usar matplotlib, que sí, cada linea que ponía me tocaba buscarla en funcionalidades, que me ofrecia, que pasaba si... mejor dicho, quería algo sencillo y funcional y así fue(creo xd)

Empezamos desde el planteo, si, ya lo mencioné, pero de ahí empecé con el desarrollo del código ya teniendo un pseudocodigo, fue un poco triste porque el código que iba poniendo a duras penas funcionaba, pedí ayuda a un amigo que estudia desarrollo de software para que me ayuara a definir una estructura básica, no me pudo  ayudar mucho pero entendí algo jajaja.

Empecé a meter código, dejando solo la estructura, o sea, cómo se sacan las incognitas, definiendo las operaciones que se van a hacer en el programa
Seguidamente, empecé a tantear, puse solo dos compuestos para realizar la prueba y que estuviera funcionando, si lo hacía, pero no funcionaba como quería, entonces me dí cuenta que me faltaba una variable, la famosa temperatura, con mucho miedo de dañar el código (porque así fue, pero se pudo recuperar despúes de investigar como podía aplicar este cambio) puse la funcion de poder añadir la temperatura para que el calculo sea más exacto.

El código no funcionaba, se me pasó la importación de la biblioteca entonces la importé, investigué que funcionalidades me ofrecía y si, en el primer intento todo bien, pero a partir de ahí, no la cargaba, pero aún así, el codigo funcionaba.

# Relleno (?)
Ya para darle más forma al código, añadí más compuestos en la biblioteca para que la posibilidad sea mayor, aún despúes de meter todo eso, mi codigo a penas llegaba a las 200 lineas, entonces pedí ayuda al querido internet, para ver que podía añadirle al codigo para rellenar más sajshaj

Bueno, entonces se llegó a la conclusión de que se podía añadir un archivo externo en el cual se almacenen todos los resultados para la facilidad del usuario, tambien añadir una gráfica para una mayor facilidad.

Y para no alargarnamos más, esto fue una historia resumida, siento que el programa si sirve en un caso real, en mi caso le pude haber pasado el código a la profe de principios de química, para hacer una simulacion y hacer una clase mas interactiva.
El código todavía tiene un muy amplio campo de mejora, que sé que seguiré trabajando en un futuro ya que todo empezó como un proyecto pero le empecé a sentir un cariño, quiero seguir metiendole para generar más utilidad.
¡Muchas gracias!
