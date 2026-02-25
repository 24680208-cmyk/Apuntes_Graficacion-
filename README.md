# Apuntes_Graficacion-
Alumno: Luis Angel Rodriguez Flores  

Materia: TOPICOS AVANZADOS DE PROGRAMACION

---

# Introducción

En este repositorio se presenta el desarrollo de los temas correspondientes a la **Unidad I: Introducción a la Graficación por Computadora**.

Aquí se explica la historia de la graficación por computadora, sus principales áreas de aplicación y algunos aspectos matemáticos que permiten su funcionamiento.

La graficación por computadora es una parte importante de la informática moderna, ya que permite crear imágenes, animaciones y simulaciones que se utilizan en videojuegos, películas, arquitectura, medicina y muchas otras áreas.

---

# Objetivo

El objetivo de este trabajo es comprender los conceptos básicos relacionados con:

- Historia y evolución de la graficación por computadora  
- Áreas donde se utiliza actualmente  
- Principios matemáticos utilizados para generar gráficos  

También se busca entender la importancia de la graficación por computadora dentro del desarrollo tecnológico actual.

---

# Unidad I. Introducción a la graficación por computadora

---

## 1.1 Historia y evolución de la graficación por computadora

La graficación por computadora es la rama de la informática que se encarga de crear, modificar y mostrar imágenes utilizando computadoras.

Los primeros desarrollos comenzaron en los años 50 y 60. En ese tiempo las computadoras solo podían mostrar líneas simples o figuras básicas.

Uno de los avances más importantes fue el sistema Sketchpad creado en 1963 por Ivan Sutherland. Este programa permitía dibujar directamente en la pantalla con un lápiz óptico y es considerado uno de los primeros sistemas de gráficos interactivos.

Durante los años 70 y 80 comenzaron a desarrollarse algoritmos para generar imágenes más complejas y también aparecieron los primeros sistemas de diseño asistido por computadora.

En los años 90 la tecnología avanzó gracias a las tarjetas gráficas y los gráficos en 3D. Esto permitió crear videojuegos y películas con efectos visuales mucho más realistas.

Actualmente la graficación por computadora utiliza tecnologías como el modelado 3D, la animación digital, la simulación física y la realidad virtual.

---

## 1.2 Áreas de aplicación

La graficación por computadora se utiliza en muchas áreas.

### Videojuegos
Permite crear mundos virtuales, personajes, escenarios y efectos visuales en tiempo real.

### Cine y animación
Se utilizan gráficos generados por computadora para crear efectos especiales, personajes digitales y escenarios completos.

### Arquitectura e ingeniería
Se usan programas de diseño asistido por computadora para crear modelos de edificios, máquinas y diferentes estructuras.

### Medicina
Permite visualizar el interior del cuerpo humano mediante imágenes generadas por estudios médicos.

### Educación
Se utilizan simulaciones y modelos visuales para facilitar el aprendizaje.

### Publicidad y diseño
Las empresas utilizan gráficos digitales para crear anuncios, animaciones y contenido visual.

---

## 1.3 Aspectos matemáticos de la graficación

La graficación por computadora se basa en diferentes conceptos matemáticos.

### Sistema de coordenadas

Las imágenes se representan mediante puntos.

En 2D  
(x, y)

En 3D  
(x, y, z)

Estas coordenadas permiten ubicar objetos dentro de una escena.

### Vectores

Los vectores representan dirección y movimiento.

Ejemplo:

V = (x, y, z)

### Transformaciones geométricas

Permiten modificar los objetos.

Traslación → mover  
Rotación → girar  
Escalamiento → cambiar tamaño

Estas operaciones normalmente se realizan utilizando matrices.

### Proyecciones

Permiten convertir objetos 3D en imágenes 2D para mostrarlos en la pantalla.

- Proyección paralela  
- Proyección en perspectiva

### Renderizado

Es el proceso final donde la computadora calcula colores, luces, sombras y texturas para generar la imagen final.

---

## 1.4 Modelos del color: RGB, CMY, HSV y HSL

Los modelos de color son sistemas que permiten representar colores de forma digital para que puedan ser utilizados en computadoras, pantallas, impresoras y programas de diseño. Cada modelo usa diferentes formas de combinar colores para generar una gran variedad de tonalidades.

En la graficación por computadora los modelos de color son muy importantes porque permiten controlar la iluminación, las texturas y la apariencia de los objetos dentro de una escena.

### Modelo RGB

El modelo RGB (Red, Green, Blue) es uno de los más utilizados en computadoras, televisores y dispositivos móviles.

Este modelo se basa en la combinación de tres colores de luz:

- Rojo (Red)  
- Verde (Green)  
- Azul (Blue)

Cada color puede tener valores entre 0 y 255.

Ejemplos:

Rojo → (255, 0, 0)  
Verde → (0, 255, 0)  
Azul → (0, 0, 255)  
Blanco → (255, 255, 255)  
Negro → (0, 0, 0)

Cuando estos colores se combinan en diferentes cantidades se pueden generar millones de colores. Este modelo es el que utilizan la mayoría de las pantallas.

### Modelo CMY

El modelo CMY (Cyan, Magenta, Yellow) se utiliza principalmente en impresoras.

A diferencia del modelo RGB, este modelo funciona mediante la absorción de la luz usando tintas.

Sus colores principales son:

- Cyan  
- Magenta  
- Amarillo

Al combinar estos colores se pueden obtener otros tonos.

Por ejemplo:

Cyan + Magenta = Azul  
Cyan + Amarillo = Verde  
Magenta + Amarillo = Rojo

En impresión profesional se usa una variante llamada CMYK, donde se agrega el color negro para mejorar la calidad.

### Modelo HSV

El modelo HSV (Hue, Saturation, Value) representa los colores de una forma más parecida a cómo los percibe el ojo humano.

Está compuesto por tres elementos:

Hue (Matiz)  
Representa el tipo de color dentro del círculo cromático.

Saturation (Saturación)  
Indica qué tan intenso o puro es el color.

Value (Valor)  
Indica el nivel de brillo del color.

Este modelo se utiliza mucho en programas de edición de imágenes y diseño.

### Modelo HSL

El modelo HSL (Hue, Saturation, Lightness) es similar al modelo HSV, pero maneja la iluminación de manera diferente.

Sus componentes son:

Hue (Matiz)  
Tipo de color.

Saturation (Saturación)  
Intensidad del color.

Lightness (Luminosidad)  
Indica qué tan claro u oscuro es el color.

Este modelo es muy utilizado en diseño web y en herramientas de edición de gráficos.

---

## Tutorial: Cómo iluminar un cubo y sus caras en Blender

A continuación se muestra un pequeño tutorial para iluminar un cubo en Blender.

### Paso 1: Abrir Blender

Abre el programa Blender. Al iniciar aparecerá una escena con un cubo por defecto.

<img width="960" height="565" alt="image" src="https://github.com/user-attachments/assets/a84f0f9d-5b67-4b6d-8020-c98bc8cd8a0d" />


Si no aparece, puedes agregar uno desde:

Add → Mesh → Cube

### Paso 2: Cambiar a modo de visualización

En la parte superior izquierda objet mode por edit mode

<img width="960" height="566" alt="image" src="https://github.com/user-attachments/assets/2de9f12f-3c99-4474-8d99-6a048e569bea" />

luego seleccionamos celect mode:face

<img width="960" height="562" alt="image" src="https://github.com/user-attachments/assets/7d6995c9-53fa-4d23-82cf-0e907a486f96" />

### Paso 3: Iluminar cara del cubo
Seleccionamos la cara del cubo que bayamos a iluminar 

<img width="959" height="565" alt="image" src="https://github.com/user-attachments/assets/1ea9a4ab-c593-4c3e-a880-199fc1c4dac1" />

despues en la parte derecha nos vamos a material 

<img width="958" height="565" alt="image" src="https://github.com/user-attachments/assets/f568379a-283d-4a30-acda-7d12ab97925d" />

despues seleccionamos Add material slot

<img width="960" height="563" alt="image" src="https://github.com/user-attachments/assets/7a91dd3d-39f2-4045-a122-144ad43fbb39" />

Después seleccionamos select

<img width="960" height="561" alt="image" src="https://github.com/user-attachments/assets/894e2eb3-f40f-4ad4-a6ad-b51089bbed9d" />

Selecciónelos new

<img width="960" height="562" alt="image" src="https://github.com/user-attachments/assets/7b65fa34-7fb2-4f5d-af6a-4b95b23f67d7" />



### Paso 4: Colorear las caras del cubo

Después seleccionamos el color

<img width="960" height="563" alt="image" src="https://github.com/user-attachments/assets/aab342ed-8ad0-4846-b625-75fdceb64725" />

Después es la parte superior derecha seleccionamos v y v, wport shading: material preview

<img width="960" height="565" alt="image" src="https://github.com/user-attachments/assets/65d2b1d5-f24a-492f-84cc-aa59f44bc835" />

Y haci quedaría nuestra primer cara del cubo iluminada

<img width="960" height="561" alt="image" src="https://github.com/user-attachments/assets/b3f7e4df-4e57-49f4-a01f-d15648173d29" />

Y volvemos hacer el mismo procedimiento para volver a iluminar la segunda cara y podemos seguir así repitiendo el proceso hasta poder completar todas las caras de diferentes colores de iluminación

<img width="960" height="562" alt="image" src="https://github.com/user-attachments/assets/7847721b-b9af-4534-9cf8-180f1871332d" />

## Conclusión

En esta práctica en Blender aprendí a ponerle diferentes colores a cada cara de un cubo usando materiales. También aprendí cómo hacer que cada lado se vea iluminado y cómo aplicar los materiales correctamente en el objeto.

Al principio me costó un poco entender cómo seleccionar cada cara y asignarle su color, pero practicando fui entendiendo mejor cómo funciona Blender. Esta actividad me ayudó a conocer más las herramientas básicas del programa y cómo cambiar la apariencia de un objeto 3D.

Al final logré hacer un cubo con diferentes colores en cada cara, lo que me permitió practicar y aprender algo nuevo dentro de Blender.
