# Apuntes_Graficacion-
Alumno: Luis Angel Rodriguez Flores  

Materia: Graficación

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

---

## 1.5. Representación y trazo de líneas y polígonos

La representación y el trazo de líneas y polígonos es uno de los fundamentos principales de la graficación por computadora. A partir de estos elementos básicos se construyen todas las figuras y objetos que vemos en la pantalla, tanto en gráficos 2D como en modelos 3D.

### Representación de líneas

Una línea en el entorno digital se representa mediante dos puntos en el plano cartesiano:

(x1, y1) → punto inicial  
(x2, y2) → punto final  

La computadora no dibuja la línea como en el papel, sino que en realidad enciende pequeños puntos llamados píxeles para simular la línea entre esos dos puntos. Para lograr esto, se utilizan algoritmos matemáticos que calculan qué píxeles deben activarse para que la línea se vea recta y continua.

Algunos algoritmos importantes para el trazo de líneas son:

- **Algoritmo DDA (Digital Differential Analyzer)**  
  Calcula los puntos intermedios usando incrementos pequeños y progresivos.

- **Algoritmo de Bresenham**  
  Es más eficiente porque utiliza principalmente operaciones con números enteros, lo que lo hace más rápido para las computadoras.

Estos algoritmos permiten que las líneas se dibujen correctamente en cualquier dirección.

### Representación de polígonos

Un polígono es una figura geométrica cerrada formada por tres o más líneas rectas unidas por sus extremos. Cada punto donde se unen las líneas se llama **vértice**.

Ejemplos:

- 3 vértices → Triángulo  
- 4 vértices → Cuadrado o rectángulo  
- 5 vértices → Pentágono  

En gráficos por computadora, un polígono se representa mediante una lista ordenada de vértices:

(x1, y1)  
(x2, y2)  
(x3, y3)  
...  

Al unir estos puntos en orden se forma la figura.

### Polígonos en 3D

En gráficos tridimensionales los polígonos también incluyen la coordenada Z:

(x, y, z)

En el modelado 3D, la mayoría de los objetos están formados por muchos polígonos pequeños que juntos crean superficies complejas. Normalmente se utilizan triángulos porque son más fáciles de procesar por la computadora.

Por ejemplo, un cubo en 3D está compuesto por 6 caras, y cada cara puede dividirse en dos triángulos.

### Relleno y renderizado

Después de trazar el contorno del polígono, la computadora puede rellenarlo con un color, una textura o aplicar iluminación. Este proceso es importante en videojuegos y animaciones, ya que permite que los objetos tengan apariencia realista.

El cálculo del relleno también utiliza algoritmos que determinan qué píxeles están dentro del polígono.

### Importancia

La representación y el trazo de líneas y polígonos es la base de toda la graficación digital. Desde figuras simples en 2D hasta modelos complejos en 3D, todo se construye a partir de estos elementos.

Sin líneas y polígonos no sería posible crear personajes, escenarios, objetos ni animaciones dentro de una computadora.

---

## 1.5.1 Formatos de imagen

Los formatos de imagen son estructuras digitales que permiten almacenar y visualizar imágenes en diferentes dispositivos. Cada formato tiene características específicas que lo hacen más adecuado dependiendo del uso que se le quiera dar, como calidad, tamaño del archivo o compatibilidad.

Existen dos tipos principales de imágenes digitales:

### Imágenes rasterizadas (mapa de bits)

Están formadas por píxeles. Cada píxel contiene información de color.  
Si la imagen se amplía demasiado, puede perder calidad y verse borrosa.

Formatos más comunes:

- **JPEG (.jpg)**  
  Muy utilizado para fotografías. Tiene buena calidad y tamaño reducido, pero pierde un poco de información al comprimirse.

- **PNG (.png)**  
  Permite fondo transparente y no pierde calidad al comprimirse.

- **BMP (.bmp)**  
  Formato básico sin compresión. Archivos más pesados.

- **GIF (.gif)**  
  Permite animaciones simples y usa pocos colores.

### Imágenes vectoriales

Están formadas por líneas, curvas y formas definidas mediante fórmulas matemáticas.  
No pierden calidad al cambiar de tamaño.

Formatos más comunes:

- **SVG (.svg)**  
  Muy usado en diseño web.

- **EPS (.eps)**  
  Utilizado en diseño gráfico profesional.

En graficación por computadora es importante conocer los formatos de imagen, ya que dependiendo del proyecto se debe elegir el formato adecuado para obtener mejor calidad o menor tamaño de archivo.

---

## Ejercicio práctico: Dibujo de un polígono

En esta práctica se realizó el dibujo de un polígono utilizando herramientas de modelado. El objetivo fue comprender cómo se representan las figuras mediante vértices y líneas, y cómo se forman las caras al unir estos puntos.

<img width="955" height="559" alt="image" src="https://github.com/user-attachments/assets/91b2f67b-4ba6-47d6-82b2-d6758cc71916" />

Durante el ejercicio se trabajó con:

- Creación de vértices  
- Unión de aristas  
- Formación de caras  
- Aplicación básica de materiales  

Y podemos cambiarle el radio y podemos ponerle mas lados 

<img width="955" height="562" alt="image" src="https://github.com/user-attachments/assets/5eafc921-5505-45ed-bac1-c00bc3069323" />

Esta práctica permitió entender cómo se construyen las figuras en gráficos 2D y 3D a partir de estructuras geométricas simples.

---

## Ejercicio práctico: La Flor de la Vida

En esta práctica se realizó el diseño de la figura conocida como “Flor de la Vida”, que está compuesta por múltiples círculos superpuestos de forma simétrica.

<img width="960" height="563" alt="image" src="https://github.com/user-attachments/assets/fd0ad2c2-ba1d-43c8-975c-bfeb0a8e33d1" />


El objetivo del ejercicio fue:

- Practicar el uso de figuras geométricas básicas  
- Trabajar con simetría y repetición  
- Comprender la precisión en la colocación de objetos  

 y podemos modificar para que la flor se vea con  mas vueltas Cada 60 grados para obtener 6 círculos alrededor

 <img width="960" height="564" alt="image" src="https://github.com/user-attachments/assets/6b8c63b5-244e-411e-bef9-8126b30d647b" />


Este ejercicio ayudó a mejorar el manejo de herramientas de transformación como mover, rotar y escalar objetos dentro del entorno de trabajo.

---

## 1.6. Procesamiento de mapas de bits

El procesamiento de mapas de bits consiste en la manipulación y modificación de imágenes formadas por píxeles. Un mapa de bits (bitmap) es una imagen digital compuesta por una matriz de puntos llamados píxeles, donde cada píxel contiene información de color.

Este tipo de imágenes son conocidas como imágenes rasterizadas y se utilizan principalmente en fotografías y gráficos digitales.

### ¿Qué es un píxel?

Un píxel es la unidad más pequeña de una imagen digital. Cada píxel almacena información de color, normalmente representada en el modelo RGB.

Por ejemplo:

(255, 0, 0) → Rojo  
(0, 255, 0) → Verde  
(0, 0, 255) → Azul  

La combinación de millones de píxeles permite formar una imagen completa.

---

### Resolución

La resolución indica la cantidad de píxeles que tiene una imagen.

Ejemplo:

1920 x 1080 significa que la imagen tiene 1920 píxeles de ancho y 1080 de alto.

Entre mayor resolución tenga una imagen, mayor será su nivel de detalle, pero también aumentará el tamaño del archivo.

---

### Operaciones básicas en mapas de bits

El procesamiento de mapas de bits incluye varias operaciones, entre ellas:

- Ajuste de brillo  
- Ajuste de contraste  
- Cambios de color  
- Filtros  
- Recorte  
- Escalado  
- Rotación  

Estas operaciones se realizan modificando directamente los valores de los píxeles.

---

### Filtros digitales

Los filtros permiten modificar la apariencia de una imagen aplicando operaciones matemáticas sobre los píxeles.

Algunos ejemplos son:

- Filtro de desenfoque  
- Filtro de nitidez  
- Detección de bordes  
- Escala de grises  

Estos filtros son muy utilizados en edición de imágenes, fotografía digital y visión por computadora.

---

### Ventajas de los mapas de bits

- Permiten representar imágenes con muchos detalles.
- Son ideales para fotografías.
- Son compatibles con la mayoría de los dispositivos.

### Desventajas

- Pierden calidad al ampliarse.
- Los archivos pueden ser pesados si tienen alta resolución.

---

### Importancia en la graficación por computadora

El procesamiento de mapas de bits es fundamental en áreas como:

- Edición de imágenes  
- Diseño gráfico  
- Videojuegos  
- Animación  
- Medicina (imágenes médicas)  

Permite mejorar, analizar y modificar imágenes digitales para diferentes aplicaciones.

---
## Bibliografía

Angel, E., & Shreiner, D. (2015). *Interactive computer graphics: A top-down approach with WebGL* (7th ed.). Pearson.

Foley, J. D., Van Dam, A., Feiner, S. K., & Hughes, J. F. (2014). *Computer graphics: Principles and practice* (3rd ed.). Addison-Wesley.

Hearn, D., & Baker, M. P. (2011). *Computer graphics with OpenGL* (4th ed.). Pearson Education.

Hill, F. S., & Kelley, S. M. (2014). *Computer graphics using OpenGL* (3rd ed.). Pearson.

Gonzalez, R. C., & Woods, R. E. (2018). *Digital image processing* (4th ed.). Pearson.

Burger, W., & Burge, M. J. (2016). *Principles of digital image processing: Core algorithms*. Springer.

Blender Foundation. (2023). *Blender manual*. https://docs.blender.org/manual/en/latest/
