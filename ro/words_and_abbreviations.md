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
`grid__row` (unul sau mai multe "rânduri" ale gridului modular)

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

O parte, un element, o "unitate" separată. Un cuvânt universal dacă nu este ceva specific. <br>
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

Titlu (часто применяется на заголовочных тегах, но не обязательно на них). <br>
Prescurtare: нет  <br>
Exemplu: <br>
`promo__title` (titlu pentru bloc de publicitate)

### `subtitle`

Subtitlu. <br>
Prescurtare: нет <br>
Exemplu: <br>
`post__subtitle` (subtitlul postării de blog)

### `name`

Название. <br>
Сокращение: нет <br>
Пример: `product__name` <br>

### `slogan`

Слоган. <br>
Сокращение: нет <br>
Пример: <br>
`logo__slogan` (слоган в блоке логотипа)

### `user`

Пользователь. <br>
Сокращение: нет <br>
Пример: <br>
`user` (блок авторизованного/неавторизованного посетителя, к примеру, в шапке)

### `label`, `tag`

Метка, тег. <br>
Сокращение: нет <br>
Пример: <br>
`label` (лейбл), <br>
`post__tags-list` (список меток записи в блоге)

### `category`

Рубрика(и). <br>
Сокращение: `cat`  <br>
Пример: <br>
`post__cats` (рубрики записи в блоге)

### `dropdown`

Выпадающий элемент (направление выпадения не имеет значения). <br>
Сокращение: `drop`  <br>
Пример: <br>
`filter__drop` (выпадающий по клику блок в фильтре)

### `search`

Поиск. <br>
Сокращение: нет <br>
Пример: <br>
`search-form` (блок быстрого поиска, возможно, в «шапке»)

### `socials`

Социальные сети (иконки, обычно). <br>
Сокращение: нет <br>
Пример: <br>
`socials__list` (список с соц. ссылками)

### `carousel`, `slider`

Карусель, слайдер (несколько сменяющих друг друга слайдов). <br>
Сокращение: нет <br>
Пример: <br>
`promo__slider` (карусель в промо-блоке)

### `header`

Верхняя часть, «шапка». <br>
Сокращение: нет <br>
Пример: <br>
`page-header` («шапка» страницы), <br>
`post__header` («шапка» записи в блоге)

### `footer`

Нижняя часть, «подвал». <br>
Сокращение: нет <br>
Пример: <br>
`page-footer` («подвал» страницы), <br>
`post__footer` («подвал» записи в блоге)

### `additional`

Добавление чего-либо. <br>
Сокращение: `add`  <br>
Пример: <br>
`location__btn-add` (кнопка добавления в блоке какого-то места)

### `info`, `meta`

Информация о какой-либо сущности. <br>
Сокращение: нет <br>
Пример: <br>
`post__info` (информация о записи в блоге)  

### `body`

Главная контентная часть чего-либо. <br>
Сокращение: нет <br>
Пример: <br>
`post__body` (основной текстовой фрагмент записи в блоге)

### `content`

Содержимое чего-либо. <br>
Сокращение: нет <br>
Пример: <br>
`post__content` (основной текстовой фрагмент записи в блоге)

### `section`

Крупный раздел чего-либо. <br>
Сокращение: нет <br>
Пример: <br>
`promo__section` (большой раздел промо-блока)

### `icon`

Иконка. <br>
Сокращение: нет <br>
Пример: <br>
`icon--twitter` (иконка соц. сети (модификатор))

### `link`

Cсылка. <br>
Сокращение: нет <br>
Пример: <br>
`product__more-link` (ссылка «Далее» в блоке продукта)

### `list`

Cписок. <br>
Сокращение: нет <br>
Пример: <br>
`features__list` (список преимуществ)

### `description`

Описание какой-либо сущности <br>
Сокращение: `descr` <br>
Пример: <br>
`product__descr` (описание продукта)

### `image`

Изображение. <br>
Сокращение: `img`  <br>
Пример: <br>
`promo__img` (изображение в промо-блоке)

### `picture`

Изображение. <br>
Сокращение: `pict`, `pic`  <br>
Пример: <br>
`promo__pict` (картинка в промо-блоке)

### `toggle`

Переключение, тумблер. Часто — «гамбургер», переключающий показ/сокрытие главного меню (на медиа-условии, при котором меню скрывается под «гамбургером»). <br>
Сокращение: нет <br>
Пример: <br>
`main-nav__toggle` (переключатель видимости гл. меню)

### `tab`

Вкладка. <br>
Сокращение: нет <br>
Пример: <br>
`tabs` (вкладки), <br>
`promo__tab` (вкладка в промо-блоке)

### `thumbnail`

Миниатюра (обычно, в какой-либо галерее). <br>
Сокращение: `thumb` <br>
Пример: <br>
`photo__thumb` (миниатюра в фотогалерее)

### `avatar`

Аватарка, маленькая картинка пользователя. <br>
Сокращение: нет <br>
Пример: <br>
`user__avatar` (аватарка пользователя в блоке пользователя в шапке)

### `text`

Текстовой фрагмент (обычно, выводимый из CMS). <br>
Сокращение: нет <br>
Пример: <br>
`about__text` (текст «о нас», вероятно обертка вокруг нескольких параграфов)

### `author`

Автор. <br>
Сокращение: нет <br>
Пример: <br>
`post__author` (имя/ник автора записи в блоге)

### `more`

«далее», «подробнее». <br>
Сокращение: нет <br>
Пример: <br>
`product__more-link` (кнопка или ссылка в промо-блоке, предлагающая ознакомиться подробнее)

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
