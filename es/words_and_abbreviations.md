# Palabras y abreviaturas de las clases CSS

La división en las subsecciones es condicional y no implica ninguna obligación.

Hecho adicionalmente en <https://github.com/goitacademy/dictionary-html-css/blob/main/uk/common-words.md>.

## Bloques/elementos de gran tamaño

### `page`

Página (generalmente el elemento raíz). <br> Abreviatura: no <br> Ejemplo: `page`

### `container`

Contenedor, envoltura. <br> Abreviatura: no <br> Ejemplo: `container`

### `grid`

Rejilla (para colocar los bloques en una rejilla modular). <br> Abreviatura: no <br> Ejemplo: <br> `grid` (elemento en el que habrá una rejilla modular)

### `row`

Envoltura para las celdas de la rejilla modular. <br> Abreviatura: no <br> Ejemplo: <br> `grid__row` (una o varias "filas" de la rejilla modular)

### `column`

Celda de la rejilla modular. <br> Abreviatura: `col`  <br> Ejemplo: <br> `grid__col-md-6` (celda que ocupa 6 columnas en ancho MD)

### `wrapper`

Envoltura de algo. <br> Abreviatura: `wrap`  <br> Por ejemplo: <br> `contacts__wrapper` (envolviendo el contenido del bloque de contacto)

### `inner`

Envoltura interior de algo ( por lo general para limitar el ancho y la alineación central). <br> Abreviatura: no <br> Ejemplo: <br> `promo__inner` (envoltura interior de la unidad promocional)

### `navigation`

Navegación. <br> Abreviatura: `nav`  <br> Ejemplo: <br> `main-nav` (navegación principal)

### `promo`

Publicidad interna, algún tipo de introducción. <br> Abreviatura: no <br> Ejemplo: `promo` <br>

### `features`

Características, ventajas. <br> Abreviatura: no <br> Ejemplo: <br> `features` (un bloque que describe las características y ventajas)

### `cart`

Carrito de la tienda. <br> Abreviatura: no <br> Ejemplo: <br> `cart` (bloque del carrito en la página del carrito)

### `sidebar`, `aside`

Información adicional (normalmente una columna estrecha en la página de un blog). <br> Abreviatura: no <br> Ejemplo: `sidebar`, `aside`  <br>

## Bloques/elementos pequeños

### `item`, `element`, `part`

Parte, elemento, "unidad" independiente. Es una palabra universal si no se te ocurre nada en específico. <br> Abreviatura: `element` → `el`  <br> Ejemplo: <br> `main-nav__list-item` (es un elemento de lista en la navegación principal,`li`), <br> `filter__part` (parte típica del filtro)

### `widget`

Widget. <br> Abreviatura: no <br> Ejemplo: <br> `aside__widget` (widget en la casilla de información adicional)

### `logo`

Logotipo. <br> Abreviatura: no <br> Ejemplo: <br> `logo` (no lo vas a creer...) `.partner__logo` (logotipo del socio)

### `field`

Campo del formulario. <br> Abreviatura: no <br> Ejemplo: <br> `field-text` (unidad de conjunto de forma universal), <br> `field-radio` (unidad de conjunto de forma universal), <br> `field-checkbox` (unidad de conjunto de forma universal), <br> `field-select` (unidad de conjunto de forma universal), <br> `field-file` (unidad de conjunto de forma universal)

### `pagination`

Navegación por varias páginas (1 2 3 ...). <br> Abreviatura: no <br> Ejemplo: `pagination` <br>

### `breadcrumbs`

"Migajas de pan" (Inicio > Catálogo > Productos). <br> Abreviatura: no <br> Ejemplo: `breadcrumbs` <br>

### `modal`

Ventana modal. <br> Abreviatura: no <br> Ejemplo: `modal` <br>

### `popup`

Bloque emergente (normalmente haciendo clic en algo). <br> Abreviatura: no <br> Ejemplo: `popup` <br>

### `tooltip`

Tooltip, es un pequeño bloque (normalmente pasando el mouse por encima de algo). <br> Abreviatura: no <br> Ejemplo: `tooltip` <br>

### `copyright`

Copyright. <br> Abreviatura: no <br> Ejemplo: `copyright` <br>

### `button`

Botón/Botones. El botón en sí siempre es un [bloque BEM](http://nicothin.github.io/idiomatic-pre-CSS/#bem-block). Puede tener una combinación con los elementos BEM. La palabra puede usarse en las clases de envoltura (véase en el ejemplo). <br> Abreviatura: `btn` <br> Ejemplo: <br> `btn` (botón individual), <br> `.promo__btns` (envoltorio para los botones de la unidad promocional)

### `title`, `heading`, `caption`

Título (suele aplicarse en los tags del título, aunque no es necesario que aparezca en ellos). <br> Abreviatura: no <br> Ejemplo: <br> `promo__title` (título del bloque promocional)

### `subtitle`

Subtítulo. <br> Abreviatura: no <br> Ejemplo: <br> `post__subtitle` (subtítulo de la publicación del blog)

### `name`

Título. <br> Abreviatura: no <br> Ejemplo: `product__name` <br>

### `slogan`

Lema. <br> Abreviatura: no <br> Ejemplo: <br> `logo__slogan` (eslogan en el bloque del logotipo)

### `user`

Usuario. <br> Abreviatura: no <br> Ejemplo: <br> `user` (bloque de visitantes autorizados/no autorizados, por ejemplo, en el encabezado)

### `label`, `tag`

Etiqueta, tag. <br> Abreviatura: no <br> Ejemplo: <br> `label` (etiqueta), <br> `post__tags-list` (lista de tags de publicaciones del blog)

### `category`

Categoría(s). <br> Abreviatura: `cat`  <br> Ejemplo: <br> `post__cats` (títulos de las publicaciones del blog)

### `dropdown`

Elemento desplegable (la dirección desplegable no tiene valor). <br> Abreviatura: `drop`  <br> Ejemplo: <br> `filter__drop` (casilla desplegable donde se puede hacer clic en el filtro)

### `search`

Buscar. <br> Abreviatura: no <br> Ejemplo: <br> `search-form` (bloque de búsqueda rápida, posiblemente en el "encabezado")

### `socials`

Redes sociales (por lo general, iconos). <br> Abreviatura: no <br> Ejemplo: <br> `socials__list` (lista con enlaces de las redes sociales)

### `carousel`, `slider`

Carrusel, control deslizante (varias diapositivas sucesivas). <br> Abreviatura: no <br> Ejemplo: <br> `promo__slider` (carrusel en bloque promocional)

### `header`

La parte superior, "encabezado". <br> Abreviatura: no <br> Ejemplo: <br> `page-header` (encabezado de la página), <br> `post__header` ("encabezado" de la entrada del blog)

### `footer`

Parte inferior, "pie de página". <br> Abreviatura: no <br> Ejemplo: <br> `page-footer` ("pie de página" de la página), <br> `post__footer` ("pie de página" de la publicación del blog)

### `additional`

Agregar algo (adicional). <br> Abreviatura: `add`  <br> Ejemplo: <br> `location__btn-add` (botón de agregar un bloque de algún lugar)

### `info`, `meta`

Información sobre una entidad. <br> Abreviatura: no <br> Ejemplo: <br> `post__info` (información sobre el blog)

### `body`

La parte del contenido principal de algo. <br> Abreviatura: no <br> Ejemplo: <br> `post__body` (fragmento de texto principal de la publicación del blog)

### `content`

El contenido de algo. <br> Abreviatura: no <br> Ejemplo: <br> `post__content` (fragmento de texto principal de la publicación del blog)

### `section`

Sección grande de algo. <br> Abreviatura: no <br> Ejemplo: <br> `post__content` (fragmento de texto principal de la publicación del blog)

### `icon`

Ícono. <br> Abreviatura: no <br> Ejemplo: <br> `icon--twitter` (ícono de la red social (modificador))

### `link`

Enlace. <br> Abreviatura: no <br> Ejemplo: <br> `product__more-link` ("siguiente" enlace en el bloque de productos)

### `list`

Lista. <br> Abreviatura: no <br> Ejemplo: <br> `features__list` (lista de ventajas)

### `description`

Descripción de la entidad <br> Abreviatura: `descr` <br> Ejemplo: <br> `product__descr` (descripción del producto)

### `image`

Imagen. <br> Abreviatura: `img`  <br> Ejemplo: <br> `promo__img` (imagen de la unidad de promoción)

### `picture`

Imagen. <br> Abreviatura: `pict`, `pic`  <br> Ejemplo: <br> `promo__pict` (foto del bloque promocional)

### `toggle`

Conmutación, tumblr. Por lo general, un conmutador "hamburguesa" permite mostrar/ocultar el menú principal (en caso de que el menú esté oculto en la parte inferior de la "hamburguesa"). <br> Abreviatura: no <br> Ejemplo: <br> `main-nav__toggle` (cambio de visibilidad del menú principal)

### `tab`

Pestaña. <br> Abreviatura: no <br> Ejemplo: <br> `tabs` (pestañas), <br> `promo__tab` (pestaña con el bloque promocional)

### `thumbnail`

Miniatura (por lo general en una galería de algún tipo). <br> Abreviatura: `thumb` <br> Ejemplo: <br> `photo__thumb` (miniatura de la galería de fotos)

### `avatar`

Avatar, una pequeña imagen del usuario. <br> Abreviatura: no <br> Ejemplo: <br> `user__avatar` (avatar del usuario en la casilla de usuario del encabezado)

### `text`

Fragmento de texto ( por lo general es emitido por el CMS). <br> Abreviatura: no <br> Ejemplo: <br> `about__text` (el texto "sobre nosotros" es quizás una envoltura de algunos párrafos)

### `author`

Autor. <br> Abreviatura: no <br> Ejemplo: <br> `post__author` (nombre/apodo del autor de la publicación del blog)

### `more`

"más", "más detalles". <br> Abreviatura: no <br> Ejemplo: <br> `product__more-link` (un botón o enlace en el bloque promocional que ofrece más detalles)

## Modificaciones, estados

### `active`, `current`

Elemento activo (elemento de navegación, pestaña activa). <br> Abreviatura: no <br> Ejemplo: <br> `main-nav__item--active` (modificador del elemento de navegación principal correspondiente a la página en la que se encuentra el visitante)

### `hidden`

Oculto. <br> Abreviatura: no <br> Ejemplo: <br> `product--hidden` (modificador para ocultar el bloque de productos)

### `shown`

Se muestra. <br> Abreviatura: no <br> Ejemplo: <br> `product--shown` (modificador que muestra el producto)

### `error`

Estado de error. <br> Abreviatura: no <br> Ejemplo: <br> `field-text--error` (modificador que marca un bloque de texto como erróneo)

### `success`

Estado de éxito. <br> Abreviatura: no <br> Ejemplo: <br> `field-text--success`

### `warning`

Advertencia. <br> Abreviatura: no <br> Ejemplo: <br> `btn--warning` (modificador que cambia el aspecto del botón)

### `pending`

Esperar algo (por ejemplo, una respuesta del servidor luego del envío de un formulario asíncrono). <br> Abreviatura: no <br> Ejemplo: <br> `btn--pending` (modificador que cambia el aspecto del botón)

## Tamaños

### `muy pequeño`

Muy pequeño. <br> Abreviatura: `xs` <br> Ejemplo: <br> `grid__col-xs-6` (celda que ocupa 6 columnas de la rejilla modular respectivamente ancho), <br> `screen-xs` (nombre de la variable con  el ancho de la ventana en valor)

### `pequeño`

Pequeño. <br> Abreviatura: `sm` <br> Ejemplo: <br> `grid__col-sm-6` (celda que ocupa 6 columnas de la rejilla modular respectivamente ancho), <br> `screen-sm` (nombre de la variable con  el ancho de la ventana en valor)

### `mediano`

Mediano. <br> Abreviatura: `md` <br> Ejemplo: <br> `grid__col-md-6` (celda que ocupa 6 columnas de la rejilla modular respectivamente. ancho), <br> `screen-md` (nombre de la variable con  el ancho de la ventana en valor)

### `large`

Grande. <br> Abreviatura: `lg` <br> Ejemplo: <br> `grid__col-lg-6` (celda que ocupa 6 columnas de la rejilla modular respectivamente ancho), <br> `screen-lg` (nombre de la variable con  el ancho de la ventana en valor)

### `extra large`

Muy grande. <br> Abreviatura: `xl` <br> Ejemplo: <br> `grid__col-xl-6` (celda que ocupa 6 columnas de la rejilla modular respectivamente ancho), <br> `screen-xl` (nombre de la variable con  el ancho de la ventana en valor)

### `extra extra large`

Bastante grande. <br> Abreviatura: `xxl` <br> Ejemplo: <br> `grid__col-xxl-6` (celda que ocupa 6 columnas de la rejilla modular respectivamente ancho), <br> `screen-xxl` (nombre de la variable con  el ancho de la ventana en valor)

### `narrow`

Estrecho. <br> Abreviatura: no <br> Ejemplo: <br> `btn--narrow` (modificador que hace que el botón sea más estrecho)

### `wide`

Ancho. <br> Abreviatura: no <br> Ejemplo: <br> `btn--wide` (modificador que hace que el botón sea más ancho)

### `phone`, `mobile`

Dispositivos móviles (teléfonos de hasta 5 pulgadas). <br> Abreviatura: no <br> Ejemplo: <br> `promo--phone` (modificación de la unidad de promoción para dispositivos)

### `tablet`

Tablets (de hasta unas 12 pulgadas). <br> Abreviatura: no <br> Ejemplo: <br> `promo--tablet` (modificación de la unidad de promoción para dispositivos)

### `notebook`, `laptop`

Laptops. <br> Abreviatura: no <br> Ejemplo: <br> `promo--laptop` (modificación de la unidad de promoción para dispositivos)

### `escritorio`

Computadoras de escritorio. <br> Abreviatura: no <br> Ejemplo: <br> `promo--desktop` (Modificación de la unidad de promoción por consiguiente. dispositivos)

## Otros

### `previous`

Anterior (a veces - enlace/botón). <br> Abreviatura: `prev`  <br> Ejemplo: <br> `slider__prev` (botón/flecha en el control deslizante)

### `siguiente`

Siguiente (a veces - enlace/botón). <br> Abreviatura: no <br> Ejemplo: <br> `slider__next` (botón/flecha en el control deslizante)

### `publicidad`

Fragmento de anuncio (precaución, puede cortarse con cortadores de banners). <br> Abreviatura: `adv`  <br> Ejemplo: <br> `aside__adv` (anuncio en la barra lateral)

### `background`

Fondo (normalmente algún cambio en el color de fondo del bloque). <br> Abreviatura: `bg` <br> Ejemplo: <br> `top-rated--bg-gray` (modificación del color de fondo del cuadro de productos/servicios mejor valorados)

### `número`

Número. <br> Abreviatura: `num`  <br> Ejemplo: <br> `field-text--num` (modificador de un campo de texto para permitir una disposición diferente de los campos numéricos)
