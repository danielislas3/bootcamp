# Trivia

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
<!--* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)-->
* [3. Consideraciones generales](#3-consideraciones-generales)
* [4. Recomendaciones](#4-recomendaciones)
* [5. Criterios de aceptación del proyecto](#6-criterios-de-aceptación-del-proyecto)
* [6. Consideraciones técnicas](#7-consideraciones-técnicas)
* [7. Ambiente de trabajo y lecturas complementarias](#7-ambiente-de-trabajo-y-lecturas-complementarias)

***

## 1. Preámbulo

Una _trivia_ es un tipo de juego, generalmente en el marco de un concurso, en el
que se plantea una serie de preguntas cuyas respuestas deben ser escogidas entre
diferentes opciones predeterminadas.

En la actualidad existen muchas posibilidades de participar de una trivia
_online_. Con una rápida búsqueda en internet, te darás cuenta de que existen
trivias de muchas temáticas (ciencia, series, televisión, etc.). Hay varias que
ofrecen, incluso, dinero como recompensa.

![TRIVIA](https://phandroid.s3.amazonaws.com/wp-content/uploads/2018/01/hq-trivia-android-screenshot.jpg)

## 2. Resumen del proyecto

**¿Qué tengo que hacer exactamente?** Como es obvio, construirás la aplicación
_Web_ de una _trivia_.

El objetivo principal de este proyecto es que tengas una primera experiencia
desarrollando aplicaciones _Web_ (WebApp) que interactúen con la usuaria a
través del navegador, utilizando HTML, CSS y JavaScript.

La temática es libre, decídela rápidamente y luego piensa en cómo debe ser la
experiencia para tus usuarias. Piensa en las pantallas, el flujo, los mensajes,
colores, etc.

<!--
## 3. Objetivos de aprendizaje

> ℹ️ Esta sección será auomáticamente generada en el idioma pertinente, a partir
> de los objetivos de aprendizaje declarados en [`project.yml`](./project.yml),
> al crear el repo del proyecto para un cohort en particular usando
> [`./scripts/create-cohort-project.js`](../../scripts#create-cohort-project-coaches).
>
> Acá puedes ver una [lista de todos los objetivos de aprendizaje](../../learning-objectives/data.yml)
> que contempla nuestra currícula.
-->
## 3. Consideraciones generales

* Este proyecto se debe trabajar en duplas.
* Debes preocuparte de que ambas puedan hacer y aprender de todo. Acá no sirve
eso de "tú haces el HTML y CSS y yo hago el JavaScript". El objetivo es aprender,
no "terminar y entregar".
* Completar el proyecto **no es un requisito para ser admitida al _bootcamp_**.
* Dejarnos entender con transparencia tu proceso **sí es un requisito para considerarte.**.
* Queremos verte aprender, no hacer lo que ya sabes.

## 4. Recomendaciones
### 4.1. Prototipo.
Algo que siempre ayuda a poner “en concreto” lo que tienes en mente, es hacer un
simple prototipo en papel y lápiz **de todo el proyecto**. Dibujar es un proceso
rápido que permite entender cómo, cuándo y dónde suceden las cosas;
dónde exactamente debe decir tal o cual cosa, qué pasa si el usuario hace A o B,
dónde debe hacer _click_, qué información exactamente quieres mostrarle, etc.
**Dedica un máximo de dos horas a esto antes de ponerte a codear**.

### 4.2. No postergues lo que no sabes hacer, comienza por ahí
No gastes horas embelleciendo tus prototipos o haciendo logotipos teniendo la
sensación de que estás “avanzando”. Es natural que tengas el impulso de hacerlo,
es tu cerebro pidiendo su dosis de **satisfacción inmediata**. No te dejes engañar
por la “ilusión” del avance, **tu objetivo es aprender**. Enfréntate a lo que no
sabes lo más pronto posible, es el único camino para aprender. Como te decíamos
líneas arriba,  **Queremos ver cómo enfrentas el aprendizaje de lo que no sabes,
danos la oportunidad de verlo.**

### 4.3. Aprender por encima de completar el proyecto
Evita la tentación de copiar y pegar código que “funcione” para ir completando
el proyecto sin entender cómo ni por qué funciona. Prefiere siempre hacer poco
pero que entiendes y puedes explicar, antes que mucho que funciona a
medias y/o que no sabes bien cómo ni por qué funciona.

### 4.4. Achicar el gran problema en problemas más pequeños
Un "superpoder" que esperamos puedas desarrollar durante el _bootcamp_ es el de
definir "micro-proyectos" que te acerquen paso a paso a la solución del
"gran proyecto".  Podríamos decir que es algo así como comenzar armando un
rompecabezas/_puzzle_ por las esquinas o bordes sin saber necesariamente cómo
encajarán al final. Déjate llevar y explora libremente, no tienes que saberlo
todo antes de comenzar.

Más adelante te daremos algunas sugerencias como ejemplo.

## 5. Criterios de aceptación del proyecto
Reconocemos y valoramos la diversidad por encima de muchas otras coas. Sabemos
que cada una de ustedes sabe un poco más o un poco menos de Desarrollo Web,
también sabemos que cada una aprende distinto, a diferente ritmo. No esperamos
que todas completen lo mismo

Te proponemos trabajar en "hitos". No trabajes haciendo toooooooooooooooooodo
el HTML y CSS de todas las pantallas que imaginaste y que solamente funcione una
parte y a medias; tampoco un montón de funcionalidad en la consola pero que no
tiene una interfaz para ser utilizada por una usuaria no-developer.

La siguiente metáfora te puede ayudar a comprender mejor la idea.
![AGILE](https://miro.medium.com/max/1400/1*qINsG4WH_BDN-viMJUH6Ng.png)

Esas etapas, desde la patineta hasta el auto, es a lo que llamaremos "hitos".
Trabaja a conciencia hasta donde alcances.

-----------
### Hito 1
La versión más simple de una _trivia_.
- 1 sola pantalla o vista.
- 2 preguntas con, al menos, 3 alternativas de respuesta cada una.
- 1 botón para responder y ver la respuesta correcta.
- No te dice si acertaste o no pero sí te dice qué alternativa era correcta.

<details>
<summary>Sugerencia de micro-proyecto A</summary>

##### Solamente el "esqueleto" estático
- Dos preguntas con sus respectivas alternativas de respuesta en forma de
_radio buttons_ (🔘)
- El botón para “Responder y ver resultados”.

##### Aprenderás:
Cómo construir una página básica HTML con elementos de formulario.
</details>

<details>
<summary>Sugerencia de micro-proyecto B</summary>

##### Prueba darle algo de interacción
Cuando la usuaria dé _click_ en alguno de los _radio button_, muéstrale un
mensaje de alerta (_alert_) en el navegador que contenga el valor (texto) del
_radio button_ cliqueado.

**Pista**: Para mostrar un mensaje de alerta básico hay una función de JavaScript
llamada “_alert_”. Esta función puede “escuchar” eventos del navegador como
_click_ y hacer algo cuando suceda usando _onclick_ o _addEventListener_.

##### Aprenderás:
- Detectar eventos en el navegador (los _clicks_ de la usuaria) y hacer algo
cuando sucedan.
- Identificar los elementos HTML que hay en el navegador y obtener sus valores
y/o estados.

</details>
<details>
<summary>Sugerencia de micro-proyecto C</summary>

##### Prueba darle algo de interacción más parecida a la que necesitas
En lugar de mostrar el valor de cada _radio button_ cuando se le hace _click_,
que solamente se marque la opción seleccionada y se muestre el _alert_ con  
los valores de los _radio button_ seleccionados cuando haga _click_ en
el botón “Responder y ver resultados”.

##### Aprenderás:
- Detectar eventos en el navegador (los clicks del usuario).
- Identificar los elementos HTML que hay en el navegador y obtener sus valores/estados.

</details>

-----------
### Hito 2
Agrega una pantalla simple de bienvenida:
-  Tiene una caja de texto (_input text_) en la que se debe escribir el nombre
de quien juega.
- Un botón de "jugar" o "comenzar" para ir a las preguntas.
- Esta vez deberán haber al menos 3 preguntas.
- Antes de las peguntas debe decir "Hola [el nombre que se escribió en la
pantalla de bienvenida]"
- El botón de responder muestra la alternativa correcta para cada pregunta y
, además, muestra si la respuesta fue correcta o incorrecta.
- Un botón para volver a jugar que vuelve a la pantalla inicial en la que se
pide el nombre.

<details>
<summary>Sugerencia de micro-proyecto A</summary>

##### Evaluando las respuestas de tu usuaria
Evalúa si las respuestas seleccionadas son correctas o incorrectas. Para hacerlo,
elige una de las alternativas de la pregunta 1 como la respuesta “correcta”.
Al dar _click_ en el botón “Responder y ver resultados”  muestra un _alert_  
que diga “Respuesta correcta” o “Respuesta incorrecta” según corresponda.

**Pistas:** Lee sobre condicionales y control de flujo (IF, ELSE).

##### Aprenderás:
- Identificar los elementos HTML que hay en el navegador y obtener sus
valores/estados.
- Comparar los valores/estados de los elementos y hacer algo según el
resultado que obtengas de la comparación/evaluación.


</details>

-----------

### Hito 3
- Permítele a la usuaria elegir entre 2 tipos de preguntas después de escribir
su nombre y antes de ir a responder.
Por ejemplo, unas sobre comida y otras sobre cervezas.
- Agrega un puntaje a preguntas correctas e incorrectas y muestra un puntaje
total al final.

-----------
### Hito 4
Agrega una cuenta regresiva con un tiempo límite para responder a las preguntas.

----------
### Hito 5
Sube tu código a un repositorio de GitHub y publica tu aplicación _Web en
GitHub Pages.

-----------
### General
Independientemente de hasta qué hito alcances a hacer, asegúrate de:

- Documentar **brevemente** tu trabajo en un documento o el archivo `README.md`
de tu repositorio contándonos cómo fue tu proceso de diseño y cómo crees que el
producto resuelve el problema (o problemas) que tiene tu usuario.

- Durante tu trabajo deberás haber hecho e iterado (volver a hacer) bocetos
(_sketches_) de tu propuesta usando papel y lápiz. Te recomendamos tomar fotos
de todas las iteraciones que hagas, que las pongas en tu documento o las subas
a tu repositorio y las menciones en tu `README.md`.

## 6. Consideraciones técnicas

La lógica del proyecto debe estar implementada completamente en JS, HTML y CSS
En este proyecto NO debes usar librerías o _frameworks_,
solo [vanilla JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e).

Este _boilerplate_ (plantilla de proyecto en el repositorio de GitHub) contiene
tres archivo, eres libre agregar o quitar archivos/carpetas. **Si usas un editor
de código en línea como Codepen o Replit omite este punto.**

Los archivos del _boilerplate_:

### `src/index.html`

Acá va la página que se mostrará al usuario, también nos sirve para indicar
qué script se usará y unir todo lo que hemos hecho.

Encontrarás 1 etiqueta inicial, la cual si deseas puedes borrar y empezar de
cero:

```html
 <div id="root"></div>
```

### `src/style.css`

Este archivo debe contener las reglas de estilo. Queremos que escribas tus
propias reglas, por eso NO está permitido el uso de frameworks de CSS
(Bootstrap, materialize, etc).

### `src/main.js`

Acá escribirás todo el código que tenga que ver con la interacción del DOM
(seleccionar, actualizar y manipular elementos del DOM y eventos), entre otras
funciones que sean necesarias para actualizar el resultado en la pantalla (UI).

## 7. Ambiente de trabajo y lecturas complementarias

### Prepara tu ambiente de trabajo
#### Si estás dando tus primeros pasos en el Desarrolo Web:
Quizás prefieras trabajar con alguna herramienta de edición de código en línea
como [Codepen](https://codepen.io/pen/)

#### Si ya tienes cierta experiencia y vas a trabajar con un repositorio de código:

1. Antes que nada, asegúrate de tener un :pencil: editor de texto en
   condiciones, algo como [Atom](https://atom.io/) o
   [Visual Studio Code](https://code.visualstudio.com/).
2. Para ejecutar los comandos a continuación necesitarás una :shell:
   [UNIX Shell](../../topics/shell),
   que es un programita que interpreta líneas de comando (command-line
   interpreter) así como tener [git](../../topics/scm/01-git)
   instalado. Si usas un sistema operativo "UNIX-like", como GNU/Linux o MacOS,
   ya tienes una _shell_ (terminal) instalada por defecto (y probablemente `git`
   también). Si usas Windows puedes usar [Git bash](https://git-scm.com/download/win),
   aunque recomendaría que consideres probar :penguin: GNU/Linux.
3. Haz tu propio :fork_and_knife: [fork](https://help.github.com/articles/fork-a-repo/)
   del repo de tu cohort, tus _coaches_ te compartirán un _link_ a un repo y te
   darán acceso de lectura en ese repo.
4. :arrow_down: [Clona](https://help.github.com/articles/cloning-a-repository/)
   tu *fork* a tu computadora (copia local).

### Recursos y temas relacionados

#### Diseño de experiencia de usuario (User Experience Design)

* Ideación
* Prototipado (sketching)

#### Desarrollo Front-end

* Tipos de valores
* Declaración de variables
* Control de flujo

#### Herramientas

* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)
* [GitHub Pages](https://pages.github.com/)

#### Organización del Trabajo

* [Metodologías Ágiles](https://www.youtube.com/watch?v=v3fLx7VHxGM)
* [Scrum en menos de 2 minutos](https://www.youtube.com/watch?v=TRcReyRYIMg)
* [Scrum en Detalle](https://youtu.be/nOlwF3HRrAY). No
  esperamos que hagas todo eso desde este proyecto.
