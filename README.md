# Bitácora Unidad 7: Tipografía Jugable (Word as a Playable System)
**Estudiante:** Diego Sebastian Molina Julian
**ID:** 000621964
**Curso:** Simulación Para Sistemas Interactivos

---

## 🔗 Entregable Principal
* **Sistema tipográfico jugable:** [Prototipo Unidad 7 - TOTOS lab](https://diem-jln.github.io/TOTOS_lab/)

---

## Actividad 01: Referentes y posibilidades de los sistemas jugables
> *Reflexiones sobre Ji Lee (Word as Image), Playables y motores de física.*

* **Reflexión principal:**
Al estudiar el proyecto *Word as Image* de Ji Lee y las piezas de *Playables*, entendí que la tipografía puede trascender su función de lectura lineal para convertirse en un sistema de construcción de sentido a través del juego. No se trata de añadir adornos externos a las letras, sino de que su escala, posición y comportamiento físico comuniquen la idea. 

En unidades anteriores utilizamos fuerzas y oscilaciones puras, pero al introducir bibliotecas de física (o simulaciones espaciales complejas en WebGL/p5.js), las letras logran adquirirmasa, volumen y restricciones. Esto es vital para un sistema jugable, ya que la física provee una expectativa natural de cómo los objetos deberían reaccionar a nuestras interacciones, permitiendo que la persona descubra el significado no leyendo un texto estático, sino "tocando" y manipulando el sistema.

---

## Actividad 02: Encargo de Diseño
> *Reto de diseño: una identidad que se descubre jugando.*

### 1. La Organización y su Contexto
* **Empresa / Organización:** TOTOS lab.
* **¿Qué hace y a qué público se dirige?:** TOTOS Lab es un laboratorio creativo dedicado a construir y fortalecer la presencia digital mediante estrategias accesibles, creación de contenido visual auténtico y la gestión de comunidades. Su enfoque se basa en trabajar directamente con los clientes sin intermediarios, optimizando sus procesos con tecnología y aplicando la metodología de Growth Hacking.

Audiencia: Su público objetivo está compuesto por emprendedores, marcas personales, y pequeñas y medianas empresas.
* **Contexto de uso:** La propuesta esta pensada para usarse de manera introductoria en la portada web de su portafolio digital.

### 2. Intención Semántica (El Atributo)
* **Atributo de identidad a comunicar:**La capacidad de síntesis y estructuración estratégica a partir de datos o piezas aparentemente caóticas (perspectiva multidimensional).
* **Justificación:** Elegí este atributo porque sintetiza el valor de TOTOS lab: en los procesos de growth hacking y construcción de marca, los elementos iniciales suelen presentarse de manera desarticulada y saturada; sin embargo, al adoptar la perspectiva y el enfoque metodológico correcto, cada fragmento encuentra su cohesión para revelar una identidad sólida y funcional..

### 3. El Sistema Jugable (Reglas y Consecuencias)
Desarrollé una experiencia interactiva y un rompecabezas tipográfico 3D utilizando p5.js y WebGL, donde los elementos gráficos provienen estrictamente de las letras que componen "TOTOS lab".

* **¿Qué puede hacer la persona?:** La persona puede interactuar arrastrando el cursor o rotando la vista en el lienzo 3D para orbitar el punto de observación alrededor de un cúmulo de fragmentos geométricos y tipográficos dispersos en el espacio tridimensional.
* 
* **Reglas del sistema:** Los componentes tipográficos están fijados en coordenadas tridimensionales con distintas profundidades en el eje Z; el sistema no permite desplazar las letras de forma individual, sino que su alineación aparente está estrictamente gobernada por el ángulo y la orientación de la cámara virtual.
* 
* **Consecuencias y descubrimiento:** Al explorar libremente las diferentes perspectivas, la persona experimenta la transición del caos aparente a la claridad estructural cuando la cámara alcanza el punto focal exacto (proyección anamórfica), haciendo que la nube volumétrica converja en el logotipo legible de TOTOS lab y evidenciando que el orden depende de encontrar la perspectiva correcta.

---

## Actividad 03: Autoevaluación Ponderada

| Criterio | Puntos | Valoración | Evidencia / Sustento |
| :--- | :---: | :---: | :--- |
| **Cumplimiento del encargo:** El sistema utiliza las letras de una organización, permite jugar con ellas y funciona en tiempo real en la Web. | 25 | `25` | El proyecto está desplegado en GitHub Pages (`diem-jln.github.io/TOTOS_lab/`) operando en tiempo real con WebGL. La geometría y los fragmentos volumétricos se derivan estrictamente de los caracteres tipográficos que componen la marca TOTOS lab. |
| **Comprensión y verificación:** Puedo explicar y justificar el modelo, sus estados, reglas, y predecir el efecto de modificar un parámetro. | 25 | `25` | Implementé una proyección anamórfica en p5.js/WebGL donde cada letra tiene coordenadas tridimensionales fijas en el eje Z. Si altero la distancia focal, la matriz de vista o la posición relativa de los glifos, la convergencia visual colapsa en ruido espacial, demostrando dominio sobre las transformaciones matriciales y la profundidad de campo. |
| **Interacción e identidad:** Puedo justificar qué permiten descubrir las acciones y sus consecuencias sobre el atributo elegido. | 25 | `25` | La interacción de rotación orbital obliga a explorar activamente hasta encontrar la perspectiva exacta donde las piezas dispersas convergen en el logotipo legible. Esta acción materializa el atributo central de TOTOS lab: la capacidad de síntesis estratégica para estructurar claridad a partir de elementos que inicialmente parecen caóticos. |
| **Resolución tipográfica y experiencia:** La composición, ritmo y respuestas perceptibles sostienen la intención y permiten explorar el sistema. | 25 | `20` | El contraste entre los volúmenes tipográficos oscuros y la iluminación del espacio 3D ofrece una lectura limpia. La inercia suave de la cámara responde con naturalidad al cursor, prescindiendo de interfaces intrusivas o marcadores de puntuación para guiar el descubrimiento a través de la curiosidad visual. |
| **TOTAL (Nota propuesta)** | **100** | **`95 / 100`** | |
