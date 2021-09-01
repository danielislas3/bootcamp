# Trivia

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)
* [4. Consideraciones generales](#4-consideraciones-generales)
* [5. Criterios de aceptación mínimos del proyecto](#5-criterios-de-aceptación-mínimos-del-proyecto)
* [6. Hacker edition](#6-hacker-edition)
* [7. Consideraciones técnicas](#7-consideraciones-técnicas)
* [8. Pistas, tips y lecturas complementarias](#8-pistas-tips-y-lecturas-complementarias)

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

**¿Qué tengo que hacer exactamente?** Como es obvio, construirás una aplicación _Web_
de una _trivia_.

El objetivo principal de este proyecto es que tengas una primera experiencia
desarrollando aplicaciones _Web_ (WebApp) que interactúen con la usuaria a
través del navegador, utilizando HTML, CSS y JavaScript.

La temática es libre, decídela rápidamente y luego piensa en cómo debe ser la
experiencia para tus usuarias. Piensa en las pantallas, el flujo, los mensajes,
colores, etc.



## 3. Objetivos de aprendizaje

> ℹ️ Esta sección será auomáticamente generada en el idioma pertinente, a partir
> de los objetivos de aprendizaje declarados en [`project.yml`](./project.yml),
> al crear el repo del proyecto para un cohort en particular usando
> [`./scripts/create-cohort-project.js`](../../scripts#create-cohort-project-coaches).
>
> Acá puedes ver una [lista de todos los objetivos de aprendizaje](../../learning-objectives/data.yml)
> que contempla nuestra currícula.

## 4. Consideraciones generales

* Este proyecto se debe trabajar en duplas.
* Debes preocuparte de que ambas puedan hacer y aprender de todo. Acá no sirve
eso de "tú haces el HTML y CSS y yo hago el JavaScript".

## 5. Recomendaciones
### 5.1. Prototipo.
Algo que siempre ayuda a poner “en concreto” lo que tienes en mente, es hacer un
prototipo "de baja fidelidad" **de todo el proyecto**. Dibujar en papel y lápiz es
un proceso rápido que permite entender cómo, cuándo y dónde suceden las cosas;
dónde exactamente debe decir tal o cual cosa, qué pasa si el usuario hace A o B,
dónde debe hacer _click_, qué información exactamente quieres mostrarle, etc.
**Dedica un máximo de dos horas a esto antes de ponerte a codear**.

### 5.2. No postergues lo que no sabes hacer, comienza por eso
No te quedes horas embelleciendo tus prototipos o haciendo logotipos o esquemas
de color teniendo la sensación de que estás “avanzando”. Es natural que tengas
el impulso de quedarte haciendo lo que puedes imaginar cómo se hace o lo que ya
sabes hacer, es tu cerebro pidiendo su dosis de **satisfacción inmediata**.
No te dejes engañar por la “ilusión” del avance, **tu objetivo es aprender,
no entregar el proyecto**. Enfréntate a lo que no sabes lo más pronto posible,
es el único camino para aprender. No te preocupes por mostrarnos lo que ya
“sabes hacer”, no es eso lo que más nos interesa observar. **Queremos ver cómo
enfrentas el aprendizaje de lo que no sabes, danos la oportunidad de verlo.**

### 5.3. Aprender por encima de completar el proyecto
Evita la tentación de copiar y pegar código que “funcione” para ir completando
el proyecto sin entender cómo ni por qué funciona. Prefiere siempre hacer poco
pero que entiendes y puedes explicar, antes que mucho que funciona a
medias y que no sabes bien cómo ni por qué funciona.

### 5.4. Achicar el gran problema problemas más pequeños
Un "superpoder" que esperamos puedas desarrollar durante el _bootcamp_ es el de
definir "micro-proyectos" que te acerquen paso a paso a la solución del
"gran proyecto".  Podríamos decir que es algo así como comenzar armando un
rompecabezas/_puzzle_ por las esquinas o bordes sin saber necesariamente cómo
encajarán al final. Déjate llevar y explora libremente, no tienes que saberlo
todo antes de comenzar.

Más adelante te daremos algunas sugerencias a modo de ejemplo.

## 5. Criterios de aceptación del proyecto
Reconocemos y valoramos la diversidad por encima de muchas otras coas. Sabemos
que cada una de ustedes sabe un poco más o un poco menos de Desarrollo Web,
también sabemos que cada una aprende distinto, a diferente ritmo, tiene otras
responsabilidades, necesidades, disponibilidad de tiempo, etc. No esperamos que
todas completen lo mismo

Te proponemos trabajar en "hitos". No trabajes haciendo toooooooooooooooooodo
el HTML y CSS de todas las pantallas que imaginaste pero solamente funciona una
parte y a medias; tampoco un montón de funcionalidad en la consola pero que no
tiene una interfaz.

La siguiente metáfora te puede ayudar a comprender mejor la idea.
![AGILE](https://miro.medium.com/max/1400/1*qINsG4WH_BDN-viMJUH6Ng.png)

Estas etapas desde la patineta hasta el auto es a lo que llamaremos "hitos".
Trabaja a conciencia hasta donde alcances.

### Hito 1
La versión más simple de una _trivia_.
- 1 sola pregunta con, al menos, 3 alternativas de respuesta.
- 1 botón para responder y ver la respuesta correcta.
- No te dice si acertaste o no pero sí te dice qué alternativa era correcta.

### Hito 2
Agrega una pantalla simple de bienvenida:
-  Tiene una caja de texto (_input text_) en la que se debe escribir el nombre
de quien juega.
- Un botón de "jugar" o "comenzar" para ir a las preguntas.
- Esta vez deberán haber al menos 3 preguntas.
- Antes de las peguntas debe decir "Hola [el nombre que se escribió en la
pantalla de bienvenida]"
- El botón de responder muestra la alternativa correcta para cada pregunta.
- Un botón para volver a jugar que vuelve a la pantalla inicial en la que se
pide el nombre.

### Hito 3
- Permítele al jugador elegir entre 2 tipos de preguntas antes de ir a responder.
Por ejemplo, unas sobre comida y otras sobre cervezas.
- Agrega un puntaje a preguntas correctas e incorrectas y muestra un puntaje total.

### Hito 4
Agrega una cuenta regresiva con un tiempo límite para responder a las preguntas.

### Hito 5
Sube tu código a un repositorio de GitHub y publica tu aplicación _Web en
GitHub Pages.

### Definición del producto

Documenta **brevemente** tu trabajo en el archivo `README.md` de tu repositorio,
contándonos cómo fue tu proceso de diseño y cómo crees que el producto resuelve
el problema (o problemas) que tiene tu usuario.

#### Prototipo de baja fidelidad

Durante tu trabajo deberás haber hecho e iterado bocetos (_sketches_) de tu
solución usando papel y lápiz. Te recomendamos tomar fotos de todas las
iteraciones que hagas, que las subas a tu repositorio y las menciones en tu
`README.md`.

### Implementación de la Interfaz de Usuario (HTML/CSS/JS)

Luego de diseñar tu interfaz de usuario deberás trabajar en su implementación.
**No** es necesario que construyas la interfaz exactamente como la diseñaste.
No tienes tiempo ilimitado para trabajar, así es que deberás priorizar.

El [MVP](https://www.youtube.com/watch?v=0Dn-BHj6l2E) (producto mínimo viable)
de tu implementación debe:

1. Mostrar una pantalla de bienvenida, pida tu nombre para comenzar a jugar.
2. Mostrar un mensaje de Hola [tu nombre] y dos botones para comenzar a jugar.
   - Jugar con preguntas de tipo A (Por ejemplo: sobre comida)
   - Jugar con preguntas de tipo B (Por ejemplo: sobre cervezas)
3. Lanzar la pregunta 1 con alternativas, el usuario responde, luego se muestra
   la pregunta 2 y luego la 3.
4. Mostrar una pantalla de resultados (respuestas correctas) y dos botones de
   volver a jugar:
   - Jugar con preguntas de tipo A (Por ejemplo: sobre comida)
   - Jugar con preguntas de tipo B (Por ejemplo: sobre cervezas)

## 6. Hacker edition

Si **terminaste** con todo lo anterior y te queda tiempo, intenta explorar y
completar lo siguiente:

* Agregar una cuenta regresiva con un tiempo límite para responder cada pregunta.
* Subir tu código a GitHub (commit/push) y desplegar la interfaz usando GitHub
pages.

## 7. Consideraciones técnicas

La lógica del proyecto debe estar implementada completamente en JS, HTML y CSS
En este proyecto NO está permitido usar librerías o frameworks,
solo [vanilla JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e).

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

## 8. Pistas, tips y lecturas complementarias

### Primeros pasos

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
5. A codear se ha dicho! :rocket:

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
