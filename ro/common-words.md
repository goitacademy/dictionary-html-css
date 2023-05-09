# Cuvinte utilizate frecvent în clasele CSS

## Imagini

`image`, `img`, `picture`, `pic` — imagine

`icon` — iconiță, pictogramă

`logo` — logo, siglă

`userpic`, `avatar` — imagine de utilizator, imagine mică de utilizator

`thumbnail`, `thumb` — miniatură, imagine mică

## Text

`title`, `subject`, `heading`, `headline`, `caption` — titlu

`subtitle` — subtitlu

`slogan` — slogan

`lead`, `tagline` — paragraf principal în text

`text` — conținut text

`desc` — descriere, opțiune pentru conținutul textului

`excerpt` — un fragment de text, utilizat de obicei înainte de linkul "Citește mai mult...".

`quote`, `blockquote` — citat

`snippet` — parte de cod

`link` — link

`copyright`, `copy` — copyright

## Liste

`list`, `items` — listă

`item` — element al listei

## Blocuri

`page` — elementul rădăcină al paginii

`header` — antet (al paginii sau elementului)

`footer` — subsol (al paginii sau elementului)

`section` — secțiune de conținut (una din mai multe)

`main`, `body` — partea principală (a paginii sau elementului)

`content` — conținutul elementului

`sidebar` — bară laterală (a paginii sau elementului)

`aside` — bloc cu informații suplimentare

`widget` — widget, de exemplu, în bara laterală

## Layout

`wrapper`, `wrap` — înveliș, de obicei extern

`inner` — înveliș intern

`container`, `holder`, `box` — container

`grid` — layout (al paginii sau elementului) ca o rețea (de obicei conține `row` și `col`)

`row` — container sub formă de rând

`col`, `column` — container sub formă de coloană

## Controale

`button`, `btn` —  buton, de exemplu, pentru a trimite formularul

`control` — controale, de exemplu, săgeți înainte/înapoi în galeria foto, butoane de glisare

`dropdown` — lista derulantă

## Media Queries

`phone`, `mobile` — dispozitive mobile

`phablet` — telefoane cu ecran mare (6-7")

`tablet` — tablete

`notebook`, `laptop` — laptop

`desktop` — calculatoare desktop

## Dimensiuni

`tiny`, `xs` — minuscul, foarte mic

`small`, `sm` — mic

`medium`, `base` — mediu

`big`, `large`, `lg` — mare

`huge`, `xl` — foarte mare

`narrow` — îngust

`wide` — larg

## Diverse

`search` — căutare

`socials` — bloc de iconițe social media

`advertisement`, `adv`, `commercial`, `promo` — bloc de publicitate (tăiat de Adblock, nu se recomandă utilizarea unor astfel de clase pentru blocurile cu reclame interne)

`features`, `benefits` — lista caracteristicilor principale ale produsului, serviciului

`slider`, `carousel` — slider, element interactiv cu conținut derulant

`pagination` — navigare pe pagină

`user`, `author` — utilizator, autorul înregistrării sau al comentariului

`meta` — bloc cu informații suplimentare, de exemplu, bloc de tag-uri și de date în postare

`cart`, `basket` — coș

`breadcrumbs` — lanț de navigație, "breadcrumbs"

`more`, `all` — link către toate informațiile

`modal` — fereastră modală

`popup` — fereastră pop-up

`tooltip`, `tip` — sugestie, indicație

`preview` — anunț, fragment, cum ar fi o știre sau o postare, poate fi format dintr-un titlu, o descriere și o imagine. Se prevede un link către versiunea integrală

`overlay` — strat de suprapunere, de exemplu, pentru întunecarea imaginilor sau crearea ferestrelor modale

## Stări

`active`, `current` — elementul activ, de exemplu elementul de meniu curent

`visible` — element vizibil

`hidden` — element ascuns

`error` — stare de eroare

`warning` — stare de avertizare

`success` — stare de execuție cu succes a sarcinii

`pending` — stare de așteptare, de exemplu înainte de schimbarea stării în eroare sau succes

## Exemple de utilizare

### Listă simplă

```html
<ul class="list">
  <li class="item">Primul</li>
  <li class="item">Al doilea</li>
  <li class="item">Al treilea</li>
</ul>
```

### Imaginea utilizatorului (userpic)

```html
<div class="user">
  <img class="user__img" src="userpic.png" alt="Martin Brooks">
  <a class="user__link" href="#">Martin Brooks</a>
</div>
```

### Galerie

```html
<div class="gallery">
  <ul class="gallery__list">
    <li class="gallery__item">
      <img class="gallery__img" src="flowers.jpg" alt="Înflorind ca și cum ar fi ultima dată">
    </li>
    <li class="gallery__item">
      <img class="gallery__img" src="trees.jpg" alt="Parcul «Trei pini»">
    </li>
  </ul>
</div>
```

### Navigare

```html
<nav class="nav">
  <a class="nav__link nav__link--active">Principal</a>
  <a class="nav__link" href="#">Secundar</a>
  <a class="nav__link" href="#">Al treilea de la sfârșit</a>
  <a class="nav__link" href="#">Penultimul</a>
  <a class="nav__link" href="#">De la sfârșit</a>
</nav>
```

```html
<nav class="nav">
  <ul class="nav__list">
    <li class="nav__item nav__item--current">
      <a class="nav__link">Acasă</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Articole</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Galerie foto</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Contacte</a>
    </li>
  </ul>
</nav>
```

### Widget pentru bara laterală

```html
<div class="widget">
  <h4 class="widget__title">Facem jeleu</h4>

  <div class="widget__content">
    <p>Pentru a face un jeleu sociabil și prietenos,
    vom avea nevoie de un rulou de spumă poliuretanică, 
    două kilograme de zahăr, trei ouă și o jumătate de  
    linguriță de acetonă.</p>

    <a class="widget__link" href="#">Nu citi mai departe...</a>
  </div>
</div>
```

### Bloc de știri

```html
<div class="news">
    <h3 class="news__title">Știrile de ieri</h3>

    <ul class="news__list">
        <!-- la clasa elementului adăugăm clasa blocului,
             pentru a crea un nou spațiu de nume -->
        <li class="news__item item-news">
            <h4 class="item-news__title">Competiția de patinaj viteză Forks</h4>
            <div class="item-news__text">
              <p>Echipa câștigătoare a fost echipa Turbo din Iași</p>

              <a href="#" class="item-news__link">Citește mai mult</a>
            </div>
        </li>

        <li class="news__item item-news">
            <h4 class="item-news__title">Oamenii de știință au explicat rolul pilei în    îngrijirea unghiilor</h4>
            <div class="item-news__text">
              <p>Oamenii de știință din Marea Britanie au lăudat 
                contribuția pilei la obținerea unor unghii lungi 
                de un metru și jumătate.</p>

              <a href="#" class="item-news__link">Nu citi mai departe</a>
            </div>
        </li>
    </ul>
</div>
```

### Articol sau postare de blog (varianta simplă)

```html
<article class="article">
  <h3 class="article__title">Deschidem chackrele la o legătură de pătrunjel</h3>
  <time class="article__datetime">32 mai, 10:87</time>

  <div class="article__author author-article">
    <img class="author-article__img" src="userpic.png" alt="Venera Baltă">
    <a class="author-article__link" href="#">Venera Baltă</a>
    <div class="author-article__desc">Expertul nostru în chakre</div>
  </div>

  <div class="article__content">
    Mergi la piață și cumpără o legătură de 100g de pătrunjel de la băbuțe.
    Scoate gândacii și omizile și curăță-le cum trebuie. Dă gândacii pisicii, 
    și pune omizile în ghiveciul de la cactus, unul pentru Ioan, iar celălalt Billy, 
    și vei avea Vestul Sălbatic în ghiveci. Întoarce-te la legătura de pătrunjel.   
    Privește-l cu drag și scarpină-l după ureche. Leagă-l cu o panglică de satin,
    și fă-i o fundă. Felicitări! Acum ai o legătură complet domesticită de 
    pătrunjel care te va urma cu plăcere și își va încolți semințele în papucii tăi.
  </div>
</article>
```

### Articol sau postare de blog (varinata dificilă)

```html
<article class="entry">
  <header class="entry__header">
    <h3 class="entry__title title-entry">
      <a class="title-entry__link" href="#">Rățuștele de cauciuc ca modalitate de autodescoperire</a>
    </h3>

    <time class="entry__datetime">32 mai, 10:87</time>
  </header>

  <div class="entry__author author-entry">
    <img class="author-entry__img" src="userpic.png" alt="Andaluzia Poşircă">

    <a class="author-entry__link" href="#">Andaluzia Poşircă</a>
  </div>

  <div class="entry__content">
    Scoate din pod o cutie cu o jumătate de sută de rățuște 
    de cauciuc rămase de la petrecerile de Revelion. Fă o pentagramă 
    cu rațele și lumânări aprinse pe podeaua camerei. Așează-te în 
    mijloc în poziția lotus, ia câte un dicționar germano-brazilian în 
    fiecare mână, tușește, umple-ți pieptul cu aer și spune tare și 
    încrezător, cu toată dăruirea "Quack!".
  </div>

  <div class="entry__tags tags-entry">
    <h4 class="tags-entry__title">Tag-uri</h4>

    <ul class="tags-entry__list">
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">hora cu propriile mâini</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">șlapi de porțelan</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">lustruirea pantofilor în gătit</a>
      </li>
    </ul>
  </div>

  <div class="entry__actions actions-entry">
    <ul class="actions-entry__list">
      <li class="actions-entry__item actions-entry__item--read">
        <a class="actions-entry__link" href="#">238 răspunsuri</a>
      </li>
      <li class="actions-entry__item actions-entry__item--write">
        <a class="actions-entry__link" href="#">Scrie la loto sport</a>
      </li>
      <li class="actions-entry__item actions-entry__item--share">
        <a class="actions-entry__link" href="#">Distribuie</a>
      </li>
    </ul>
  </div>
</article>
```
