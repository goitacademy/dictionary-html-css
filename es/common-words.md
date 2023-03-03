# Palabras que siempre se usan en las clases de CSS

## Imágenes

`image`, `img`, `picture`, `pic` — imagen

`icon` — ícono

`logo` — logotipo

`userpic`, `avatar` — nombre del usuario, foto del usuario

`thumbnail`, `thumb` — miniatura, imagen en miniatura

## Texto

`title`, `subject`, `heading`, `headline`, `caption` — título

`subtitle` — subtítulo

`slogan` — eslogan

`lead`, `tagline` — párrafo principal del texto

`text` — contenido textual

`desc` — descripción, opción de contenido textual

`excerpt` —extracto del texto, que suele usarse antes del enlace "Leer más..."

`quote`, `blockquote` — cita

`snippet` — ejemplo de código

`link` — enlace

`copyright`, `copy` — copyright

## Listas

`list`, `items` — lista

`item` — elemento de la lista

## Bloques

`page` — elemento raíz de la página

`header` — encabezado (páginas o elementos)

`footer` — pie de página (páginas o elementos)

`section` — sección de contenido (uno de tantos)

`main`, `body` — parte principal (páginas o elementos)

`content` — contenido del elemento

`sidebar` — barra lateral (páginas o elementos)

`aside` — bloque con información adicional

`widget` — widget, por ejemplo, en la barra lateral

## Disposición

`wrapper`, `wrap` — envoltura, normalmente externa

`inner` — envoltura interna

`container`, `holder`, `box` — contenedor

`grid` — disposición (páginas y elementos) en forma cuadrícula (normalmente con `row` и `col`)

`row` — contenedor en forma de cadena

`col`, `column` — contenedor en forma de columna

## Elementos de control

`button`, `btn` —  botón para enviar un formulario, por ejemplo

`control` — elementos de control, por ejemplo, las flechas «Siguiente/atrás» en la galería de fotos, botones del control deslizante

`dropdown` — lista desplegable

## Declaración de medios

`phone`, `mobile` — dispositivos móviles

`phablet` — teléfonos con pantalla grande (6-7")

`tablet` — tablet

`notebook`, `laptop` — laptop

`desktop` — computadoras de escritorio

## Tamaños

`tiny`, `xs` — pequeño, diminuto

`small`, `sm` — pequeño

`medium`, `base` — mediano

`big`, `large`, `lg` — grande

`huge`, `xl` — enorme

`narrow` — estrecho

`wide` — ancho

## Otros

`search` — buscar

`socials` — bloque de iconos de las redes sociales

`advertisement`, `adv`, `commercial`, `promo` — bloque publicitario (bloqueado por Adblock, no se recomienda usar este tipo de clases para bloques con publicidad interna)

`features`, `benefits` — lista de las principales características del producto, servicio

`slider`, `carousel` — control deslizante, elemento interactivo de contenido desplazable

`pagination` — navegación por páginas

`user`, `author` — usuario, autor de un registro o comentario

`meta` — bloque de información adicional, por ejemplo, un bloque de tag y fecha en el post

`cart`, `basket` — papelera

`breadcrumbs` — cadena de navegación, "migajas de pan"

`more`, `all` — enlace a la información completa

`modal` — ventana (diálogo) modal

`popup` — ventana emergente

`tooltip`, `tip` — información sobre las herramientas

`preview` — un anuncio, un extracto, como una noticia o un post, puede consistir de un título, una descripción y una imagen. Se espera un enlace a la versión completa

`overlay` — sobreposición, por ejemplo, para oscurecer imágenes o crear ventanas modales

## Estados

`active`, `current` — el elemento activo, por ejemplo, el elemento de menú actual

`visible` — elemento visible

`hidden` — elemento oculto

`error` — estado de error

`warning` — estado de alerta

`success` — estado de realización exitosa de la tarea

`pending` — estado de espera, por ejemplo, antes de que el estado cambie de error a success

## Ejemplo de uso

### Lista simple

```html
<ul class="list">
  <li class="item">Primero</li>
  <li class="item">Segundo</li>
  <li class="item">Tercero</li>
</ul>
```

### Imagen de usuario (nombre del usuario)

```html
<div class="user">
  <img class="user__img" src="userpic.png" alt="Дормидонт Петрович">
  <a class="user__link" href="#">Dormidont Petrovich</a>
</div>
```

### Galería

```html
<div class="gallery">
  <ul class="gallery__list">
    <li class="gallery__item">
      <img class="gallery__img" src="flowers.jpg" alt="Цветём как в последний раз">
    </li>
    <li class="gallery__item">
      <img class="gallery__img" src="trees.jpg" alt="Парк «Три сосны»">
    </li>
  </ul>
</div>
```

### Navegación

```html
<nav class="nav">
  <a class="nav__link nav__link--active">Inicio</a>
  <a class="nav__link" href="#">Secundaria</a>
  <a class="nav__link" href="#">Tercera</a>
  <a class="nav__link" href="#">Penúltima</a>
  <a class="nav__link" href="#">El final</a>
</nav>
```

```html
<nav class="nav">
  <ul class="nav__list">
    <li class="nav__item nav__item--current">
      <a class="nav__link">Principal</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Artículos</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Galería de fotos</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Contactos</a>
    </li>
  </ul>
</nav>
```

### Widget de la barra lateral

```html
<div class="widget">
  <h4 class="widget__title">Cultivando gelatina</h4>

  <div class="widget__content">
    <p>Para hacer crecer una linda gelatina,
    necesitaremos un tubo de espuma de caucho, dos kilos de azúcar,
    tres huevos y media cucharadita de acetona.</p>

    <a class="widget__link" href="#">Dejar de leer</a>
  </div>
</div>
```

### Sección de noticias

```html
<div class="news">
    <h3 class="news__title">Noticias de ayer</h3>

    <ul class="news__list">
        <!-- agregar una clase bloque a la clase elemento,
              para crear un nuevo espacio de nombres -->
        <li class="news__item item-news">
            <h4 class="item-news__title">Concurso de patinaje de velocidad sobre hielo</h4>
            <div class="item-news__text">
              <p>El equipo ganador fue el equipo Kilek de Petrozavodsk</p>

              <a href="#" class="item-news__link">Leer más</a>
            </div>
        </li>

        <li class="news__item item-news">
            <h4 class="item-news__title">Los científicos han aclarado la importancia de la lima en el cuidado de las uñas</h4>
            <div class="item-news__text">
              <p>Científicos británicos han reconocido la
                contribución de la lima al crecimiento de uñas que miden un metro y medio.</p>

              <a href="#" class="item-news__link">Dejar de leer</a>
            </div>
        </li>
    </ul>
</div>
```

### Artículo o post del blog (versión simple)

```html
<article class="article">
  <h3 class="article__title">Sensación de los chakras en el manojo de perejil</h3>
  <time class="article__datetime">32 de Mayo, 10:87</time>

  <div class="article__author author-article">
    <img class="author-article__img" src="userpic.png" alt="Клешня Андреевна">
    <a class="author-article__link" href="#">Kleshnia Andreyevna Dolgorukaya</a>
    <div class="author-article__desc">Nuestra experta en chakras</div>
  </div>

  <div class="article__content">
    Ve al mercado y compra un ramo de 100 gramos de perejil a las viejitas.
    Luego retira los bichos y gusanos y límpialos bien. Dale los bichos al 
    gato, pon los gusanos en la maceta del cactus, ponle el nombre de John
    y al segundo Billy, y ahora tendrás al Viejo Oeste en tu maceta. Regresa
    al manojo de perejil. Míralo cariñosamente y ráscate detrás de la oreja
     puedes hacerlo para ti o para tu gato. Amárralo con una cinta,
    asegurándote de hacer un lazo. ¡Felicidades! Ahora tienes un manojo de
    perejil completamente domesticado que te perseguirá felizmente
    y hará brotar sus semillas en tus zapatos.
  </div>
</article>
```

### Artículo o post del blog (versión compleja)

```html
<article class="entry">
  <header class="entry__header">
    <h3 class="entry__title title-entry">
      <a class="title-entry__link" href="#">Los patitos de hule como forma de autodescubrimiento</a>
    </h3>

    <time class="entry__datetime">32 de Mayo, 10:87</time>
  </header>

  <div class="entry__author author-entry">
    <img class="author-entry__img" src="userpic.png" alt="Василиса Сергеевич">

    <a class="author-entry__link" href="#">Vasilisa Sergeyevich</a>
  </div>

  <div class="entry__content">
    Saca del ático una caja con medio centenar de patitos de hule que
    sobraron de las celebraciones de Nochevieja. Haz un pentagrama
    con patos y velas encendidas en el suelo del cuarto.
    Siéntate en el centro en posición de meditación
     coge un diccionario alemán-brasileño en cada mano,
    tose, llena el pecho de aire y di "¡Cuac!" en voz alta
    y con confianza, con total compromiso.
  </div>

  <div class="entry__tags tags-entry">
    <h4 class="tags-entry__title">Метки</h4>

    <ul class="tags-entry__list">
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">хоровод своими руками</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">фарфоровые тапки</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">гуталин в кулинарии</a>
      </li>
    </ul>
  </div>

  <div class="entry__actions actions-entry">
    <ul class="actions-entry__list">
      <li class="actions-entry__item actions-entry__item--read">
        <a class="actions-entry__link" href="#">238 ответов</a>
      </li>
      <li class="actions-entry__item actions-entry__item--write">
        <a class="actions-entry__link" href="#">Написать в спортлото</a>
      </li>
      <li class="actions-entry__item actions-entry__item--share">
        <a class="actions-entry__link" href="#">Поделиться</a>
      </li>
    </ul>
  </div>
</article>
```
