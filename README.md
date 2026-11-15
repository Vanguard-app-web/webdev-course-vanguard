# Fundamentos de Desarrollo Web: HTML y CSS

## Resumen del Curso

Curso introductorio para estudiantes de secundaria que quieren crear su primera página web con HTML y CSS. La ruta de aprendizaje se organiza en cinco misiones de Web Quest y propone construir progresivamente una página de perfil para Pixel.

Las lecciones combinan explicaciones visuales, demostraciones en un editor en línea y pausas para practicar. **No necesitas instalar programas: solo abre tu navegador web.**

- **Duración total prevista:** aproximadamente 60 minutos; pendiente de confirmar con las duraciones finales de las cinco misiones.
- **Público objetivo:** estudiantes de 12 a 17 años sin experiencia en programación.
- **Prerrequisitos:** ninguno.
- **Herramientas necesarias:** navegador web y conexión a Internet. Las prácticas utilizarán herramientas gratuitas y en línea.
- **Formato previsto:** cinco videos de 5 a 15 minutos, publicados como no listados en YouTube.

**Repositorio de código fuente:** [Vanguard — Web Development Course](https://github.com/Vanguard-app-web/webdev-course-vanguard).

> **Estado del curso:** las cinco misiones cuentan con video, práctica precargada y código inicial y completo, con HTML y CSS en archivos separados.

## Secuencia de las Lecciones

### Misión 1: Descubre la web

**Responsable:** Antony Alexander Jimenez Saavedra — [saavedraantony-max](https://github.com/saavedraantony-max).

**Duración:** 8 minutos y 54 segundos.

**Descripción:** descubre cómo el navegador interpreta una página web y cómo se complementan HTML y CSS. Crea el primer saludo de Pixel con un encabezado principal y un párrafo, añade una sección sobre lo que está aprendiendo y cambia su contenido observando la vista previa. Conoce también la función de `<!doctype html>`, `<html>`, `<head>` y `<body>` en un documento completo.

**Enlace:** [Ver la misión 1 en YouTube](https://youtu.be/ILUyw7PBHYE).

**Consejos clave:**

- HTML describe el contenido y su estructura; CSS controla su presentación. En esta misión se introduce CSS, pero todavía no se escriben reglas de estilo.
- `<h1>` identifica el encabezado principal, `<h2>` presenta una sección y `<p>` contiene un párrafo. Un párrafo no es otro nivel de encabezado.
- Una etiqueta de cierre utiliza una barra, como `</h1>` o `</p>`, para indicar dónde termina el elemento.
- `<!doctype html>` declara el tipo de documento. `<head>` contiene información de la página y `<body>` contiene lo que se muestra en ella. El `<title>` de la pestaña es distinto del encabezado visible `<h1>`.
- CodePen prepara la estructura del documento: en su panel HTML se escriben los elementos visibles. Al abrir los archivos del repositorio, esa estructura ya está incluida.
- Cambia una cosa cada vez y observa el resultado: modificar el texto de un párrafo conserva su significado como párrafo.

**Empieza a programar:** [Abrir el ejercicio precargado en LiveCodes](https://livecodes.io/?html=%3Ch1%3EHola%2C%20Pixel%3C%2Fh1%3E%0A%3Cp%3EBienvenido%20a%20mi%20primera%20p%C3%A1gina%20web.%3C%2Fp%3E&css=%2F%2A%20En%20esta%20misi%C3%B3n%20trabajamos%20con%20HTML.%20Los%20estilos%20se%20a%C3%B1aden%20en%20la%20misi%C3%B3n%204.%20%2A%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n%201%20%C2%B7%20Descubre%20la%20web).

El video utiliza CodePen. La práctica abre el mismo punto de partida en LiveCodes, otro editor gratuito que funciona en el navegador, con HTML y CSS separados y sin JavaScript.

1. Abre la práctica. El punto de partida contiene el saludo `<h1>Hola, Pixel</h1>` y el párrafo de bienvenida, los dos primeros elementos de la demostración.
2. Debajo, añade `<h2>¿Qué estoy aprendiendo?</h2>` y un párrafo que diga «Estoy aprendiendo HTML y pronto usaré CSS».
3. Cambia ese párrafo a «Estoy aprendiendo HTML y quiero crear sitios web». Comprueba que cambia el texto y que el encabezado principal sigue distinguiéndose del título de sección.
4. Compara tu resultado con el ejemplo completo. El archivo CSS solo contiene un comentario: los estilos se trabajan en la misión 4.

**Desafío:** cambia el encabezado principal por tu propio saludo y añade un párrafo donde cuentes lo que te gusta. Comprueba en la vista previa que aparecen tu saludo y el nuevo párrafo, que conservas un único `<h1>` y que las etiquetas están cerradas. No hay un texto único correcto: prueba con tus propias palabras.

**Código de esta misión:**

| Versión | HTML | CSS |
| --- | --- | --- |
| Punto de partida | [index.html](starter-files/mision-01/index.html) | [style.css](starter-files/mision-01/style.css) |
| Ejemplo completo | [index.html](completed-examples/mision-01/index.html) | [style.css](completed-examples/mision-01/style.css) |

Cada `index.html` carga el `style.css` de su propia carpeta. Para usar estos archivos en CodePen, copia únicamente el contenido de `<body>` al panel HTML y el contenido de `style.css` al panel CSS; no copies la etiqueta `<link>`.

### Misión 2: Organiza tu contenido

**Responsable:** Brayan Benjamin Huerta Cardenas — [brayanjk22](https://github.com/brayanjk22).

**Duración:** 11 minutos y 3 segundos.

**Descripción:** organiza la página de Pixel con un título principal, secciones y párrafos. Construye paso a paso una lista con viñetas para sus pasatiempos y otra numerada para sus metas, observando cómo responde la vista previa. Añade importancia y énfasis dentro de un párrafo y termina con una pregunta y un desafío para practicar.

**Enlace:** [Ver la misión 2 en YouTube](https://youtu.be/b9Je5N0OyIA).

**Consejos clave:**

- `<h1>` identifica el encabezado principal, `<h2>` presenta secciones del mismo nivel y `<p>` desarrolla sus ideas. Los encabezados expresan jerarquía; no se eligen solo por el tamaño de la letra.
- `<ul>` agrupa elementos sin una secuencia necesaria; `<ol>` representa una lista en la que el orden importa. El navegador muestra las viñetas o los números.
- Cada elemento se escribe con `<li>` dentro de su lista. Al añadir o retirar uno, incluye tanto su contenido como sus etiquetas de apertura y cierre.
- `<strong>` indica importancia y normalmente se ve en negrita; `<em>` indica énfasis y suele verse en cursiva. Ambas etiquetas aportan significado dentro del mismo párrafo.
- Cambia una cosa cada vez y observa el resultado. Revisa que los elementos estén dentro de su lista y que las etiquetas anidadas se cierren antes del párrafo que las contiene.

**Práctica:** [Abrir el ejercicio precargado en LiveCodes](https://livecodes.io/?html=%3Ch1%3EHola%2C+soy+Pixel%3C%2Fh1%3E%0A%3Cp%3EBienvenido+a+mi+primera+p%C3%A1gina+web.%3C%2Fp%3E%0A%0A%3Ch2%3E%C2%BFQu%C3%A9+estoy+aprendiendo%3F%3C%2Fh2%3E%0A%3Cp%3EEstoy+aprendiendo+HTML+y+pronto+usar%C3%A9+CSS.%3C%2Fp%3E&css=%2F*+En+esta+misi%C3%B3n+trabajamos+con+HTML.+Los+estilos+se+a%C3%B1aden+en+la+misi%C3%B3n+4.+*%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n+2+%C2%B7+Organiza+tu+contenido).

El video utiliza CodePen. La práctica abre el mismo punto de partida en LiveCodes, otro editor gratuito en el navegador, con HTML y CSS separados y sin JavaScript. El saludo y el párrafo iniciales reproducen la variante de texto del video; si vienes de la misión 1 puedes conservar tus propios textos y seguir los mismos cambios de estructura.

1. Cambia «¿Qué estoy aprendiendo?» por «Sobre mí» y su párrafo por «Me gustan los robots y aprender a programar». Conserva el título principal y la bienvenida.
2. Añade `<h2>Mis pasatiempos</h2>` y una lista `<ul>` con tres `<li>`: Dibujar robots, Escuchar música y Resolver acertijos. Prueba un cuarto elemento, «Leer historias», comprueba la nueva viñeta y retíralo para volver a tres.
3. Añade `<h2>Mis metas</h2>` y una lista `<ol>` con Aprender HTML, Practicar CSS y Crear una página completa. Observa la numeración automática y explica por qué aquí sí importa la secuencia.
4. En el párrafo «Sobre mí», rodea «robots» con `<strong>` y «aprender a programar» con `<em>`. Comprueba que las dos partes siguen dentro del mismo `<p>`.
5. Compara con el ejemplo completo: un `<h1>`, tres secciones `<h2>`, tres pasatiempos y tres metas. El CSS solo contiene un comentario; todavía no se aplican estilos.

**Desafío:** añade una sección «Mis comidas favoritas» o «Mis juegos favoritos» con tres elementos. Elige el tipo de lista según si la secuencia importa y explica tu elección. Comprueba que el encabezado aparece antes de la lista, que hay tres elementos dentro de ella y que conservas el resto de la página. Una posible respuesta del video usa `<ul>` para arroz con pollo, pasta y ensalada de frutas; puedes usar tus propios ejemplos. El desafío se añade después del ejemplo completo de la lección.

**Código de esta misión:**

| Versión | HTML | CSS |
| --- | --- | --- |
| Punto de partida | [index.html](starter-files/mision-02/index.html) | [style.css](starter-files/mision-02/style.css) |
| Ejemplo completo | [index.html](completed-examples/mision-02/index.html) | [style.css](completed-examples/mision-02/style.css) |

Cada `index.html` carga el `style.css` de su carpeta. Para usar el ejercicio en CodePen, copia solo el contenido de `<body>` al panel HTML y el comentario de `style.css` al panel CSS; no copies la etiqueta `<link>`. El ejemplo completo coincide con el punto de partida de la misión 3.

### Misión 3: Conecta tu página

**Responsable:** Luisa Nhiriel Casalino Berrocal — [lulu22nhiri](https://github.com/lulu22nhiri).

**Duración:** 9 minutos.

**Descripción:** añade a la página de Pixel un enlace que salta a sus metas, un enlace externo a una guía de HTML y una imagen con texto alternativo. Agrupa el contenido por temas y prepara la clase de la tarjeta que se usará para aplicar estilos en la siguiente misión.

**Enlace:** [Ver la misión 3 en YouTube](https://youtu.be/jTsvDy6rGkI).

**Consejos clave:**

- El atributo `href` de un enlace `<a>` indica el destino. Cambiar el texto visible mantiene el mismo destino si conservas el atributo.
- Para saltar a una parte de la misma página, haz coincidir `href="#metas"` con `id="metas"` en el encabezado de destino.
- En `<img>`, `src` indica dónde está la imagen y `alt` describe su contenido para quienes no pueden verla.
- Usa `<main>` para el contenido principal, `<section>` para agruparlo por tema y `<footer>` para el pie. La clase `tarjeta` permite seleccionar ese bloque desde CSS en la misión 4.

**Práctica:** [Abrir el ejercicio precargado en LiveCodes](https://livecodes.io/?html=%3Ch1%3EHola%2C+soy+Pixel%3C%2Fh1%3E%0A++++%3Cp%3EBienvenido+a+mi+primera+p%C3%A1gina+web.%3C%2Fp%3E%0A%0A++++%3Ch2%3ESobre+m%C3%AD%3C%2Fh2%3E%0A++++%3Cp%3EMe+gustan+los+%3Cstrong%3Erobots%3C%2Fstrong%3E+y+%3Cem%3Eaprender+a+programar%3C%2Fem%3E.%3C%2Fp%3E%0A%0A++++%3Ch2%3EMis+pasatiempos%3C%2Fh2%3E%0A++++%3Cul%3E%0A++++++++%3Cli%3EDibujar+robots%3C%2Fli%3E%0A++++++++%3Cli%3EEscuchar+m%C3%BAsica%3C%2Fli%3E%0A++++++++%3Cli%3EResolver+acertijos%3C%2Fli%3E%0A++++%3C%2Ful%3E%0A%0A++++%3Ch2%3EMis+metas%3C%2Fh2%3E%0A++++%3Col%3E%0A++++++++%3Cli%3EAprender+HTML%3C%2Fli%3E%0A++++++++%3Cli%3EPracticar+CSS%3C%2Fli%3E%0A++++++++%3Cli%3ECrear+una+p%C3%A1gina+completa%3C%2Fli%3E%0A++++%3C%2Fol%3E&css=%2F*+En+esta+misi%C3%B3n+trabajamos+con+HTML.+Los+estilos+se+a%C3%B1aden+en+la+misi%C3%B3n+4.+*%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n+3+%C2%B7+Conecta+tu+p%C3%A1gina).

1. Abre la práctica y añade un enlace interno a «Mis metas» y otro a la guía de HTML. Cambia temporalmente el texto del enlace externo y comprueba que sigue abriendo la misma guía.
2. Inserta una imagen debajo de «Sobre mí» y escribe su texto alternativo. Agrupa el perfil con `<main class="tarjeta">`, secciones y un pie.
3. Revisa la vista previa y compara tu HTML con el ejemplo completo.

**Desafío:** crea un enlace a un recurso de aprendizaje que te interese y escribe un `alt` que describa la imagen que elijas. Comprueba en la vista previa que la imagen carga y que el enlace lleva al sitio que escogiste.

| Versión | HTML | CSS |
| --- | --- | --- |
| Punto de partida | [index.html](starter-files/mision-03/index.html) | [style.css](starter-files/mision-03/style.css) |
| Ejemplo completo | [index.html](completed-examples/mision-03/index.html) | [style.css](completed-examples/mision-03/style.css) |

### Misión 4: Dale estilo con CSS

**Responsable:** Giovanni Marcelo Gallegos De La Cruz.

**Duración:** 11 minutos y 17 segundos en la versión corregida.

**Descripción:** aplica CSS a la página de Pixel. Usa selectores para dar estilo al título, los subtítulos y los enlaces, y ajusta el fondo, la tipografía y el espaciado.

**Enlace:** [Ver Misión 4 en YouTube](https://youtu.be/oMIzA7jUDWA).

**Consejos clave:**

- Usa `h1`, `h2` y `a` para seleccionar los títulos, subtítulos y enlaces.
- Cambia el color del texto con `color` y el fondo con `background-color`.
- Ajusta la tipografía con `font-family` y `line-height`. Usa `margin` para el espacio exterior y `padding` para el interior.

**Práctica:** [Abrir la página de Pixel en LiveCodes](https://livecodes.io/?html=%3Cmain%20class%3D%22tarjeta%22%3E%0A%20%20%20%20%20%20%20%20%3Ch1%3EHola%2C%20soy%20Pixel%3C%2Fh1%3E%0A%20%20%20%20%20%20%20%20%3Cp%3EBienvenido%20a%20mi%20primera%20p%C3%A1gina%20web.%3C%2Fp%3E%0A%0A%20%20%20%20%20%20%20%20%3Csection%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ch2%3ESobre%20m%C3%AD%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Cp%3EMe%20gustan%20los%20%3Cstrong%3Erobots%3C%2Fstrong%3E%20y%20%3Cem%3Eaprender%20a%20programar%3C%2Fem%3E.%3C%2Fp%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Cimg%20src%3D%22https%3A%2F%2Fplacehold.co%2F600x320%2Fpng%22%20alt%3D%22Imagen%20de%20ejemplo%20de%20seiscientos%20por%20trescientos%20veinte%20p%C3%ADxeles%22%3E%0A%20%20%20%20%20%20%20%20%3C%2Fsection%3E%0A%0A%20%20%20%20%20%20%20%20%3Csection%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ch2%3EMis%20pasatiempos%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Cul%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EDibujar%20robots%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EEscuchar%20m%C3%BAsica%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EResolver%20acertijos%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3C%2Ful%3E%0A%20%20%20%20%20%20%20%20%3C%2Fsection%3E%0A%0A%20%20%20%20%20%20%20%20%3Csection%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ch2%3EMis%20metas%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Col%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EAprender%20HTML%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EPracticar%20CSS%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3ECrear%20una%20p%C3%A1gina%20completa%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3C%2Fol%3E%0A%20%20%20%20%20%20%20%20%3C%2Fsection%3E%0A%0A%20%20%20%20%20%20%20%20%3Csection%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ch2%3EUn%20recurso%20para%20aprender%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ca%20href%3D%22https%3A%2F%2Fdeveloper.mozilla.org%2Fes%2Fdocs%2FWeb%2FHTML%22%3EAprender%20m%C3%A1s%20sobre%20HTML%3C%2Fa%3E%0A%20%20%20%20%20%20%20%20%3C%2Fsection%3E%0A%0A%20%20%20%20%20%20%20%20%3Cfooter%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Cp%3EP%C3%A1gina%20de%20pr%C3%A1ctica%20creada%20con%20HTML.%3C%2Fp%3E%0A%20%20%20%20%20%20%20%20%3C%2Ffooter%3E%0A%20%20%20%20%3C%2Fmain%3E&css=%2F*%20Escribe%20aqu%C3%AD%20las%20reglas%20CSS%20de%20la%20Misi%C3%B3n%204.%20*%2F&activeEditor=css). Escribe las reglas en el panel CSS y observa los cambios en la vista previa.

**Desafío:** cambia el color de fondo, el color del título y la tipografía de la página. Comprueba los tres cambios en la vista previa y que el título siga siendo legible.

| Material | HTML | CSS |
| --- | --- | --- |
| Ejercicio inicial | [index.html](starter-files/mision-04/index.html) | [style.css](starter-files/mision-04/style.css) |
| Ejemplo completo | [index.html](completed-examples/mision-04/index.html) | [style.css](completed-examples/mision-04/style.css) |

### Misión 5: El desafío final: tu página web

**Responsable:** Fabricio Jose Rivera Rupay — [Fabricio1924](https://github.com/Fabricio1924).

**Duración del video:** 13 minutos y 44 segundos.

**Descripción:** reúne lo aprendido para transformar la página de Pixel en una tarjeta de perfil organizada. Aprende a limitar su ancho, centrar el contenido, distinguir el espacio interior del exterior y aplicar fondos, bordes y esquinas redondeadas. Después adapta la imagen, conserva una señal visual en los enlaces y comprueba el diseño en vistas amplias y estrechas. La misión también muestra errores comunes y cómo corregirlos observando el resultado en CodePen.

**Enlace:** [Ver la misión 5 en YouTube](https://youtu.be/I9BesDGiYkI).

**Consejos clave:**

- HTML describe el contenido; CSS controla su presentación. Podemos mejorar el diseño sin reemplazar la estructura de la página.
- El selector de clase debe coincidir con el nombre escrito en el atributo `class` del HTML. Una letra diferente puede impedir que se apliquen los estilos.
- `padding` representa el espacio interior, `border` delimita la caja y `margin` controla el espacio exterior. No son intercambiables.
- `max-width` limita el crecimiento de la tarjeta y los márgenes laterales automáticos permiten centrarla cuando sobra espacio. Con `box-sizing: border-box`, el ancho incluye el relleno y el borde.
- Una imagen puede adaptarse al ancho de su contenedor y conservar sus proporciones. Un enlace debe seguir siendo reconocible después de cambiar su decoración.
- Revisa las llaves, los nombres y los puntos y coma. Cambia una cosa cada vez y comprueba el resultado en más de un tamaño de ventana.

**Proyecto final:** personalizar la tarjeta de perfil de Pixel manteniendo su estructura y aplicando los estilos aprendidos.

**Práctica en línea:** [abrir el punto de partida en JSFiddle](https://jsfiddle.net/oym7feLd/).

**Ejemplo completo en línea:** [consultar la tarjeta terminada en JSFiddle](https://jsfiddle.net/0t214mdn/1/).

El video utiliza CodePen. Estas prácticas contienen el mismo HTML y CSS en JSFiddle, otro editor gratuito que funciona en el navegador. No necesitas instalar programas ni iniciar sesión para abrirlas y ejecutarlas.

1. Abre el punto de partida y pulsa **Run / Ejecutar** para ver el resultado.
2. Conserva el contenido del panel HTML y completa el panel CSS siguiendo el video; el panel JavaScript permanece vacío.
3. Ajusta el ancho del panel de resultado para comprobar la imagen y la tarjeta. Compara tus cambios con el ejemplo completo cuando termines.

**Desafío:** inventa un personaje y cambia el saludo, la descripción, los pasatiempos, el enlace y los colores. Conserva la clase de la tarjeta, comprueba cada modificación y revisa que el texto se lea y la imagen quepa tanto en una vista amplia como en una estrecha. Al terminar, explica qué propiedad cambiaste y qué efecto produjo.

**Código de esta misión:**

| Versión | HTML | CSS |
| --- | --- | --- |
| Punto de partida | [index.html](starter-files/mision-05/index.html) | [style.css](starter-files/mision-05/style.css) |
| Ejemplo completo | [index.html](completed-examples/mision-05/index.html) | [style.css](completed-examples/mision-05/style.css) |

El punto de partida conserva la página y los estilos básicos de la misión anterior. El ejemplo completo añade el modelo de caja, la tarjeta centrada, la imagen adaptable y el ajuste para pantallas estrechas. Cada `index.html` carga el `style.css` de su propia carpeta. La fotografía del robot se carga desde Unsplash y necesita conexión a Internet.

Para usar estos archivos en CodePen, copia solo el bloque `<main class="tarjeta">...</main>` de `index.html` en el panel HTML y el contenido de `style.css` en el panel CSS. No copies la etiqueta `<link>`: el editor conecta sus paneles automáticamente.

## Recursos Adicionales

- **Código fuente del curso:** [repositorio de GitHub](https://github.com/Vanguard-app-web/webdev-course-vanguard).
- **Archivos iniciales:** [starter-files](starter-files/).
- **Ejemplos completos:** [completed-examples](completed-examples/).
- **Utilidades técnicas:** [scripts](scripts/), carpeta reservada para herramientas auxiliares del curso; no contiene guiones de narración.
- **Editor mostrado en el video de la misión 5:** [CodePen](https://codepen.io/pen/).
- **Prácticas precargadas de la misión 5:** [punto de partida](https://jsfiddle.net/oym7feLd/) y [ejemplo completo](https://jsfiddle.net/0t214mdn/1/) en JSFiddle.

### Todas las actividades prácticas

| Misión | Actividad | Empezar a programar |
| --- | --- | --- |
| 1 | Crear el saludo de Pixel con h1 y un párrafo, añadir una sección con h2 y modificar el texto en la vista previa | [Abrir el ejercicio precargado en LiveCodes](https://livecodes.io/?html=%3Ch1%3EHola%2C%20Pixel%3C%2Fh1%3E%0A%3Cp%3EBienvenido%20a%20mi%20primera%20p%C3%A1gina%20web.%3C%2Fp%3E&css=%2F%2A%20En%20esta%20misi%C3%B3n%20trabajamos%20con%20HTML.%20Los%20estilos%20se%20a%C3%B1aden%20en%20la%20misi%C3%B3n%204.%20%2A%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n%201%20%C2%B7%20Descubre%20la%20web) |
| 2 | Organizar la página de Pixel con encabezados y párrafos, construir listas de pasatiempos y metas y añadir importancia y énfasis | [Abrir el ejercicio precargado en LiveCodes](https://livecodes.io/?html=%3Ch1%3EHola%2C+soy+Pixel%3C%2Fh1%3E%0A%3Cp%3EBienvenido+a+mi+primera+p%C3%A1gina+web.%3C%2Fp%3E%0A%0A%3Ch2%3E%C2%BFQu%C3%A9+estoy+aprendiendo%3F%3C%2Fh2%3E%0A%3Cp%3EEstoy+aprendiendo+HTML+y+pronto+usar%C3%A9+CSS.%3C%2Fp%3E&css=%2F*+En+esta+misi%C3%B3n+trabajamos+con+HTML.+Los+estilos+se+a%C3%B1aden+en+la+misi%C3%B3n+4.+*%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n+2+%C2%B7+Organiza+tu+contenido) |
| 3 | Añadir y probar enlaces internos y externos, insertar una imagen con texto alternativo y organizar la página de Pixel | [Abrir el ejercicio precargado en LiveCodes](https://livecodes.io/?html=%3Ch1%3EHola%2C+soy+Pixel%3C%2Fh1%3E%0A++++%3Cp%3EBienvenido+a+mi+primera+p%C3%A1gina+web.%3C%2Fp%3E%0A%0A++++%3Ch2%3ESobre+m%C3%AD%3C%2Fh2%3E%0A++++%3Cp%3EMe+gustan+los+%3Cstrong%3Erobots%3C%2Fstrong%3E+y+%3Cem%3Eaprender+a+programar%3C%2Fem%3E.%3C%2Fp%3E%0A%0A++++%3Ch2%3EMis+pasatiempos%3C%2Fh2%3E%0A++++%3Cul%3E%0A++++++++%3Cli%3EDibujar+robots%3C%2Fli%3E%0A++++++++%3Cli%3EEscuchar+m%C3%BAsica%3C%2Fli%3E%0A++++++++%3Cli%3EResolver+acertijos%3C%2Fli%3E%0A++++%3C%2Ful%3E%0A%0A++++%3Ch2%3EMis+metas%3C%2Fh2%3E%0A++++%3Col%3E%0A++++++++%3Cli%3EAprender+HTML%3C%2Fli%3E%0A++++++++%3Cli%3EPracticar+CSS%3C%2Fli%3E%0A++++++++%3Cli%3ECrear+una+p%C3%A1gina+completa%3C%2Fli%3E%0A++++%3C%2Fol%3E&css=%2F*+En+esta+misi%C3%B3n+trabajamos+con+HTML.+Los+estilos+se+a%C3%B1aden+en+la+misi%C3%B3n+4.+*%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n+3+%C2%B7+Conecta+tu+p%C3%A1gina) |
| 4 | Dar estilo a la página de Pixel con CSS | [Abrir el ejercicio precargado en LiveCodes](https://livecodes.io/?html=%3Cmain%20class%3D%22tarjeta%22%3E%0A%20%20%20%20%20%20%20%20%3Ch1%3EHola%2C%20soy%20Pixel%3C%2Fh1%3E%0A%20%20%20%20%20%20%20%20%3Cp%3EBienvenido%20a%20mi%20primera%20p%C3%A1gina%20web.%3C%2Fp%3E%0A%0A%20%20%20%20%20%20%20%20%3Csection%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ch2%3ESobre%20m%C3%AD%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Cp%3EMe%20gustan%20los%20%3Cstrong%3Erobots%3C%2Fstrong%3E%20y%20%3Cem%3Eaprender%20a%20programar%3C%2Fem%3E.%3C%2Fp%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Cimg%20src%3D%22https%3A%2F%2Fplacehold.co%2F600x320%2Fpng%22%20alt%3D%22Imagen%20de%20ejemplo%20de%20seiscientos%20por%20trescientos%20veinte%20p%C3%ADxeles%22%3E%0A%20%20%20%20%20%20%20%20%3C%2Fsection%3E%0A%0A%20%20%20%20%20%20%20%20%3Csection%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ch2%3EMis%20pasatiempos%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Cul%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EDibujar%20robots%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EEscuchar%20m%C3%BAsica%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EResolver%20acertijos%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3C%2Ful%3E%0A%20%20%20%20%20%20%20%20%3C%2Fsection%3E%0A%0A%20%20%20%20%20%20%20%20%3Csection%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ch2%3EMis%20metas%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Col%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EAprender%20HTML%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3EPracticar%20CSS%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3ECrear%20una%20p%C3%A1gina%20completa%3C%2Fli%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3C%2Fol%3E%0A%20%20%20%20%20%20%20%20%3C%2Fsection%3E%0A%0A%20%20%20%20%20%20%20%20%3Csection%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ch2%3EUn%20recurso%20para%20aprender%3C%2Fh2%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Ca%20href%3D%22https%3A%2F%2Fdeveloper.mozilla.org%2Fes%2Fdocs%2FWeb%2FHTML%22%3EAprender%20m%C3%A1s%20sobre%20HTML%3C%2Fa%3E%0A%20%20%20%20%20%20%20%20%3C%2Fsection%3E%0A%0A%20%20%20%20%20%20%20%20%3Cfooter%3E%0A%20%20%20%20%20%20%20%20%20%20%20%20%3Cp%3EP%C3%A1gina%20de%20pr%C3%A1ctica%20creada%20con%20HTML.%3C%2Fp%3E%0A%20%20%20%20%20%20%20%20%3C%2Ffooter%3E%0A%20%20%20%20%3C%2Fmain%3E&css=%2F*%20Escribe%20aqu%C3%AD%20las%20reglas%20CSS%20de%20la%20Misi%C3%B3n%204.%20*%2F&activeEditor=css) |
| 5 | Personalizar la tarjeta de perfil y comprobar su diseño en distintos anchos | [Abrir la práctica en JSFiddle](https://jsfiddle.net/oym7feLd/) |

### Material de cada misión

| Misión | Archivos iniciales | Ejemplo completo |
| --- | --- | --- |
| 1 | [mision-01](starter-files/mision-01/) | [mision-01](completed-examples/mision-01/) |
| 2 | [mision-02](starter-files/mision-02/) | [mision-02](completed-examples/mision-02/) |
| 3 | [mision-03](starter-files/mision-03/) | [mision-03](completed-examples/mision-03/) |
| 4 | [mision-04](starter-files/mision-04/) | [mision-04](completed-examples/mision-04/) |
| 5 | [mision-05](starter-files/mision-05/) | [mision-05](completed-examples/mision-05/) |

**¡Gracias por completar el curso! Guarda tus prácticas, prueba cambios pequeños y sigue aprendiendo.**

---

## Elaboración

- **Universidad:** Universidad Peruana de Ciencias Aplicadas.
- **Carrera:** Ingeniería de Software.
- **Período académico:** 202620.
- **Curso:** 1ASI0730 — Aplicaciones Web.
- **NRC:** [PENDIENTE: indicar el NRC de Aplicaciones Web].
- **Nombre del equipo:** Vanguard.
- **Líder del equipo:** [PENDIENTE: indicar nombres y apellidos].
- **Fecha de entrega:** [PENDIENTE: indicar la fecha correspondiente].

### Integrantes del equipo

| Código | Nombres y apellidos |
| --- | --- |
| u202424008 | Luisa Nhiriel Casalino Berrocal |
| u202424466 | Giovanni Marcelo Gallegos De La Cruz |
| u20241e550 | Brayan Benjamin Huerta Cardenas |
| u202420031 | Antony Alexander Jimenez Saavedra |
| u202423883 | Fabricio Jose Rivera Rupay |

### Organización del trabajo

La distribución de las misiones conserva el mismo orden utilizado por el equipo en el curso anterior.

| Misión | Responsable | Aporte documentado |
| --- | --- | --- |
| 1. Descubre la web | Antony Alexander Jimenez Saavedra | [Video de la misión 1](https://youtu.be/ILUyw7PBHYE), [código inicial](starter-files/mision-01/), [ejemplo completo](completed-examples/mision-01/) y [práctica precargada](https://livecodes.io/?html=%3Ch1%3EHola%2C%20Pixel%3C%2Fh1%3E%0A%3Cp%3EBienvenido%20a%20mi%20primera%20p%C3%A1gina%20web.%3C%2Fp%3E&css=%2F%2A%20En%20esta%20misi%C3%B3n%20trabajamos%20con%20HTML.%20Los%20estilos%20se%20a%C3%B1aden%20en%20la%20misi%C3%B3n%204.%20%2A%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n%201%20%C2%B7%20Descubre%20la%20web). Documentación de la introducción a HTML y CSS, los primeros encabezados y párrafos, la práctica y el desafío. |
| 2. Organiza tu contenido | Brayan Benjamin Huerta Cardenas — [brayanjk22](https://github.com/brayanjk22) | Preparación y narración del [video de la misión 2](https://youtu.be/b9Je5N0OyIA); [código inicial](starter-files/mision-02/), [ejemplo completo](completed-examples/mision-02/) y [práctica precargada](https://livecodes.io/?html=%3Ch1%3EHola%2C+soy+Pixel%3C%2Fh1%3E%0A%3Cp%3EBienvenido+a+mi+primera+p%C3%A1gina+web.%3C%2Fp%3E%0A%0A%3Ch2%3E%C2%BFQu%C3%A9+estoy+aprendiendo%3F%3C%2Fh2%3E%0A%3Cp%3EEstoy+aprendiendo+HTML+y+pronto+usar%C3%A9+CSS.%3C%2Fp%3E&css=%2F*+En+esta+misi%C3%B3n+trabajamos+con+HTML.+Los+estilos+se+a%C3%B1aden+en+la+misi%C3%B3n+4.+*%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n+2+%C2%B7+Organiza+tu+contenido). Documentación de encabezados, párrafos, listas, importancia y énfasis, con práctica y desafío. |
| 3. Conecta tu página | Luisa Nhiriel Casalino Berrocal | [Video de la misión 3](https://youtu.be/jTsvDy6rGkI), [código inicial](starter-files/mision-03/), [ejemplo completo](completed-examples/mision-03/) y [Abrir el ejercicio precargado en LiveCodes](https://livecodes.io/?html=%3Ch1%3EHola%2C+soy+Pixel%3C%2Fh1%3E%0A++++%3Cp%3EBienvenido+a+mi+primera+p%C3%A1gina+web.%3C%2Fp%3E%0A%0A++++%3Ch2%3ESobre+m%C3%AD%3C%2Fh2%3E%0A++++%3Cp%3EMe+gustan+los+%3Cstrong%3Erobots%3C%2Fstrong%3E+y+%3Cem%3Eaprender+a+programar%3C%2Fem%3E.%3C%2Fp%3E%0A%0A++++%3Ch2%3EMis+pasatiempos%3C%2Fh2%3E%0A++++%3Cul%3E%0A++++++++%3Cli%3EDibujar+robots%3C%2Fli%3E%0A++++++++%3Cli%3EEscuchar+m%C3%BAsica%3C%2Fli%3E%0A++++++++%3Cli%3EResolver+acertijos%3C%2Fli%3E%0A++++%3C%2Ful%3E%0A%0A++++%3Ch2%3EMis+metas%3C%2Fh2%3E%0A++++%3Col%3E%0A++++++++%3Cli%3EAprender+HTML%3C%2Fli%3E%0A++++++++%3Cli%3EPracticar+CSS%3C%2Fli%3E%0A++++++++%3Cli%3ECrear+una+p%C3%A1gina+completa%3C%2Fli%3E%0A++++%3C%2Fol%3E&css=%2F*+En+esta+misi%C3%B3n+trabajamos+con+HTML.+Los+estilos+se+a%C3%B1aden+en+la+misi%C3%B3n+4.+*%2F&editor=codemirror&activeEditor=markup&languages=html%2Ccss&title=Misi%C3%B3n+3+%C2%B7+Conecta+tu+p%C3%A1gina). Documentación de la lección, la práctica y el desafío. |
| 4. Dale estilo con CSS | Giovanni Marcelo Gallegos De La Cruz | Demostración de selectores, colores, tipografía y espaciado. Incluye el [ejercicio inicial](starter-files/mision-04/) y el [ejemplo completo](completed-examples/mision-04/). |
| 5. El desafío final: tu página web | Fabricio Jose Rivera Rupay | Guion, narración y [video de la misión 5](https://youtu.be/I9BesDGiYkI); [código inicial](starter-files/mision-05/), [ejemplo completo](completed-examples/mision-05/) y [práctica precargada](https://jsfiddle.net/oym7feLd/). Estructura inicial del repositorio y documentación de su sección en este README. |

Cada integrante completará su sección del plan, sus enlaces reales y sus archivos reservados. Los aportes deberán registrarse mediante commits de la cuenta correspondiente. El equipo completará después el resumen conjunto de la elaboración y comprobará la continuidad entre las misiones.
