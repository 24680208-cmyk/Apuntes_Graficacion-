# Apuntes_Graficacion-
Alumno: Luis Angel Rodriguez Flores  

Materia: Graficación

---
### 1.1. Historia y evolución de la graficación por computadora

La graficación por computadora es la rama de la informática encargada de la creación, representación y manipulación de imágenes mediante sistemas digitales. Su desarrollo ha estado estrechamente vinculado con el avance de la tecnología computacional, tanto en hardware como en software.

Los primeros antecedentes de la graficación por computadora surgieron en la década de 1950, cuando las computadoras comenzaron a utilizarse para mostrar información en forma de gráficos simples, como líneas y puntos. En esa etapa, los dispositivos de salida eran muy limitados y las imágenes eran monocromáticas. Los gráficos eran utilizados principalmente para fines científicos y militares.

Durante la década de 1960 se desarrollaron los primeros sistemas interactivos que permitían modificar gráficos en tiempo real. En este periodo surgieron conceptos fundamentales como las primitivas gráficas (puntos, líneas y polígonos), así como los primeros sistemas de diseño asistido por computadora (CAD), que revolucionaron áreas como la ingeniería y la arquitectura.

En los años 70 se perfeccionaron los algoritmos matemáticos para generar líneas, círculos y curvas con mayor precisión. También comenzaron a desarrollarse técnicas básicas de modelado tridimensional y sombreado.

La década de 1980 marcó un avance importante con la aparición de las computadoras personales y las tarjetas gráficas. Las interfaces gráficas de usuario (GUI) comenzaron a reemplazar las interfaces basadas en texto, facilitando el uso de gráficos en entornos más accesibles. En esta etapa crecieron significativamente los videojuegos y el diseño digital.

En los años 90 y principios del siglo XXI, el desarrollo de las Unidades de Procesamiento Gráfico (GPU) permitió realizar cálculos complejos de manera más rápida y eficiente. Esto impulsó el modelado 3D avanzado, la animación digital y los efectos especiales en la industria del cine y los videojuegos.

Actualmente, la graficación por computadora es fundamental en áreas como la realidad virtual, la realidad aumentada, la inteligencia artificial, la simulación científica y la medicina. Las técnicas modernas como el renderizado en tiempo real y el trazado de rayos han permitido alcanzar niveles de realismo cada vez mayores.

---

### 1.2. Áreas de aplicación

La graficación por computadora tiene múltiples aplicaciones en distintos campos profesionales y científicos.

En el diseño gráfico se utiliza para la creación de logotipos, ilustraciones, material publicitario y contenido visual para medios digitales e impresos. En la animación y el cine permite desarrollar personajes, escenarios y efectos especiales que enriquecen la producción audiovisual.

En la industria de los videojuegos se emplea para crear entornos interactivos en dos y tres dimensiones, incorporando iluminación, texturas y efectos visuales avanzados. En arquitectura e ingeniería, el diseño asistido por computadora facilita la elaboración de planos, modelos estructurales y simulaciones antes de la construcción física.

En medicina, la graficación por computadora se utiliza para procesar y analizar imágenes médicas como radiografías, tomografías y resonancias magnéticas, contribuyendo a diagnósticos más precisos. En educación, permite desarrollar simulaciones y materiales interactivos que mejoran la comprensión de conceptos complejos.

También es fundamental en la simulación científica, donde se representan fenómenos físicos y matemáticos mediante modelos digitales. Además, se aplica en realidad virtual y aumentada para crear entornos inmersivos utilizados en entrenamiento, entretenimiento e industria.

---

### 1.3. Aspectos matemáticos de la graficación

La base de la graficación por computadora es matemática. Sin el uso de principios matemáticos no sería posible representar imágenes digitales con precisión.

La geometría permite definir puntos, líneas, curvas y polígonos que conforman los objetos digitales. En gráficos tridimensionales se utilizan vértices, aristas y caras para formar modelos sólidos.

Los sistemas de coordenadas cartesianas permiten ubicar objetos en el espacio, ya sea en dos dimensiones (x, y) o en tres dimensiones (x, y, z). El álgebra lineal es fundamental, ya que mediante vectores y matrices se realizan transformaciones como traslación, rotación, escalado y reflexión.

Las transformaciones geométricas permiten modificar la posición, orientación y tamaño de los objetos sin alterar su estructura básica. La interpolación se utiliza para calcular valores intermedios entre puntos, lo cual es esencial en animaciones y degradados de color.

El cálculo matemático también interviene en la generación de curvas suaves, superficies complejas y efectos de iluminación, permitiendo obtener representaciones visuales más realistas.

---

### 1.4. Modelos del color: RGB, CMY, HSV y HSL

Los modelos de color son sistemas que permiten representar y manipular colores en medios digitales y físicos.

El modelo RGB (Red, Green, Blue) es un modelo aditivo utilizado en dispositivos electrónicos como monitores y pantallas. Combina luz roja, verde y azul para formar otros colores. Cuando los tres colores están en su máxima intensidad se obtiene el blanco. Cada canal suele manejar valores numéricos de 0 a 255.

El modelo CMY (Cian, Magenta y Amarillo) es un modelo sustractivo utilizado en impresión. Funciona absorbiendo luz en lugar de emitirla. Generalmente se complementa con el color negro, formando el modelo CMYK, para mejorar la profundidad y el contraste en materiales impresos.

El modelo HSV (Hue, Saturation, Value) organiza el color en tres componentes: tono, saturación y valor. El tono representa el tipo de color, la saturación indica la intensidad y el valor determina el brillo. Este modelo facilita la selección intuitiva de colores en programas de diseño.

El modelo HSL (Hue, Saturation, Lightness) es similar al HSV, pero utiliza luminosidad en lugar de valor. Permite ajustar la claridad del color sin modificar completamente su tono base.

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
