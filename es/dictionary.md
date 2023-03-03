# Diccionario de términos de frontend

Índice: [0-9](#0-9) [A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) J [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) X Y Z

## 0-9

### 9-slice scaling

**escalado en 9 partes** (escalado sin distorsión), una técnica que permite cambiar el tamaño de un objeto sin distorsión geométrica. El objeto se divide en 9 partes (3 filas y 3 columnas), cada una de las cuales se escala según sus propias reglas: las esquinas no se escalan en absoluto, la parte central se escala en altura y anchura, y el resto sólo en anchura o en altura.

## A

### accessibility, a11y

**accesibilidad,** la posibilidad de que todos puedan utilizar la interfaz, independientemente de sus limitaciones físicas o técnicas.

### adaptive design

**diseño adaptativo,** un enfoque del diseño de sitios web que tiene en cuenta la adaptabilidad a distintos dispositivos y entornos, en contraste con el habitual diseño "fijo" solo para computadoras. Una forma de crear un diseño adaptativo es mediante técnicas de [diseño responsivo](#responsive-design).

### almost standards mode

**modo casi estándar,** es un modo de interpretación y visualización de páginas por parte del navegador, en el que éste se aparta deliberadamente de los estándares (como en el [modo de compatibilidad](#quirks-mode)) sólo para ciertos casos especiales, utilizado para páginas con [docktips](#doctype) de transición HTML 4 y XHTML 1.

### anchor

1. **vínculo,** hipervínculo entre dos documentos.
2. **Ancla,** enlace a un elemento dentro del documento, puede ser parte de un hipervínculo.

### animation

**animación,** cambio suave de los parámetros visuales de un objeto.

### asset

**recurso,** componente de un sitio web: archivos de texto, gráficos, vídeo, bases de datos, etc. En sentido estricto, un "recurso estático" sería: estilos, scripts, gráficos de diseño, en contraposición al [contenido](https://github.com/web-standards-ru/dictionary/blob/master/dictionary.md#content) dinámico.

### assert

**verificación,** condición que se está verificando, utilizada en pruebas, p. ej. _field assert has failed — la comprobación del campo ha fallado._

### at-keyword

**clave de directiva,** véase. [directiva](#at-rule)

### at-rule

**directiva,** tipo de [declaración](#statement) que empieza con el símbolo `@`, p. ej. _@import_.

### attribute

**atributo,** p. ej. `rel="stylesheet"`.

- attribute name — **nombre del atributo**
- attribute value — **valor del atributo**

## B

### back-end

**backend**

1. el campo de las tecnologías web que operan en el servidor.
2. es la parte interna del sistema de servidores que gestionan los datos.

### background

**fondo,** p. ej. _background image — imagen de fondo._

- background-color — **color de fondo**
- background-position — **posición del fondo**
- background-size — **tamaño del fondo**
- background-repeat — **repetición del fondo**
- background-origin — **límites del fondo**
- background-clip — **recorte del fondo**
- background-attachment — **archivo adjunto de fondo**
- background-image — **imagen de fondo**

### baseline

** línea de base,** línea imaginaria en la base de las letras de una cadena.

### bikeshed

**prestar demasiada atención a banalidades,** (véase. [ley de las trivialidades](https://ru.wikipedia.org/wiki/Закон_тривиальности)). No existe un equivalente definido en español, es mejor traducir el significado general, p. ej. _avoid bikeshedding — no discutir sobre pequeñeces_.

### blending mode

**modo de mezcla,** es un algoritmo de mezcla de capas utilizado en editores gráficos o directamente en CSS, p. ej. _overlay blending mode — modo de mezcla de superposiciones._

### block

1. **bloque de declaración,** parte estructural de la [declaración](#statement). Son corchetes, y contienen declaraciones de propiedades (o, en el caso de una expresión de medios, bloques de estilo).
2. **vista de bloque,** véase. [vista](#display)

### blockquote

**cita de bloque,** Elemento HTML para resaltar el área _que no es cadena_ del documento. Puede contener un atributo `cite` con un enlace a la fuente original.

### border

**borde,** es la parte exterior visible del bloque, p. ej. _border-left — el borde de la izquierda._

- border-collapse — unión de bordes
- border-color — color del borde
- border-image — borde gráfico
- border-image-outset — sangría del borde gráfico
- border-image-repeat — repetición del borde gráfico
- border-image-slice — partición del borde gráfico
- border-image-source — ubicación de la imagen para el borde gráfico
- border-image-width — grosor del borde gráfico
- border-radius — redondeo del borde
- border-style — estilo del borde
- border-width — anchura del borde

### border-radius

**redondeo del borde,** p. ej., _border-radius: 3px — redondear el borde en 3 píxeles, border-top-left-radius — redondeo de la esquina superior izquierda,_ Véase también [esquinas redondeadas](#rounded-corners).

### bounding box

**cuadro delimitador**

### box model

**modelo de cuadros,** sistema de dimensiones del cuadro, que consta del contenido, la sangría, el borde y la sangría exterior.

### box-shadow

**sombra (del cuadro),** p. ej. _box-shadow is red — la sombra del cuadro es roja._

### breadcrumbs

**migajas de pan,** navegación auxiliar en un sito web, que muestra la estructura o los pasos seguidos en orden secuencial.

### breakpoint

1. **punto de interrupción,** — es una de las traducciones polisémicas más utilizadas, el significado exacto se infiere claramente del contexto.
2. **punto de parada,** es la línea del código en la que se detiene un script para que se llame al depurador.
3. **punto de control,** las condiciones en las que la distribución del sitio cambia de una a otra. Característico para las expresiones de medios.

### browser

**navegador**

### button

**botón**

1. un elemento de la interfaz que, al hacer clic en él, envía un formulario o realiza otra acción.
2. elemento de formulario `<button>` o `<input type="button">` (también `submit` y `image`).

## C

### callback

**Callback,** ejecución de código al finalizar una función, p. ej. _pass value in a callback — pasar el valor en un callback._

### candidate recommendation (CR)

**candidato por recomendación,** estado de especificaciones [W3C](#world-wide-web-consortium-w3c), una posible opción para [la recomendación propuesta](#proposed-recommendation-pr).

### cascade

### cascade

**cascada,** esquema descrito en la especificación CSS que define cómo se aplican los bloques de estilo a un elemento.

### cascade layer

**capa en cascada,** es la capacidad de agrupar y controlar el orden en que se aplican los estilos dentro de una [misma fuente](#cascade-origin), declarada con la [directiva](#at-rule) `@layer`. P. ej. _rules within a cascade layer cascade together_ — _reglas de una capa en cascada se combinan entre sí_

### cascade origin

**fuente de cascada,** el área de descripción de estilos incorporada en los navegadores, el orden de las fuentes determina la aplicación de estilos o [cascadas](#cascade): de estilos del navegador a las transition-declaraciones. P. ej. _there are eight cascade origings, including user styles_ — _есть восемь каскадных источников, включая пользовательские стили._

### cell

**ranura**

1. unidad estructural de la tabla.
2. elemento de tabla `<td>` o `<th>`.

### cellpadding (margen de celda)

**sangría en celdas de la** tabla.

### cellspacing

**espaciado entre las celdas de la** tabla.

### character reference

**sustitución de símbolos,** p. ej. `&nbsp;`. Demos paso también a una traducción no del todo exacta, pero más establecida,**símbolo especial.**

### checkbox

**casilla de verificación**

1. Elemento de la interfaz que permite seleccionar una o varias opciones, p. ej. _checkbox is disabled — casilla de verificación está desactivada._
2. elemento de formulario `<input type="checkbox">`.

### child

1. Sust. **descendiente,** (en pl. s. children — **descendientes**)
2. adj. **filial,** p. ej. _child process_ — _proceso de filiación_

### classitis

**classitis,** enfermedad ficticia caracterizada por el uso excesivo de múltiples clases: tanto para el diseño como para el almacenamiento de información.

### clear

**deshacer la agilización,** propiedad CSS que impide que un bloque se sitúe alrededor de los bloques flotantes precedentes.

- clear: left — **deshacer la agilización de la izquierda**
- clear: right — **deshacer la agilización de la derecha**
- clear: both — **deshacer la agilización en ambos lados**

### clearfix

**clearfix,** es una técnica para evitar que los contenedores con bloques flotantes se hundan. Consiste en crear un espaciador especial que se coloca después de los bloques flotantes y anula su racionalización. Un caso especial de la solución a los problemas de desplazamiento (véase. [ la tabla resumen de todos los problemas y soluciones](http://css-live.ru/articles-css/clearfix-block-formatting-context-methods-cheatsheet.html)).

### click

**clic,** Pulsando sobre un objeto con el cursor del mouse o un dispositivo similar, p. ej. _double click is firing event — el doble clic activa un evento._

### client-side

**client-side,** área de tecnología que funciona en un navegador, suele ser sinónimo de [frontend](#front-end).

### clipping path

**Trazado de recorte**

### closure

**clausura,** es una función que contiene en su cuerpo referencias a variables declaradas en el código que la rodea.

### code

1. Sust. **código,** no calculado. (como el azúcar), p. ej. _error in code — error en el código,_ pero no en _los _ códigos (incorrecto).
2. v. **escribir el código, diseñar, programar,** por ejemplo. _to code a site — codificar un sitio web._

### colspan

**combinar columnas,** atributo HTML para combinar varias celdas de la tabla en una sola línea.

### column

**columna,** es el área vertical en una tabla, diseño o texto.

### color

**color**

### combinator

**combinador,** carácter especial usado en un selector complejo para especificar con precisión una combinación de elementos DOM, por ejemplo. `>`, `+` etc. El espacio entre los selectores también es considerado como un combinador.

- descendant combinator — **combinador descendiente,** `` (espacio).
- child combinator — **combinador del descendiente inmediato,** `>`. También se denomina **filial**.
- adjacent sibling combinator — **combinador de hermanos adyacentes,** `+`.
- general sibling combinator — **combinador de hermanos general,** `~`.

### comment

**comentario,** nota de codificación

### component

**componente,** (m.) parte integrante de algo. P. ej. _app components_ — _componentes de la aplicación_

### compositing

**composición**

### composite layer

**capa compuesta**

### compositor

**compositor** (significa. "motor de composición")

### container query

**expresión del contenedor,** declaración de la directiva `@container` con condiciones, permiten aplicar estilos dependiendo de las propiedades del contenedor _principal_. P. ej. _many container query cases can be solved with existing technology_ — _muchos casos de consulta sobre contenedores pueden resolverse con la tecnología actual_

### containing block

**contiene un bloque,** en relación con el cual se calculan las dimensiones y posiciones del bloque. En pocas palabras, el bloque contenedor es el principal de este bloque, no por DOM, sino por el flujo del documento. P. ej. _containing block isn’t always the content area of the parent_ — _no siempre es el área de contenido del bloque principal._

### content

**contenido**

- metadata content — **contenido meta**
- flow content — **contenido de flujo**
- sectioning content — **contenido estructural**
- heading content — **contenido del encabezado**
- phrasing content — **redacción de contenido**
- embedded content — **contenido integrado**
- interactive content — **contenido interactivo**
- palpable content — **contenido tangible**
- script-supporting content — **contenido compatible con scripts **
- grouping content — **agrupar contenidos**

### continuous integration

**integración continua,** la práctica de ensamblar, probar y desplegar el software de forma frecuente y automatizada

### cookie

**cookie,** pequeño fragmento de datos que se envía desde el servidor y se guarda en el navegador.

- access to cookies — **acceso a las cookies**
- cookie banner — **banner de cookies**
- authorization cookie — **autorización de cookie **
- first-party cookies — **cookies primarias**
- third-party cookies — **cookies de terceros**

### cross-browser

**cross-browser,** funciona en todos los navegadores, fusionados.

### cross-platform

**cross-platform,** funciona en todas las plataformas, fusionado.

### custom properties

**propiedades personalizadas,** propiedades CSS de la forma `-my-property` que los propios desarrolladores pueden crear y usar más adelante en el código como variables con la función `var()`. También es normal traducir **variables CSS,** p. ej. _CSS variables, also known as CSS custom properties, are landing in Chrome 49 — Las variables CSS, conocidas también como propiedades personalizadas CSS, llegan a Chrome 49._

### CSS Working Group (CSSWG)

**Grupo de trabajo CSS**

### custom

**personalizado** (aprox. **personalizado**)

- custom element — **elemento personalizado **.
- custom attribute — **atributo personalizado**.

## D

### data binding

**vinculación de datos,** sincronización automática de datos entre dos entidades, por lo general un modelo y una representación.

### declaration

**declaración,** declaración de propiedad y valor.

### deep comparison

**comparación detallada,** es una comparación de dos objetos, en la que se compara la estructura de los objetos y se comprueba la igualdad de las primitivas contenidas en los objetos.

### deploy, deployment

**configuración, despliegue, disposición, extensión,** publicar los cambios directamente en un servidor público (producción) o a través de sistemas intermediarios y procesos de compilación automatizados.

### deprecated

**obsoleto,** el estado de una característica lingüística que no se recomienda usar porque _ya_ ha sido sustituida, eliminada o _lo será_ en futuras versiones, p. ej. _this API is a replacement of the deprecated `React.addons.cloneWithProps()` — esta API sustituye a la obsoleta `React.addons.cloneWithProps()`_ o _`<applet>` is deprecated in favor of `<object>` — `<applet>` está obsoleto en favor de `<object>`_.

### design

1. sust. **diseño,** el aspecto visual del sitio web, puede incluir los principios de interacción y las soluciones arquitectónicas, p. ej. _new design for a site — nuevo diseño para un sitio web_.
2. v. **desarrollar,** crear o diseñar la apariencia y funcionalidad.

### device pixel ratio

cm. [pixel ratio](#pixel-ratio)

### dirty checking

**comprobación de propiedades "sucias" del objeto,** es decir, [la comparación detallada](#deep-comparison) de las propiedades del modelo, que resulta en [callback](#callback) si algo ha cambiado.

### disable

**desactivar**

### disabled

**inactivo,** estado del elemento de formulario en el que está prohibido cambiar, p. ej. _disabled button — botón desactivado._

### display

1. **vista,** propiedad css que determina cómo se muestra el bloque.

 - display: none - **vista oculta**
 - display: block — **forma de bloque**
 - display: inline — **vista en línea**
 - display: inline-block — **tipo de bloque de línea**

- display: flex — **vista flexbox** (véase. [flexbox](#flexbox))
- display: inline-flex — **vista flexbox de cadena** (véase. [flexbox](#flexbox))

2. **pantalla,** p. ej. _pantalla del smartphone, resolución de la pantalla_.

### divitis

**divatosis,** es una enfermedad ficticia caracterizada por el uso de solo de elementos `<div>` en lugar de otros [semánticamente](#semantics) apropiados.

### DOM

**modelo de objetos del documento, inicio**

### doctype

**doctype,** forma de contrucción `<DOCTYPE html>` al inicio del documento indica la versión de HTML usada. Usado por los navegadores para seleccionar un modo ([estándar](#standards-mode-standards-compliance-mode), [más normal](#almost-standards-mode) o [conforme](#quirks-mode)).

### dropdown

**menú desplegable,** es un elemento de interfaz que revela información adicional cuando se activa.

## E

### easing

**la suavidad, una función de suavidad,** describe el cambio en la velocidad de animación mediante palabras clave o curvas de Bezier, p. ej. _transition easing is linear — la flexibilización transitoria es lineal._

### editor’s draft (ED)

**borrador del editor,** es el estado inicial de la especificación [W3C](#world-wide-web-consortium-w3c) sugerido por uno de los editores. Un borrador de [trabajo](#working-draft-wd) está basado en el borrador editorial.

### element

**elemento**

- void elements — **elementos vacíos**
- raw text elements — **elementos de texto libre**
- escapable raw text elements — **elementos de texto sin formato escapables**
- foreign elements — **elementos externos**
- normal elements — **elementos normales**

### em

**em,** una unidad de medida en CSS que depende del tamaño de la fuente principal, p. ej. _font-size: 3em — tamaño de fuente 3em._

### enable

**activar**

### enabled

**activo,** estado del elemento del formulario en el que está permitido cambiar, p. ej. _enabled button — botón activado._

### engine

**motor,** p ej. _Safari is based on WebKit engine — Safari se basa en el motor WebKit._

## F

### fallback

**fallback,** es una implementación adicional en caso de que el navegador no disponga de las funciones necesarias, como la activación de scripts o el uso de códecs de vídeo, p. ej. _fallback to a link — volver a un enlace._

### favicon

**favicon,** es un icono de sitio web, por lo general de 16×16 píxeles en formato ICO.

### feature query

**directiva`@suppórts`,** es una construcción condicional que permite aplicar estilos de forma selectiva en función de la compatibilidad del navegador con determinadas propiedades y valores. Todavía no se ha establecido una traducción directa siguiendo el ejemplo de las [expresiones multimedia](#media-query)

### fieldset

**grupo de campos,** un elemento que combina varios campos de formulario, p. ej. _green border on a fieldset — borde verde en el grupo de campos._

### figure

**figura,** es un elemento HTML5 que contiene una imagen, vídeo, tabla, gráfico o fragmento de código.

### figcaption

**título de la figura,** título o pie de figura.

### filter

**filtro**

- filter: brightness — **brillo**
- filter: contrast — **contraste**
- filter: grayscale — **escala de grises**
- filter: sepia — **sepia**
- filter: invertir - **invertir**
- filter: saturate — **saturación**
- filter: hue-rotate — **rotación del color**
- filter: blur — **desenfoque**
- filter: opacity — **opacidad**
- filter: drop-shadow — **sombra**

### flash of…

- flash of unstyled text, FOUT — **parpadeo de texto sin estilo,** mostrar texto en la fuente del sistema antes de cargar a la fuente web
- flash of invisible text, FOIT — **flash de texto invisible,** no existe texto en la página antes de que se cargue la fuente web.
- flash of faux text, FOFT — **flash de texto falso,** mostrar los contornos del texto en una fuente básica modificada antes de cargar las fuentes necesarias

### flexbox

**flexbox,** mecanismo [diseños](#layout).

- flex container — **contenedor-flex**
- flex item — **artículo-flex**
- flex-direction — **dirección-flex**
- flex-wrap — **transferencia de elementos flex,** determina si el contenedor es de una o varias líneas
- flex-basis — **tamaño base** del elemento flexible en el eje principal
- flex-grow — **factor de crecimiento**
- flex-shrink — **encogimiento-flex**
- main axis — **eje principal,** la dirección en la que se suceden los elementos flex en el contenedor
- cross axis — **eje transversal,** dirección perpendicular al eje principal
- main size — **tamaño principal,** es el tamaño del elemento flex a lo largo del eje principal
- cross size — **dimensión transversal,** tamaño del elemento flex a lo largo del eje transversal
- justify-content — **distribución de los elementos flex** por el eje principal
- align-items — **alineación de elementos flex** por el eje transversal
- align-self — **alineación del elemento flex** en el eje transversal
- align-content — **alineación de las líneas** del contenedor con el eje transversal
- order — **número de serie** del elemento flex

### float

1. adj. **float,** es un bloque que hace que los siguientes bloques fluyan a su alrededor, p. ej. _float layout — disposición en bloques flotantes._
2. v. **agilizar,** seguir de cerca el bloque flotante, p. ej. _text is floating to the right — el texto fluye hacia la derecha._
3. v. **pulsar,** a la derecha o a la izquierda, debido a las propiedades flotantes, p. ej. _float block to the left — presiona el bloque a la izquierda._

### font

**fuente**

- font-weight — **saturación**

  - font-weight: normal — **normal**
  - font-weight: bold — **negrita** o **media negrita** (en términos tipográficos)
  - font-weight: bolder — **más negrita**
  - font-weight: lighter — **más clara**

- font-style — **estilo de fuente**

  - font-style: normal — **recta**
  - font-style: italic — **cursiva**
  - font-style: oblique — **inclinada**

- font-size — **tamaño de letra, tamaño del punto**

- font-family — **familia tipográfica, fuente**

  - font-family: serif — **serif**
  - font-family: sans-serif — **sin serif**
  - font-family: monospace — **monoespaciado**

### footer

**pie de página**

1. zona visible característica del final de la página.
2. elemento `<footer>` — la parte semántica con metadatos.

### formatting context

**contexto de formateo,** en CSS, es la zona en la que los elementos visuales de una página (texto, bloques, celdas, etc.) se alinean según determinadas reglas.

- block formatting context, BFC — **contexto de formato de bloque,** **CFB** (p. ej. _element with `overflow` establishes the new BFC — el elemento con `oveflow` crea un nuevo BFC_)
- grid formatting context — **contexto de formateo de celdas** (véase. [grid layout](#grid-layout))
- flexbox formatting context — **contexto de formateo flexbox** (véase. [flexbox](#flexbox))
- inline formatting context — **contexto lineal del formato**
- table formatting context — **contexto de formato de tablas**

### forced color mode

**modo de color obligado,** en el que los colores específicos del desarrollador se cambian a la fuerza por los colores del sistema o los especificados por el usuario, la mayoría de las veces para aumentar el contraste y hacer el contenido más accesible a los discapacitados visuales.

### fragment identifier

**identificador de fragmento,** texto después de `#` en la URL, lo que permite hacer referencia a una parte específica del documento. Se utiliza principalmente en las especificaciones y al trabajar con SVG, en HTML se emplea el término [ancla](#anchor) que es más familiar.

### framework

**marco,** es un conjunto de bibliotecas y componentes para simplificar el desarrollo. Suele constituir la estructura básica del producto. _P. ej., [Twitter Bootstrap](http://getbootstrap.com/)._

### front-end

**frontend**

1. Campo tecnológico para el desarrollo de interfaces web, incluye herramientas y tecnologías de apoyo que se ejecutan en el navegador o en el [lado del cliente](#client-side).
2. parte externa del sistema del servidor, responsable de recibir datos, enviar respuestas y generar código para el navegador, forma parte del [lado del servidor](#server-side).

### full screen

**modo pantalla completa,** comportamiento de un programa o parte de este, en el que se utiliza toda la pantalla.

### fullstack

**fullstack**

1. Área de especialización que incluye [frontend](#front-end) y [backend](#back-end).
2. especialista que pueda encargarse de todos los aspectos del proyecto, desde la parte del cliente hasta la del servidor.

P. ej., _Katerina solucionó las bases de datos y corrigió "frontender" por "fullstack" en su CV._

### function

**función**

1. En programación, es un fragmento de código de un programa (un subprograma) al que se puede acceder desde cualquier otra parte del programa.
2. En CSS, puede estar presente en la [declaración](#declaration) en el lugar del valor. P. ej., `url(img/gradient.png)`.

## G

### generated content

**contenido generado,** parte de un documento creado mediante CSS, [un pseudoelemento](#pseudo-element) y la propiedad `content`.

### graceful degradation

**degradación gradual** — es el enfoque en el que la interfaz del sitio web se degrada para los navegadores más antiguos en los que parte de la tecnología utilizada no es compatible. De este modo, se reduce en la medida de lo posible el perjuicio ocasionado al usuario. Por ejemplo: el color de fondo en lugar del degradado, los gráficos de mapa de bits en lugar de los vectoriales o la reproducción de vídeo mediante un plug-in. También existe una traducción más literal _"degradación elegante"_.

### gradient

**gradiente,** es la transición suave de un color a otro.

- linear gradient — **gradiente lineal**
- radial gradient — **gradiente radial**
- conical gradient — **gradiente cónica**

### grid

1. **rejilla,** es una forma de ordenar la disposición de los elementos en un diseño mediante un ritmo vertical u horizontal, p. ej. _module grid — rejilla modular._
2. **grid,** una cuadrícula bidimensional de filas y columnas en formato de [grid](#grid-layout).

### **grid layout**

**grid layout,**es un mecanismo[ de disposición](#layout) que permite disponer elementos en una cuadrícula bidimensional — [grid](#grid) (2).

- **grid container** — _contenedor de rejilla_
- **grid item** — _elemento de rejilla_
- **grid track** — _franja de rejilla_, es un término genérico para las filas y columnas de la _rejilla_
- **grid cell** — _unidad de rejilla_
- **grid line** — _línea de rejilla_, límite virtual entre _franjas de rejilla_ adyacentes, a las que se pueden vincular _elementos de rejilla_.
- **grid area** — _área de rejilla_, un espacio para colocar _elementos de rejilla_, limitado a cuatro _líneas de rejilla_
- **grid gutter** — _intervalo de rejilla_, espacio entre _franjas de rejilla_ adyacentes

## H

### header

**encabezado**

1. zona visible, característica del inicio de la página.
2. elemento `<header>` — parte semántica del encabezado.

### height

**altura**

## I

### icon font

**fuente de iconos,** es una fuente sintética que contiene iconos y otras imágenes vectoriales planas para el diseño de sitios web, p. ej. _build an icon font — elabore una fuente de iconos._

### immutable

**inmutable,** es el término más comúnmente aplicado a los datos (tipos de datos) en la programación funcional.

### implement

**implementar, aplicar** p. ej. _Firefox has implemented support of everything — Firefox ha implementado soporte para todo._

### inline

1. **de línea,** que tiene propiedades de una línea.

 - inline block — **bloque de líneas**.
 - inline box — **elemento de línea** en el formato de línea: la parte del contenido del contenedor de línea a la que se aplican directamente las reglas CSS, p. ej. _anonymous inline box — elemento de línea anónimo._.
 - inline element — **elemento de línea**.

2. **integrado,** líneas de código ubicadas adentro.

 - inline styles — **estilos integrados**.
 - inline SVG — **SVG integrado**.
 - inline script — **script integrado**.

### input

**elemento de formulario,** permite al usuario interactuar con la interfaz, por ejemplo: un cuadro de texto, un botón, un interruptor.

### intrinsic dimensions

**dimensiones inherentes,** la anchura y altura determinadas por el propio elemento, no por el entorno. CSS no puede indicar cómo se calculan las dimensiones propias. Únicamente los elementos sustituibles pueden tener dimensiones propias, por ejemplo: imágenes, vídeo, audio y otros bloques con presentación independiente del desarrollador.

### internationalization, i18n

**internacionalización,** es un proceso de diseño y desarrollo de interfaces que permite la [localización](#localization-l10n) para diferentes regiones (diferente cultura o idioma) sin modificaciones técnicas, p. ej., _`Intl.DateTimeFormat` - es un constructor de clase que permite formatear la fecha y la hora en función de la configuración regional._

### interoperability

**interoperatividad**

## K

### kerning

**kerning,** es la distancia entre pares de letras, teniendo en cuenta su forma, para una escritura más uniforme.

### keyframe

**fotograma clave,** uno de los puntos de animación fijados, cuyos cambios son automáticos.

### keyframe animation

**animación por fotogramas,** una forma de crear animaciones en CSS mediante fotogramas clave.

### keyword

**palabra clave**

## L

### label

**etiqueta,** establece la conexión entre un determinado elemento y un elemento de un formulario.

### last call (LC)

**borrador final,** estado de la especificación [W3C](#world-wide-web-consortium-w3c) para las últimas correcciones antes del estado de [candidato a recomendación](#candidate-recommendation-cr) _(se canceló en 2014, ahora solo se encuentra en especificaciones más antiguas)_.

### layout

**disposición,** es la organización de los bloques principales de la página, p. ej. _3 columns layout — disposición de 3 columnas._

### legend

**leyenda,** encabezado de un grupo de elementos de formulario, se define mediante un [grupo de campos](#fieldset)

### length

**largo**

### letter-spacing

**espaciado entre letras, tracking,** la distancia total entre letras en un texto, es diferente de [kerning](#kerning).

### library

**biblioteca,** un conjunto de soluciones listas para simplificar el proceso de desarrollo. Por lo general, una biblioteca implementa una función específica o un conjunto de funciones relacionadas, p. ej., la animación.

### line-box

**contenedor de línea** en el formato de línea: es un contenedor virtual que contiene todos los elementos de una misma línea.

### line-height

**altura de línea, interlineado,** distancia entre las líneas base del texto.

### list

**lista,** listado secuencial de un grupo de elementos.

- ordered list — **lista ordenada,** ordenada según un determinado principio.
- unordered list — **lista desordenada,** una en la que el orden no tiene importancia.

### list-style

**estilo de lista**

### localization, l10n

**localización,** el proceso de adaptación de la interfaz a la correspondencia lingüística y cultural de una determinada región (país, localización), p. ej., _`new Date().toLocaleDateString('en-US')` - convierte una fecha a su representación de cadena, según la localización de EE.UU. _

## M

### margin

**sangría externa,** p. ej. _margin-bottom: -10px — sangría negativa inferior 10 píxeles._

### margin box

**sangría exterior de algo**

### matrix

**matriz (transformación),** descripción de la transformación de un objeto mediante una matriz.

### media query

**declaración de medios,** la declaración de una directiva `@media` con determinadas [condiciones](#media-query-list), permite aplicar estilos en función de las capacidades del dispositivo. La traducción literal de "media query" es menos precisa expresando su función real.

### media query list

**condiciones de declaración de medios,** una lista de condiciones que definen cuándo se aplicarán las declaraciones dentro de la directiva `@media`. P. ej., `only screen and (min-width: 35em)`.

### media type

**tipo de medio,** puede ser una condición de declaración de medio. Indica a qué método de salida están destinados los estilos (p. ej. `screen` — en pantalla, `print` — para imprimir, `speech` — para un sintetizador de voz).

### media feature

**media feature (función de medio),** puede ser una condición para la declaración medios. Define la característica del medio. P. ej., `min-width`.

### mixin

**mezcla,** es un conjunto de propiedades que amplía el comportamiento de otra entidad, que se encuentra en los preprocesadores de CSS y en los patrones de JavaScript, p. ej. _mixin is clearing — la mezcla limpia el flujo._

### mobile first

**El móvil primero,** Un enfoque de desarrollo en el que el diseño de un servicio parte de una versión para móviles en lugar de una versión para pantallas más grandes. El término fue introducido por Luke Wroblewski en [el libro con el mismo nombre](https://abookapart.com/products/mobile-first).

### mock object

**objeto ficticio**

### mock-up

**maqueta,** es el aspecto o diseño de un sitio web con distintos grados de detalle, p. ej. _designer has sent a page mock-up — el diseñador ha enviado la maqueta de la página._

### modal

1. adj. **modal,** bloquea la interfaz para realizar una acción, p. ej. _modal dialog — dialogo modal._
2. sust. **ventana modal (diálogo),** elemento de la interfaz, véase _modal._

### multiple

**múltiple,** se repite dos o más veces, p. ej. _multiple backgrounds — múltiples fondos._

### multiple columns

1. **multicolumnas,** es un mecanismo CSS que permite alinear texto en varias columnas, p. ej. _multiple columns support in IE — Soporte multicolumna en IE. _ Preferible a las incómodas 'columnas múltiples'.
2. **multicolumna,** compuesta por varias columnas, p. ej. _multiple columns layout — disposición de múltiples columnas._

## N

### nested

**anidado,** que se encuentra dentro de algo, p. ej. _double nesting — anidación doble._

### node

**nodo,** elemento de estructura, p. ej. _child node — nodo hijo (secundario)._

### number

**número, tipo numérico**

## O

### opacity

**opacidad,** es el grado de opacidad, p. ej. _opacity: 0.1 — opacidad 10%._ A menudo se denomina erróneamente transparencia.

### opaque

**opaco,** es el grado de opacidad, p. ej. _opaque by 75% — opaco al 75%,_ significa transparencia del 25%.

### outline

**contorno,** contorno uniforme exterior del elemento, no participa en el modelo de bloques.

## P

### package manager

**gestor de paquetes,** más raramente **administrador de paquetes,** es un software auxiliar para gestionar la instalación, configuración, actualizaciones y eliminación de componentes de software.

### padding

**sangría interna,** p. ej. _padding-top: 10px — sangría interior superior de 10 píxeles._

### pagination

1. **navegación por páginas,** normalmente una lista de enlaces con los números de las páginas en las que se divide el documento.
2. **paginación,** la división de un documento en páginas separadas para facilitar su lectura, descarga u otros fines.

### pattern

**patrón,** es un enfoque formalizado para escribir código, p. ej. _JavaScript patterns — patrones JavaScript._

### parent

**elemento principal**

### percentage

**valor porcentual, porcentaje**

### performance

**rendimiento,** característico de la velocidad de carga, la velocidad de renderizado, etc., p. ej. _CSS performance — rendimiento de CSS._

### performance budget

**presupuesto para el rendimiento,** los indicadores de rendimiento máximo admisibles de la aplicación web. Salirse de este presupuesto supone una caída del rendimiento. P. ej. _Performance Budget Metrics — indicadores del presupuesto de rendimiento._

### persistent data structures

**estructuras de datos permanentes**

### pinch

**pellizcar (estirar) con los dedos,** es un gesto para controlar la interfaz táctil: pellizcar (o estirar, dependiendo de la dirección) con los dedos en la pantalla táctil.

### pixel

**píxel,** unidad de medida para el diseño en pantallas, en pl. **pixeles,** abreviado. **px.**

- physical pixel — **píxel físico,** en una celda en la matriz, la unidad de resolución de la pantalla del dispositivo.
- device independent pixel (dip) — **píxel virtual,** píxel independiente del dispositivo, puede ser mayor, menor o igual que un píxel físico.
- bitmap pixel — **píxel rasterizado**.

### pixel density

**densidad de píxeles,** es el número de píxeles que se ajustan a una unidad de tamaño lineal de pantalla, p. ej. _pixel density of the screen is 326 ppi — la pantalla tiene una densidad de píxeles de 326 ppi._

### pixel ratio

**relación de píxeles,** es la relación entre el píxel físico y el píxel virtual, p. ej. _screen has pixel ratio of 2 — la relación de píxeles de la pantalla es de 2._

### placeholder

1. **marcador de posición,** es un sustituto temporal de una imagen, texto, etc. P. ej.: _En lugar del retrato del presidente, se inserta de forma temporal un marcador de posición con gatitos_.
2. **sugerencia de campo,** atributo de un campo de texto, diseñado para sugerir cómo se debe completar el campo. La mayoría de las veces es un ejemplo de cómo rellenarlo. P. ej.: `placeholder="+7 (999) 123-12-13"`.

### ppi (pixel per inch)

**píxeles por pulgada,** unidad de medida de la densidad de píxeles (véase. [pixel density](#pixel-density)).

### plugin

**TODO**

### polyfill

**polyfill,** es un script que recrea una funcionalidad faltante, p. ej. _new polyfill for IE6 — nuevo polyfill para IE6._

### progressive web metrics

**métricas web progresivas,** un conjunto de métricas de la página, relacionadas con [el rendimiento](#performance).

- first paint — **primer renderizado**
- first contentful paint (FCP) — **el primer renderizado significativo**
- first meaningful paint — **el primer renderizado importante**
- visually ready — **preparado visualmente**
- visually complete — **completado visualmente**
- first interactive — **primera interactividad**
- estimated input latency — **latencia estimada de entrada**
- time to interactive (TTI) — **tiempo hasta la primera interactividad**
- time to first consistently interactive — **tiempo hasta la primera interactividad consistente**
- largest contentful paint (LCP) — **el renderizado significativo más grande**
- cumulative layout shift (CLS) — **un cambio acumulativo en el diseño**
- total blocking time (TBT) — **tiempo total de bloqueo**
- first input delay (FID) — **el tiempo de respuesta para la primera interacción**

### prolyfill

**prolyfill,** es una de las variantes de [polyfill](#polyfill), que se diferencia en que reproduce una funcionalidad _probable_, descrita en la especificación pero aún no implementada en los navegadores.

### popup

**ventana emergente, popup,** es una ventana o elemento de interfaz independiente que aparece encima de la actual, p. ej. _annoying popup — las molestas ventanas emergentes._

### position

**posicionamiento**

- position: static — **estático**
- position: absolute — **absoluta**
- position: relative — **relativa**
- position: fixed — **fija**
- position: sticky — **anclada**

### preprocessor

**preprocesador,** es una herramienta que convierte el código de una sintaxis a otra, p. ej. _Sass CSS preprocessor — Preprocesador CSS Sass._

### progress bar

**progress bar** o barra de progreso, es un elemento de la interfaz que muestra el progreso de una operación.

### progressive enhancement

**mejoras progresivas** — es un enfoque en el que todos los navegadores reciben la misma funcionalidad básica, pero en los navegadores modernos esta funcionalidad se amplía en función de la compatibilidad con las nuevas tecnologías. Por ejemplo: degradados, gráficos vectoriales, reproducción de vídeo.

### Progressive Web App (PWA)

**aplicación web progresiva,** — un enfoque del desarrollo de aplicaciones web que combina las ventajas de los sitios web convencionales y las aplicaciones nativas: carga rápida, instalación en el SO, funcionamiento sin conexión, notificaciones push, acceso a las API del sistema. La información para la instalación se describe en el webmanifest. El enfoque progresivo consiste en que, en un navegador normal es simplemente un sitio web, pero en los navegadores y sistemas operativos compatibles es una aplicación.

### promises

**promises,** es una forma de ejecutar scripts de forma asíncrona, en contraste con el uso de callbacks.

### property

**propiedad,** p.ej. _Propiedad CSS_.

### proposed recommendation (PR)

**recomendación propuesta,** estado de la especificación [W3C](#world-wide-web-consortium-w3c), candidato probable a [recomendación](#recommendation-rec).

### pseudo-element

**pseudoelemento,** elemento interno adicional creado con CSS y `::before` o `::after`.

### pseudo-class

**pseudoclase,** se utiliza para vincular la declaración a un determinado estado de un elemento DOM. Se separa del selector con el símbolo de dos puntos `:`. P. ej., la declaración del bloque de reglas con el selector `.item:hover` se aplica cuando se pasa el mouse por encima. `.item`.

### pull request, pr

**pull request,** petición para aceptar cambios en una rama del repositorio desde una bifurcación u otra rama.

## Q

### quirks mode

**modo de compatibilidad,** un modo de interpretación y visualización de páginas que utiliza el navegador, en el que éste se aparta deliberadamente de los estándares para poder mostrar documentos creados antes de principios de la década de 2000 y que se basan en los errores y características de los navegadores de aquella época. Se usa para páginas sin [doctype](#doctype) y con doctypes obsoletos (p. ej. HTML 3.2).

## R

### radio button

**boton de radio,** es un elemento de formulario `<input type="radio">` para seleccionar una opción de entre varias, p.ej. _radio button is checked — el radio button está seleccionado._

### recalculate

**recalcular**

### recommendation (REC)

**recomendación,** estado final de la especificación [W3C](#world-wide-web-consortium-w3c), recomendada para su implementación en navegadores y su uso por desarrolladores.

### registry

**registro,**espacio para el almacenamiento de paquetes, p. ej. _GitHub Package Registry — Registro de paquetes de GitHub._ La traducción "registro" es poco acertada, ya que entra en conflicto con el _registro de letras _utilizado en el frontend.

### reflow

**reajuste**

### rem

**rem,** unidad de medida en CSS que depende del tamaño de fuente del elemento raíz `<html>`, p. ej. _font-size: 3rem — tamaño de fuente: 3rem._

### render

**renderización**

### repaint

**volver a dibujar**

### reset

**reset,** normalmente es el restablecimiento de los estilos por defecto en CSS, p. ej. _style reset file — archivo de restablecimiento del estilo._

### resolution

**resolución,** es el número de píxeles físicos en la pantalla del dispositivo, p. ej. _screen resolution is 1024×768 pixels — resolución de pantalla de 1024×768 píxeles._

### responsive design

**diseño adaptativo,** es uno de los métodos tecnológicos para crear [un diseño adaptativo](#adaptive-design).

### Responsive Images Community Group (RICG)

**Grupo comunitario de imágenes adaptativas**

### rest parameters

**parámetros residuales,** (también _parámetros restantes_, informal. _parámetros-rest_) en JavaScript permite que los parámetros de función sin nombre se representen como un array.

### root

**raíz**

### rounded corners

**esquinas redondeadas,** p. ej. _rounded corners are out of fashion — las esquinas redondeadas han pasado de moda,_ véase. [redondeo de marcos](#border-radius).

### row

**línea, fila**

- área horizontal en una tabla o diseño.
- elemento de tabla `<tr>`.

### rowspan

**fusionar filas,** es un atributo HTML para fusionar varias celdas de una tabla en una sola columna.

### rule-set

**bloque de estilos de elemento,** consta de un selector (o declaración de medios) y un bloque de declaración.

## S

### shallow comparison

**comparación superficial,** es una comparación que comprueba si dos variables hacen referencia a un mismo objeto en la memoria.

### scaffolding

**scaffolding,** es la generación automática de código según la descripción, método de metaprogramación.

### scale

1. sust. **escala**
2. v. **escalar**

### scope

**área de visibilidad,** es una parte limitada de la estructura del programa, en la que está disponible la variable declarada o `<style scoped>` se aplican estilos.

### screen reader

**lector de pantalla,** es un programa que lee en voz alta la información que está en la pantalla del dispositivo, es un tipo de tecnología de asistencia. Los usan personas videntes a las que les resulta más fácil asimilar la información de oído, personas disléxicas, ciegas o con deficiencias visuales. P. ej. _they use screen reader to navigate the web_ — _ellos usan el lector de pantalla para navegar por la web_, _screen reader will say “image cat”_ — _el lector de pantalla dirá "imagen de gato"_.

### script

**script,** son las instrucciones que describen el comportamiento de la página, p. ej. _scripts are not loaded yet — los scripts aún no se han cargado._

### scroll

1. **desplazamiento,** es un elemento de interfaz para mover una parte oculta de la página o bloque, es un indicador de que el elemento anidado es más grande que el principal, p. ej. _horizontal scroll is disabled — el desplazamiento horizontal está prohibido._
2. **desplazar,** desplazar la parte oculta de una página o bloque.

### scrollbar

**barra de desplazamiento,** es el nombre formal de la [barra de scroll](#scroll), p. ej. _system scrollbars — barras de desplazamiento del sistema._

### sectioning roots

**raíces estructurales**

### semantics

**semántica,** es la carga semántica de los elementos HTML, p. ej. _semantic coding — programación semántica._

### selector

**selector,** es la parte estructural necesaria del [bloque de estilos](#rule-set). Responsable de vincular las declaraciones a los elementos DOM.

- simple selector — **selector simple,** puede ser [pseudoclase](#pseudo-class) o uno de los siguientes tipos:
  - type selector — ** selector de tipo,** hace referencia a un tag, p.ej. `ul`, `input` и др.
  - universal selector — **selector universal,** «asterisco»: `*`.
  - ID selector — **selector mediante identificador,** p. ej. `#content`.
  - class selector — **selector de clase,** p.ej. `.item`.
  - attribute selector — **selector de atributo,** p. ej. `[type=submit]`.
- compound selector (tambien: sequence of simple selectors) — **selector compuesto,** es una cadena de selectores simples, no separados por combinadores, p. ej. `input[type=submit]:focus`.
- complex selector — **selector complejo,** son varios selectores simples y/o compuestos, separados por combinadores:
  - descendant selector — **selector de descendiente,** p. ej. `ul li`.
  - child selector — **selector de descendiente directo,** p.ej. `#buttons > *`. También suele llamarse **subordinado**.
  - adjacent sibling selector — **selector de hermanos adyacentes** p ej. `.item + .item`. También suele llamarse **vecino**.
  - general sibling selector — **selector general de vecinos,** p.ej. `.item ~ .item`.

### server-side

**server-side,** área de la tecnología que se ejecuta en un servidor, a menudo sinónimo de [backend](#back-end).

### shadow DOM

**DOM en la sombra, modelo del documento en la sombra.**

### shapes

**figuras, figuras CSS**

### shared

1. adj. **compartido,** p. ej. _shared memory — memoria compartida_
2. adj. **público,** p. ej. _shared folder — carpeta pública_, _shared access — acceso público_

### shim

**shim,** es un código que ayuda a unificar el funcionamiento de los navegadores, por lo general implementando lo que falta o normalizando el soporte existente, p. ej. _HTML5 shim for IE8 — Shim HTML5 para IE8._

### sibling

**vecino** (en el sentido: "elemento vecino").

### sidebar

**barra lateral,** es la parte lateral del sitio web con contenido secundario, p. ej. _sidebar is on the right side — a la derecha se encuentra la barra lateral._

### skew

1. sust. **inclinación**
2. v. **inclinar**

### source maps

**mapas de código,** marcado especial que permite ordenar los archivos fuente y el código compilado para su depuración.

### specification, spec

**especificación,** es la documentación tecnológica para desarrolladores y creadores de navegadores, por lo general en uno de los siguientes estados: de propuesto a aprobado por el W3C, p. ej. _specification draft — borrador de especificación_

### spread

**extender,** operador en JavaScript que extiende las expresiones en los lugares en donde está previsto usar múltiples argumentos al llamar a las funciones `doSomething(...array)`, se esperan múltiples elementos en los arrays `[1, 2, ...array]`) y la adición o sobrescritura de campos en los objetos `{ ...object, field: 'value' }`.

### specificity

**especificidad,** es la característica del [selector CSS](#selector) que define su prioridad en la [cascada](#cascade). Se compone del peso de cada [selector simple](#selector) en su composición.

### stacking context

**contexto de superposición,** elemento de la estructura visual de la página que limita la acción de la propiedad `z-index` de sus descendientes y que se coloca en el eje _z_ como una unidad (totalmente encima o totalmente debajo de cualquier otro elemento). P. ej. _elements with opacity create new stacking context — los elementos con opacidad forman un nuevo contexto de superposición._

### staging server

**servidor de depuración,** el servidor en el que se prueba y depura el producto.

### standards mode, standards compliance mode

**modo estándar,** el modo de interpretación y visualización de la página por parte del navegador, en el que este está obligado a seguir las normas en la medida de lo posible. Se usa para páginas con [doctypes](#doctype) suficientemente modernos, p. ej. doctype HTML5.

### statement

**declaración,** elemento estructural de CSS. Este puede ser un bloque de estilos de elemento, una directiva de importación, una declaración de medios, etc.

### string

1. **tipo cadena,** en programación, es un tipo de datos cuyos valores son una secuencia arbitraria (cadena) de caracteres alfabéticos.
2. **cadena,** en CSS es el valor de cadena de una directiva o propiedad. P. ej., en `content:"\201d"` la cadena es `"\201d"`.

### stub object

**marcador de posición**

### style

1. sust. **estilos,** p. ej. _apply styles to an element — aplicar estilos al elemento,_ plural. es preferible: _estilos del elemento,_ y no _estilo del elemento_ (no es correcto).
2. v. **diseñar,** p. ej. _how to style selects — cómo diseñar los selects,_ es preferible al verbo ambiguo "estilizar".

### style guide

**guía de estilo,** p.ej. _project code style guide — guía de estilo del código del proyecto_.

### stylesheet

**tabla de estilos,** p. ej. _tabla de estilos del documento_.

### swipe

**deslizar,** gesto para manejar la interfaz táctil: movimiento de deslizar los dedos por la pantalla táctil.

### submit

**envío,** p. ej. _envío de formularios_.

## T

### tab

1. **pestaña,** es una de las capas de interfaz de un sitio web o programa, que se activa seleccionando su título, p. ej. _open in new tab — abrir en una nueva pestaña._
2. **tab,** es la tecla de tabulación, que inserta un carácter de tabulación, cambia el enfoque al siguiente elemento de la interfaz o completa una palabra parcialmente escrita, p. ej. _press Ctrl Tab — pulse control-tab._
3. **tab,** es el símbolo de tabulación, tiene un ancho configurable y se usa para introducir sangrías en el código, p. ej. _tabs are better than spaces — los tabs son mejores que los espacios_

### tag

1. **tag,** es el nombre de un elemento en HTML. Existen tags de apertura, de cierre e individuales. P. ej. _no hay tag de cierre — closing tag is missing._
 - tag name — **nombre del tag**
 - start tag — **tag de apertura**
 - end tag — **tag de cierre**
2. **etiqueta,** marcador de contenido, generalmente es una palabra corta.

### tap

**pulsar,** gesto para manejar una interfaz táctil: un toque único a la pantalla táctil.

### text

**texto**

### textarea

**campo de texto,** elemento de formulario para introducir varias líneas de texto.

### text-align

**nivelación, justificación,** orientación de las líneas de texto en una dirección determinada, o uniformemente a lo ancho de un bloque.

- text-align: left — **a la izquierda**
- text-align: right — **a la derecha**
- text-align: justify — **a lo ancho (justificar)**

### text-shadow

**sombra (texto),** p. ej. _text-shadow is red — la sombra del texto es roja._

### throttling

**throttling,** es la introducción de restricciones artificiales, por ejemplo, para reducir la frecuencia de las llamadas a los gestores de eventos en JavaScript o la velocidad de la red y la potencia del CPU durante las pruebas.

### thumb

1. Abreviatura de [thumbnail](#thumbnail).
2. **deslizador,** elemento para manejar la [barra de desplazamiento](#scrollbar).

### thumbnail

**miniatura,** es la copia reducida de una imagen.

### title

1. **título,** cuando se trata del elemento `<title>`, o sobre el título de un elemento.
2. **sugerencia,** cuando se trata del atributo `title=""`.

### toggle

**interruptor,** para pasar de un estado a otro, _cambiar de clase — toggle classes._

### tooltip

**sugerencia,** información auxiliar que aparece al pasar el cursor por encima de un elemento o al activarlo, concretamente `title=""`.

### touch interface

**interfaz táctil**

### transform

**transformación,** p. ej. _transform: scale(2) — transformar la escala por un factor de 2._

### transition

**transición,** p ej. _transition: all 2s linear — transición lineal con una duración de 2 segundos._

### translate

**mover,** mover el objeto usando una transformación CSS, p. ej. _translate(x, y) — moverse a X y Y._

### transpiler

**transpiler,** Un compilador que convierte el código fuente de un lenguaje de programación, a un código fuente en otro lenguaje  de programación.

### typography

**tipografía,** formato de texto mediante la selección de fuentes, parámetros de línea y otros.

## U

### unit

**unidad de medida,** p. ej. _rem unit — unidad de medida "rem"._

### unit testing

**pruebas unitarias**

### URI

**identificador unificado de recursos,** es la secuencia de caracteres que identifica un recurso abstracto o físico.

### URL

1. _informal._ **dirección**. Valor recomendado para usar en la traducción de artículos.

2. **localizador unificado de recursos,** [URI](#uri) que ofrece además información sobre la ubicación del recurso, p. ej. _background: url("http://www.example.com/picture.png")_

### user experience (UX)

**experiencia de usuario,** es la totalidad de la experiencia al interactuar con algo (interfaz, dispositivo, producto). En el contexto del área de conocimiento, se recomienda usar la abreviatura UX ( p. ej. _especialista en UX_).

### user interface (UI)

**interfaz de usuario,** en un contexto claro, se recomienda utilizar simplemente "interfaz".

### utility

**utilidad,** un programa con un propósito muy concreto.

## V

### valid

**válido,** cumple una norma, especificación u otro reglamento, p. ej. _valid markup — maquetado válido_.

### validator

**validador,** instrumento para comprobar el cumplimiento de una norma, especificación u otro reglamento (véase. [valid](#valid)), p. ej. _W3C markup validator — Validador de marcado W3C_.

### value

**valor,** p. ej. _Valor de la propiedad CSS_.

### variable units

**unidades de medida variables,** — propiedades personalizadas que pueden utilizarse como unidades de medida en CSS. Está permitido usarlo de forma abreviada, sin la palabra "medida", p. ej. _variable units make this easier to write — Las unidades variables facilitan su escritura._

### vendor prefix

**prefijo de navegador,** prefijo de la propiedad CSS `-webkit-` o `-moz-`, p. ej. _add vendor prefixes — añada los prefijos de navegador._

### vendor files

**archivos de terceros,** estilos, scripts y otros recursos (dependencias) de otros autores usados en el proyecto, p. ej. _tons of vendor scripts included in the code — muchos scripts de terceros están incluidos en el código._

### vertical-align

**alineación vertical,** es la disposición de los elementos verticalmente dentro de una línea de texto o tabla.

### viewport

**viewport**

1. es el área visible de un documento en la pantalla.
2. elemento `<meta name="viewport">`, que gestiona la adaptación de las páginas en dispositivos móviles.

## W

### website, web site

**sitio,** son páginas que están unidas por una sola dirección. La traducción "sitio web" esta de más.

### worker

**worker,** interfaz de JavaScript que permite ejecutar un script en un flujo secundario.

- web worker — **worker web**
- service worker — **worker de servicio**
- shared worker — **worker público**

### working draft (WD)

**borrador de trabajo,** estado temprano de la especificación [W3C](#world-wide-web-consortium-w3c).

### worklet

**worklet,** es una clase de JavaScript que tiene métodos predefinidos con una firma determinada y que da acceso a varias API del navegador. [Proyecto Houdini](https://github.com/w3c/css-houdini-drafts/wiki) contempla los siguientes tipos de worklets:

- paint worklet — **worklet de renderizado**
- compositor worklet — **worklet de composición**
- layout worklet — **worklet de disposición**

### World Wide Web Consortium (W3C)

**Consorcio WWW,** es una organización que desarrolla estándares web. Traducir "web" como "red" en el siglo XXI ya resulta algo chistoso.

### web standards

**estándares web**

### width

**ancho**

### word-spacing

**espacio entre palabras**

### workaround

**una solución alternativa (técnica),** es una forma de resolver un problema en condiciones limitadas, p. ej. _to figure out workaround — encontrar una solución alternativa._
