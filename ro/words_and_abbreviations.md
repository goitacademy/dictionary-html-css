# Cuvinte și abrevieri în clasele CSS

Divizarea în subsecțiuni este condiționată și nu prevede nicio obligație.

Realizat ca o completare la: <https://github.com/goitacademy/dictionary-html-css/blob/main/ro/common-words.md>.

## Blocuri/elemente mari

### `page`

Pagină (de obicei, elementul rădăcină). <br>
Prescurtare: niciuna <br>
Exemplu: `page`

### `container`

Container, wrapper. <br>
Prescurtare: niciuna <br>
Exemplu: `container`

### `grid`

Grid (pentru amplasarea blocurilor pe un grid modular). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`grid` (element pe care va fi amplasat gridul modular)

### `row`

Înveliș pentru celulele gridului modular. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`grid__row` (unul sau mai multe rânduri ale gridului modular)

### `column`

Celula gridului modular. <br>
Prescurtare: `col` <br>
Exemplu: <br>
`grid__col-md-6` (celulă care ocupă 6 coloane pe lățimea MD)

### `wrapper`

Înveliș a ceva. <br>
Prescurtare: `wrap` <br>
Exemplu: <br>
`contacts__wrapper` (înveliș în jurul conținutului blocului de contact)

### `inner`

Înveliș intern a ceva (cel mai des, pentru a limita lățimea și alinierea la centru). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo__inner` (înveliș intern al blocului de publicitate)

### `navigation`

Navigare. <br>
Prescurtare: `nav` <br>
Exemplu: <br>
`main-nav` (navigare principală)

### `promo`

Publicitate internă, un fel de introducere. <br>
Prescurtare: niciuna <br>
Exemplu: `promo` <br>

### `features`

Caracteristici, avantaje. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`features` (bloc care descrie caracteristicile și avantajele)

### `cart`

Coș din magazin. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`cart` (bloc de coș pe pagina coșului)

### `sidebar`, `aside`

Informații suplimentare (cel mai des o coloană îngustă pe o pagină de blog). <br>
Prescurtare: niciuna  <br>
Exemplu: `sidebar`, `aside`  <br>

## Blocuri/elemente mici

### `item`, `element`, `part`

O parte, un element, o unitate separată. Un cuvânt universal dacă nu este ceva specific. <br>
Prescurtare: `element` → `el` <br>
Exemplu: <br>
`main-nav__list-item` (element de listă în navigarea principală, probabil, `li`), <br>
`filter__part` (parte tipică a filtrului)

### `widget`

Widget. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`aside__widget` (widget în blocul de informații suplimentare)

### `logo`

Logo. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`logo` (n-o să-ți vină să credeți...)
`.partner__logo` (logo partener)

### `field`

Câmp de formular. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`field-text` (bloc universal pentru formulare), <br>
`field-radio` (bloc universal pentru formulare), <br>
`field-checkbox` (bloc universal pentru formulare), <br>
`field-select` (bloc universal pentru formulare), <br>
`field-file` (bloc universal pentru formulare)

### `pagination`

Navigare prin mai multe pagini (1 2 3 ...). <br>
Prescurtare: niciuna <br>
Exemplu: `pagination` <br>

### `breadcrumbs`

Breadcrumbs (Acasă > Catalog > Produs). <br>
Prescurtare: niciuna <br>
Exemplu: `breadcrumbs` <br>

### `modal`

Fereastră modală. <br>
Prescurtare: niciuna <br>
Exemplu: `modal` <br>

### `popup`

Bloc pop-up (de obicei, la click pe ceva). <br>
Prescurtare: niciuna <br>
Exemplu: `popup` <br>

### `tooltip`

O sugestie/indicație, un bloc mic (de obicei, prin trecerea deasupra a ceva). <br>
Prescurtare: niciuna <br>
Exemplu: `tooltip` <br>

### `copyright`

Copyright. <br>
Prescurtare: niciuna <br>
Exemplu: `copyright` <br>

### `button`

Buton/butonae. Butonul în sine — întotdeauna un [bloc BEM](http://nicothin.github.io/idiomatic-pre-CSS/#bem-block). Poate conține un mix de elemente BEM. Cuvântul poate fi utilizat în clasele wrapper (vezi exemplu). <br>
Prescurtare: `btn` <br>
Exemplu: <br>
`btn` (buton aparte), <br>
`.promo__btns` (înveliș pentru butoane din blocul publicitar)

### `title`, `heading`, `caption`

Titlu (se aplică cel mai des la tag-urile de titlu, dar nu neapărat). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo__title` (titlu pentru blocul publicitar)

### `subtitle`

Subtitlu. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`post__subtitle` (subtitlul postării pe blog)

### `name`

Nume, denumire. <br>
Prescurtare: niciuna <br>
Exemplu: `product__name` <br>

### `slogan`

Slogan. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`logo__slogan` (slogan în blocul logo)

### `user`

Utilizator. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`user` (bloc de vizitatori autorizați/neautorizați, de exemplu, în antet)

### `label`, `tag`

Tag, etichetă. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`label` (label), <br>
`post__tags-list` (listă de tag-uri pentru postările pe blog)

### `category`

Categorie. <br>
Prescurtare: `cat` <br>
Exemplu: <br>
`post__cats` (categorii pentru postările pe blog)

### `dropdown`

Element derulant (direcția derulării nu contează) <br>
Prescurtare: `drop` <br>
Exemplu: <br>
`filter__drop` (bloc derulant la click din filtru)

### `search`

Căutare. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`search-form` (bloc pentru căutare rapidă, eventual în antet)

### `socials`

Social media (iconițe, de obicei). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`socials__list` (listă cu linkuri către rețelele sociale)

### `carousel`, `slider`

Carousel, slider (mai multe slide-uri succesive). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo__slider` (carousel în blocul publicitar)

### `header`

Partea de sus, antet. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`page-header` (antetul paginii), <br>
`post__header` (antet pentru postările pe blog)

### `footer`

Partea de sus, subsol. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`page-footer` (subsolul paginii), <br>
`post__footer` (subsol pentru postările pe blog)

### `additional`

Adăugarea a ceva. <br>
Prescurtare: `add`  <br>
Exemplu: <br>
`location__btn-add` (buton de adăugare într-un loc undeva în bloc)

### `info`, `meta`

Informații despre o entitate. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`post__info` (informații despre o postare din blog)  

### `body`

Partea principală de conținut a ceva. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`post__body` (fragment text principal al postării de pe blog)

### `content`

Conținutul a ceva. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`post__content` (fragment text principal al postării de pe blog)

### `section`

Secțiune mare din ceva. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo__section` (secțiune mare a blocului publicitar)

### `icon`

Iconiță. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`icon--twitter` (iconiță pentru rețele sociale (modificator))

### `link`

Link. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`product__more-link` (link "Următorul" în blocul produsului)

### `list`

Listă. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`features__list` (lista de avantaje)

### `description`

Descrierea unei entități. <br>
Prescurtare: `descr` <br>
Exemplu: <br>
`product__descr` (descrierea produsului)

### `image`

Imagine. <br>
Prescurtare: `img` <br>
Exemplu: <br>
`promo__img` (imagine a blocului publicitar)

### `picture`

Imagine. <br>
Prescurtare: `pict`, `pic` <br>
Exemplu: <br>
`promo__pict` (imagine a blocului publicitar)

### `toggle`

Comutator. Cel mai des un comutator "hamburger" pentru a afișa/ascunde meniul principal (în condițiile în care meniul este ascuns sub "hamburger"). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`main-nav__toggle` (comutator de vizibilitate a meniului principal)

### `tab`

Filă. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`tabs` (file), <br>
`promo__tab` (filă a blocului publicitar)

### `thumbnail`

Miniatură (de obicei, într-o galerie). <br>
Prescurtare: `thumb` <br>
Exemplu: <br>
`photo__thumb` (miniatură în galeria foto)

### `avatar`

Avatar, o mică imagine a utilizatorului.  <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`user__avatar` (avatarul utilizatorului în blocul utilizatorului din antet)

### `text`

Fragment textual (de obicei, extras din CMS). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`about__text` (text "Despre noi", probabil un înveliș în jurul a câteva paragrafe)

### `author`

Автор. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`post__author` (numele/nickul autorului postării de pe blog)

### `more`

"Detalii", "Mai multe". <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`product__more-link` (buton sau link din blocul publicitar care sugerează detalii suplimentare)

## Modificări, stări

### `active`, `current`

Element activ (element de navigare, filă activă). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`main-nav__item--active` (modificator pe elementul principal de navigare care corespunde paginii pe care se află vizitatorul)

### `hidden`

Ascunde. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`product--hidden` (modificator, care ascunde produsul)

### `shown`

Arată. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`product--shown` (modificator, care arată produsul)

### `error`

Stare de eroare. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`field-text--error` (modificator, care marchează un bloc text ca fiind eronat)

### `success`

Stare de succes. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`field-text--success`

### `warning`

Avertizare. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`btn--warning` (modificator, care schimbă tipul butonului)

### `pending`

Așteptarea a ceva (de exemplu, un răspuns de la server după trimiterea unui formular asincron). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`btn--pending` (modificator, care schimbă aspectul butonului)

## Dimensiuni

### `extra small`

Forte mic. <br>
Prescurtare: `xs` <br>
Exemplu: <br>
`grid__col-xs-6` (celulă care ocupă 6 coloane din gridul modular pe lățimea respectivă), <br>
`screen-xs` (nume de variabilă cu lățimea viewport-ului corespunzătoare ca valoare)

### `small`

Mic. <br>
Prescurtare: `sm` <br>
Exemplu: <br>
`grid__col-sm-6` (celulă care ocupă 6 coloane din gridul modular pe lățimea respectivă, <br>
`screen-sm` (nume de variabilă cu lățimea viewport-ului corespunzătoare ca valoare

### `medium`

Mediu. <br>
Prescurtare: `md` <br>
Exemplu: <br>
`grid__col-md-6` (celulă care ocupă 6 coloane din gridul modular pe lățimea respectivă), <br>
`screen-md` (nume de variabilă cu lățimea viewport-ului corespunzătoare ca valoare)

### `large`

Mare. <br>
Prescurtare: `lg` <br>
Exemplu: <br>
`grid__col-lg-6` (celulă care ocupă 6 coloane din gridul modular pe lățimea respectivă), <br>
`screen-lg` (nume de variabilă cu lățimea viewport-ului corespunzătoare ca valoare)

### `extra large`

Foarte mare. <br>
Prescurtare: `xl` <br>
Exemplu: <br>
`grid__col-xl-6` (celulă care ocupă 6 coloane din gridul modular pe lățimea respectivă), <br>
`screen-xl` (nume de variabilă cu lățimea viewport-ului corespunzătoare ca valoare)

### `extra extra large`

Extrem de mare. <br>
Prescurtare: `xxl` <br>
Exemplu: <br>
`grid__col-xxl-6` (celulă care ocupă 6 coloane din gridul modular pe lățimea respectivă), <br>
`screen-xxl` (nume de variabilă cu lățimea viewport-ului corespunzătoare ca valoare)

### `narrow`

Îngust. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`btn--narrow` (modificator, care face butonul îngust)

### `wide`

Lat. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`btn--wide` (modificator, care face butonul lat)

### `phone`, `mobile`

Dispozitive mobile (telefoane de până la 5 inch). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo--phone` (modificarea blocului publicitar pentru dispozitivele respective)

### `tablet`

Tablete (orientativ până la 12 inch). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo--tablet` (modificarea blocului publicitar pentru dispozitivele respective)

### `notebook`, `laptop`

Laptopuri. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo--laptop` (modificarea blocului publicitar pentru dispozitivele respective)

### `desktop`

Calculatoare desktop. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo--desktop` (modificarea blocului publicitar pentru dispozitivele respective)

## Altele

### `previous`

Anterior (cel mai des, un link/buton). <br>
Prescurtare: `prev` <br>
Exemplu: <br>
`slider__prev` (buton/săgeată pe slider)

### `next`

Următorul (cel mai des, un link/buton). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`slider__next` (buton/săgeată pe slider)

### `advertisement`

Fragment publicitar (atenție, acesta poate fi tăiat printr-un instrument de ștergere a bannerelor). <br>
Prescurtare: `adv` <br>
Exemplu: <br>
`aside__adv` (bloc publicitar în bara laterală)

### `background`

Fundal (cel mai des, o modificare a culorii de fundal a blocului). <br>
Prescurtare: `bg` <br>
Exemplu: <br>
`top-rated--bg-gray` (modificarea culorii de fundal a blocului cu produsele/serviciile cele mai populare)

### `number`

Număr. <br>
Prescurtare: `num`  <br>
Exemplu: <br>
`field-text--num` (modificator pentru câmp text, care permite aranjarea într-un mod diferit a câmpurilor numerice)
