# Glosar de termeni frontend

Cuprins: [0-9](#0-9) [A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) J [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) X Y Z

## 0-9

### 9-slice scaling

**9-slice scaling** (scalare fără distorsiuni), o tehnică care permite redimensionarea obiectului fără distorsiuni geometrice. Obiectul este împărțit în 9 părți (3 rânduri și 3 coloane), fiecare dintre acestea fiind redimensionată în funcție de propriile reguli: colțurile nu sunt deloc redimensionate, partea central este redimensionată în înălțime și lățime, iar restul părților sunt redimensionate fie numai în lățime, fie numai în înălțime.

## A

### accessibility, a11y

**accesibilitate,** capacitatea de utilizare a interfeței de oricine, indiferent de restricțiile fizice sau tehnice.

### adaptive design

**design adaptiv**, abordare a web designului care ia în considerare adaptarea la diferite dispozitive și medii, spre deosebire de designul obișnuit "fix", destinat exclusiv calculatoarelor. O modalitate de a crea design adaptiv este prin tehnici de [responsive design] (#responsive-design).

### almost standards mode

**mod aproape standard,** mod de interpretare și afișare a unei pagini de către browser, în care browserul se abate în mod deliberat de la standarde (ca în [compatibility mode](#quirks-mode)) numai pentru anumite cazuri speciale, utilizat pentru paginile de tranziție cu [doctypes](#doctype) HTML 4 și XHTML 1.

### anchor

1. **link,** hyperlink între două documente.
2. **ancoră,** referință la un element dintr-un document, poate face parte dintr-un hyperlink.

### animation

**animație,** schimbare lină a parametrilor vizuali ai unui obiect.

### asset

**resursă,** parte componentă a unui site: fișiere text, grafică, video, baze de date, etc. În sens restrâns, o "resursă statică": stiluri, scripturi, grafică de design, spre deosebire de [conținutul] dinamic (https://github.com/web-standards-ru/dictionary/blob/master/dictionary.md#content).

### assert

**verificare,** condiție, care este verificată, utilizată în testare, de ex. _field assert has failed — verificarea câmpului a eșuat._

### at-keyword

**cheia directivei,** vezi [directivă](#at-rule)

### at-rule

**directivă,** tip de [declarație](#statement) care începe cu un semn `@`, de ex. _@import_.

### attribute

**atribut,** de ex. `rel="stylesheet"`

- attribute name — **nume atribut**
- attribute value — **valoare atribut**

## B

### back-end

**back-end**

1. Zonă a tehnologiei web care rulează pe un server.
2. Partea internă a sistemului serverului, care se ocupă cu prelucrarea datelor.

### background

**fundal,** de ex. _background image — imagine de fundal._

- background-color — **culoare fundal**
- background-position — **poziție fundal**
- background-size — **dimensiune fundal**
- background-repeat — **repetare fundal**
- background-origin — **graniță fundal**
- background-clip — **decupare fundal**
- background-attachment — **fixare fundal**
- background-image — **imagine de fundal**

### baseline

**linie de bază,** linie imaginară la baza literelor din șir.

### bikeshed

**a acorda o atenție excesivă banalităților,** (vezi [legea banalității]([legea banalității](https://en.wikipedia.org/wiki/Law_of_triviality)). Nu există un echivalent stabilit în limba română, este mai bine să se traducă sensul general, de exemplu _avoid bikeshedding - nu vă certați din fleacuri._

### blending mode

**mod de amestecare,** algoritm de amestecare a layerelor utilizat în editorii grafici sau direct în CSS, de exemplu. _overlay blending mode — mod de amestecare prin suprapunere.

### block
1. **bloc de declarații,** parte structurală a [declarației](#statement). Închisă între acolade și conține declarații cu proprietăți (sau, în cazul unei expresii media, blocuri de stil).
2. **aspect de bloc,** vezi [view](#display).

### blockquote

**blockquote,** element HTML pentru evidențierea secțiunii fără ghilimele a unui document. Poate conține un atribut `cite` cu o legătură către sursa originală.

### border

**chenar,** partea exterioară vizibilă a blocului, de exemplu. _border-left este chenarul din stânga._

- border-collapse — **combinare chenar**
- border-color — **culoare chenar**
- border-image — **chenar grafic**
- border-image-outset — **distanță chenar grafic**
- border-image-repeat — **repetare chenar grafic**
- border-image-slice — **tăierea pe părți a chenarului grafic**
- border-image-source — **adresa imaginii pentru chenarul grafic**
- border-image-width — **grosime chenar grafic**
- border-radius — **rotunjire chenar**
- border-style — **stil chenar**
- border-width — **lățime chenar**

### border-radius

**rotunjire chenar,** de ex., _border-radius: 3px — rotunjirea chenarului cu 3 px, border-top-left-radius — rotunjirea colțului din stânga sus,_ de asemenea, vezi [rotunjire colțuri](#rounded-corners).

### bounding box

**bloc de bordură**

### box model

**model bloc,** sistem dimensional de blocuri, format din conținut, margină, chenar și padding.

### box-shadow

**umbra (blocului),** de ex. _box-shadow is red — umbra blocului este roșie._

### breadcrumbs

**breadcrumbs,** navigare auxiliară pe site, care indică în mod succesiv structura sau pașii parcurși de utilizator.

### breakpoint

1. **breakpoint,** este una dintre traducerile utilizate în mod obișnuit, sensul exact fiind clar din context.
2. **punct de oprire,** o linie din cod la care execuția scriptului este întreruptă pentru a apela debuggerul.
3. **punct de control,** condiția în care aspectul site-ului se schimbă din unul în altul. Tipic pentru expresiile media.

### browser

**browserr**

### button

**buton**

1. Element de interfață, la apăsarea căruia este trimis un formular sau se face o altă acțiune.
2. Element de formular `<button>` sau `<input type="button">` (de asemenea `submit` și `image`).

## C

### callback

**callback,** executarea codului atunci când funcția este terminată, de exemplu. _pass value in a callback - transmite valoarea într-un callback._

### candidate recommendation (CR)

**candidat la recomandare,** statutul specificației [W3C](#world-wide-web-consortium-w3c), o opțiune posibilă pentru [recomandarea propusă](#proposed-recommendation-pr).

### cascade

### cascade

**cascadă,** schemă descrisă în specificația CSS care definește modul în care blocurile de stil sunt aplicate unui element.

### cascade layer

**layer în cascadă,** modalitate de a grupa și de a controla ordinea în care sunt aplicate stilurile în cadrul unei singure [surse](#cascade-origin), declarată cu ajutorul [directivei](#at-rule) `@layer`. De ex. _rules within a cascade layer cascade together_ — _regulile din cadrul layerelor în cascadă se aplică în cascadă la un loc._

### cascade origin

**sursă în cascadă,** zonă de descriere a stilurilor încorporată în browsere, ordinea surselor determină aplicarea stilurilor sau [cascada](#cascade): de la stilurile browserului la transition-property. De ex. _there are eight cascade origings, including user styles_ — _există opt surse în cascadă, inclusiv stilurile utilizatorului._

### cell

**celulă**

1. Unitate structurală a tabelului.
2. Element al tabelului `<td>` sau `<th>`.

### cellpadding

**padding în celulele** tabelului.

### cellspacing

**distanța între celulele** tabelului.

### character reference

**entități,** de ex. `&nbsp;`. De asemenea, se acceptă o traducere nu complet exactă, dar mai bine cunoscută **simboluri speciale.**

### checkbox

**checkbox**

1. Element de interfață pentru selectarea uneia sau mai multor opțiuni, de exemplu _checkbox is disabled - checkbox este inactiv._
2. Element de formular `<input type="checkbox">`.

### child

1. Substantiv **copil,** (plural children — **copii**)
2. Adjectiv **înrudit,** de ex. _child process — proces înrudit_

### classitis

**classitis,** o boală inventată caracterizată prin utilizarea excesivă a mai multor clase: atât pentru proiectare, cât și pentru stocarea informațiilor.

### clear

**clear,** proprietate CSS care setează dacă un bloc trebuie să fie mutat sub blocurile plutitoare care îl preced. 

- clear: left — **bloc împins sub blocurile plutitoare din stânga**
- clear: right — **bloc împins sub blocurile plutitoare din dreapta**
- clear: both — **bloc împins sub toate blocurile plutitoare**

### clearfix

**clearfix,** metodă pentru a împiedica colapsul containerelor cu blocuri plutitoare. Aceasta constă în crearea unui spațiu special care este plasat după blocurile plutitoare și care anulează deplasarea acestora.

### click

**click,** apăsarea pe obiect cu cursorul mouse-ului sau cu un dispozitiv similar, de exemplu _double click is firing event — dublu click declanșează evenimentul._

### client-side

**client-side,** domeniu al tehnologiei bazate pe browser, adesea sinonim cu [front-end](#front-end).

### clipping path

**imagine decupată**

### closure

**closure,** funcție care conține în corpul său referințe către variabilele declarate în codul înconjurător.

### code

1. Substantiv **cod,** fără plural, (ca soare), de ex. _error in code — eroare în cod,_ dar nu _eroare în coduri (greșit)._
2. Verb **a scrie cod, a programa,** de ex. _to code a site — a scrie codul unui site._

### colspan

**объединение столбцов,** HTML-атрибут для объединения нескольких ячеек таблицы в одной строке.

### column

**столбец, колонка,** вертикальная область в таблице, раскладке или тексте.

### color

**цвет**

### combinator

**комбинатор,** специальный символ, использующийся в сложном селекторе для точного указания комбинации DOM-элементов, напр. `>`, `+` и др. Пробел между селекторами также считается комбинатором.

- descendant combinator — **комбинатор потомка,** `` (пробел).
- child combinator — **комбинатор непосредственного потомка,** `>`. Также называется **дочерним**.
- adjacent sibling combinator — **комбинатор непосредственного соседства,** `+`.
- general sibling combinator — **комбинатор соседства,** `~`.

### comment

**комментарий,** пояснение к коду

### component

**компоне́нт,** (м. р.) составная часть чего-либо. Напр. _app components_ — _компоненты приложения_

### compositing

**компо́зитинг**

### composite layer

**композитный слой**

### compositor

**композитор** (в знач. «движок композитинга»)

### container query

**выражение от контейнера,** объявление директивы `@container` с условиями, позволяет применять стили в зависимости от свойств _родительского_ контейнера. Напр. _many container query cases can be solved with existing technology_ — _во многих случаях вместо выражений от контейнера можно использовать существующие технологии._

### containing block

**содержащий блок** — блок, относительно которого рассчитываются размеры и положения данного блока. Упрощенно, содержащий блок — это родитель данного блока не по DOM, а по потоку документа. Напр. _containing block isn’t always the content area of the parent_ — _содержащий блок — это не всегда контентная область родителя._

### content

**содержимое**

- metadata content — **метасодержимое**
- flow content — **потоковое содержимое**
- sectioning content — **структурное содержимое**
- heading content — **заголовочное содержимое**
- phrasing content — **текстовое содержимое**
- embedded content — **внедряемое содержимое**
- interactive content — **интерактивное содержимое**
- palpable content — **содержимое для вывода**
- script-supporting content — **скриптовое содержимое**
- grouping content — **группирующее содержимое**

### continuous integration

**непрерывная интеграция,** практика частой, автоматизированной сборки, тестирования и развёртывания программного обеспечения

### cookie

**кукa,** небольшой фрагмент данных, который отправляется с сервера и сохраняется в браузере.

- access to cookies — **доступ к кукам**
- cookie banner — **сообщение о куках**
- authorization cookie — **авторизационная кука**
- first-party cookies — **собственные куки**
- third-party cookies — **сторонние куки**

### cross-browser

**кроссбра́узерный,** работающий во всех браузерах, слитно.

### cross-platform

**кроссплатфо́рменный,** работающий на всех платформах, слитно.

### custom properties

**кастомные свойства,** CSS-свойства вида `--my-property`, которые разработчики могут создавать самостоятельно и использовать дальше в коде как переменные с помощью функции `var()`. Также распространён перевод **CSS-переменные,** напр. _CSS variables, also known as CSS custom properties, are landing in Chrome 49 — CSS-переменные, также известные как кастомные CSS-свойства, появятся в Chrome 49._

### CSS Working Group (CSSWG)

**Рабочая группа CSS**

### custom

**кастомный** (возм. **пользовательский**)

- custom element — **кастомный элемент**.
- custom attribute — **кастомный атрибут**.

## D

### data binding

**связывание данных,** автоматическая синхронизация данных между двумя сущностями, обычно моделью и представлением.

### declaration

**декларация,** объявление свойства и значения.

### deep comparison

**глубокое сравнение,** сравнение двух объектов, при этом производится сравнение структуры объектов и проверяется равенство примитивов содержащихся внутри объектов.

### deploy, deployment

**деплой, развёртывание, выкладка, выкатка,** публикация изменений либо напрямую на публичный сервер (продакшен), либо через промежуточные системы и процессы автоматической сборки.

### deprecated

**устаре́вший,** статус возможности языка, которая не рекомендуется к использованию, поскольку либо _уже_ была заменена, удалена или _будет_ в следующих версиях, напр. _this API is a replacement of the deprecated `React.addons.cloneWithProps()` — этот API замена устаревшему `React.addons.cloneWithProps()`_ или _`<applet>` is deprecated in favor of `<object>` — `<applet>` помечен устаревшим в пользу `<object>`_.

### design

1. сущ. **дизайн,** визуальный облик сайта, может включать принципы взаимодействия и архитектурные решения, напр. _new design for a site — новый дизайн для сайта_.
2. гл. **разрабатывать,** создавать или проектировать внешний вид и функциональность.

### device pixel ratio

см. [pixel ratio](#pixel-ratio)

### dirty checking

**проверка на «грязные» свойства объекта,** то есть [глубокое сравнение](#deep-comparison) свойств модели, который приводит к [обратному вызову](#callback), если что-то изменилось.

### disable

**деактивировать**

### disabled

**неактивный,** состояние элемента формы, в котором его изменение запрещено, напр. _disabled button — неактивная кнопка._

### display

1. **вид,** css-свойство, определяющее тип отображения блока.

 - display: none — **скрытый вид**
 - display: block — **блочный вид**
 - display: inline — **строчный вид**
 - display: inline-block — **вид строчного блока**

- display: flex — **вид флекс-контейнера** (см. [flexbox](#flexbox))
- display: inline-flex — **вид строчного флекс-контейнера** (см. [flexbox](#flexbox))

2. **экран,** напр. _экран смартфона, разрешение экрана_.

### divitis

**диватоз,** выдуманное заболевание, для которого характерно использование только элементов `<div>` вместо [семантически](#semantics) подходящих.

### DOM

**объектная модель документа, дом**

### doctype

**докта́йп,** конструкция вида `<DOCTYPE html>` в начале документа, которая обозначает используемую версию HTML. Используется браузерами для выбора режима ([стандартного](#standards-mode-standards-compliance-mode), [почти стандартного](#almost-standards-mode) или [совместимости](#quirks-mode)).

### dropdown

**выпадающее меню,** элемент интерфейса, раскрывающий дополнительную информацию при активации.

## E

### easing

**плавность, функция плавности,** описывает изменение скорости анимации с помощью ключевых слов или кривых Безье, напр. _transition easing is linear — плавность перехода линейная._

### editor’s draft (ED)

**редакторский черновик,** ранний статус спецификации [W3C](#world-wide-web-consortium-w3c), предложенный одним из редакторов. На основании редакторского черновика может быть составлен [рабочий черновик](#working-draft-wd).

### element

**элемент**

- void elements — **пустые элементы**
- raw text elements — **элементы со свободным текстом**
- escapable raw text elements — **элементы с экранируемым свободным текстом**
- foreign elements — **сторонние элементы**
- normal elements — **обычные элементы**

### em

**ем,** единица измерения в CSS, которая зависит от размера шрифта родителя, напр. _font-size: 3em — размер шрифта 3 ема._

### enable

**активировать**

### enabled

**активный,** состояние элемента формы, в котором его изменение разрешено, напр. _enabled button — активная кнопка._

### engine

**движок,** напр. _Safari is based on WebKit engine — Сафари работает на движке Вебкит._

## F

### fallback

**фолбэк,** запасной вариант, дополнительная реализация на случай отсутствия в браузере нужных возможностей, вроде включённых скриптов или нужных видеокодеков, напр. _fallback to a link — сфолбэчить на ссылку._

### favicon

**фавико́нка,** значок сайта, обычно 16×16 пикселей в формате ICO.

### feature query

**директива `@suppórts`,** условная конструкция, которая позволяет выборочно применять стили в зависимости от поддержки браузером тех или иных свойств и значений. Прямого устоявшегося перевода по примеру [медиавыражений](#media-query) пока нет.

### fieldset

**группа полей,** элемент, объединяющий несколько полей формы, напр. _green border on a fieldset — зелёная рамка на группе полей._

### figure

**фигура,** элемент из HTML5, содержащий изображение, видео, таблицу, график или фрагмент кода.

### figcaption

**заголовок фигуры,** заглавие или подпись к фигуре.

### filter

**фильтр**

- filter: brightness — **яркость**
- filter: contrast — **контрастность**
- filter: grayscale — **бесцветность**
- filter: sepia — **сепия**
- filter: invert — **инверсия**
- filter: saturate — **насыщенность**
- filter: hue-rotate — **поворот цвета**
- filter: blur — **размытость**
- filter: opacity — **непрозрачность**
- filter: drop-shadow — **тень**

### flash of…

- flash of unstyled text, FOUT — **мелькание текста без стилей,** отображение текста системным шрифтом до загрузки веб-шрифта
- flash of invisible text, FOIT — **мелькание невидимого текста,** отсутствие текста на странице до загрузки веб-шрифта
- flash of faux text, FOFT — **мелькание синтезированного текста,** отображение начертаний текста изменённым основным шрифтом до загрузки нужных шрифтов

### flexbox

**флексбокс,** механизм [раскладки](#layout).

- flex container — **флекс-контейнер**
- flex item — **флекс-элемент**
- flex-direction — **направление главной оси**
- flex-wrap — **перенос флекс-элементов,** определяет, является ли контейнер однострочным или многострочным
- flex-basis — **базовый размер** флекс-элемента по главной оси
- flex-grow — **коэффициент растягивания**
- flex-shrink — **коэффициент сжатия**
- main axis — **главная ось,** направление, в котором флекс-элементы следуют друг за другом в контейнере
- cross axis — **поперечная ось,** направление, перпендикулярное главной оси
- main size — **главный размер,** размер флекс-элемента по главной оси
- cross size — **поперечный размер,** размер флекс-элемента по поперечной оси
- justify-content — **распределение флекс-элементов** по главной оси
- align-items — **выравнивание флекс-элементов** по поперечной оси
- align-self — **выравнивание флекс-элемента** по поперечной оси
- align-content — **выравнивание строк** контейнера по поперечной оси
- order — **порядковый номер** флекс-элемента

### float

1. прил. **плавающий,** свойство блока, заставляющее последующие блоки обтекать его, напр. _float layout — раскладка на плавающих блоках._
2. гл. **обтекать,** следовать вплотную к плавающему блоку, напр. _text is floating to the right — текст обтекает справа._
3. гл. **прижимать,** упираться вправо или влево, обычно из-за плавающих свойств, напр. _float block to the left — прижмите блок влево._

### font

**шрифт**

- font-weight — **насыщенность**

  - font-weight: normal — **нормальная**
  - font-weight: bold — **жирная** или **полужирная** (в типографской традиции)
  - font-weight: bolder — **жирнее**
  - font-weight: lighter — **светлее**

- font-style — **стиль шрифта**

  - font-style: normal — **прямой**
  - font-style: italic — **курси́в**
  - font-style: oblique — **наклонный**

- font-size — **размер шрифта, кегль**

- font-family — **семейство шрифта, гарнитура**

  - font-family: serif — **с засечками**
  - font-family: sans-serif — **без засечек**
  - font-family: monospace — **моноширинный**

### footer

**подвал**

1. характерная визуальная область в конце страницы.
2. элемент `<footer>` — смысловая часть с метаинформацией.

### formatting context

**контекст форматирования,** в CSS — область, в которой выстраиваются визуальные элементы страницы (фрагменты текста, блоки, ячейки и т.п.) по определенным правилам.

- block formatting context, BFC — **блочный контекст форматирования,** **БКФ** (напр. _element with `overflow` establishes the new BFC — элемент с `oveflow` создает новый БКФ_)
- grid formatting context — **контекст форматирования гридов** (см. [grid layout](#grid-layout))
- flexbox formatting context — **контекст форматирования флексбоксов** (см. [flexbox](#flexbox))
- inline formatting context — **строчный контекст форматирования**
- table formatting context — **табличный контекст форматирования**

### forced color mode

**режим принудительных цветов,** в котором указанные разработчиком цвета принудительно заменяются на системные или пользовательские, чаще всего для повышения контрастности и большей доступности контента для слабовидящих.

### fragment identifier

**идентификатор фрагмента,** текст после `#` в URL, позволяющий сослаться на конкретную часть документа. Используется в основном в спецификациях и при работе с SVG, в HTML устоялся более привычный термин [якорь](#anchor).

### framework

**фреймво́рк,** набор библиотек и компонентов для упрощения разработки. Как правило, представляет собой базовый каркас продукта. _Напр., [Twitter Bootstrap](http://getbootstrap.com/)._

### front-end

**фронте́нд**

1. область технологий для разработки веб-интерфейсов, включает вспомогательные инструменты и технологии работающие в браузере или [клиентсайд](#client-side).
2. внешняя часть серверной системы, отвечающая за приём данных, отправку ответов и генерацию кода для браузера, входит в [серверсайд](#server-side).

### full screen

**полноэкранный режим,** поведение программы или её части, в котором она занимает весь экран целиком.

### fullstack

**фулсте́к**

1. область специализации, которая включает в себя [фронтенд](#front-end) и [бэкенд](#back-end).
2. специалист, который может отвечать за все аспекты проекта: от клиентской до серверной части.

Напр., _Катерина разобралась с базами данных и исправила в резюме «фронтендер» на «фулстек»._

### function

**функция**

1. в программировании — поименованный фрагмент программного кода (подпрограмма), к которому можно обратиться из другого места программы.
2. в CSS — может присутствовать в [декларации](#declaration) на позиции значения. Напр., `url(img/gradient.png)`.

## G

### generated content

**сгенерированное содержимое,** часть документа, созданная с помощью CSS, [псевдоэлемента](#pseudo-element) и свойства `content`.

### graceful degradation

**постепенная деградация** — подход, при котором интерфейс сайта деградирует для старых браузеров, где не поддерживаются какие-то из используемых технологий. При этом ущерб для пользователя по возможности смягчается. Например: цвет подложки вместо градиента, растровая графика вместо векторной, проигрывание видео с помощью плагина. Встречается также более буквальный перевод _«изящная деградация»_.

### gradient

**градие́нт,** плавный переход от одного цвета к другому.

- linear gradient — **линейный градиент**
- radial gradient — **радиальный градиент**
- conical gradient — **конический градиент**

### grid

1. **сетка,** способ упорядочить расположение элементов в дизайне с помощью вертикального или горизонтального ритма, напр. _module grid — модульная сетка._
2. **грид,** двумерная сетка из рядов и колонок в [грид-раскладке](#grid-layout).

### **grid layout**

**грид-раскладка,** механизм [раскладки](#layout), позволяющий располагать элементы по двумерной сетке — [гриду](#grid) (2).

- **grid container** — _грид-контейнер_
- **grid item** — _грид-элемент_
- **grid track** — _грид-полоса_, собирательный термин для рядов и колонок _грида_
- **grid cell** — _грид-ячейка_
- **grid line** — _грид-линия_, виртуальная граница между соседними _грид-полосами_, к которой можно привязывать _грид-элементы_
- **grid area** — _грид-область_, пространство для размещения _грид-элементов_, ограниченное четырьмя _грид-линиями_
- **grid gutter** — _грид-интервал_, промежуток между соседними _грид-полосами_

## H

### header

**шапка**

1. характерная визуальная область в начале страницы.
2. элемент `<header>` — смысловая озаглавливающая часть.

### height

**высота**

## I

### icon font

**иконочный шрифт,** синтетический шрифт, содержащий иконки и другие плоские векторные изображения для оформления сайта, напр. _build an icon font — собери иконочный шрифт._

### immutable

**неизменяемый,** термин чаще всего применяется к данным (типам данных) в функциональном программировании.

### implement

**внедрять, реализовывать** напр. _Firefox has implemented support of everything — Файрфокс внедрил поддержку всего._

### inline

1. **строчный,** имеющий строчные свойства.

 - inline block — **строчный блок**.
 - inline box — **элемент строки** в строчном форматировании: часть наполнения контейнера строки, к которой непосредственно применяются CSS-правила, напр. _anonymous inline box — анонимный элемент строки_.
 - inline element — **строчный элемент**.

2. **встроенный,** находящийся внутри строки кода.

 - inline styles — **встроенные стили**.
 - inline SVG — **встроенный SVG**.
 - inline script — **встроенный скрипт**.

### input

**элемент формы,** обеспечивающий взаимодействие пользователя с интерфейсом, например: текстовое поле, кнопка, переключатель.

### intrinsic dimensions

**собственные размеры,** ширина и высота, определяемые самим элементом, а не окружением. CSS не может указывать, как вычисляются собственные размеры. Только замещаемые элементы могут иметь собственные размеры, например: картинки, видео, аудио и другие блоки, представление которых не зависит от разработчика.

### internationalization, i18n

**интернационализация,** процесс проектирования и разработки интерфейса, позволяющий производить [локализацию](#localization-l10n) для различных регионов (различающихся по культуре или языку) без каких-либо технических изменений, напр., _`Intl.DateTimeFormat` - конструктор класса, позволяющий форматировать дату и время с учетом локали._

### interoperability

**интероперабельность**

## K

### kerning

**кернинг,** расстояние между парами букв, учитывающее их форму для более равномерного набора.

### keyframe

**ключевой кадр,** одна из заданных точек анимации, изменения между которыми происходят автоматически.

### keyframe animation

**покадровая анимация,** способ задания анимации в CSS с помощью ключевых кадров.

### keyword

**ключевое слово**

## L

### label

**метка,** устанавливает связь между определённым элементом и элементом формы.

### last call (LC)

**последний черновик,** статус спецификации [W3C](#world-wide-web-consortium-w3c) для последних правок перед статусом [кандидата в рекомендации](#candidate-recommendation-cr) _(отменен в 2014 г., встречается только у старых спецификаций)_.

### layout

**раскладка,** расположение основных блоков на странице, напр. _3 columns layout — раскладка в 3 столбца._

### legend

**легенда,** заголовок группы элементов формы, определяется с помощью [группы полей](#fieldset)

### length

**длина**

### letter-spacing

**межбуквенное расстояние, тре́кинг,** общее расстояние между буквами в тексте, отличается от [кернинга](#kerning).

### library

**библиотека,** набор готовых решений для упрощения разработки. Как правило, библиотека реализует какую-то конкретную функцию или набор связанных функций, напр., анимацию.

### line-box

**контейнер строки** в строчном форматировании: виртуальный контейнер, содержащий в себе все элементы одной строки.

### line-height

**высота строки, интерлинья́ж,** расстояние между базовыми линиями текста.

### list

**список,** последовательное перечисление группы элементов.

- ordered list — **упорядоченный список,** отсортированный по какому-либо принципу.
- unordered list — **неупорядоченный список,** в котором порядок следования не имеет значения.

### list-style

**стиль списка**

### localization, l10n

**локализация,** процесс адаптации интерфейса под языковые и культурные соответствия определённого региона (страны, локали), напр., _`new Date().toLocaleDateString('en-US')` - преобразует дату в ее строковое представление, согласно локали США._

## M

### margin

**внешний отступ,** напр. _margin-bottom: -10px — нижний отрицательный отступ 10 пикселей._

### margin box

**внешние отступы чего-л.**

### matrix

**ма́трица (трансформации),** описание трансформации объекта с помощью матрицы.

### media query

**медиавыраже́ние,** объявление директивы `@media` с некими [условиями](#media-query-list), позволяет применять стили в зависимости от возможностей устройства. Вариант перевода «медиазапросы» менее точно отражает суть работы.

### media query list

**условия медиавыражения,** список условий, определяющих, в каких случаях будут применяться объявления внутри директивы `@media`. Напр., `only screen and (min-width: 35em)`.

### media type

**медиати́п (тип устройства),** может быть условием медиавыражения. Указывает, для какого способа вывода предназначены стили (напр. `screen` — на экран, `print` — на печать, `speech` — для синтезатора речи).

### media feature

**медиафи́ча (характеристика устройства),** может быть условием медиавыражения. Определяет характеристику устройства. Напр., `min-width`.

### mixin

**при́месь,** набор свойств, расширяющий поведение другой сущности, встречается в CSS-препроцессорах и паттернах JavaScript, напр. _mixin is clearing — примесь очищает поток._

### mobile first

**Сначала мобильные,** подход разработки, при котором проектирование сервиса начинается с мобильной версии, а не с версии для больших экранов. Термин введён Люком Вроблевски в [одноимённой книге](https://abookapart.com/products/mobile-first).

### mock object

**фиктивный объект**

### mock-up

**макет,** внешний вид или дизайн сайта различной степени детализации, напр. _designer has sent a page mock-up — дизайнер прислал макет страницы._

### modal

1. прил. **мода́льный,** блокирующий интерфейс для выполнения какого-либо действия, напр. _modal dialog — модальный диалог._
2. сущ. **модальное окно (диалог),** элемент интерфейса, см. _модальный._

### multiple

**множественный,** повторённый два и более раз, напр. _multiple backgrounds — множественные фоны._

### multiple columns

1. **мультиколо́нки,** механизм из CSS, позволяющий выстроить текст в несколько колонок, напр. _multiple columns support in IE — поддержка мультиколонок в IE._ Предпочтительнее, чем громоздкие «множественные колонки».
2. **многоколо́ночный,** состоящий из нескольких колонок, напр. _multiple columns layout — многоколоночная раскладка._

## N

### nested

**вложенный,** находящийся внутри чего-либо, напр. _double nesting — двойная вложенность._

### node

**узел,** элемент структуры, напр. _child node — дочерний узел._

### number

**число, числовой тип**

## O

### opacity

**непрозрачность,** степень непрозрачности, напр. _opacity: 0.1 — непрозрачность 10%._ Часто ошибочно называется прозрачностью.

### opaque

**непрозрачный,** степень непрозрачности, напр. _opaque by 75% — непрозрачен на 75%,_ значит прозрачность 25%.

### outline

**обводка,** внешний равномерный контур элемента, не участвующий в блочной модели.

## P

### package manager

**менеджер пакетов,** реже **диспетчер пакетов,** вспомогательное ПО для управления установкой, настройкой, обновлением и удалением компонентов ПО.

### padding

**внутренний отступ,** напр. _padding-top: 10px — верхний внутренний отступ 10 пикселей._

### pagination

1. **постраничная навигация,** обычно список ссылок с номерами страниц, на которые разбит документ.
2. **разделение на страницы,** разделение документа на отдельные страницы для удобства чтения, загрузки или других целей.

### pattern

**па́ттерн,** формализованный подход к написанию кода, напр. _JavaScript patterns — паттерны JavaScript._

### parent

**родитель**

### percentage

**процентное значение, проценты**

### performance

**быстродействие,** характеристика скорости загрузки, отрисовки и т.п., напр. _CSS performance — быстродействие CSS._

### performance budget

**бюджет на быстродействие,** максимально допустимые показатели быстродействия веб-приложения. Выход за рамки такого бюджета означает спад быстродействия. Напр. _Performance Budget Metrics — показатели бюджета на быстродействие._

### persistent data structures

**постоянные структуры данных**

### pinch

**сведение (разведение) пальцев,** жест для управления сенсорным интерфейсом: сведение (в зависимости от направления — разведение) пальцев на сенсорном экране.

### pixel

**пи́ксель,** единица измерения для экранного дизайна, в мн.ч. **пиксели,** сокр. **пк.**

- physical pixel — **физический пиксель,** ячейка на матрице, единица разрешения дисплея устройства.
- device independent pixel (dip) — **виртуальный пиксель,** независимый от устройства пиксель, может быть больше, меньше или равен физическому.
- bitmap pixel — **растровый пиксель**.

### pixel density

**плотность пикселей,** количество пикселей, которое помещается в единицу линейного размера экрана, напр. _pixel density of the screen is 326 ppi — плотность пикселей экрана 326 пикселей на дюйм._

### pixel ratio

**пиксельное соотношение,** отношение физического пикселя к виртуальному, напр. _screen has pixel ratio of 2 — пиксельное соотношение экрана равно 2._

### placeholder

1. **заглушка,** временный заменитель картинки, текста и т.п. Напр.: _Вместо портрета президента вставь пока заглушку с котиками_.
2. **подсказка поля,** атрибут текстового поля, предназначен для подсказки о том, как это поле заполнять. Чаще всего представляет собой пример заполнения. Напр.: `placeholder="+7 (999) 123-12-13"`.

### ppi (pixel per inch)

**пикселей на дюйм,** единица измерения плотности пикселей (см. [pixel density](#pixel-density)).

### plugin

**TODO**

### polyfill

**полифи́л,** скрипт, воссоздающий недостающую функциональность, напр. _new polyfill for IE6 — новый полифил для IE6._

### progressive web metrics

**прогрессивные веб-метрики,** набор метрик страницы, связанных с [быстродействием](#performance).

- first paint — **первая отрисовка**
- first contentful paint (FCP) — **первая существенная отрисовка**
- first meaningful paint — **первая значимая отрисовка**
- visually ready — **визуальная готовность**
- visually complete — **визуальная завершённость**
- first interactive — **первая интерактивность**
- estimated input latency — **ожидаемая задержка ввода**
- time to interactive (TTI) — **время до первой интерактивности**
- time to first consistently interactive — **время до стабильной интерактивности**
- largest contentful paint (LCP) — **наибольшая существенная отрисовка**
- cumulative layout shift (CLS) — **совокупное изменение раскладки**
- total blocking time (TBT) — **суммарное время блокировки**
- first input delay (FID) — **время отклика на первое взаимодействие**

### prolyfill

**пролифи́л,** один из вариантов [полифила](#polyfill), отличающийся тем, что воспроизводит _вероятную_ функциональность, описанную в спецификации, но пока не реализованную в браузерах.

### popup

**всплывающее окно, попа́п,** отдельное окно или элемент интерфейса, появляющийся поверх текущего, напр. _annoying popup — назойливый попап._

### position

**позиционирование**

- position: static — **статичное**
- position: absolute — **абсолютное**
- position: relative — **относительное**
- position: fixed — **фиксированное**
- position: sticky — **закреплённое**

### preprocessor

**препроце́ссор,** инструмент, преобразующий код из одного синтаксиса в другой, напр. _Sass CSS preprocessor — CSS-препроцессор Sass._

### progress bar

**прогресс-бар** или индикатор выполнения — элемент интерфейса, отражающий прогресс выполнения операции.

### progressive enhancement

**прогрессивное улучшение** — подход, при котором все браузеры получают одинаковую базовую функциональность, но в современных браузерах эта функциональность расширяется в соответствии с поддержкой новых технологий. Например: градиенты, векторная графика, воспроизведение видео.

### Progressive Web App (PWA)

**прогрессивное веб-приложение,** — подход к разработке веб-приложений, сочетающий преимущества обычных сайтов и нативных приложений: быстрая загрузка, установка в ОС, работа в офлайне, пуш-уведомления, доступ к системным API. Информация для установки описывается в веб-манифесте. Прогрессивность подхода в том, что в обычном браузере — это просто сайт, а в поддерживающих браузерах и ОС — приложение.

### promises

**про́мисы,** способ асинхронного выполнения скриптов, противопоставляется использованию обратных вызовов.

### property

**свойство,** напр. _CSS-свойство_.

### proposed recommendation (PR)

**предложенная рекомендация,** статус спецификации [W3C](#world-wide-web-consortium-w3c), вероятный кандидат в [рекомендацию](#recommendation-rec).

### pseudo-element

**псевдоэлемент,** дополнительный внутренний элемент, созданный с помощью CSS и `::before` или `::after`.

### pseudo-class

**псевдокласс,** используется для привязки декларации к определенному состоянию элемента DOM. Отделяется от селектора знаком двоеточия `:`. Напр., декларация блока правил с селектором `.item:hover` применится, когда на `.item` наведут курсор.

### pull request, pr

**пулреквест,** запрос на принятие изменений в ветку репозитория из форка или другой ветки.

## Q

### quirks mode

**режим совместимости,** режим интерпретации и отображения страницы браузером, в котором браузер целенаправленно отходит от стандартов ради отображения документов, созданных до начала 2000-х гг. и полагавшихся на ошибки и особенности браузеров того времени. Используется для страниц без [доктайпа](#doctype) и с устаревшими доктайпами (напр. HTML 3.2).

## R

### radio button

**радиокно́пка,** элемент формы `<input type="radio">` для выбора одного варианта из нескольких, напр. _radio button is checked — радиокнопка выбрана._

### recalculate

**перерасчет**

### recommendation (REC)

**рекомендация,** финальный статус спецификации [W3C](#world-wide-web-consortium-w3c), рекомендованной для внедрения в браузеры и использования разработчиками.

### registry

**реестр,** место для хранения пакетов, напр. _GitHub Package Registry — реестр пакетов Гитхаба._ Калька «регистр» является неудачным переводом, поскольку конфликтует с употребимым во фронтенде значением _регистр букв._

### reflow

**перекомпоновка**

### rem

**рем,** единица измерения в CSS, которая зависит от размера шрифта корневого элемента `<html>`, напр. _font-size: 3rem — размер шрифта 3 рема._

### render

**отрисовка**

### repaint

**перерисовка**

### reset

**сброс,** обычно сброс стилей по умолчанию в CSS, напр. _style reset file — файл сброса стилей._

### resolution

**разрешение,** количество физических пикселей на экране устройства, напр. _screen resolution is 1024×768 pixels — разрешение экрана 1024×768 пикселей._

### responsive design

**отзывчивый дизайн,** один из технологических методов создания [адаптивного дизайна](#adaptive-design).

### Responsive Images Community Group (RICG)

**Общественная группа по адаптивным изображениям**

### rest parameters

**остаточные параметры,** (также _оставшиеся параметры_, разг. _рест-параметры_) синтаксис в JavaScript, позволяющий представить неименованные параметры функции в виде массива.

### root

**корень**

### rounded corners

**скруглённые углы,** напр. _rounded corners are out of fashion — скруглённые углы вышли из моды,_ см. также [скругление рамки](#border-radius).

### row

**строка, ряд**

- горизонтальная область в таблице или раскладке.
- элемент таблицы `<tr>`.

### rowspan

**объединение строк,** HTML-атрибут для объединения нескольких ячеек таблицы в одном столбце.

### rule-set

**блок стилей элемента,** состоит из селектора (или медиавыражения) и блока деклараций.

## S

### shallow comparison

**поверхностное сравнение,** сравнение, при котором проверяется, ссылаются ли две переменные на один и тот же объект в памяти.

### scaffolding

**скафо́лдинг,** автоматическая генерация кода по описанию, метод метапрограммирования.

### scale

1. сущ. **масштаб**
2. гл. **масштабировать**

### scope

**область видимости,** ограниченная часть программной структуры, в которой доступна объявленная переменная, либо применяются `<style scoped>` стили.

### screen reader

**скринри́дер,** программа, озвучивающая информацию с экрана устройства, один из видов вспомогательных технологий. Их используют зрячие люди, которым проще воспринимать информацию на слух, люди с дислексией, слепые или слабовидящие. Напр. _they use screen reader to navigate the web_ — _для навигации в сети они используют скринридер_, _screen reader will say “image cat”_ — _скринридер прочитает «изображение кошка»_.

### script

**скрипт,** инструкции, описывающие поведение страниц, напр. _scripts are not loaded yet — скрипты пока не подгрузились._

### scroll

1. **прокрутка,** элемент интерфейса для перемещения скрытой части страницы или блока, является признаком того, что вложенный элемент больше родительского, напр. _horizontal scroll is disabled — горизонтальная прокрутка запрещена._
2. **прокручивать,** перемещать скрытую часть страницы или блока.

### scrollbar

**полоса прокрутки,** формальное название [прокрутки](#scroll), напр. _system scrollbars — системные полосы прокрутки._

### sectioning roots

**структурные основы**

### semantics

**семантика,** смысловая нагрузка HTML-элементов, напр. _semantic coding — семантическая вёрстка._

### selector

**селектор,** необходимая структурная часть [блока стилей](#rule-set). Отвечает за привязку деклараций к элементам DOM.

- simple selector — **простой селектор,** может быть [псевдоклассом](#pseudo-class) или одним из следующих типов:
  - type selector — **селектор по типу,** обращается к тегу, напр. `ul`, `input` и др.
  - universal selector — **универсальный селектор,** «звездочка»: `*`.
  - ID selector — **селектор по идентификатору,** напр. `#content`.
  - class selector — **селектор по классу,** напр. `.item`.
  - attribute selector — **селектор по атрибуту,** напр. `[type=submit]`.
- compound selector (др. sequence of simple selectors) — **составной селектор,** цепочка простых селекторов, не разделенных комбинаторами, напр. `input[type=submit]:focus`.
- complex selector — **сложный селектор,** несколько простых и/или составных селекторов, разделенных комбинаторами:
  - descendant selector — **селектор потомка,** напр. `ul li`.
  - child selector — **селектор непосредственного потомка,** напр. `#buttons > *`. Также часто называется **дочерним**.
  - adjacent sibling selector — **селектор непосредственного соседства,** напр. `.item + .item`. Также часто называется **соседским**.
  - general sibling selector — **селектор соседства,** напр. `.item ~ .item`.

### server-side

**серверсайд,** область технологий, работающих на сервере, часто синоним [бэкенда](#back-end).

### shadow DOM

**теневой DOM, теневая модель документа**

### shapes

**фигуры, CSS-фигуры**

### shared

1. прил. **разделяемый,** напр. _shared memory — разделяемая память_
2. прил. **общий,** напр. _shared folder — общая папка_, _shared access — общий доступ_

### shim

**шим,** код, помогающий унифицировать работу с браузерами, обычно реализует недостающую или нормализует существующую поддержку, напр. _HTML5 shim for IE8 — HTML5-шим для IE8._

### sibling

**сосед** (в знач. «соседний элемент»).

### sidebar

**боковая панель,** боковая часть сайта со второстепенным содержимым, напр. _sidebar is on the right side — справа находится боковая панель._

### skew

1. сущ. **наклон**
2. гл. **наклонять**

### source maps

**карты кода,** специальная разметка, позволяющая привести в соответствие исходные файлы и скомпилированный код для отладки.

### specification, spec

**спецификация,** документация по технологии для разработчиков и производителей браузеров, обычно в одном из статусов: от предложенной до утверждённой W3C, напр. _specification draft — черновик спецификации._

### spread

**расширение,** оператор в JavaScript, расширяющий выражения в тех местах, где предусмотрено использование нескольких аргументов при вызовах функций `doSomething(...array)`, ожидается несколько элементов в массивах `[1, 2, ...array]`) и добавление или перезапись полей в объектах `{ ...object, field: 'value' }`.

### specificity

**специфичность,** характеристика [CSS-селектора](#selector), определяющая его приоритет [в каскаде](#cascade). Складывается из веса каждого [простого селектора](#selector) в его составе.

### stacking context

**контекст наложения,** элемент визуальной структуры страницы, ограничивающий действие свойства `z-index` его потомков и размещаемый по оси _z_ как единое целое (либо целиком поверх, либо целиком под любым другим элементом). Напр. _elements with opacity create new stacking context — элементы с полупрозрачностью образуют новый контекст наложения._

### staging server

**отладочный сервер,** сервер, на котором продукт проходит тестирование и отладку.

### standards mode, standards compliance mode

**стандартный режим,** режим интерпретации и отображения страницы браузером, в котором браузер обязан максимально полно соблюдать стандарты, насколько может. Используется для страниц с более-менее современными [доктайпами](#doctype), напр. доктайпом HTML5.

### statement

**объявление,** структурный элемент CSS. Это может быть блок стилей элемента, директива импорта, медиавыражение и т.д.

### string

1. **строковый тип,** в программировании — тип данных, значениями которого является произвольная последовательность (строка) символов алфавита.
2. **строка,** в CSS — строковое значение директивы или свойства. Напр., в `content: "\201d"` строкой является `"\201d"`.

### stub object

**заглушка**

### style

1. сущ. **стили,** напр. _apply styles to an element — применить стили к элементу,_ мн.ч. предпочтительнее: _стили элемента,_ а не _стиль элемента_ (неправильно).
2. гл. **оформлять,** напр. _how to style selects — как оформить селекты,_ предпочтительнее, чем двусмысленное «стилизовать».

### style guide

**руководство по стилю,** напр. _project code style guide — руководство по стилю кода проекта_.

### stylesheet

**таблица стилей,** напр. _таблица стилей документа_.

### swipe

**смахивание,** жест для управления сенсорным интерфейсом: смахивающее движение пальцев по сенсорному экрану.

### submit

**отправка,** напр. _отправка формы_.

## T

### tab

1. **вкладка,** один из слоёв интерфейса сайта или программы, который активируется выбором его заголовка, напр. _open in new tab — открыть в новой вкладке._
2. **таб,** клавиша табуляции, вставляет символ табуляции, переключает фокус на следующий элемент интерфейса, либо дополняет частично набранное слово, напр. _press Ctrl Tab — нажмите контрол-таб._
3. **таб,** символ табуляции, имеет настраиваемую ширину и используется для отступов в коде, напр. _tabs are better than spaces — табы лучше пробелов._

### tag

1. **тег,** обозначение элемента в HTML, существуют открывающие, закрывающие и одиночные теги. Напр. _закрывающий тег отсутствует — closing tag is missing._
 - tag name — **название тега**
 - start tag — **открывающий тег**
 - end tag — **закрывающий тег**
2. **метка,** маркер содержимого, обычно короткое слово.

### tap

**нажатие,** жест для управления сенсорным интерфейсом: однократное касание сенсорного экрана.

### text

**текст**

### textarea

**текстовая область,** элемент формы для ввода многострочного текста.

### text-align

**выравнивание, вы́ключка,** ориентация строк текста в определённом направлении, либо равномерно по ширине блока.

- text-align: left — **влево**
- text-align: right — **вправо**
- text-align: justify — **по ширине**

### text-shadow

**тень (текста),** напр. _text-shadow is red — тень текста красная._

### throttling

**тротлинг,** введение искусственных ограничений, например, для уменьшения частоты вызовов обработчиков событий в JavaScript или скорости сети и мощности ЦП при тестировании.

### thumb

1. Сокращение от [thumbnail](#thumbnail).
2. **ползунок,** элемент управления [полосой прокрутки](#scrollbar).

### thumbnail

**миниатюра,** уменьшенная копия изображения.

### title

1. **заголовок,** если речь идёт об элементе `<title>`, либо о заглавии элемента.
2. **подсказка,** если речь идёт об атрибуте `title=""`.

### toggle

**переключать,** переводить из одного состояния в другое, _переключить классы — toggle classes._

### tooltip

**всплывающая подсказка,** вспомогательная информация, появляющаяся при наведении на элемент или при его активации, в частности `title=""`.

### touch interface

**сенсорный интерфейс**

### transform

**трансформация,** напр. _transform: scale(2) — трансформация масштабированием в 2 раза._

### transition

**переход,** напр. _transition: all 2s linear — линейный переход длительностью 2 секунды._

### translate

**перемещать,** перемещение объекта с помощью CSS-трансформации, напр. _translate(x, y) — перемещение на X и Y._

### transpiler

**транспилер,** компилятор, преобразующий исходный код на одном яз. программирования в исходный код на другом яз. программирования.

### typography

**типографика,** оформление текста с помощью выбора гарнитуры, параметров строки и других.

## U

### unit

**единица изменения,** напр. _rem unit — единица измерения «рем»._

### unit testing

**модульное тестирование**

### URI

**унифицированный идентификатор ресурса,** последовательность символов, идентифицирующая абстрактный или физический ресурс.

### URL

1. _разг._ **адрес**. Значение рекомендовано к использованию при переводах статей.

2. **унифицированный указатель ресурса,** [URI](#uri), который предоставляет ещё и информацию о местонахождении этого ресурса, напр. _background: url("http://www.example.com/picture.png")_

### user experience (UX)

**пользовательский опыт,** совокупность ощущений от взаимодействия с чем-л. (интерфейсом, девайсом, продуктом). В контексте области знаний рекомендуется употреблять аббревиатуру UX (напр., _UX-специалист_).

### user interface (UI)

**пользовательский интерфейс,** в прозрачном контексте рекомендуется употреблять просто «интерфейс».

### utility

**утили́та,** программа с узким назначением.

## V

### valid

**валидный,** соответствующий стандарту, спецификации или другому нормативу, напр. _valid markup — валидная разметка_.

### validator

**валидатор,** средство проверки соответствия стандарту, спецификации или другому нормативу (см. [valid](#valid)), напр. _W3C markup validator — валидатор разметки W3C_.

### value

**значение,** напр. _значение CSS-свойства_.

### variable units

**переменные единицы измерения,** — кастомные свойства, которые можно использовать как единицы измерения в CSS. Допустимо использование в сокращённом виде, без слова «измерения», напр. _variable units make this easier to write — переменные единицы делают эту запись проще._

### vendor prefix

**бра́узерный пре́фикс,** приставка к CSS-свойству `-webkit-` или `-moz-`, напр. _add vendor prefixes — добавьте браузерные префиксы._

### vendor files

**сторонние файлы,** стили, скрипты и другие ресурсы (зависимости) других авторов, использующиеся в проекте, напр. _tons of vendor scripts included in the code — куча сторонних скриптов подключены в коде._

### vertical-align

**вертикальное выравнивание,** расположение элементов по вертикали в пределах строки текста или таблицы.

### viewport

**вьюпо́рт**

1. видимая область документа в рамках экрана.
2. элемент `<meta name="viewport">`, управляющий адаптацией страниц на мобильных устройствах.

## W

### website, web site

**сайт,** объединённые под одним адресом страницы, перевод «веб-сайт» избыточен.

### worker

**воркер,** интерфейс в JavaScript, позволяющий выполнить скрипт не в основном потоке.

- web worker — **веб-воркер**
- service worker — **сервис-воркер**
- shared worker — **общий воркер**

### working draft (WD)

**рабочий черновик,** ранний статус спецификации [W3C](#world-wide-web-consortium-w3c).

### worklet

**во́рклет,** класс в JavaScript, обладающий заранее известными методами с определённой сигнатурой, дающий доступ к различным браузерным API. [Проект Гудини](https://github.com/w3c/css-houdini-drafts/wiki) предусматривает следующие виды ворклетов:

- paint worklet — **ворклет отрисовки**
- compositor worklet — **ворклет композитинга**
- layout worklet — **ворклет раскладки**

### World Wide Web Consortium (W3C)

**Консорциум всемирной сети,** организация, разрабатывающая веб-стандарты. Переводить «web» как «паутину» в XXI веке уже смешно.

### web standards

**веб-стандарты**

### width

**ширина**

### word-spacing

**межсловный пробел**

### workaround

**обходное решение (приём),** способ решения задачи в ограниченных условиях, напр. _to figure out workaround — придумать обходной приём._
