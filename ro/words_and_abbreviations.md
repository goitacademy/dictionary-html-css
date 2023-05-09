# Cuvinte și abrevieri în clasele CSS

Divizarea în subsecțiuni este condiționată și nu prevede nicio obligație.

Realizat ca o completare la: <https://github.com/goitacademy/dictionary-html-css/blob/main/ro/common-words.md>.

## Blocurile/elementele mari

### `page`

Pagina (de obicei, elementul rădăcină). <br>
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
`grid` (element în care va fi amplasat gridul modular)

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

Înveliș intern a ceva (cel mai des pentru a limita lățimea și alinierea la centru). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo__inner` (înveliș intern a blocului de publicitate)

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

Coșul din magazin. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`cart` (bloc de coș pe pagina coșului)

### `sidebar`, `aside`

Informații suplimentare (cel mai des o coloană îngustă pe o pagină de blog). <br>
Prescurtare: niciuna  <br>
Exemplu: `sidebar`, `aside`  <br>

## Мелкие блоки/элементы

### `item`, `element`, `part`

O parte, un element, o unitate separată. Un cuvânt universal dacă nu este ceva specific. <br>
Prescurtare: `element` → `el` <br>
Exemplu: <br>
`main-nav__list-item` (un element de listă în navigarea principală, probabil, `li`), <br>
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
`logo` (n-o să vă vină să credeți...)
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

Navigarea prin mai multe pagini (1 2 3 ...). <br>
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

Buton/butonae. Butonul în sine — întotdeauna un [bloc BEM](http://nicothin.github.io/idiomatic-pre-CSS/#bem-block). Poate avea un amestec de elemente BEM. Cuvântul poate fi utilizat în clasele wrapper (vedeți exemplu). <br>
Prescurtare: `btn` <br>
Exemplu: <br>
`btn` (buton aparte), <br>
`.promo__btns` (înveliș pentru butoane din blocul de publicitate)

### `title`, `heading`, `caption`

Titlu (se aplică cel mai des la tag-urile de titlu, dar nu neapărat). <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`promo__title` (titlu pentru bloc de publicitate)

### `subtitle`

Subtitlu. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`post__subtitle` (subtitlul postării de blog)

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
Prescurtare: `cat`  <br>
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
`post__body` (fragment text principal al postării din blog)

### `content`

Conținutul a ceva. <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`post__content` (fragment text principal al postării din blog)

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

Descrierea unei entități.<br>
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
`post__author` (numele/nickul autorului postăriid din blog)

### `more`

"Detalii", "Mai multe". <br>
Prescurtare: niciuna <br>
Exemplu: <br>
`product__more-link` (buton sau link din blocul publicitar care sugerează detalii suplimentare)

## Модификации, состояния

### `active`, `current`

Активный элемент (пункт навигации, активный таб). <br>
Сокращение: нет <br>
Пример: <br>
`main-nav__item--active` (модификатор на пункте гл. навигации, соответствущем странице, на которой пребывает посетитель)

### `hidden`

Скрытое. <br>
Сокращение: нет <br>
Пример: <br>
`product--hidden` (модификатор, скрывающий блок продукта)

### `shown`

Показанное. <br>
Сокращение: нет <br>
Пример: <br>
`product--shown` (модификатор, показывающий продукт)

### `error`

Состояние ошибки. <br>
Сокращение: нет <br>
Пример: <br>
`field-text--error` (модификатор, помечающий блок текстового поля как ошибочное)

### `success`

Состояние успеха. <br>
Сокращение: нет <br>
Пример: <br>
`field-text--success`

### `warning`

Предупреждение. <br>
Сокращение: нет <br>
Пример: <br>
`btn--warning` (модификатор, меняющий вид кнопки)

### `pending`

Ожидание чего-либо (к примеру, ответа севера после асинхронной отправки формы). <br>
Сокращение: нет <br>
Пример: <br>
`btn--pending` (модификатор, меняющий вид кнопки)

## Размеры

### `extra small`

Очень маленький. <br>
Сокращение: `xs` <br>
Пример: <br>
`grid__col-xs-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xs` (имя переменной с соотв. шириной вьюпорта в значении)

### `small`

Маленький. <br>
Сокращение: `sm` <br>
Пример: <br>
`grid__col-sm-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-sm` (имя переменной с соотв. шириной вьюпорта в значении)

### `medium`

Средний. <br>
Сокращение: `md` <br>
Пример: <br>
`grid__col-md-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-md` (имя переменной с соотв. шириной вьюпорта в значении)

### `large`

Большой. <br>
Сокращение: `lg` <br>
Пример: <br>
`grid__col-lg-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-lg` (имя переменной с соотв. шириной вьюпорта в значении)

### `extra large`

Очень большой. <br>
Сокращение: `xl` <br>
Пример: <br>
`grid__col-xl-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xl` (имя переменной с соотв. шириной вьюпорта в значении)

### `extra extra large`

Сафсэм балшой. <br>
Сокращение: `xxl` <br>
Пример: <br>
`grid__col-xxl-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xxl` (имя переменной с соотв. шириной вьюпорта в значении)

### `narrow`

Узкий. <br>
Сокращение: нет <br>
Пример: <br>
`btn--narrow` (модификатор, делающий кнопку узкой)

### `wide`

Широкий. <br>
Сокращение: нет <br>
Пример: <br>
`btn--wide` (модификатор, делающий кнопку широкой)

### `phone`, `mobile`

Мобильные устройства (телефоны до 5 дюймов). <br>
Сокращение: нет  <br>
Пример: <br>
`promo--phone` (модификация промо-блока для соотв. устройств)

### `tablet`

Планшеты (ориентировочно до 12 дюймов). <br>
Сокращение: нет <br>
Пример: <br>
`promo--tablet` (модификация промо-блока для соотв. устройств)

### `notebook`, `laptop`

Ноутбуки. <br>
Сокращение: нет      <br>
Пример: <br>
`promo--laptop` (модификация промо-блока для соотв. устройств)

### `desktop`

Настольные компьютеры. <br>
Сокращение: нет <br>
Пример: <br>
`promo--desktop` (модификация промо-блока для соотв. устройств)

## Прочее

### `previous`

Предыдущее (часто - ссылка/кнопка). <br>
Сокращение: `prev`  <br>
Пример: <br>
`slider__prev` (кнопка/стрелка на слайдере)

### `next`

Следущее (часто - ссылка/кнопка). <br>
Сокращение: нет <br>
Пример: <br>
`slider__next` (кнопка/стрелка на слайдере)  

### `advertisement`

Рекламный фрагмент (осторожно, может вырезаться баннерорезками). <br>
Сокращение: `adv`  <br>
Пример: <br>
`aside__adv` (рекламный блок в сайдбаре)

### `background`

Фон (чаще — какое-то изменение фонового цвета блока). <br>
Сокращение: `bg` <br>
Пример: <br>
`top-rated--bg-gray` (модификация фонового цвета блока самых рейтинговых товаров/услуг)

### `number`

Число. <br>
Сокращение: `num`  <br>
Пример: <br>
`field-text--num` (модификатор для текстового поля, позволяющий иначе оформить числовые поля)
