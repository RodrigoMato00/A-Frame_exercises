# Breve introduccion a la Ralidad Virtual

La Realidad Virtual es una simulación generada por computadora de una imagen o un entorno tridimensional con el que una persona puede interactuar de forma aparentemente real o física mediante un equipo electrónico especial, euipado con una o varias pantallas en su interior y auriculares.

Esta tecnología genera imagenes realistas, sonidos y otras sensaciones para situar al usuario en un entorno virtual inmersivo.

## WebXR

WebXR es una API que permite a los desarrolladores crear experiencias XR, XR engloba la realidad virtual, la realidad aumentada y las nuevas tecnologías de inmersión.

## A-Frame

A-Frame es un marco web para crear experiencias de realidad virtual (VR). A-Frame se basa en la parte superior de HTML, por lo que es fácil comenzar. Pero A-Frame no es solo un gráfico de escena 3D o un lenguaje de marcado; el núcleo es un poderoso marco de entidad-componente que proporciona una estructura declarativa, extensible y componible para three.js.

A-Frame es compatible con la mayoría de los auriculares VR como Vive, Rift, Windows Mixed Reality, Daydream, GearVR, Cardboard, Oculus Go e incluso se puede usar para realidad aumentada. Aunque A-Frame es compatible con todo el espectro, A-Frame tiene como objetivo definir experiencias de realidad virtual interactivas totalmente inmersivas que van más allá del contenido básico de 360°, haciendo un uso completo del seguimiento posicional y los controladores.

### Introduccion a A-FRame

- A-Frame se puede añadir utilizando:
  `<script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>`

- El código A-Frame está contenido dentro de un elemento <a-scene> que establece la escena con las siguientes primitivas:
  - `<a-box>`
  - `<a-sphere>`
  - `<a-cylinder>`
  - `<a-plane>`
  - `<a-sky>`

- Cada una de las primitivas puede transformarse con los siguientes componentes:
  - color
  - position
  - rotation
  - scale

### 0-VR_html-basico

Html basico para crear una experiencia de realidad virtual

Este HTML el script inicial llamando a A-Frame, una escena con un cubo Rojo.

### 1-Flor_de_la_vida

La Flor de la Vida es una figura geométrica compuesta por múltiples círculos superpuestos y espaciados uniformemente, que están dispuestos de manera que forman un patrón en forma de flor con una simetría séxtuple, algo así como un hexágono. El centro de cada círculo está en la circunferencia de seis círculos circundantes del mismo diámetro.

En este proyecto se crea una escena con una flor de la vida y se usara la primitiva `<a-circle>` para crear los círculos y el posicionamiento a utilizar.

### 2-Sistema_Solar_1

Nuestro sistema solar está formado por nuestra estrella, el Sol, y todo lo que está unido a ella por la gravedad: los planetas Mercurio, Venus, la Tierra, Marte, Júpiter, Saturno, Urano y Neptuno, decenas de lunas.

- Crear un esqueleto para el programa en el archivo HTML.

- En el elemento `<head>`, añade un elemento `<script>` con un atributo src source que apunte al URL del A-Frame.

- En el elemento `<body>`, añade el elemento `<a-scene>` con un color de fondo.

- Crea el Sol y los planetas usando esferas y posisionandolos en sus respectivos lugares, agregarles un color caracteriztico, utiliza radius para darle el radio a cada esfera. Utiliza la primitiva `<a-sphere>` para crear las esferas.

### 3-crear_escena

El sistema de gestión de activos es donde podemos almacenar texturas, audio y archivos de modelos 3D dentro de `<a-assets>`.
- `<a-sky>` para añadir el cielo o la imagen de 360°.
- `<a-plane>` para añadir el suelo.
- `<a-ligt>` para añadir la iluminación.
- `<a-sound>` para añadir el sonido.
- `<a-text>` para añadir el texto.
- `<a-gltf-model>` para añadir modelos 3D.

Crear la escena utilizando los elementos anteriores.







