# Common words used in CSS classes

## Images

`image`, `img`, `picture`, `pic` — image

`icon` — icon

`logo` — logo

`userpic`, `avatar` — userpic, a small picture of the user

`thumbnail`, `thumb` — thumbnail, a reduced image

## Text

`title`, `subject`, `heading`, `headline`, `caption` — title

`subtitle` — subtitle

`slogan` — slogan

`lead`, `tagline` — lead paragraph in the text

`text` — textual content

`desc` — description, a variation of the text content

`excerpt` — text excerpt, usually used before the "Read more..." link.

`quote`, `blockquote` — quotation

`snippet` — a code sample

`link` — link

`copyright`, `copy` — copyright

## Lists

`list`, `items` — list

`item` — list item

## Blocks

`page` — root page element

`header` — header (of a page or item)

`footer` — footer (of a page or item)

`section` — content section (one of several)

`main`, `body` — the main part (of a page or an element)

`content` — item content

`sidebar` — sidebar (of the page or item)

`aside` — a block with additional information

`widget` — widget, for example, in a sidebar

## Layout

`wrapper`, `wrap` — wrapper, usually an external one

`inner` — inner wrap

`container`, `holder`, `box` — container

`grid` — Layout (of a page or item) as a grid (usually contains `row` and `col`)

`row` — container as a row

`col`, `column` — container as a column

## Control items

`button`, `btn` —  a button, such as for submitting a form

`control` — controls, such as the "Forward/Backward" arrows in a photo gallery, or the slider control buttons

`dropdown` — drop-down list

## Media queries

`phone`, `mobile` — mobile devices

`phablet` —big-screen smartphones (6-7")

`tablet` — tablets

`notebook`, `laptop` — laptops

`desktop` — desktop computers

## Dimensions

`tiny`, `xs` — small, tiny

`small`, `sm` — small

`medium`, `base` — medium

`big`, `large`, `lg` — big

`huge`, `xl` — huge

`narrow` — narrow

`wide` — wide

## Miscellaneous

`search` — search

`socials` — a block of social network icons

`advertisement`, `adv`, `commercial`, `promo` — advertising block (Adblock can block it, it is not recommended to use these classes for blocks with internal advertising).

`features`, `benefits` — a list of the main features of a product or service

`slider`, `carousel` — slider, an interactive element with scrolling content

`pagination` — page navigation

`user`, `author` — user, the author of a post or comment

`meta` — a block with additional information, such as a tag and date block in the post

`cart`, `basket` — cart

`breadcrumbs` — a navigation sequence

`more`, `all` — a link to more info

`modal` — modal (dialog) window

`popup` — pop-up window

`tooltip`, `tip` — tooltip

`preview` — An announcement, an excerpt, such as a news item or post, may consist of a headline, a description and a picture. It is supposed to be a link to the full version

`overlay` — an overlapping layer, for example to darken images or to create modal windows

## Status

`active`, `current` — the active item, such as the current menu option

`visible` — visible element

`hidden` — hidden element

`error` — error status

`warning` — warning status

`success` — successful task completion status

`pending` — pending state, for example, before the status changes to error or success

## Usage Examples

### Simple list

```html
<ul class="list">
  <li class="item">First</li>
  <li class="item">Second</li>
  <li class="item">Third</li>
</ul>
```

### User picture (userpic)

```html
<div class="user">
  <img class="user__img" src="userpic.png" alt="Дормидонт Петрович">
  <a class="user__link" href="#">Dormidont Petrovich</a>
</div>
```

### Gallery

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

### Navigation

```html
<nav class="nav">
  <a class="nav__link nav__link--active">Home</a>
  <a class="nav__link" href="#">Secondary</a>
  <a class="nav__link" href="#">Third from the end</a>
  <a class="nav__link" href="#">Penultimate</a>
  <a class="nav__link" href="#">The very end</a>
</nav>
```

```html
<nav class="nav">
  <ul class="nav__list">
    <li class="nav__item nav__item--current">
      <a class="nav__link">Home</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Articles</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Photo gallery</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Contact</a>
    </li>
  </ul>
</nav>
```

### Widget in the sidebar

```html
<div class="widget">
  <h4 class="widget__title">Making gelatin</h4>

  <div class="widget__content">
    <p>To grow a sociable friendly gelatin, we 
    will need a roll of polyurethane, two kilograms 
    of sugar, three eggs, and half a teaspoon of acetone.</p>

    <a class="widget__link" href="#">Don't Read More...</a>
  </div>
</div>
```

### News block

```html
<div class="news">
    <h3 class="news__title">Yesterday's news</h3>

    <ul class="news__list">
        <!-- add a block class to the element class,
             to create a new namespace -->
        <li class="news__item item-news">
            <h4 class="item-news__title">Butterfish skating competition</h4>
            <div class="item-news__text">
              <p>The winning team was the butterfish team from Petrozavodsk</p>

              <a href="#" class="item-news__link">Read more</a>
            </div>
        </li>

        <li class="news__item item-news">
            <h4 class="item-news__title">Scientists have further clarified the role of the nail file in nail care.</h4>
            <div class="item-news__text">
              <p>British scientists have recognized the file's
                contribution to growing one-and-a-half-meter-long nails.</p>

              <a href="#" class="item-news__link">Don't Read More</a>
            </div>
        </li>
    </ul>
</div>
```

### Article or blog post (simple version)

```html
<article class="article">
  <h3 class="article__title">Sensing the chakras of a bunch of parsley</h3>
  <time class="article__datetime">May 32nd, 10:87</time>

  <div class="article__author author-article">
    <img class="author-article__img" src="userpic.png" alt="Клешня Андреевна">
    <a class="author-article__link" href="#">Kleshnia Andreyevna Dolgorukaya</a>
    <div class="author-article__desc">Our Chakra Expert</div>
  </div>

  <div class="article__content">
    Go to the bazaar and buy a 100 gram bunch of parsley from the old ladies.
    Sort it carefully, remove bugs and caterpillars. Let the bugs play with 
    the cat, put the caterpillars in a cactus pot, give them
    the names John and Billy, and now you have the Wild West in a cactus pot. Now go back to
    the bunch of parsley. Look at it tenderly and scratch yourself just right
    behind your ear, you can do it by yourself or ask the cat. Take a satin ribbon,
    and tie a bow with it. Congratulations! Now you have a fully domesticated
     bunch of parsley, which will playfully chase you around and sprout its
    seeds in your slippers.
  </div>
</article>
```

### Article or blog post (complicated version)

```html
<article class="entry">
  <header class="entry__header">
    <h3 class="entry__title title-entry">
      <a class="title-entry__link" href="#">Rubber ducks as a way of self-awareness</a>
    </h3>

    <time class="entry__datetime">May 32nd, 10:87</time>
  </header>

  <div class="entry__author author-entry">
    <img class="author-entry__img" src="userpic.png" alt="Василиса Сергеевич">

    <a class="author-entry__link" href="#">Vasilisa Sergeyevich</a>
  </div>

  <div class="entry__content">
    Get a box from the attic with 50 rubber ducks from the New Year's
    Eve celebration. Place them on the floor, arranging them to form a
    pentagram from ducks and burning candles.
    Sit in the middle and assume the lotus pose, take a
    German-Brazilian dictionary in each hand, cough, fill your
    chest with air, and say "Quack!" loudly and confidently, with
    complete commitment.
  </div>

  <div class="entry__tags tags-entry">
    <h4 class="tags-entry__title">Marks</h4>

    <ul class="tags-entry__list">
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">any other thing</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">any other thing</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">and one more thing</a>
      </li>
    </ul>
  </div>

  <div class="entry__actions actions-entry">
    <ul class="actions-entry__list">
      <li class="actions-entry__item actions-entry__item--read">
        <a class="actions-entry__link" href="#">238 answers</a>
      </li>
      <li class="actions-entry__item actions-entry__item--write">
        <a class="actions-entry__link" href="#">A great text here</a>
      </li>
      <li class="actions-entry__item actions-entry__item--share">
        <a class="actions-entry__link" href="#">Share</a>
      </li>
    </ul>
  </div>
</article>
```
