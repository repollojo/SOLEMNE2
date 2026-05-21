# SOLEMNE2

---

## Información del proyecto

### Nombre del proyecto
$0.00

### Autora
Marianne Balkenhol

---

# Descripción objetiva

## ¿Qué es el proyecto?

Este proyecto es un sistema visual interactivo desarrollado en p5.js que busca representar una crítica hacia la cosificación de la mujer y cómo muchas veces el cuerpo femenino es tratado como un producto de consumo dentro de una lógica de mercado.

El sistema utiliza distintos elementos gráficos y reglas interactivas para construir una experiencia visual donde la mujer aparece representada como una etiqueta de venta, similar a las utilizadas en productos cárnicos o de supermercado.

---

## ¿Qué se ve en pantalla?

En pantalla aparece una composición visual formada por distintos elementos interactivos y gráficos:

- Un fondo Op Art compuesto por rectángulos repetitivos.
- Una etiqueta inspirada en las etiquetas de venta de carne.
- Un código de barras generado aleatoriamente.
- Información de “producto” como peso, precio y fecha.
- Dos imágenes de maniquíes femeninos.
- Relojes animados distribuidos alrededor de la composición.
- Un triángulo rojo interactivo.
- Texto central con la palabra “MUJER”.


---

## ¿Qué elementos visuales aparecen?

Los principales elementos visuales del sistema son:

- Código de barras.
- Etiqueta de supermercado.
- Relojes.
- Fondo Op Art.
- Maniquíes femeninos.
- Texto.
- Interacciones mediante mouse.
- Cambios de color y movimiento.

---

# Descripción conceptual

## Idea central del proyecto y relación con el sistema diseñado

La idea central del proyecto es representar cómo la mujer muchas veces es vista socialmente como un objeto de consumo y no como una persona.

La obra busca criticar la manera en que el cuerpo femenino entra en una lógica de mercado desde edades muy tempranas, especialmente desde la pubertad, momento en que comienza a ser observado, evaluado y consumido visualmente.

La etiqueta inspirada en productos cárnicos busca representar esta reducción de la mujer a un objeto comercializable, donde aparecen elementos típicos de productos en venta como códigos, precios, peso y fecha.

Además, el sistema también busca representar la presión relacionada con el envejecimiento femenino. A medida que el tiempo avanza, la mujer comienza a perder “valor” dentro de esta lógica de consumo, ya que el mercado visual y social privilegia constantemente la juventud.

Los relojes y la aceleración del tiempo representan esta ansiedad relacionada con la edad y la presión social por mantenerse joven.

---

## Regla de oro del sistema

### Regla principal

Mientras más el usuario baja el mouse en el eje Y, más se acelera el tiempo y más inestable se vuelve el sistema visual.

Esto representa la ansiedad generada por el envejecimiento y la presión social impuesta sobre las mujeres para mantenerse jóvenes y deseables dentro de una lógica de consumo.

---

### Segunda regla importante

Si el usuario presiona el triángulo rojo, la etiqueta deja de funcionar como producto y aparece el mensaje “NO EN VENTA”.

Esto representa una crítica hacia la cosificación femenina y una negación a que el cuerpo de la mujer pueda ser tratado como mercancía.

---

## ¿Cómo se relaciona esta lógica con la problemática de género elegida?

La problemática principal trabajada en este proyecto es la cosificación de la mujer.

Toda la lógica del sistema está construida para representar cómo el cuerpo femenino muchas veces es reducido a un objeto visual o comercial.

El precio, código de barras, datos de producto y maniquíes representan esta deshumanización.

Por otro lado, el tiempo y los relojes representan cómo la sociedad también condiciona el valor femenino dependiendo de la edad y la juventud.



---

# Input / Output y sistema

## INPUT

Las principales entradas de información son:

- La posición vertical del cursor (`mouseY`).
- La acción de presionar el mouse (`mousePressed`).
- La posición del click dentro o cerca del triángulo rojo interactivo.
- Valores aleatorios generados mediante la función `random()`.
- Variables de estado internas, como `etiquetaNegra` y `anguloReloj`.


---

## PROCESAMIENTO DEL SISTEMA

La información ingresada es procesada continuamente dentro del loop draw().

El sistema traduce los inputs en transformaciones como: 
- condicionales (`if / else`),
- loops (`while` y `for`),
- funciones propias,
- variables de estado,
- rotaciones,
- escalas,
- generación aleatoria,
- y mapeos mediante `map()`.

La posición del mouse altera la velocidad y dirección de los relojes, además de modificar la intensidad del fondo Op Art. Esto genera una sensación visual de ansiedad y aceleración temporal.

El click del usuario cambia estados dentro del sistema. Cuando el click ocurre sobre el triángulo rojo, la etiqueta deja de operar como producto comercial y cambia a una lectura crítica mediante el mensaje “NO EN VENTA”.

Paralelamente, cada click genera nuevos números aleatorios para el código de barras, reforzando la idea de serialización y reemplazo constante del cuerpo femenino.

---

## OUTPUT

El sistema produce distintos outputs visuales como respuesta a la interacción del usuario.

Entre las principales salidas visuales se encuentran:

- Aceleración o inversión del movimiento de los relojes.
- Alteración del fondo geométrico.
- Transformación visual de la etiqueta.
- Aparición del mensaje “NO EN VENTA”.
- Generación constante de nuevos códigos de barras.
- Cambios en la lectura conceptual de la obra según la interacción.

De esta manera, el sistema transforma acciones simples del usuario en respuestas visuales que construyen una crítica hacia la cosificación femenina y la lógica de consumo aplicada sobre el cuerpo de la mujer.

---

# Pensamiento computacional

## Reglas que gobiernan el sistema

- Si el mouse baja = el tiempo se acelera.
- Si el mouse se presiona = los relojes cambian dirección.
- Si el usuario hace click = se genera un nuevo código.
- Si el click ocurre dentro del triángulo rojo = cambia el estado de la etiqueta.
- Si la etiqueta cambia = desaparece la lógica de venta.

---

## Explicación de la interactividad
La interactividad del sistema busca representar la presión constante sobre la mujer dentro de esta lógica de consumo. El movimiento del mouse acelera el tiempo y altera visualmente el entorno, representando la ansiedad por envejecer y la pérdida de “valor” dentro de estándares impuestos. Sin embargo, la interacción más importante ocurre cuando el usuario presiona el triángulo rojo, ya que la etiqueta deja de funcionar como producto y aparece el mensaje “NO EN VENTA”, transformando el sistema en una crítica directa a la cosificación femenina.

---

# Referentes

### Etiqueta de carne 

<img width="950" height="511" alt="image" src="https://github.com/user-attachments/assets/c68d5205-7735-4a23-aeaf-34be015a3e8e" />

---


### Vanessa Beecroft
Mujeres vestidas como maniquíes, como si todas fueran iguales entre sí, sin identidad propia.
<img width="2048" height="1624" alt="image" src="https://github.com/user-attachments/assets/c5badb8f-9ebd-4ecc-9890-ad3f8b5e8797" />

---


### Jenny Holzer

Textos y crítica social sobre el consumo del cuerpo de la mujer

<img width="1500" height="1039" alt="image" src="https://github.com/user-attachments/assets/e24ebf37-b725-4be7-8217-6161fff44acd" />

<img width="2268" height="1276" alt="image" src="https://github.com/user-attachments/assets/25674469-dbb7-48ee-b553-0804098a11b6" />

---


### Naomi Wolf

En "El mito de la belleza"
Explica cómo la sociedad transforma la belleza y la juventud femenina en formas de control, haciendo que el valor de la mujer disminuya con el paso del tiempo.

<img width="352" height="486" alt="image" src="https://github.com/user-attachments/assets/757eedf8-d615-4dae-bf29-2e2515b184d7" />

<img width="201" height="251" alt="image" src="https://github.com/user-attachments/assets/e40a5351-7cf4-4e4b-af93-fe78ed285116" />

---


### Boceto inicial
Una vez que tuve la idea principal del proyecto, el resto del sistema lo fui construyendo y desarrollando en p5.js mediante distintas ideas que se me ocurrieron en el momento para representar mejor la problemática de la cosificación femenina.
<img width="1389" height="1600" alt="BOCETO" src="https://github.com/user-attachments/assets/7c5ca8d3-cb26-4962-9260-01131bbeeb47" />


---

# Diagrama de Flujo

<img width="2238" height="12050" alt="ee" src="https://github.com/user-attachments/assets/4ec7a0f3-bda9-4d59-bd22-27715944f88e" />


**Link a PDF de mejor calidad**

[DIAGRAMA FLUJO.pdf](https://github.com/user-attachments/files/28117710/DIAGRAMA.FLUJO.pdf)






---

# Código p5.js

```javascript
// VARIABLES

let codigo = ""; // creo una variable llamada codigo y la dejo vacía para guardar los números del código de barras
let etiquetaNegra = false; // creo una variable booleana que parte en falso para saber si la etiqueta está negra o normal
let maniqui1; // creo una variable para guardar la primera imagen
let maniqui2; // creo una variable para guardar la segunda imagen
let anguloReloj = 0; // creo una variable para controlar la rotación de los relojes


// CARGA DE IMÁGENES

function preload() { // función que carga archivos antes de que empiece el programa
  maniqui1 = loadImage("maniqui1.png"); // carga la imagen maniqui1.png y la guarda en la variable maniqui1
  maniqui2 = loadImage("maniqui2.png"); // carga la imagen maniqui2.png y la guarda en la variable maniqui2
}


// CONFIGURACIÓN INICIAL

function setup() { // función que se ejecuta una sola vez al inicio
  createCanvas(650, 500); // crea un lienzo de 650 píxeles de ancho y 500 píxeles de alto
  noFill(); // hace que las figuras no tengan relleno por defecto
  strokeWeight(2); // define que el grosor del borde sea de 2 píxeles
  angleMode(DEGREES); // hace que los ángulos se usen en grados y no en radianes
  generarCodigo(); // llama a la función que genera los números del código de barras
}


// DIBUJO PRINCIPAL

function draw() { // función que se repite constantemente en loop
  background(0); // pinta el fondo negro en cada repetición


  // FONDO OP ART

  let tam = 900; // creo una variable llamada tam y le asigno 900 como tamaño inicial

  while (tam > 0) { // loop que se repite mientras tam sea mayor que 0
    stroke(tam * 0.5); // asigna un color gris al borde usando el valor de tam
    rectMode(CENTER); // hace que los rectángulos se dibujen desde el centro
    rect(width / 2, height / 2, tam, tam); // dibuja un rectángulo centrado usando el tamaño tam
    let opArt = 1 + mouseY * 0.0015; // creo una variable que cambia según la posición vertical del mouse
    tam = tam - opArt; // reduce el tamaño de tam para que se vayan dibujando rectángulos más chicos
  }


  // VELOCIDAD RELOJES

  anguloReloj = anguloReloj + 6; // aumenta el ángulo para que los relojes giren


  // RELOJES DE FONDO

  dibujarReloj(75, 70, 0.45); // dibuja un reloj en x 75, y 70, con escala 0.45
  dibujarReloj(575, 75, 0.4); // dibuja un reloj en x 575, y 75, con escala 0.4
  dibujarReloj(80, 420, 0.55); // dibuja un reloj en x 80, y 420, con escala 0.55
  dibujarReloj(575, 420, 0.5); // dibuja un reloj en x 575, y 420, con escala 0.5
  dibujarReloj(325, 65, 0.45); // dibuja un reloj en x 325, y 65, con escala 0.45
  dibujarReloj(25, 250, 0.38); // dibuja un reloj en x 25, y 250, con escala 0.38
  dibujarReloj(560, 230, 0.4); // dibuja un reloj en x 560, y 230, con escala 0.40


  // ETIQUETA

  rectMode(CORNER); // hace que el rectángulo se dibuje desde la esquina superior izquierda
  fill(245, 180); // asigna un relleno gris claro con transparencia
  stroke(70); // asigna un borde gris oscuro
  strokeWeight(2); // asigna un grosor de borde de 2 píxeles
  rect(132.5, 145, 385, 230); // dibuja la etiqueta en x 132.5, y 145, con ancho 385 y alto 230


  // TRIÁNGULO INTERACTIVO

  noStroke(); // elimina el borde de la figura
  fill(181, 20, 20); // asigna un color rojo oscuro al triángulo
  triangle(517.5, 375, 480, 375, 517.5, 337); // dibuja el triángulo interactivo en la esquina de la etiqueta


  // ETIQUETA NEGRA

  if (etiquetaNegra === true) { // si etiquetaNegra es verdadera, se activa esta versión negra de la etiqueta
    fill(0); // asigna relleno negro
    stroke(0); // asigna borde negro
    rect(132.5, 145, 385, 230); // dibuja un rectángulo negro encima de la etiqueta
    noStroke(); // elimina los bordes para los textos
    textAlign(CENTER); // centra el texto horizontalmente
    textStyle(BOLD); // pone el texto en negrita
    textSize(36); // asigna tamaño 36 al texto
    fill(191, 17, 17); // asigna color rojo al texto
    text("MUJER", 315, 275); // escribe la palabra mujer en el centro de la etiqueta
    textAlign(LEFT); // alinea el texto hacia la izquierda
    textSize(16); // asigna tamaño 16 al texto
    fill(255); // asigna color blanco al texto
    text("Precio Total:", 150, 315); // escribe el texto precio total en la parte derecha
    textStyle(BOLD); // pone el texto en negrita
    textSize(45); // asigna tamaño 44 al texto
    text("$ NO EN VENTA", 150, 360); // escribe el precio en la parte inferior derecha
    return; // detiene el draw en esta parte para que no se dibuje lo demás
  }


  // CÓDIGO DE BARRAS

  stroke(0); // asigna color negro a las líneas del código de barras

  let x = 140; // creo una variable x que indica desde dónde empiezan las líneas

  while (x < 510) { // loop que se repite mientras x sea menor que 510
    strokeWeight(random([1, 2, 3])); // asigna un grosor aleatorio de 1, 2 o 3 a cada línea
    strokeCap(SQUARE); // hace que las puntas de las líneas sean cuadradas
    line(x, 155, x, 215); // dibuja una línea vertical del código de barras
    x = x + random(3, 6); // aumenta x de forma aleatoria para separar las líneas
  }


  // NÚMEROS DEL CÓDIGO

  noStroke(); // elimina el borde para el texto
  fill(0); // asigna color negro al texto
  textAlign(CENTER); // centra el texto
  textStyle(NORMAL); // deja el texto sin negrita
  textSize(12); // asigna tamaño 12 al texto
  text(codigo, 325, 230); // dibuja los números del código de barras en la etiqueta


  // IMÁGENES

  tint(255); // deja las imágenes con su color normal
  image(maniqui1, 0, 300, 210, 310); // dibuja la primera imagen en x 0, y 300, con ancho 210 y alto 310
  image(maniqui2, 350, 30, 140, 220); // dibuja la segunda imagen en x 350, y 30, con ancho 140 y alto 220


  // TEXTO CENTRAL

  textAlign(CENTER); // centra el texto horizontalmente
  textStyle(BOLD); // pone el texto en negrita
  textSize(36); // asigna tamaño 36 al texto
  fill(191, 17, 17); // asigna color rojo al texto
  text("MUJER", 315, 275); // escribe la palabra mujer en el centro de la etiqueta


  // INFORMACIÓN IZQUIERDA

  textAlign(LEFT); // alinea el texto hacia la izquierda
  textSize(14); // asigna tamaño 14 al texto
  fill(55); // asigna un color gris oscuro al texto
  textStyle(NORMAL); // deja el texto sin negrita
  text("Empacado", 140, 295); // escribe la palabra empacado en la parte izquierda
  textStyle(BOLD); // pone el texto en negrita
  text("10-Mar-1990", 140, 315); // escribe la fecha de empacado
  noStroke(); // elimina cualquier borde del texto
  textStyle(NORMAL); // deja el texto sin negrita
  textSize(14); // asigna tamaño 14 al texto
  text("Peso:", 140, 340); // escribe la palabra peso
  textStyle(BOLD); // pone el texto en negrita
  textSize(26); // asigna tamaño 26 al texto
  text("52 Kg", 140, 365); // escribe el peso en la parte inferior izquierda


  // INFORMACIÓN DERECHA

  textStyle(NORMAL); // deja el texto sin negrita
  textSize(16); // asigna tamaño 16 al texto
  text("Precio Total:", 355, 315); // escribe el texto precio total
  textStyle(BOLD); // pone el texto en negrita
  textSize(44); // asigna tamaño 44 al precio
  text("$ 0.00", 355, 360); // escribe el precio final
}


// GENERAR CÓDIGO

function generarCodigo() { // función propia que crea los números del código de barras
  codigo = ""; // vacía la variable codigo antes de volver a llenarla

  for (let i = 0; i < 37; i++) { // loop for que se repite 37 veces para crear 37 números
    let numero = floor(random(0, 10)); // crea un número aleatorio entre 0 y 9 y le quita los decimales
    codigo = codigo + numero + " "; // agrega el número a la variable codigo con un espacio
  }
}


// DIBUJAR RELOJ

function dibujarReloj(x, y, tam) { // función propia que dibuja un reloj usando posición x, posición y y tamaño
  push(); // guarda el estado actual del dibujo para que los cambios no afecten lo demás
  translate(x, y); // mueve el origen del dibujo a la posición x e y del reloj
  scale(tam); // cambia el tamaño del reloj usando la variable tam

  let velocidadExtra = map(mouseY, 0, height, 0.8, 1.2); // crea una velocidad extra según la posición vertical del mouse
  let sentido = 1; // crea una variable para controlar la dirección del giro


  // DIRECCIÓN DE RELOJES

  if (mouseIsPressed) { // si el mouse está presionado, pasa lo siguiente
    sentido = -1; // cambia el sentido del giro hacia el lado contrario
  } else if (mouseY < height / 6) { // si el mouse está en la parte superior del lienzo, pasa lo siguiente
    sentido = 1; // mantiene el sentido normal del giro
  } else { // si no se cumple ninguna condición anterior, pasa esto
    sentido = 20; // aumenta mucho el sentido para que el reloj gire más rápido
  }


  // ROTACIÓN

  rotate(anguloReloj * sentido * velocidadExtra); // rota el reloj usando el ángulo, el sentido y la velocidad extra


  // CUERPO DEL RELOJ

  noStroke(); // elimina el borde del cuerpo del reloj
  fill(0); // asigna color negro al cuerpo del reloj
  ellipse(0, 0, 90, 90); // dibuja un círculo en el centro del reloj


  // MANILLA BLANCA

  stroke(255); // asigna color blanco a la primera manilla
  strokeWeight(5); // asigna grosor 5 a la primera manilla
  line(0, 0, 30, 0); // dibuja la primera manilla desde el centro hacia la derecha


  // MANILLA GRIS

  push(); // guarda el estado actual antes de rotar la segunda manilla
  rotate(anguloReloj * sentido * velocidadExtra); // rota la segunda manilla usando el mismo movimiento
  stroke(160); // asigna color gris a la segunda manilla
  strokeWeight(3); // asigna grosor 3 a la segunda manilla
  line(0, 0, 0, -32); // dibuja la segunda manilla desde el centro hacia arriba
  pop(); // vuelve al estado anterior antes de rotar la segunda manilla


  // CENTRO DEL RELOJ

  noStroke(); // elimina el borde del centro del reloj
  fill(90); // asigna color gris oscuro al centro
  ellipse(0, 0, 13, 13); // dibuja el círculo pequeño del centro del reloj
  pop(); // restaura el estado del dibujo para que el reloj no afecte lo demás
}


// INTERACCIÓN MOUSE

function mousePressed() { // función que se ejecuta cada vez que se presiona el mouse
  if (mouseX > 480 && // revisa que el mouse esté a la derecha de x 480
      mouseX < 517.5 && // revisa que el mouse esté a la izquierda de x 517.5
      mouseY > 337 && // revisa que el mouse esté abajo de y 337
      mouseY < 375) { // revisa que el mouse esté arriba de y 375
    etiquetaNegra = !etiquetaNegra; // cambia la etiqueta de normal a negra o de negra a normal
  }

  generarCodigo(); // genera un nuevo código cada vez que se presiona el mouse
}
```

---

# Link editable del sketch


https://editor.p5js.org/marianne88/sketches/hBeYV5oJh



---






