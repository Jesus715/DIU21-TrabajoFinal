# DIU21 - Trabajo final : Resolución de un problema, caso y/o supuesto práctico
Voy a hacer un comentario a modo de conclusión de los conocimientos que he adquirido con esta asignatura, para posteriormente realizar un análisis de un caso de estudio, y seguidamente establecer una propuesta de
mejora basado en evidencias (*insights*) con una propuesta de diseño del interfaz (de al menos de un
mockup).


## PARTE I : MI EXPERIENCIA UX

   Para describir mi experiencia en estos campos, primero tenemos que entender que **UX (User eXperience)** es un proceso por el que inducimos al usuario de nuestro producto a *generar emociones positivas* sobre él. Para este fin utilizamos la **IU (UI, User Interface)**, diseñándola del tal forma que nuestro producto sea atractivo y visual para el usuario. Con estos dos conceptos podemos medir cuál será la **Usabilidad**, es decir, cómo de usable es nuestro producto para los diferentes usuarios en función de sus objetivos específicos. 

   Una vez teniendo claros los conceptos, las conclusiones que he obtenido sobre esto, y basándome en los resultados de los diferentes ejercicios propuestos en clase a lo largo del cuatrimestre han sido:
    
   * **Actividad 1. Etnografía :**
    Lo que saco en claro de esta actividad es que es muy necesario pararse, abstraerse de nuestros pensamientos y opiniones subjetivas, y disponernos a observar al usuario, lo que le acontece, su contexto, cualquier detalle que nos pueda ayudar a solucionar un problema cotidiano, y además, tener en cuenta aquello que no observamos, pero que se intuye, para poder realizar posteriormente un diseño más objetivo en función de los requerimientos del usuario a quien va dirigida nuestra aplicación o servicio. Gracias a esta actividad teórica, pudimos desarrollar unos personajes para las prácticas, poniéndonos en su lugar y obteniendo así nuevos puntos de vista de cara al desarrollo del diseño de nuestra aplicación, que de no haberlo hecho no hubiésemos contemplado esas casuísticas.
    
   * **Actividad 2. Usabilidad :**
    A través de este ejercicio, he entendido que son igual de importantes las partes de *Heurística*, la cuál trata de examinar la calidad de uso de la interfaz siguiendo una serie de pautas que van desde aspectos más genéricos como una buena visibilidad, diseño claro y estético, que use distintos idiomas, buena navegabilidad, situación del usuario en cada momento (con *breadcrumbs*), etcétera. Para esto podemos usar diferentes técnicas como *entrevistas, card sorting, diagramas de afinidad, checklist.* Esta última fue la que usamos y, personalmente, si se hace una buena selección de los elementos a checkear, es una técnica bastante fiable para dar una valoración de la usabilidad de una aplicación. El tener estos conocimientos nos permitió aplicar a nuestro diseño de prácticas serias mejoras como minimizar el número de clicks para llegar a cualquier parte, añadir *"migas de pan"* y menú de navegación en el *footer*,  mejorando nuestra navegabilidad, haciendo un diseño más simple, con pestañas y botones intuitivos, formularios simples y con campos claros, etcétera. 
    
   * **Actividad 3. Accesibilidad :**
   Tras la realización de esta actividad, me he dado cuenta de la importancia que tiene hacer una aplicación accesible, para ampliar el abanico de usuarios de nuestra aplicación. Y no sólo para problemas físicos o mentales de los propios usuarios, sino también de los dispositivos desde los que acceden a ella, incluso contemplar posibles factores de la naturaleza como pudiese ser el reflejo del sol o un brillo muy elevado del dispositivo. No se trata sólo de hacerla accesible, sino de explicarle al usuario cómo puede usar nuestra aplicación en caso de necesitar ayuda. Además de darme cuenta de la complejidad y la minuciosidad que requiere este apartado. 
   

## PARTE II : Caso de estudio. Web YUZIN
   Para la realización de este apartado, he decidido seguir las pautas de la práctica de evaluación, ya que permite aplicar los conocimientos adquiridos, y mencionados en la parte anterior, de una manera clara y ordenada, sin dejar ningún aspecto por contemplar. 

**a. Role Play**
---

   He usado esta técnica para la selección de necesidades de 2 usuarios, obteniendo la siguiente tabla :
   | Tiradas/Dados | Tipos     | Actividad   |  Emociones   
| ------------- | -------- | ----------- | ----
| 1ª  |  2 | 4  | 5   
| 2ª  |  3 | 6  | 2

- De la primera tirada, voy a suponer que fuese mi tío Jesús quien se va a disponer a organizar una actividad cultural con la familia y se siente disgustado en el momento en el que se sienta, por un mal día en el trabajo.
- De la segunda, supongo que son mis amigos quienes van a organizar una ruta turística por la ciudad, pero tienen miedo a que no nos guste. 

A partir de esto, obtengo la tabla de las necesidades obtenidas en las tiradas :

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma 
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- 
| #USER1  | H / 50   | Administrativo  | Media       | Divertido | Web        
| #USER2  | M / 33   | Policía  | Ninguna       | Extrovertido       | Web   


**b. Cuestionario SUS**
---
   
   He usado el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño de la web. Para ello uso la hoja de cálculo, y así calcular los resultados, sigiendo las pautas para usar la escala SUS e interpretarlos.

A continuación, adjunto el pdf con el cuestionario y el resultado obtenido :
[Cuestionario SUS](https://github.com/Jesus715/DIU21-TrabajoFinal/blob/main/Cuestionario_SUS.pdf)

Tras la realización, el website ha obtenido una valoración de **MARGINAL**, según el cuestionario de ambos usuarios.


**c. INFORME DE USABILIDAD**
---

   **c.1 Descripción del Website**
   ---
      
   Yuzin ha sido desde hace muchos años una revista (en formato físico) que promociona las
   actividades culturales de la ciudad que se editaba mes a mes. Se ha hecho un rediseño y orientación de la web en la que la revista digital se queda en
   segundo plano.
   
   **c.2 Resumen ejecutivo**
   ---
   
   El objeto de este test de usabilidad es la página web Yuzin, desarrollado por Yuzin Club Cultural. Para descubrir el grado de usabilidad de dicha página, se ha realizado un test a los 2 usuarios seleccionados en el **apartado a** y se les ha pedido que realicen algunas actividades permitidas por la página, y sin
ningún tipo de ayuda. Además, se les ha pasado un cuestionario el cual han rellenado en base a sus experiencias vividas en el proceso ([Cuestionario SUS](https://github.com/Jesus715/DIU21-TrabajoFinal/blob/main/Cuestionario_SUS.pdf), del **apartado b**).
Este documento contiene las respuestas de dichos voluntarios, colocadas en forma de tabla para su mejor comprensión y análisis.
Los problemas detectados en la página web son: mala navegabilidad, diseño pobre, y ligera inconsistencia.

   **c.3 Evaluación de tareas /escenarios**
   ---
   Las tareas a realizar en la web son las siguientes :
   
   * Tarea 1 - Buscar un servicio concreto
   * Tarea 2 - Buscar una tarea concreta
   * Tarea 3 - Realizar una reserva
   * Tarea 4 - Reconocer dónde estoy
   
   
   
   | Participante | Tarea 1 | Tarea 2 | Tarea 3 | Tarea 4  
   | ------------- | -------- | ----------- | ----------- | -----------  
   | #USER1  | OK  | OK  | OK | -   
   | #USER2  | OK  | OK  | - | -
   | Success | 2 | 2 | 1 | 0
   | Completion Rates | 100% | 100% | 50% | 0%
   
   
   **c.4 Cuestionario después de realizar las tareas para USER1 y USER2**
   ---
   
   |  | Strongly Disagree | Disagree | Neutral | Agree | Strongly Agree | Mean Rating 
   | ----------- | -------- | ----------- | ----------- | ----------- | -------- | ---------
   | Thought Website was easy to use  |   |  1 |  1 |   |   |   2.5  
   | Would use website frequently  |   | 2  |   |   |   | 2  
   | Found it difficult to keep track of where they were in website |   |   |   |   |  2 |  5 
   | Thought most people would learn to use website quickly |   |   | 2  |   |   |  3 
   | Can get information quickly |   |   |   | 1  | 1 |  4.5 
   | Homepage’s content makes me want to explore site |   |   | 1  |  1 |   |  3.5 
   | Site’s content would keep me coming back |   |   | 2  |   |   |  3 
   | Website is well organized |   | 2  |   |   |   | 2  
   
   
   **c.5 Consejos**
   ---
   
   Lo primero que llama la atención es la barra de navegación tan mal escogida, tanto por su disposición, como por su diseño y claridad.
   Otro error grave es que el usuario no sabe en ningún momento dónde se encuentra. Es responsive, pero no mucho. Es decir, intenta adaptarse a cualquier tamaño, pero hay muchos elementos que no lo hacen correctamente, como llama la atención el que desaparezca la barra de navegación, quedando un menú dropdown invisible ya que el elemento sobre el que se hace click para que aparezca es del mismo color que el fondo de la barra. Esto hace que la navegabilidad sea nefasta.
   Después hay un formulario de búsqueda con un mensaje poco o nada intuitivo.
   Debería de tener la opción de seleccionar más idiomas, ya que se trata de un sitio de cultura, y lo que busca es fomentar el turismo.
   La accesibilidad ni está, ni se le espera, no hay ningún apartado dedicado a ella, los tamaños de las fuentes varían demasiado, aunque se adapta bien cuando se hace zoom. 
   
   **c.6 Conclusión**
   ---
   
   En general, la página está mal diseñada. Pese a eso, no es muy difícil realizar acciones sobre ella, la página comete errores en los campos de los formularios (Aparecen en blanco y sin etiqueta).
En los test realizados la nota ha sido media-baja, y en conjunto con el bajo grado de aceptación por parte de los usuarios, queda clara la idea de que esta es una página web mal diseñada, usable (ya que la mayoría de las tareas que se han intentado hacer, se han conseguido sin problema), pero poco accesible, que se puede mejorar y mucho.
La página se ve bien cuando cambias colores (estos no son relevantes a la hora de usarla, en este caso), el menú, aunque para mi gusto es simple y feo a más no poder, tiene espacio suficiente entre sus ítems.


## PARTE III : MI PROPUESTA DE MEJORA
Ya que la información está más o menos bien estructurada, voy a dedicarme a hacer un rediseño de la página principal, manteniendo su gama de colores, fuente, logos y la mayoría de imágenes, pero aportando algunas nuevas llamativas, con lo que obtendría el siguiente **Moodboard** :

![Moodboard](https://github.com/Jesus715/DIU21-TrabajoFinal/blob/main/Moodboard.jpg)

Una vez teniendo los elementos que voy a usar. Los ***Guidelines*** que voy a utilizar son los siguientes : 

* **BUSCAR.**
Search/results: tenemos un formulario formado por varios selectores de búsqueda, y los resultados van a apareciendo automáticamente.

* **NAVEGACIÓN.**
Piramidal: tenemos una pagina de inicio (inicio) de la cual derivan otras 5, y de esas páginas derivan otras, haciéndose en forma de pirámide.

* **INFORMACIÓN.**
List Inlay: muestra como una lista los eventos disponibles, así como los lugares a visitar.
Gallery: los eventos y espacios culturales son un conjunto de imágenes con un texto asociado y una opción de compra.

* **ASISTENTES / WIZARDS.**
Migas de pan: Se ha usado una barra de navegación encima de la información, la cual muestra el path
de dicha pagina. Ademas se dispone de herramientas para la navegación adicionales en el footer.

* **REGISTRAR.**
Sign In / Account Registration: patrón clásico de inicio de sesión y registro, formulario a completar.

* **DATOS DE USUARIO.**
No puedo acceder a esa información, ya que no soy socio.

Para finalizar, se muestra el **Mockup** resultante de aplicar estos patrones de diseño, junto con los elementos deul *Moodboard* ya mencionados :

![Mockup](https://github.com/Jesus715/DIU21-TrabajoFinal/blob/main/Mockup.jpg)
