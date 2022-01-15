---
layout: default-slate
permalink: "/:title/"
---


---

_Hace un tiempo quise adentrarme un poco en temas de construcción de mundos de ciencia ficción, e investigué sobre el concepto de la nave espacial. Tristemente, una nave como el Ala-X es totalmente absurda, tanto por la ingente cantidad de leyes naturales que ignora, como por el supuesto rol que ejercería como "caza espacial". De todos modos, la idea de un vehículo para viajar por el espacio es factible, solo que mucho más limitada._

_Investigando todo esto me topé con [este artículo](https://canmom.github.io/physics/designing-a-spaceship) en el blog de una tal canmom. Me resultó muy interesante, y no encontré mucho más tan completo, así que en cuanto me abrí esta página pensé que sería algo que me interesaría tener aquí traducido. Traducirlo también me ha forzado a entender a la fuerza algunas cosas que no me habían quedado muy claras._

_El artículo está traducido sin cambiar gran cosa, alguna expresión que no entendía, y alguna aclaración. Recomiendo echarle un ojo al [blog de canmom](https://canmom.github.io/physics/), su sección de física tiene algunos artículos parecidos a este y en general está interesante._

---

&nbsp;


# Construyendo una nave espacial realista 

&nbsp;

Post original: [Building a realistic spaceship](https://canmom.github.io/physics/designing-a-spaceship)

Por canmom

<!-- 

Artículo traducido de Canmom
Revisado y reexpresado por mí

***

https://canmom.github.io/physics/designing-a-spaceship

http://www.projectrho.com/public_html/rocket/

https://www.quora.com/Are-spaceship-designs-shown-in-movies-possible-How-do-they-work-fictionally-compared-to-real-life

https://worldbuilding.stackexchange.com/questions/12354/what-would-a-space-fighter-look-like

https://www.youtube.com/watch?v=OO6NTx92J18

https://worldbuilding.stackexchange.com/questions/12354/what-would-a-space-fighter-look-like

***
 --> 




> _Pregunta_:\\
Asumiendo que una nave estelar nunca tiene que viajar a través de una atmósfera y no tiene que preocuparse por las colisiones con, por ejemplo asteroides o armas de atacantes (tal vez algún tipo de campo de fuerza, o un sistema de armas interceptor perfecto), ¿hay alguna razón de peso para que las naves espaciales tengan una forma particular? (supongamos también que la nave estelar puede viajar a velocidades relativistas)


¡Ajá!¡Excelente pregunta! Me encanta hablar de naves espaciales.

<!-- 
La mayor parte de lo que sé proviene de [Atomic Rockets](http://www.projectrho.com/public_html/rocket/), que tiene demasiado amor por las viejas novelas de ciencia ficción, pero también mucha información útil y, más recientemente, muchas conversaciones con [arborine](https://geotheologist.tumblr.com/), que ha pensado / sabe mucho sobre los hábitats espaciales y, en general, es maravilloso.
 --> 

Hay algunas consideraciones de diseño que limitan la forma que debe tener la nave espacial ...

1. necesita soportar las tensiones de la aceleración sin romperse
2. necesita disipar el calor generado por la tripulación, la maquinaria a bordo y la luz solar directa en el vacío altamente aislante del espacio
3. necesita poder maniobrar correctamente y, por ejemplo, no empezar a girar incontrolablemente cuando el motor arranque.
4. su rotación debe ser estable a largo plazo en vuelo.
5. debe ser capaz de resistir impactos con escombros interplanetarios / interestelares, que aunque consisten solo en gas enrarecido y partículas pequeñas, pueden (dependiendo de la misión) acercarse a velocidades extremadamente altas, incluso relativistas
6. necesita proteger el equipamiento y la tripulación de la radiación espacial (de estrellas o rayos cósmicos)
7. necesita proteger a la tripulación de cualquier radiación producida por los motores de la nave o su fuente de energía (¡un gran problema si usa algo aterrador como la energía nuclear o la aniquilación de antimateria!)
8. Si hay humanos a bordo, es necesario que tengan compartimentos presurizados para que vivan y espacio suficiente para que se sientan cómodos durante la duración del viaje.
9. necesita minimizar el alcance del daño si algo sale mal, por ejemplo, si parte de la nave se despresuriza.
10. necesita sobrevivir durante toda la duración del viaje, lo que probablemente significa que debe ser autosuficiente
11. Necesita llevar suficiente masa de reacción de propulsor para que la aceleración obtenida sea suficiente para lo que sea que tenga que hacer.
12. Debe ser lo más liviano posible, porque cada unidad de masa de la nave espacial también agrega muchas unidades de masa de reacción, dependiendo de las aceleraciones que requiera la misión (recordemos que frenar en el espacio es tan costoso como acelerar).
13. Si quieres que la tripulación experimente la "gravedad" artificial, debe ser capaz de acelerar cerca de la aceleración de gravedad terrestre durante casi toda la misión, o tener secciones de la nave espacial capaces de girar para crear una fuerza centrífuga similar.

Y seguramente haya muchas más.

De modo que, aunque no hay razón para que tu nave sea de determinada forma, ¡hay un montón de limitaciones!


## 1. Tensiones de propulsión 

#### Hazlo fuerte, quizás pon el motor delante para ahorrar masa


Lo primero depende mucho de dónde coloques tus cohetes. La mayoría de los diseños colocan la propulsión en la parte trasera de la nave, empujando hacia adelante.

Si colocas el sistema de propulsión en la parte trasera de la nave, necesitas que tu nave sea resistente a las fuerzas de compresión, lo que se suma a la masa de la misión: la resistencia a la compresión generalmente requiere vigas masivas, y cosas por el estilo, y es difícil evitarlas. Cuando estás acelerando, se sentirá como si la gravedad empujase todo hacia la parte trasera de la nave y, como un edificio, la nave ha de ser lo suficientemente fuerte para mantenerse intacta. De lo contrario, tu motor atravesará directamente la nave, la aplastará, se romperá o algo igualmente malo.



Algunos diseños, como el *Valkyrie*, y de hecho algunos de los primeros cohetes que se construyeron, tienen el sistema de propulsión en el frente de la nave, remolcando el resto detrás.

Si haces eso, tu nave necesita resistencia a la tracción para no soltarse. Por lo general no se necesita tanta masa para resistir las fuerzas de tracción como para resistir las de compresión, ¡pero poner el motor en la parte delantera significa que tu tripulación está directamente bajo la zona de escape del motor! (el problema de la radiación es un problema general de los motores nucleares y de antimateria, pero es particularmente severo cuando estás justo en el haz del motor...)


<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-00.jpg" style="float:center;width:40%;height:40%;scale:0.9"> 

<!-- 
&nbsp;

&nbsp;
--> 


El *Valkyrie* evita esto al tener un escudo de sombra entre el motor y el compartimento de la tripulación, el cual absorbe la radiación del motor y proyecta una sombra sobre el compartimento.


<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-01.jpg" style="float:center;width:90%;height:90%;scale:0.9"> 

Otra opción es que los motores no apunten directamente hacia atrás, sino que tengan dos o más motores inclinados ligeramente hacia los lados en direcciones opuestas; esto es aparentemente lo que hace la nave en la película *Avatar* (la imagen de arriba, con anotaciones de *Atomic Rockets*).

Poner los motores en la parte delantera con una correa flexible es también una opción, aunque hace que sea mucho más difícil cambiar de dirección.

## 2. Disipación del calor

#### Asegúrate de que tiene grandes superficies planas, o aerosoles de gotitas recuperables que actúen como radiadores

Aunque el espacio a veces es descrito como "frío", especialmente en las películas, es un poco engañoso. Ciertamente, si no estás bajo la luz solar directa, algo en el espacio sin una fuente de calor eventualmente te enfriarás hasta temperaturas increíblemente bajas... pero por la misma razón por la que usamos frascos de vacío para mantener el té o lo que sea caliente, lleva mucho tiempo.


Si tienes algo como una nave espacial, que genera mucho calor, debes hacer algo para disipar ese calor. El único mecanismo por el que se puede perder calor en el espacio, sin atmósfera que lo lleve, es la radiación electromagnética. Para perder calor a través de la radiación, se necesita una gran superficie (es decir, grandes superficies planas llamadas "radiadores") y llevar el calor del resto de tu nave a los radiadores. Calientas los radiadores y ellos irradian su calor hacia el vacío.


<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-02.jpg" style="float:center;width:90%;height:90%;scale:0.9"> 


El transbordador espacial abria las puertas de su bahía de carga en el espacio para ayudarlo a irradiar el calor (etiquenas una vez más de *Atomic Rockets*).

Sus radiadores no deben tener sus superficies enfrentadas, o de lo contrario se calentarán entre sí y no irradiarán calor con tanta eficacia.



<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-03.jpg" style="float:center;width:90%;height:90%;scale:0.9"> 


Otro truco para enfriar la nave es usar un "Radiador de gotas de líquido" (la imagen de arriba representa el diseño "ICAN-II" de la Universidad de Penn State, no tengo idea de lo que significa). Esto implica usar el calor residual para calentar un rocío de gotas de líquido caliente, que viajan a través del espacio, enfriándose constantemente. A medida que la nave se acelera, las gotas "caen" hacia la parte trasera o delantera de la nave (según la dirección que tome) y pueden recogerse, calentarse y pulverizarse en la dirección opuesta, manteniendo una circulación continua.

*Atomic Rockets* tiene [algunos diseños realmente extraños](http://www.projectrho.com/public_html/rocket/basicdesign.php#id--Heat_Radiators--Radiator_Types--Liquid_Droplet), que incluyen discos, triángulos e incluso uno que parece una espiral (usando campos magnéticos). Hay también otros diseños en *Atomic Rockets* que no he cubierto, usando burbujas, filamentos de nanotubos, y toda clase de cosas.


## 3. Maniobrabilidad
#### Asegurate de que el vector de empuje pase por el centro de masa

Si no lo hace - si el motor está descentrado - cuando el motor arranque tendrá un momento angular (par) distinto de cero. Esto hará que la nave comience a girar alrededor de su centro de masa. A veces esto es intencional, ¡pero normalmente solo en una pequeña cantidad! Y, por lo general, una brusca propulsión lo haría girar violentamente. De modo que lo más cómodo es tener pequeños propulsores separados para girar.

Esto se complica todavía más si tu nave tiene elementos flexibles.

## 4. Rotación estable
#### Si tu nave está girando, procura que lo haga alrededor de su eje mayor

Todo cuerpo rígido tiene una cosa llamada tensor de momento de inercia que se puede calcular a partir de su distribución de masa. Sus valores propios (eigenvalores) se llaman momentos principales de inercia y sus vectores propios (eigenvectores) se llaman los ejes principales del cuerpo. Cuando el motor no está encendido, la nave está en [libre precesión](https://en.wikipedia.org/wiki/Precession#Torque-free).

Recuerdo una serie de discusiones sobre la precesión libre en nuestras conferencias de mecánica clásica en las que se decía que, dado que un cuerpo no del todo rígido pierde energía lentamente debido a las tensiones internas, pero conserva el momento angular, se precesa (el vector de velocidad angular se mueve con respecto a la coordenadas del cuerpo, si eso significa algo para tí) para terminar girando alrededor del eje principal con el mayor momento de inercia.

Si planeas que tu nave gire alrededor de un eje diferente, deberías andar con cuidado, ya que precesará lentamente para girar alrededor del eje mayor.


<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-04.jpg" style="float:center;width:90%;height:90%;scale:0.9"> 

Cuando Estados Unidos lanzó su primer satélite, el *Explorer 1*, en 1958, esto no se sabía. El satélite, de forma similar a la de un bolígrafo, lo pusieron a girar alrededor de su eje menor, el eje largo a través del centro de la nave.
Para sorpresa de los científicos, el eje de rotación cambiaba en vuelo, hasta que el satélite se quedaba girando de un extremo a otro. Esto llevó al primer desarrollo de la rotación de Euler (el tipo de cosas de las que estamos hablando) en más de 200 años. Pero ya está hecho, así que asegúrate de que tu nave gire alrededor de su eje principal, si gira.

([Scott Manley hablando del tema](https://youtu.be/X_rp5slf3c4?t=499))

## 5. Velocidades relativistas
#### Si vas demasiado rápido, la nave debe estar a salvo del polvo relativista

Una pequeña mota de polvo, cuando se eleva a velocidades relativistas (cercanas a la velocidad de la luz), puede tener la energía cinética de una bala o una bomba. Y, si tu nave está viajando por el espacio a velocidades relativistas, ¡cada mota de polvo en el espacio se acercará a tu nave a esas velocidades! Esto es malo.

Una solución es colocar un escudo en la parte delantera de la nave espacial, que será golpeado por el polvo relativista, pero que dispersará la mayor parte de su energía antes de que golpee algo importante.

<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-00.jpg" style="float:center;width:40%;height:40%;scale:0.9"> 

Voy a hablar del _Valkyrie_ otra vez. Quizás me gusta demasiado este diseño, pero su solución es realmente genial.

El _Valkyrie_ rocía gotas de líquido delante de la nave. Cualquier partícula entrante puede detonar inofensivamente contra las gotas, sin causar daño al aparato. Debido a que la nave acelera constantemente, las gotas de líquido "caerán" y aterrizarán relativamente lentas en la parte delantera de la nave, donde pueden reciclarse. También se utiliza para enfriar, otro "radiador de gotas líquidas".

Durante la deceleración, esto no funciona: las gotas se escapan por delante de la nave en lugar de ser recapturadas. La solución del _Valkyrie_ es triturar los tanques de combustible gastado en polvo fino y soltarlos delante de la nave a medida que decelera. Viajando a una velocidad relativista constante, los tanques de combustible triturados abrirán camino a través de las partículas de polvo interestelar que pudiera haber ante la nave.

Algo de polvo aún así se abriría paso hasta la nave, por lo que además de este truco, el _Valkyrie_ extiende muchas capas de "mantas" de material extremadamente delgado (similar a Mylar) por delante de la nave. Como la nave acelera en dirección opuesta, las mantas se extenderán frente a la nave.

Obviamente, nada ni remotamente cercano se ha llegado a intentar jamás. Así que, ¿quién sabe si realmente funcionaría? En cualquier caso, no he visto ninguna discusión sobre el polvo relativista en otros diseños de _Atomic Rockets_.



## 6. Protección frente a radiación espacial

Incluso si no viajas a velocidades relativistas, (sin la protección de una atmósfera) serás irradiado constantemente por rayos cósmicos y otras radiaciones ionizantes de cualquier estrella cercana. Esto es un problema incluso para los astronautas actuales, que se esconden detrás de los tanques de agua durante períodos de radiación particularmente intensa. A menudo es considerado como uno de los principales peligros de un viaje a Marte.

Hasta cierto punto, estás protegido por el casco de tu nave, que absorbe la mayoría de los tipos de radiación incluso si es bastante delgada. Necesita dos capas para lidiar con diferentes tipos de radiación, ya que, por ejemplo, el plomo usado para parar los rayos gamma pueden generar rayos X mortales. Todo espacio donde la gente vivirá, a largo plazo, debe protegerse de esta manera.

Durante los períodos de mayor radiación, como las erupciones solares, esto puede no ser suficiente. Necesitas que una parte de la nave espacial esté particularmente bien protegida para esconderse en estos momentos. Un método consiste en utilizar el agua (que de todos modos se lleva para beber) para proteger a la tripulación en esos momentos. Necesitas una forma de que la tripulación acceda a este área y lleve cualquier cosa particularmente vulnerable a la radiación, como alimentos, para ponerlo a salvo.

Parece ser que se están considerando otros métodos, que involucran cosas como poderosos campos eléctricos o magnéticos o burbujas de plasma, pero no sé mucho sobre ello.



## 7. Protección frente radiación propia

Para viajar largas distancias en el espacio, los cohetes químicos no suelen ser suficientes; necesitas algo con una capacidad de aceleración muy alta. Se han diseñado muchos de estos sistemas de propulsión, pero tienden a tener el efecto secundario de producir una gran cantidad de radiación ionizante. 

Esto no es necesariamente un gran problema. No es necesario que protejas todo tu reactor (que sería muy pesado), sino que puedes usar un escudo de sombra, como discutimos sobre el _Valkyrie_, para mantener tu nave a salvo de la radiación y dejar que el resto de la la radiación irradie al espacio. Pero sí implica que el resto de la nave, incluidos los radiadores térmicos, necesita mantenerse dentro del cono de seguridad creado por su escudo de sombra. Y su escudo de sombra suele ser bastante masivo, porque la principal forma en que atenuamos la radiación es hacer un bulto de materiales muy densos.

Aquí hay un ejemplo de un diseño de la NASA que usa un escudo de sombra y tiene que mantener sus radiaciones dentro de la sombra:


<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-06.jpg" style="float:center;width:90%;height:90%;scale:0.9"> 


## 8. Habitabilidad
#### Debe tener areas presurizadas para que los humanos respiren.

La presión fuera de la nave espacial es inexistente. La presión dentro de la nave espacial es probablemente de aproximadamente 1 atmósfera. Tu nave debe ser lo suficientemente fuerte para contener eso.

Definitivamente no quieres tener demasiadas partes de tu nave particularmente vulnerables a la ruptura, por lo que las paredes de sus áreas presurizadas probablemente serán agradables y curvas con esquinas mínimas.

Una forma de construir un recipiente a presión, como lo hacemos actualmente, es usar mucho metal fuerte. Pero eso agrega mucho a su masa de carga útil. Entonces otra posibilidad es tener una nave espacial inflable.

La NASA tiene uno de esos diseños llamado TransHab. Lo que supongo significa que no puede ser abordado por personas cis. Es algo así ([fuente](https://en.wikipedia.org/wiki/TransHab))


<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-07.jpg" style="float:center;width:90%;height:90%;scale:0.9"> 



## 9. Seguridad
#### Necesita ser capaz de lidiar con problemas con los mínimos daños posibles

A pesar de todos tus mejores esfuerzos, parece inevitable que en un compartimento presurizado que viaja a través del vacío del espacio algo salga terriblemente mal. Por ejemplo, si algo hace un agujero en el casco. Es necesario que eso no termine la misión y cause el menor daño posible a la tripulación.

Esto probablemente significa, internamente, que tu nave debe dividirse en compartimentos separados, de modo que si uno se despresuriza, el resto todavía está seguro. Si las paredes de tu nave pueden ser autosellables de alguna manera, aún mejor.


## 10. Sostenibilidad
#### Necesita auto-repararse y un ecosistema de autorenovación para un largo viaje.


Si estás haciendo un viaje muy largo, llevar suministros para todo el viaje requiere demasiada masa. Es mejor llevar consigo un ecosistema funcional y duradero de plantas, etc., que no se muera durante el viaje.

Crear un ecosistema cerrado es _muy difícil_ - hasta donde yo sé, no se ha logrado todavía. 

Además, partes de la nave lentamente irán fallando y se irán deteriorando. _Atomic Rockets_ afirma que las mejores pruebas de la NASA pueden durar 40 años en el espacio, y eso puede no ser suficiente para tus propósitos (incluso aprovechando al máximo la dilatación del tiempo relativista). Para un viaje muy largo, como una nave generacional o algo así, se puede suponer que todo va a ir mal, de modo que hasta cierto punto la nave debe tener las capacidades a bordo para reconstruirse incluso fuera de la seguridad de los compartimentos de la tripulación.

La necesidad de utilizarlos en ruta podría restringir los materiales que se pueden usar, y por tanto las formas que puede tener.

También es interesante pensar que la cantidad de almacenamiento digital disponible para la tripulación en una nave generacional, a no ser que puedan construir más ordenadores, se reducirá en el transcurso de la misión, lo cual podría tener interesantes efectos a nivel social.



## 11. Combustible
#### Probablemente necesites dedicar una gran parte de la nave espacial a almacenar la masa de reacción en los contenedores adecuados.

Una consecuencia de la ecuación del cohete es que por cada gramo (o cualquier unidad de masa) de carga útil (elementos estructurales, personas, comida, computadoras, robots, lo que sea) que tengas, necesitarás una cierta cantidad de gramos de masa de reacción para lanzar por la parte trasera del cohete, para propulsar.

(Una excepción a esto sería si usas un sistema propulsor como la vela solar o una vela laser en las que eres propulsado por colisiones con un material que no estás llevando contigo. O si has averiguado como hacer práctico al Estatorreactor Bussard, o cualquiera de sus variantes)

La forma de tus tanques de combustible depende en gran medida del tipo de reactor que uses, pero básicamente necesitas muchos recipientes a presión en algún lugar de la nave, probablemente separados de los módulos de la tripulación.




## 12. Ligereza
#### Debe ser realmente ligero, todo lo posible

La ecuación del cohete es una cosa muy demandante, y a menos que de algún modo vayas muy sobrado, quieres aprovechar cualquier oportunidad para ahorrar masa. ("Ir sobrado" sería algo como usar el Proyecto Orion para viajar dentro del sistema solar o algo así).

Por eso muchos diseños de naves son módulos unidos por una ligera estructura, porque quieres minimizar los elementos estructurales pesados todo cuanto sea posible.

Ya hemos hablado un poco sobre esto antes.


## 13. Gravedad artificial
#### Si proporciona gravedad, necesitas mucha aceleración o algo que gire


En un viaje largo, los huesos y músculos de la tripulación se atrofiarán a menos que se les proporcione un entorno con una fuente de "gravedad" similar a la de la Tierra.

Hay dos maneras de lograr esto, que implican acelerar toda tu nave o alguna parte de ella. Una manera es impulsarse de modo que la aceleración proporcione una fuerza equivalente a la experimentada por la gravedad, a lo largo de todo el viaje. Para comparar, las misiones espaciales actuales implican generalmente propulsiones muy breves, y mantienen la nave volando libremente durante la mayor parte de la misión. Para impulsarse a lo largo de toda la misión, la nave necesita _mucha_ más capacidad de aceleración, y por lo tanto mucha más masa propulsora por unidad de masa de carga útil.

Dado que eso es bastante exigente, la otra opción es hacer girar parte de tu nave espacial. Esto podría ser, por ejemplo, un anillo toroidal, un cilindro, una esfera o un par de habitaciones al final de brazos largos.

Dependiendo de como de larga sea la sección rotatoria, tendrá que girar más o menos rápido para mantener la gravedad necesaria. La aceleración centrífuga en un sistema de referencia rotatorio viene dada de multiplicar el cuadrado de la velocidad angular por la distancia al centro de rotación.



<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-08.png" style="float:center;width:90%;height:90%;scale:0.9"> 

Ten en cuenta que esto significa que la "gravedad" artificial en una sección giratoria con varios pisos, o en un hábitat esférico, variará a medida que se acerque o se aleje del centro. Cuanto más lejos estés, más fuerte será la gravedad.

Una sección de hábitat giratorio tiene algunas implicaciones sobre tu diseño interior. Las superficies "niveladas" serán curvadas en lugar de planas, y el efecto Coriolis se aplicará para desviar trayectorias desde una línea recta, especialmente en una sección pequeña que gira rápidamente.

Hay muchas dificultades que superar si solo una parte de tu nave está girando. Uno de los principales es el problema del soporte entre la sección giratoria y el resto de la nave: debe estar casi sin fricción o tu sección giratoria frenará lentamente su giro (y tu nave girará lentamente).

Otro problema proviene de hacer girar tu sección de giro sin que el resto de la nave espacial gire en la dirección opuesta (con posibles consecuencias de precesión y similares). Una solución es tener un volante de inercia dentro de tu nave, pero esto implica una gran masa que generalmente es inútil. Otra es tener múltiples secciones de giro en sentido contrario, de modo que el cambio de momento angular neto pueda ser 0 sin que toda la nave gire.

O bien, puedes dejar que toda la nave gire a la vez, aunque esto hace que maniobrar la nave sea algo complicado debido a la forma en que actúan los giroscopios (se convierte en una precesión forzada, y debe empujar en 90º desde la dirección en la que realmente quieres girar.


<!--  --> 
<img src="{{site.baseurl}}/assets/nave/img-09.jpg" style="float:center;width:90%;height:90%;scale:0.9"> 



Otro problema proviene del hecho de que, cuando tu nave espacial se acelera, la dirección de lo que es "abajo" cambiará. Esto puede adaptarse a algunos diseños de apariencia muy complicada que involucran brazos que se balancean hacia adentro y hacia afuera, o simplemente ser ignorados porque la mayor parte del tiempo la nave no está acelerando.


## Y más cosas, probablemente

De modo que, sí, hay _muchas_ demandas físicas en la forma de una nave espacial, ¡incluso una que nunca visita una atmósfera!

Construir una nave espacial es muy diferente a construir en la Tierra y, por supuesto, nadie _sabe_ realmente cómo construir una nave espacial para un viaje interestelar. Pero esto es lo que pensamos, basándonos en las limitaciones físicas que hemos imaginado hasta ahora ...






&nbsp;

&nbsp;



<script src="https://utteranc.es/client.js"
        repo="adrianriverof/blog"
        issue-term="pathname"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>

