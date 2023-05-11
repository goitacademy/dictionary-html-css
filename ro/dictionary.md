# Glosar de termeni frontend

Cuprins: [0-9](#0-9) [A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) J [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) X Y Z

## 0-9

### 9-slice scaling

**9-slice scaling** (scalare fără distorsiuni), o tehnică care permite redimensionarea obiectului fără distorsiuni geometrice. Obiectul este împărțit în 9 părți (3 rânduri și 3 coloane), fiecare dintre acestea fiind redimensionată în funcție de propriile reguli: colțurile nu sunt deloc redimensionate, partea centrală este redimensionată în înălțime și lățime, iar restul părților sunt redimensionate fie numai în lățime, fie numai în înălțime.

## A

### accessibility, a11y

**accesibilitate,** capacitatea de utilizare a interfeței de oricine, indiferent de restricțiile fizice sau tehnice.

### adaptive design

**design adaptiv**, abordare a web designului care ia în considerare adaptarea la diferite dispozitive și medii, spre deosebire de designul obișnuit "fix", destinat exclusiv calculatoarelor. O modalitate de a crea design adaptiv este prin tehnici de [responsive design](#responsive-design).

### almost standards mode

**mod aproape standard,** mod de interpretare și afișare a unei pagini de către browser, în care browserul se abate în mod deliberat de la standarde (ca în [compatibility mode](#quirks-mode)) numai pentru anumite cazuri speciale, utilizat pentru paginile de tranziție cu [doctype](#doctype) HTML 4 și XHTML 1.

### anchor

1. **link,** hyperlink între două documente.
2. **ancoră,** referință la un element dintr-un document, poate face parte dintr-un hyperlink.

### animation

**animație,** schimbare lină a parametrilor vizuali ai unui obiect.

### asset

**resursă,** parte componentă a unui site: fișiere text, grafică, video, baze de date, etc. În sens restrâns, o "resursă statică": stiluri, scripturi, grafică de design, spre deosebire de conținutul dinamic.

### assert

**verificare,** condiție, care este verificată, utilizată în testare, de ex. _field assert has failed — verificarea câmpului a eșuat._

### at-keyword

**cheia directivei,** vezi [directivă](#at-rule).

### at-rule

**directivă,** tip de [declarație](#statement) care începe cu un semn `@`, de ex. _@import_.

### attribute

**atribut,** de ex. `rel="stylesheet"`

- attribute name — **nume atribut**
- attribute value — **valoare atribut**

## B

### back-end

**back-end**

1. zonă a tehnologiei web care rulează pe un server.
2. partea internă a sistemului serverului, care se ocupă de prelucrarea datelor.

### background

**fundal,** de ex. _background image — imagine de fundal._

- background-color — **culoare fundal**
- background-position — **poziționare fundal**
- background-size — **dimensiune fundal**
- background-repeat — **repetare fundal**
- background-origin — **graniță fundal**
- background-clip — **decupare fundal**
- background-attachment — **fixare fundal**
- background-image — **imagine de fundal**

### baseline

**linie de bază,** linie imaginară la baza literelor unui șir.

### bikeshed

**a acorda o atenție excesivă banalităților,** (vezi [legea banalității](https://en.wikipedia.org/wiki/Law_of_triviality). Nu există un echivalent stabilit în limba română, este mai bine să se traducă sensul general, de ex. _avoid bikeshedding — nu vă certați din fleacuri._

### blending mode

**mod de amestecare,** algoritm de amestecare a layerelor utilizat în editorii grafici sau direct în CSS, de ex. _overlay blending mode — mod de amestecare prin suprapunere._

### block
1. **bloc de declarații,** parte structurală a [declarației](#statement). Cuprinsă între acolade, care conține declarații cu proprietăți (sau, în cazul unei media query, blocuri de stil).
2. **aspect de bloc,** vezi [afișare](#display).

### blockquote

**blockquote,** element HTML pentru evidențierea secțiunii fără ghilimele a unui document. Poate conține un atribut `cite` cu o legătură către sursa originală.

### border

**chenar,** partea exterioară vizibilă a blocului, de ex. _border-left — chenar din stânga._

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

**rotunjire chenar,** de ex. _border-radius: 3px — rotunjirea chenarului cu 3 px, border-top-left-radius — rotunjirea colțului din stânga sus_, vezi și [rotunjire colțuri](#rounded-corners).

### bounding box

**bounding box**

### box model

**box model,** sistem dimensional de blocuri, format din conținut, margine, chenar și padding.

### box-shadow

**umbră (bloc),** de ex. _box-shadow is red — umbra blocului este roșie._

### breadcrumbs

**breadcrumbs,** navigare auxiliară pe site, care indică în mod succesiv structura sau pașii parcurși de utilizator.

### breakpoint

1. **breakpoint, punct de rupere,** una dintre traducerile utilizate de obicei, sensul exact fiind clar din context.
2. **punct de oprire,** o linie din cod la care execuția scriptului este întreruptă pentru a apela debuggerul.
3. **punct de control,** condiția în care aspectul site-ului se schimbă din unul în altul. Tipic pentru expresiile media.

### browser

**browser**

### button

**buton**

1. element de interfață, la apăsarea căruia este trimis un formular sau se face o altă acțiune.
2. element de formular `<button>` sau `<input type="button">` (de asemenea `submit` și `image`).

## C

### callback

**callback,** executarea codului atunci când funcția este terminată, de ex. _pass value in a callback — transmite valoarea într-un callback._

### candidate recommendation (CR)

**candidat la recomandare,** statutul specificației [W3C](#world-wide-web-consortium-w3c), o opțiune posibilă pentru [recomandarea propusă](#proposed-recommendation-pr).

### cascade

### cascade

**cascadă,** algoritm descris în specificația CSS care definește modul în care blocurile de stil sunt aplicate unui element.

### cascade layer

**layer în cascadă,** modalitate de a grupa și de a controla ordinea în care sunt aplicate stilurile în cadrul unei singure [surse](#cascade-origin), declarată cu ajutorul [directivei](#at-rule) `@layer`. De ex. _rules within a cascade layer cascade together_ — _regulile din cadrul layerelor în cascadă se aplică în cascadă la un loc._

### cascade origin

**sursă în cascadă,** zonă de descriere a stilurilor încorporată în browsere, ordinea surselor determină aplicarea stilurilor sau [cascada](#cascade): de la stilurile browserului la transition-property. De ex. _there are eight cascade origings, including user styles_ — _există opt surse în cascadă, inclusiv stilurile utilizatorului._

### cell

**celulă**

1. unitate structurală a tabelului.
2. element al tabelului `<td>` sau `<th>`.

### cellpadding

**padding în celulele** tabelului.

### cellspacing

**distanța între celulele** tabelului.

### character reference

**entități,** de ex. `&nbsp;`. De asemenea, se acceptă o traducere nu complet exactă, dar mai bine cunoscută **simboluri speciale.**

### checkbox

**checkbox**

1. element de interfață pentru selectarea uneia sau mai multor opțiuni, de ex. _checkbox is disabled — checkbox dezactivat._
2. element de formular `<input type="checkbox">`.

### child

1. substantiv **copil,** (plural children — **copii**)
2. adjectiv **copil,** de ex. _child process — proces copil_

### classitis

**classitis,** boală inventată, caracterizată prin utilizarea excesivă a mai multor clase: atât pentru proiectare, cât și pentru stocarea informațiilor.

### clear

**clear,** proprietate CSS care setează dacă un bloc trebuie să fie mutat sub blocurile plutitoare care îl preced. 

- clear: left — **bloc împins sub blocurile plutitoare din stânga**
- clear: right — **bloc împins sub blocurile plutitoare din dreapta**
- clear: both — **bloc împins sub toate blocurile plutitoare**

### clearfix

**clearfix,** metodă pentru a împiedica colapsul containerelor cu blocuri plutitoare. Aceasta constă în crearea unui spațiu special care este plasat după blocurile plutitoare și care anulează deplasarea acestora.

### click

**click,** apăsarea pe obiect cu cursorul mouse-ului sau cu un dispozitiv similar, de ex. _double click is firing event — dublu click declanșează evenimentul._

### client-side

**client-side,** domeniul tehnologiei bazate pe browser, adesea sinonim cu [front-end](#front-end).

### clipping path

**imagine decupată**

### closure

**closure,** funcție care conține în corpul său referințe către variabilele declarate în codul înconjurător.

### code

1. substantiv **cod,** fără plural, (ca soare), de ex. _error in code — eroare în cod,_ dar nu _eroare în coduri (greșit)._
2. verb **a scrie cod, a programa,** de ex. _to code a site — a scrie codul unui site._

### colspan

**combinare coloane,** atribut HTML pentru combinarea mai multor celule de tabel într-o singură coloană.

### column

**coloană,** zonă verticală într-un tabel, layout sau text.

### color

**culoare**

### combinator

**combinator,** caracter special utilizat într-un selector complex pentru a specifica cu precizie combinații de elemente DOM, de ex. `>`, `+` și altele. Un spațiu între selectori este considerat, de asemenea, un combinator.

- descendant combinator — **combinator descendent,** ` ` (spațiu).
- child combinator — **combinator copil** `>`. Mai este numit **apropiat**.
- adjacent sibling combinator — **combinator direct al vecinului,** `+`.
- general sibling combinator — **combinator vecin,** `~`.

### comment

**comentariu,** explicație a codului.

### component

**componentă,** parte constitutivă a ceva. De ex. _app components_ — _componentele unei aplicații._

### compositing

**compositing**

### composite layer

**layer compozit**

### compositor

**compozitor** (adică "motor de compoziție")

### container query

**interogare a containerului,** declarație a directivei `@container` cu condiții, care permite aplicarea stilurilor în funcție de proprietățile containerului _părinte_. De ex. _many container query cases can be solved with existing technology_ — _în numeroase cazuri, tehnologia existentă poate fi utilizată în locul interogărilor containerului._
### containing block

**bloc de conținut** — bloc în raport cu care se calculează dimensiunile și pozițiile acestui bloc.  În termeni simpli, un bloc de conținut este părintele unui anumit bloc, nu conform DOM, ci conform fluxului documentului. De ex. _containing block isn’t always the content area of the parent_ — _blocul de conținut — nu este întotdeauna zona de conținut a părintelui._

### content

**conținut**

- metadata content — **meta conținut**
- flow content — **conținut de flux**
- sectioning content — **conținut de structură**
- heading content — **conținut de titluri**
- phrasing content — **conținut de text**
- embedded content — **conținut încorporat**
- interactive content — **conținut interactiv**
- palpable content — **conținut de ieșire**
- script-supporting content — **conținut de scripturi**
- grouping content — **conținut de grupare**

### continuous integration

**integrare continuă,** practică de asamblare, testare și implementare frecventă și automatizată a software-ului.

### cookie

**cookie,** un fragment scurt de date care este trimis de server și stocat în browser.

- access to cookies — **acces la cookies**
- cookies banner — **mesaj despre cookies**
- authorization cookies — **cookies de autorizare**
- first-party cookies — **cookies prima parte**
- third-party cookies — **cookies terță parte**

### cross-browser

**cross-browser,** funcționează în toate browserele.

### cross-platform

**cross-platform,** funcționează pe toate paltformele.

### custom properties

**proprietăți personalizate,** proprietăți CSS de tip `--my-property`, pe care dezvoltatorii le pot de sine stătător și le pot utiliza mai departe în cod ca variabile prin intermediul funcției `var()`. De asemenea, cunoscute ca **variabile CSS,** de ex. _CSS variables, also known as CSS custom properties, are landing in Chrome 49 — variabilele CSS, cunoscute și sub numele de proprietăți personalizate CSS, vor apărea în Chrome 49_.

### CSS Working Group (CSSWG)

**Grupul director CSS**

### custom

**custom** (variantă de traducere, **personalizat**)

- custom element — **element personalizat**
- custom attribute — **atribut personalizat**

## D

### data binding

**date legate,** sincronizarea automată a datelor între două entități, de obicei un model și o vizualizare.

### declaration

**declarație,** declarația de proprietate și de valoare.

### deep comparison

**comparație profundă,** comparația a două obiecte, comparând structura obiectelor și verificând egalitatea primitivelor conținute în obiecte.

### deploy, deployment

**deploy, implementare,** publicarea modificărilor fie direct pe un server public (producție), fie prin intermediul sistemelor intermediare și al proceselor automate de compilare.

### deprecated

**dezaprobat,** statutul unei caracteristici de limbaj a cărei utilizare nu se recomandă, întrucât deja _a fost înlocuită, eliminată_ sau _va fi_ în versiunile viitoare, de ex. _this API is a replacement of the deprecated `React.addons.cloneWithProps()` — acest API este un înlocuitor al unuia învechit `React.addons.cloneWithProps()`_ sau _`<applet>` is deprecated in favor of `<object>` — `<applet>` este dezaprobat în favoarea lui `<object>`._

### design

1. substantiv **design,** aspectul vizual al site-ului, poate încorpora principii de interacțiune și soluții de arhitectură, de ex. _new design for a site — un nou design pentru site._
2. verb **a dezvolta,** a crea sau proiecta aspectul și funcționalitatea site-ului.

### device pixel ratio

vezi [pixel ratio](#pixel-ratio)

### dirty checking

**verificare privind proprietățile "murdare" ale obiectului,** adică [comparație profundă](#deep-comparison) a proprietăților unui model care declanșează un [callback](#callback), dacă ceva s-a schimbat.

### disable

**dezactivare**

### disabled

**dezactivat,** starea unui element de formular care nu poate fi modificat, de ex. _disabled button — buton dezactivat._

### display

1. **afișare,** proprietate CSS, care definește tipul de afișare a blocurilor.

 - display: none — **afișare ascunsă**
 - display: block — **afișare de tip block**
 - display: inline — **afișare de tip inline**
 - display: inline-block — **afișare de tip inline-block**

- display: flex — **afișare de tip flex** (vezi [flexbox](#flexbox))
- display: inline-flex — **afișare de tip inline-flex** (vezi [flexbox](#flexbox))

2. **ecran,** de ex. _ecranul smartphone-ului, rezoluția ecranului._

### divitis

**divitis,** boală inventată, caracterizată prin utilizarea numai a elementelor `<div>` în locul celor potrivite din punct de vedere [semantic](#semantics).

### DOM

**modelul orientat-obiect**

### doctype

**doctype,** formulare de tip `<DOCTYPE html>` la începutul unui document, care indică versiunea HTML utilizată. Se folosește de browsere pentru a selecta unul din moduri ([standard](#standards-mode-standards-compliance-mode), [aproape standard](#almost-standards-mode) sau [compatibil](#quirks-mode)).

### dropdown

**meniu derulant** element de interfață care afișează informații suplimentare atunci când este activat.


## E

### easing

**easing, funcția easing,** descrie modificarea vitezei animației cu ajutorul cuvintelor cheie sau a curbei Bézier, de ex. _transition easing is linear — tranziție liniară._

### editor’s draft (ED)

**editor’s draft,** document preliminar al specificației [W3C](#world-wide-web-consortium-w3c), sugerat de unul dintre editori. În baza unui editor’s draft poate fi elaborat un [working draft](#working-draft-wd).

### element

**element**

- void elements — **elemente goale**
- raw text elements — **elemente de text liber**
- escapable raw text elements — **elemente de text liber escapable**
- foreign elements — **elemente străine**
- normal elements — **elemente obișnuite**

### em

**em,** unitate de măsură în CSS care depinde de dimensiunea fontului părinte, de ex. _font-size: 3em — dimensiunea fontului 3em._

### enable

**activare**

### enabled

**activat,** starea unui element de formular care poate fi modificat, de ex. _enabled button — buton activat._

### engine

**motor,** de ex. _Safari is based on WebKit engine — Safari se bazează pe motorul WebKit._

## F

### fallback

**fallback,** implementare suplimentară/de rezervă în cazul în care browserul nu dispune de caracteristici, precum scripturi activate sau video codec-uri necesare, de ex. _fallback to a link — fallback către un link._

### favicon

**favicon,** de obicei o iconiță de 16x16 pixeli în format ICO.

### feature query

**directivă `@suppórts`,** construcție condițională care permite aplicarea selectivă a stilurilor în funcție de proprietățile acceptate de browser.

### fieldset

**fieldset,** element care combină mai multe câmpuri de formular, de ex. _green border on a fieldset — chenar verde pe fieldset._

### figure

**figură,** element din HTML5, care conține o imagine, video, tabel, grafic sau un fragment de cod.

### figcaption

**titlu figură,** titlul sau legenda unei figuri.

### filter

**filtru**

- filter: brightness — **luminozitate**
- filter: contrast — **contrast**
- filter: grayscale — **tonuri de gri**
- filter: sepia — **sepia**
- filter: invert — **inversare**
- filter: saturate — **saturație**
- filter: hue-rotate — **rotire culoare**
- filter: blur — **estompare**
- filter: opacity — **opacitate**
- filter: drop-shadow — **umbră**

### flash of…

- flash of unstyled text, FOUT — **afișare text fără stiluri,** afișarea textului în fontul de sistem înainte de a încărca fontul web.
- flash of invisible text, FOIT — **afișare text invizibil,** lipsa textului pe pagină înainte de încărcarea fonturilor web.
- flash of faux text, FOFT — **afișare text sintetizat,** afișarea unui font de bază modificat înainte de a încărca fonturile necesare.

### flexbox

**flexbox,** mecanism de [layout](#layout).

- flex container — **container de tip flex**
- flex item — **element de tip flex**
- flex-direction — **direcția axei principale**
- flex-wrap — **transferul elementului de tip flex,** determină dacă containerul este inline sau multiline
- flex-basis — **dimensiunea de bază** a elementului flex pe axa principală
- flex-grow — **coeficient de întindere**
- flex-shrink — **coeficient de compresie**
- main axis — **axa principală,** direcția în care elementele flex se succed în container
- cross axis — **axa transversală,** direcția perpendiculară pe axa principală 
- main size — **dimensiunea principală,** dimensiunea elementului de tip flex în direcția principală
- cross size — **dimensiunea transversală,** dimensiunea elementului de tip flex în direcția transversală
- justify-content — **distribuția elementelor de tip flex** pe direcția principală
- align-items — **alinierea elementelor de tip flex** pe direcția transversală
- align-self — **alinierea elementelor de tip flex** pe axa transversală
- align-content — **alinierea rândurilor** containerului pe axa transversală
- order — **numărul de ordine** al elementului de tip flex

### float

1. adjectiv **plutitor,** proprietate a unui bloc care determină blocurile următoare să "curgă" în jurul acestuia, de ex. _float layout — layout pentru blocuri plutitoare._
2. verb **a curge,** urmează îndeaproape blocul plutitor, de ex. _text is floating to the right — textul curge spre dreapta._
3. verb **a presa,** presare la dreapta sau la stânga, de obicei din cauza proprietăților de plutire, de ex. _float block to the left — presează blocul în stânga._

### font

**font**

- font-weight — **saturație**

  - font-weight: normal — **normal**
  - font-weight: bold — **îngroșat** sau **semi-îngroșat**
  - font-weight: bolder — **mai gros**
  - font-weight: lighter — **mai subțire**

- font-style — **stiluri font**

  - font-style: normal — **normal**
  - font-style: italic — **înclinat**
  - font-style: oblique — **oblic**

- font-size — **dimensiune font, unitate**

- font-family — **familie font, garnitură**

  - font-family: serif — **сu serifuri**
  - font-family: sans-serif — **fără serifuri**
  - font-family: monospace — **monospace**

### footer

**subsol**

1. zonă vizuală, de obicei la sfârșitul paginii.
2. elementul `<footer>` — parte cu informații meta.

### formatting context

**context de formatare,** în CSS — zonă în care elementele paginii (text, blocuri, celule etc.) sunt aliniate în conformitate cu anumite reguli.

- block formatting context, BFC — **context de formatare a blocurilor, BFC** (de ex. _element with `overflow` establishes the new BFC — elementul cu `oveflow` creează un nou BFC_)
- grid formatting context — **context de formatare a gridurilor** (vezi [grid layout](#grid-layout))
- flexbox formatting context — **context de formatare a flexbox** (vezi [flexbox](#flexbox))
- inline formatting context — **context de formatare inline**
- table formatting context — **context de formatare tabel**

### forced color mode

**mod de culoare forțat,** în care o culoare specificată de dezvoltator este schimbată forțat într-o culoare de sistem sau specificată de utilizator, cel mai des pentru a crește contrastul și a face conținutul mai accesibil persoanelor cu deficiențe de vedere.

### fragment identifier

**identificator de fragment,** text după `#` în URL, care permite trimiterea la o anumită parte a unui document. Folosit mai ales în specificații și SVG, este cunoscut sub termenul HTML [ancoră](#anchor).

### framework

**framework,** un set de biblioteci și componente pentru a simplifica dezvoltarea. De regulă, reprezintă frame-ul de bază pentru un produs. De ex. _[Twitter Bootstrap](http://getbootstrap.com/)._

### front-end

**front-end**

1. domeniu al tehnologiei de dezvoltare a interfețelor web, care cuprinde instrumente și tehnologii auxiliare care funcționează în browser sau pe partea clientului(#client-side). 
2. partea exterioară a sistemului server, care răspunde de primirea datelor, trimiterea răspunsurilor și generarea codului pentru browser, este inclusă în partea server(#server-side).

### full screen

**modul full screen,** comportamentul programului sau al părții acestuia,  atunci când ocupă întregul ecran.

### fullstack

**fullstack**

1. domeniu de specializare care include [front-end](#front-end) și [backend](#back-end).
2. un specialist, care poate fi responsabil de toate aspectele unui proiect, de la partea client până la partea server.

De ex. _Andrei a studiat bazele de date și a înlocuit în CV "specialist front-end" cu "specialist fullstack"._

### function

**funcție**

1. în programare — fragment de cod denumit al unui program (subprogram) care poate fi accesat din altă parte a programului.
2. în CSS — poate fi prezentă într-o [declarație](#declaration) în poziția valorii. De ex. `url(img/gradient.png)`.

## G

### generated content

**conținut generat,** parte a documentului creată cu ajutorul CSS, un [pseudo-element](#pseudo-element) și proprietatea `content`. 

### graceful degradation

**degradare treptată**, abordare prin care interfața site-ului este redusă pentru browserele mai vechi, în cazul în care unele dintre tehnologiile utilizate nu sunt acceptate. În același timp, daunele aduse utilizatorului sunt atenuate ori de câte ori este posibil. De exemplu: culoare în loc de gradient, grafică bitmap în loc de grafică vectorială, redare video cu un plugin.

### gradient

**gradient,** tranziție moale de la o culoare la alta.

- linear gradient — **gradient liniar**
- radial gradient — **gradient radial**
- conical gradient — **gradient conic**

### grid

1. **rețea,** mod de a ordona layout-ul elementelor într-un design prin intermediul unui ritm vertical sau orizontal, de ex. _module grid — grid modular._
2. **grid,** rețea bidimensională formată din rânduri și coloane într-un [grid layout](#grid-layout).

### **grid layout**

**grid layout,** mecanism de [layout](#layout), care aranjează elementele într-o rețea bidimensională — [grid](#grid) (2).

- **grid container** — _grid container_
- **grid item** — _grid item_
- **grid track** — _grid track_, un termen colectiv pentru rândurile și coloanele _gridului_
- **grid cell** — _grid tcell_
- **grid line** — _grid line_, o limită virtuală între _grid track_ vecine, la care pot fi legate _elemente grid_
- **grid area** — _grid area_, spațiu de plasare a _elementelor grid_, limitat de patru _grid track_
- **grid gutter** — _grid gutter_, distanța dintre _grid track_ vecine

## H

### header

**antet**

1. zonă vizuală, de obicei la începutul paginii.
2. elementul `<header>` — parte semantică de titlu.


### height

**înălțime**

## I

### icon font

**icon font,** font sintetic care conține iconițe și alte imagini vectoriale, de exemplu pentru web design. _build an icon font — creează un icon font._

### immutable

**imuabil, neschimbat,** termenul se aplică cel mai des datelor (tipurilor de date) în programarea funcțională.

### implement

**implementa** ex. _Firefox has implemented support of everything — Firefox a implementat suportul pentru orice._

### inline

1. **inline,** având proprietăți inline.

 - inline block — **bloc inline**
 - inline box — **container inline** în formatarea inline: parte a umpluturii containerului de linii, la care se aplică direct regulile CSS, de ex. _anonymous inline box — element anonim al liniei_
 - inline element — **element inline**

2. **încorporat**, situat în interiorul unei linii de cod.

 - inline styles — **stiluri încorporate**
 - inline SVG — **SVG încorporat**
 - inline script — **script încorporat**

### input

**element de formular,** care asigură interacțiunea dintre utilizator și interfață, de ex. câmp textual, buton, comutator.

### intrinsic dimensions

**dimensiunile proprii ale elementului,** lățimea și înălțimea, sunt determinate de elementul însuși, nu de mediu. CSS nu poate specifica modul în care sunt calculate dimensiunile proprii. Doar elementele care se pot înlocui pot avea dimensiuni proprii, de ex.: imagini, video, audio și alte blocuri, prezentarea cărora nu depinde de dezvoltator.

### internationalization, i18n

**internaționalizare,** proces de proiectare și dezvoltare a interfeței care permite [localizarea](#localization-l10n) pentru diferite regiuni (diferite culturi sau limbi) fără modificări tehnice, de ex., _`Intl.DateTimeFormat` — constructor de clasă, care permite formatarea datei și a orei în funcție de cele locale._

### interoperability

**interoperabilitate**

## K

### kerning

**kerning,** distanța dintre perechile de litere, ținând cont de forma acestora pentru o scriere mai uniformă.

### keyframe

**keyframe,** unul dintre punctele de animație date, între care schimbările se produc automat.

### keyframe animation

**animație keyframe,** modalitate de a seta animația în CSS folosind keyframe-uri.

### keyword

**cuvânt cheie**

## L

### label

**etichetă,** stabilește o legătură între un anumit element și un element de formular.

### last call (LC)

**last call,** statutul specificației [W3C](#world-wide-web-consortium-w3c) pentru ultimele modificări înainte de [statutul de candidat la recomandare](#candidate-recommendation-cr) _(anulat în anul 2014, se întâlnește doar în specificațiile mai vechi)_.

### layout

**layout,** aranjarea blocurilor principale din pagină, de ex. _3 columns layout — layout din 3 coloane._

### legend

**legendă,** antetul unui grup de elemente de formular, definit de [fieldset](#fieldset).

### length

**lungime**

### letter-spacing

**spațiere între litere, tracking,** distanța totală dintre literele unui text, a nu se încurca cu [kerning](#kerning).

### library

**bibliotecă,** set de soluții pentru a simplifica dezvoltarea. De regulă, o bibliotecă implementează o anumită funcție sau un set de funcții conexe, de ex. animația.

### line-box

**container linie** în formatarea liniei: un container virtual care conține toate elementele unei singure linii.

### line-height

**înălțimea liniei,** distanța dintre liniile de bază ale textului.

### list

**listă,** enumerare secvențială a unui grup de elemente.

- ordered list — **listă ordonată,** sortată în conformitate cu un anumit principiu.
- unordered list — **listă neordonată,** în care ordinea din listă nu este importantă.

### list-style

**stil listă**

### localization, l10n

**localizare,** proces de adaptare al interfeței la convențiile lingvistice și culturale ale unei anumite regiuni (țări, localizare), de ex. _`new Date().toLocaleDateString('en-US')` — convertește data în reprezentarea sa sub formă de șir de caractere, în conformitate cu localitatea SUA._

## M

### margin

**margine exterioară,** de ex. _margin-bottom: -10px — margine negativă de jos -10px._

### margin box

**margini exterioare a ceva**

### matrix

**matrice (de transformare),** descrierea transformării unui obiect cu ajutorul unei matrice.

### media query

**media query,** declarația directivei `@media` cu oarecare [condiții](#media-query-list), care permit aplicarea stilurilor în funcție de capacitățile dispozitivului. Variantă de traducere "interogare media" este mai puțin precisă.

### media query list

**condiții media query,** listă de condiții care definesc momentul în care se aplică declarațiile din directiva `@media`. De ex. `only screen and (min-width: 35em)`.

### media type

**media type (tip dispozitiv),** poate fi o condiție de exprimare a media query. Indică pentru ce moduri de ieșire sunt destinate stilurile (de ex. `screen` — pentru ecran, `print` — pentru tipărire, `speech` — pentru sintetizator de vorbire).

### media feature

**media feature (caracteristică a dispozitivului),** poate fi o condiție a unei interogări media. Definește o caracteristică a dispozitivului. De ex. `min-width`.

### mixin

**mixin,** set de proprietăți care extind comportamentul unei alte entități, se întâlnește în preprocesoarele CSS și în pattern-urile JavaScript, de ex. _mixin is clearing — mixin se curăță._


### mobile first

**mobile first,** abordare în dezvoltare care constă în conceperea unui serviciu care începe cu o versiune mobilă mai degrabă decât cu o versiune pe ecran mare. Termen introdus de Luke Wroblewski în [cartea cu același nume](https://abookapart.com/products/mobile-first).

### mock object

**mock obiect**

### mock-up

**mock-up,** aspectul sau designul unui site mai mult sau mai puțin detaliat, de ex. _designer has sent a page mock-up — designerul a trimis un mock-up al paginii._

### modal

1. adjectiv **modal,** blocarea interfeței pentru a efectua o acțiune, de ex. _modal window — fereastră modală._
2. substantiv **fereastră modală (dialog),** element de interfață, vezi _modal._

### multiple

**multiplu,** se repetă de două sau mai multe ori, de ex. _multiple backgrounds — mai multe fundaluri._

### multiple columns

1. **multi-coloane,** mecanism CSS care permite alinierea textului în mai multe coloane, de ex. _multiple columns support in IE — suport pentru mai multe coloane în IE._ Mai comod decât "coloane multiple".
2. **multi-coloane,** format din mai multe coloane, de ex. _multiple columns layout — layout multi-coloane._

## N

### nested

**imbricat,** a fi în interiorul a ceva, de ex. _double nesting — imbricare dublă._

### node

**nod,** element de structură, de ex. _child node — nod copil._

### number

**număr, tip numeric**

## O

### opacity

**opacitate,** grad de opacitate, de ex. _opacity: 0.1 — opacitate 10%._ Adesea denumit în mod eronat transparență.

### opaque

**transparență,** grad de transparență, de ex. _opaque by 75% — opac la 75%,_ adică transparent 25%.

### outline

**contur,** conturul uniform extern al elementului care nu face parte din modelul de tip bloc.

## P

### package manager

**package manager,** software de suport pentru gestionarea instalării, configurării, actualizării și eliminării componentelor software.

### padding

**margine interioară,** de ex. _padding-top: 10px — margine interioară de sus 10px._

### pagination

1. **navigare pe pagini,** de obicei o listă de linkuri cu numerele paginilor în care este împărțit documentul.
2. **paginare,** împărțirea unui document în pagini separate pentru a facilita citirea, încărcarea sau în alte scopuri.

### pattern

**pattern,** abordare formală a scrierii codului, de ex. _JavaScript patterns — pattern-uri JavaScript._

### parent

**părinte**

### percentage

**valoarea procentuală, procente**

### performance

**performanță,** caracteristică ce ține de viteza de încărcare, de redare etc., de ex. _CSS performance — performanță CSS._

### performance budget

**buget de performanță,** performanța maximă admisibilă a aplicației web. Depășirea unui astfel de buget înseamnă că performanța este în scădere. De ex. _Performance Budget Metrics — metrici ale bugetului de performanță._

### persistent data structures

**structuri de date permanente**

### pinch

**depărtarea degetelor,** gest de utilizare a interfeței ecranului tactil: depărtarea (în funcție de direcție - întinderea) degetelor pe ecranul tactil.

### pixel

**pixel,** unitate de măsură în design, plural **pixeli,** pe scurt **px**.

- physical pixel — **pixel fizic,** celula de pe matrice, unitatea de rezoluție a display-ului dispozitivului.
- device independent pixel (dip) — **pixel virtual,** pixel independent de dispozitiv, poate fi mai mare, mai mic sau egal cu un pixel fizic.
- bitmap pixel — **pixel raster**.

### pixel density

**densitate pixeli,** numărul de pixeli care se încadrează într-o unitate de dimensiune liniară a ecranului, de ex. _pixel density of the screen is 326 ppi — densitate pixelilor ecranului 326 pixeli pe inch._

### pixel ratio

**raport de pixeli,** raportul dintre un pixel fizic și un pixel virtual, de ex. _screen has pixel ratio of 2 — raportul de pixeli al ecranului este egal cu 2._

### placeholder

1. **susbstituent,** înlocuitor temporar al unei imagini, text, etc. De ex.: _În loc de portretul președintelui, vom substitui cu imaginea unor pisicuțe_.
2. **câmp indicativ,** atributul unui câmp text, menit să ofere indicații privind modul de completare a câmpului. Cel mai adesea este un exemplu de completare. De ex.: `placeholder="+40 (737) 521 123"`.

### ppi (pixel per inch)

**pixeli pe inch,** unitate de măsură a densității pixelilor (vezi [pixel density](#pixel-density)).

### plugin

**TODO**

### polyfill

**polyfill,** script care recreează funcționalitatea lipsă, de ex. _new polyfill for IE6 — polyfill nou pentru IE6._

### progressive web metrics

**metrici web progresive,** set de metrici de pagină legate de [performanță](#performance).

- first paint — **prima schiță**
- first contentful paint (FCP) — **prima schiță substanțială**
- first meaningful paint — **prima schiță semnificativă**
- visually ready — **disponibilitate vizuală**
- visually complete — **completitudine vizuală**
- first interactive — **prima interactivitate**
- estimated input latency — **întârzierea de intrare estimată**
- time to interactive (TTI) — **timp până la prima interacțiune**
- time to first consistently interactive — **timp până la interactivitate stabilă**
- largest contentful paint (LCP) — **cea mai substanțială schiță**
- cumulative layout shift (CLS) — **modificarea cumulativă a layout-ului**
- total blocking time (TBT) — **timp total de blocare**
- first input delay (FID) — **timp de răspuns pentru prima interacțiune**

### prolyfill

**prolyfill,** o variantă a [polyfill](#polyfill), care se deosebește prin faptul că reproduce o funcționalitate _probabilă_ descrisă în specificație, dar care nu este încă implementată în browsere.

### popup

**fereastră pop-up, pop-up,** fereastră separată sau un element de interfață care apare deasupra celei curente, de ex. _annoying popup — pop-up deranjant._

### position

**poziționare**

- position: static — **statică**
- position: absolute — **absolută**
- position: relative — **relativă**
- position: fixed — **fixă**
- position: sticky — **sticky**

### preprocessor

**preprocesor,** instrument care convertește codul dintr-o sintaxă în alta, de ex. _Sass CSS preprocessor — preprocesor CSS Sass._

### progress bar

**progress bar** sau bara de progres este un element de interfață care arată progresul unei operații.

### progressive enhancement

**îmbunătățire progresivă** — abordare în care toate browserele primesc aceeași funcționalitate de bază, dar în browserele moderne această funcționalitate este extinsă pentru a sprijini noile tehnologii. De exemplu: gradienți, grafică vectorială, redare video.

### Progressive Web App (PWA)

**aplicație web progresivă**, abordare în dezvoltarea aplicațiilor web care combină avantajele site-urilor convenționale și ale aplicațiilor native: încărcare rapidă, instalare în sistemul de operare, funcționare offline, notificări push, acces la API-uri de sistem. Informațiile pentru instalare sunt descrise în manifestul web. Abordarea progresivă constă în faptul că într-un browser obișnuit este pur și simplu un site, dar în browserele și sistemele de operare de suport este o aplicație.

### promises

**promisiune,** modalitate de execuție asincronă a scripturilor, în contrast cu utilizarea callback-urilor.

### property

**proprietate,** de ex. _proprietate CSS_.

### proposed recommendation (PR)

**recomandare propusă,** statutul specificației [W3C](#world-wide-web-consortium-w3c), potențial candidat pentru [recomandare](#recommendation-rec).

### pseudo-element

**pseudo-element,** element intern suplimentar creat cu CSS și `::before` sau `::after`.

### pseudo-class

**pseudo-clasă,** utilizată pentru a lega declarația de o anumită stare a unui element DOM. Separat de selector prin două puncte `:`. De ex.: declararea blocului de reguli cu selectorul `.item:hover` se aplică, atunci când pe `.item` se trece cu cursorul.

### pull request, pr

**pull request,** cerere de acceptare a modificărilor în ramura repozitoriului din fork sau din altă ramură.

## Q

### quirks mode

**mod de compatibilitate,** mod de interpretare și afișare a paginilor de către browser, în care browserul se abate în mod deliberat de la standarde pentru a afișa documente create înainte de începutul anilor 2000 și care se bazează pe bug-uri și caracteristici ale browserului de la acea vreme. Utilizat pentru paginile fără [doctype] (#doctype) și cu doctype vechi (de exemplu, HTML 3.2).

## R

### radio button

**buton radio,** element de formular `<input type="radio">` pentru a selecta o opțiune din mai multe, de ex. _radio button is checked — buton radio selectat._

### recalculate

**recalculare**

### recommendation (REC)

**recomandare,** statutul final al specificației [W3C](#world-wide-web-consortium-w3c), recomandat pentru implementarea în browsere și utilizarea de către dezvoltatori.

### registry

**registru,** loc pentru depozitarea pachetelor, de ex. _GitHub Package Registry — registru de pachete Github._ Denumirea de "registru" este o traducere nepotrivită, deoarece contravine înțelesului de _registru de litere_ folosit în front-end.

### reflow

**reflow**

### rem

**rem,** unitate de măsură în CSS care depinde de dimensiunea fontului elementului rădăcină `<html>`, de ex. _font-size: 3rem — dimensiunea fontului 3rem._

### render

**randare**

### repaint

**redesenarea**

### reset

**resetare,** de obicei, resetează stilurile implicite în CSS, de ex. _style reset file — fișier de resetare stiluri._

### resolution

**rezoluție,** numărul de pixeli fizici de pe ecranul dispozitivului, de ex. _screen resolution is 1024×768 pixels — rezoluția ecranului este de 1024×768 pixeli._

### responsive design

**design receptiv,** una dintre metodele tehnologice de creare a unui [design adaptiv].(#adaptive-design).

### Responsive Images Community Group (RICG)

**Grup comunitar privind imaginile adaptive**

### rest parameters

**rest parameters,** sintaxă din JavaScript care permite reprezentarea parametrilor fără nume ai unei funcții sub formă de tablou.

### root

**rădăcină**

### rounded corners

**colțuri rotunjite,** de ex. _rounded corners are out of fashion — colțurile rotunjite nu mai sunt la modă,_ vezi și [border-radius](#border-radius).

### row

**linie, rând**

- zonă orizontală într-un tabel sau într-un layout.
- element de tabel `<tr>`.

### rowspan

**combinare coloane,** atribut HTML pentru combinarea mai multor celule de tabel într-o singură coloană.

### rule-set

**bloc de stil al elementului**, format dintr-un selector (sau media query) și un bloc de declarație.

## S

### shallow comparison

**compararea suprafețelor**, o comparație care verifică dacă două variabile se referă la același obiect din memorie.

### scaffolding

**scaffolding,** generarea automată a codului prin descriere, metoda metaprogramării.

### scale

1. substantiv **scalare, mărire**.
2. verb **a scala, a mări**.

### scope

**domeniu de aplicare,** partea limitată a structurii programului în care este disponibilă variabila declarată sau se aplică stilurile `<style scoped>`.

### screen reader

**screen reader,** program care redă informații de pe ecranul unui dispozitiv, un tip de tehnologie de asistare. Acestea sunt utilizate de persoanele care primesc mai ușor informațiile în formă auditivă, de persoanele dislexice, nevăzătoare sau cu deficiențe de vedere. De ex. _they use screen reader to navigate the web_ — _pentru a naviga pe web ei folosesc un screen reader_, _screen reader will say “image cat”_ — _screen reader-ul va citi "imagine pisică"_.

### script

**script,** instrucțiuni care descriu comportamentul paginilor, de ex. _scripts are not loaded yet — scripturile nu au fost încă încărcate._

### scroll

1. **defilare,** element de interfață pentru deplasarea unei părți ascunse a unei pagini sau a unui bloc, este o dovadă că elementul imbricat este mai mare decât elementul părinte, de ex. _horizontal scroll is disabled — defilarea orizontală este dezactivată._
2. **defila,** deplasarea unei părți ascunse a paginii sau a blocului.

### scrollbar

**bara de defilare,** denumire formală [defilare](#scroll), de ex. _system scrollbars — bare de defilare de sistem._

### sectioning roots

**rădăcini de secționare**

### semantics

**semantică,** încărcare semantică a elementelor HTML, de ex. _semantic coding — coding semantic._

### selector

**selector,** partea structurală necesară a [stylesheet](#rule-set). Este responsabilă de legarea declarațiilor la elementele DOM.

- simple selector — **selector simplu,** poate fi o [pseudo-clasă](#pseudo-class) sau unul dintre următoarele tipuri:
  - type selector — **selector de tip,** se referă la tag, de ex. `ul`, `input` și altele
  - universal selector — **selector universal,** "asterisk, steluță": `*`
  - ID selector — **selector de id,** de ex. `#content`
  - class selector — **selector de clasă,** de ex. `.item`
  - attribute selector — **selector de atribut,** de ex. `[type=submit]`
- compound selector (sequence of simple selectors) — **selector compus,** lanț de selectori simpli care nu sunt separați de combinatori, de ex. `input[type=submit]:focus`
- complex selector — **selector complex,** mai mulți selectori simpli și/sau compuși separați prin combinatori:
  - descendant selector — **selector descendent,** de ex. `ul li`
  - child selector — **selector copil,** de ex. `#buttons > *`. De asemenea, deseori numit  **apropiat**
  - adjacent sibling selector — **selector direct vecin,** de ex. `.item + .item`. De asemenea, deseori numit **vecin**
  - general sibling selector — **selector vecin,** de ex. `.item ~ .item`

### server-side

**partea server,** domeniul tehnologiei bazate pe server, adesea sinonim cu [back-end](#back-end).

### shadow DOM

**shadow DOM**

### shapes

**forme, forme CSS**

### shared

1. adjectiv **distribuit,** de ex. _shared memory — memorie distribuită.
2. adjectiv **comun,** de ex. _shared folder — dosar comun_, _shared access — acces comun._

### shim

**shim,** cod care ajută la unificarea browserelor, de obicei prin implementarea suportului care lipsește sau normalizarea suportului existent, de ex. _HTML5 shim for IE8 — HTML5 shim pentru IE8._

### sibling

**vecin** (în sensul de "element adiacent").

### sidebar

**bară laterală,** partea laterală a site-ului cu conținut secundar, de ex. _sidebar is on the right side — în dreapta se află bară laterală._

### skew

1. substantiv **înclinare**.
2. verb **a înclina**.

### source maps

**hărți de sursă,** marcaje speciale care fac legătură între fișierele sursă și codul compilat pentru depanare.

### specification, spec

**specificație,** documentație tehnică pentru dezvoltatorii și producătorii de browsere, de obicei în una dintre următoarele stări: de la propus la aprobat de W3C, de ex. _specification draft — draft specificație._

### spread

**spread,** operator în JavaScript, care extinde expresiile acolo unde sunt prevăzute mai multe argumente la apelarea funcțiilor `doSomething(...array)`, se așteaptă mai multe elemente în array-uri `[1, 2, ...array]`) și adăugarea sau suprascrierea câmpurilor în obiecte `{ ...object, field: 'value' }`.

### specificity

**specificitate,** caracteristică a unui [selector CSS](#selector) care determină prioritatea acestuia [într-o cascadă](#cascade). Aceasta este formată din greutatea fiecărui [selector simplu](#selector) din cadrul acestuia.

### stacking context

**context de stivuire,** element din structura vizuală a paginii care limitează acțiunea proprietății `z-index` la descendenții săi și care este plasat de-a lungul axei _z_ ca întreg (fie în întregime deasupra, fie în întregime sub orice alt element). De ex. _elements with opacity create new stacking context — elementele cu opacitate creează un nou context de stivuire._

### staging server

**server depanare,** serverul, pe care este testat și depanat produsul.

### standards mode, standards compliance mode

**mod standard,** mod de interpretare și afișare a paginii de către browser, în care browserul este obligat să respecte standardele la maximum. Utilizat pentru paginile cu [doctype](#doctype), de ex. doctype HTML5.

### statement

**declarație,** element de structură CSS. Acesta poate fi un bloc de stiluri al elementului, directivă de import, media query și altele.

### string

1. **șir de caractere,** în programare, un tip de date ale cărui valori sunt o secvență aleatorie (șir) de caractere.
2. **șir,** în CSS — valoarea de tip șir de caractere a unei directive sau a unei proprietăți. De ex. în `content: "\201d"` șirul este `"\201d"`.

### stub object

**stub, substituient**

### style

1. substantiv **stiluri,** de ex. _apply styles to an element — aplică stiluri unui element,_ plural: _stiluri element,_ și nu _stil element_ (greșit).
2. verb **a stiliza,** de ex. _how to style selects — cum stilizezi selectorii._

### style guide

**ghid de stil,** de ex. _project code style guide — ghid de stil pentru codul proiectului_.

### stylesheet

**foaie de stil,** de ex. _foaie de stil a documentului_.

### swipe

**glisare,** gest de utilizare a interfeței ecranului tactil: glisează cu degetele pe ecranul tactil.

### submit

**trimitere,** de ex. _trimite formular_.

## T

### tab

1. **filă,** unul dintre straturile interfeței site-ului sau a programului care se activează prin selectarea antetului său, de ex. _open in new tab — deschide într-o filă nouă._
2. **tab,** tasta tab, introduce un caracter de tabulare, mută accentul pe următorul element al interfeței sau completează un cuvânt scris parțial, de ex. _press Ctrl Tab — apasă Ctrl Tab._
3. **tab,** simbol de tabulare, are o lățime configurabilă și este utilizat pentru a indenta codul, de ex. _tabs are better than spaces — tab-urile sunt mai bune decât spațiile._

### tag

1. **tag,** denumirea unui element în HTML, există tag-uri de deschidere, de închidere și simple. De ex. _closing tag is missing — tag-ul de închidere lispește._
 - tag name — **denumire tag**
 - start tag — **tag de deschidere**
 - end tag — **tag de închidere**
2. **etichetă,** indicator de conținut, de obicei un cuvânt scurt.

### tap

**atingere,** gest de utilizare a interfeței ecranului tactil: atinge o dată pe ecranul tactil.

### text

**text**

### textarea

**zonă de text,**  element de formular pentru introducerea textului multilinie.

### text-align

**aliniere text,** orientarea liniilor de text într-o anumită direcție sau în mod egal pe toată lățimea blocului.

- text-align: left — **stânga**
- text-align: right — **dreapta**
- text-align: justify — **la ambele capete**

### text-shadow

**umbră (text),** de ex. _text-shadow is red — umbra textului este roșie._

### throttling

**throttling,** introducerea unor limite artificiale, de exemplu, pentru a reduce frecvența apelurilor a event handlers în JavaScript sau viteza rețelei și puterea procesorului în timpul testelor.

### thumb

1. prescurtare de la [thumbnail](#thumbnail).
2. **bară,** element de comandă din [bara de defilare](#scrollbar).

### thumbnail

**miniatură,** copie redusă a unei imagini.

### title

1. **titlu,** dacă este vorba de `<title>`, sau despre titlul elementului.
2. **sugestie,** dacă este vorba de atributul `title=""`.

### toggle

**comuta,** a trece de la o stare la alta, _toggle classes — comuta clase._

### tooltip

**sugestie/indicație,** informații auxiliare, care apar când se trece peste element sau când acesta este activat, în special `title=""`.

### touch interface

**interfață tactilă**

### transform

**transformare,** de ex. _transform: scale(2) — transformare prin scalare de 2 ori._

### transition

**tranziție,** de ex. _transition: all 2s linear — tranziție liniară de 2 secunde._

### translate

**deplasare,** deplasarea unui obiect folosind o transformare CSS, de ex. _translate(x, y) — deplasare pe X și Y._

### transpiler

**transpiler,** compilator care convertește codul sursă dintr-un limbaj de programare în cod sursă în alt limbaj de programare.

### typography

**tipografie,** formatarea textului prin selectarea garniturilor, a parametrilor liniilor și altele.

## U

### unit

**unitate de măsură,** de ex. _rem unit — unitate de măsură "rem"._

### unit testing

**testare unitară**

### URI

**identificator uniform de resurse,** secvență de caractere care identifică o resursă abstractă sau fizică.

### URL

1. **adresă**. Acest sens se recomandă să fie utilizat în traducerea articolelor.

2. **identificator uniform de resurse,** [URI](#uri), care oferă, de asemenea, informații despre locația resursei, de ex. _background: url("http://www.example.com/picture.png")_

### user experience (UX)

**experiența utilizatorului,** totalitatea experienței interacțiunii cu ceva (interfață, dispozitiv, produs). În contextul domeniului de cunoștințe se recomandă utilizarea UX (de ex. _specialist UX_).

### user interface (UI)

**interfață de utilizator,** într-un context transparent, se recomandă să se utilizeze pur și simplu "interfață".

### utility

**utilitate,** program cu scop îngust.

## V

### valid

**valid,** standard, specificație sau altă regulă, de ex. _valid markup — marcaj valid_.

### validator

**validator,** mijloc de verificare a conformității cu un standard, o specificație sau o altă regulă (vezi [valid](#valid)), de ex. _W3C markup validator — validator de marcaj W3C_.

### value

**valoare,** de ex. _valoarea proprietății CSS_.

### variable units

**unități de măsură variabile,** — proprietăți personalizate care pot fi utilizate ca unități de măsură în CSS. Se acceptă utilizarea în formă prescurtată, fără cuvântul "măsură", de ex. _variable units make this easier to write — unitățile variabile fac acest lucru mai ușor de scris._

### vendor prefix

**prefix de browser,** prefix la proprietatea CSS `-webkit-` sau `-moz-`, de ex. _add vendor prefixes — adaugă prefixe de browser._

### vendor files

**fișiere de la terți,** stiluri, scripturi și alte resurse (dependențe) de la alți autori utilizate în proiect, de ex. _tons of vendor scripts included in the code — o mulțime de scripturi de la terți conectate în cod._

### vertical-align

**alinierea verticală**, poziționarea pe verticală a elementelor într-un rând de text sau de tabel.

### viewport

**viewport**

1. zona vizibilă a documentului în cadrul ecranului.
2. elementul `<meta name="viewport">`, gestionează adaptarea paginilor pe dispozitivele mobile.

## W

### website, web site

**site, site web** set de pagini care se află sub o singură adresă, traducerea "website" este redundantă.

### worker

**worker,** interfață în JavaScript care permite ca un script să fie executat într-un fir care nu este firul principal.

- web worker — **web worker**
- service worker — **service worker**
- shared worker — **worker comun**

### working draft (WD)

**working draft,** document preliminar al specificației [W3C](#world-wide-web-consortium-w3c).

### worklet

**worklet,** clasă în JavaScript care conține metode predefinite cu o anumită semnătură, care oferă acces la diverse API-uri ale browserului. [Proiectul Houdini](https://github.com/w3c/css-houdini-drafts/wiki) prevede următoarele tipuri de worklet:

- paint worklet — **paint worklet**
- compositor worklet — **compositor worklet**
- layout worklet — **layout worklet**

### World Wide Web Consortium (W3C)

**World Wide Web Consortium**, organizația care elaborează standardele web. Traducerea cuvântului "web" ca "rețea" în secolul XXI este deja ridicolă.

### web standards

**standarde web**

### width

**lățime**

### word-spacing

**word-spacing** spațierea dintre cuvinte.

### workaround

**găsire soluție,** modalitate de a rezolva o problemă în condiții limitate, de ex. _to figure out workaround — să găsim o soluție._
