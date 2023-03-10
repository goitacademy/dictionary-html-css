# Dictionary of frontend terms

Table of contents: [0-9](#0-9) [A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) J [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) X Y Z

## 0-9

### 9-slice scaling

**9-slice scaling** (non-distortive scaling), a technique that allows you to resize an object without geometric distortion. The object is divided into 9 parts (three rows and three columns), each of which is scaled following its own rules: the corners are not scaled at all, the central part is scaled by height and width, the remaining parts are scaled either by width only or by height only.

## A

### accessibility, a11y

**accessibility,** the ability to use the interface by everyone, regardless of any physical or technical limitation.

### adaptive design

**adaptive design,** the approach to website design, which takes into account the adaptability to different devices and conditions, contrary to the widespread "fixed" design only for computers. One way to create an adaptive design is through [responsive design](#responsive-design) techniques.

### almost standards mode

**almost standard mode,** a page interpretation and display mode in which the browser deliberately avoids the standards (as in [compatibility mode](#quirks-mode)) only for certain special cases. It is used for pages with transitional [docktips](#doctype) HTML 4 and XHTML 1.

### anchor

1. **link,** a hyperlink between two documents.
2. **anchor,** a link to an element within the document, can be part of a hyperlink.

### animation

**animation,** a smooth change in the visual appearance of an object.

### asset

**asset,** a constituent part of a site: text files, graphics, video, databases, etc. In a more restricted sense, "static asset": styles, scripts, design graphics, in contrast to dynamic [content](https://github.com/web-standards-ru/dictionary/blob/master/dictionary.md#content).

### assert

**verification,** A condition that is checked, used in testing, e.g. _field assert has failed_

### at-keyword

**directive key,** see [directive](#at-rule)

### at-rule

**directive,** type [declaration](#statement) beginning with `@`, e.g. _@import_.

### attribute

**attribute,** e.g. `rel="stylesheet"`.

- attribute name — **attribute name**
- attribute value — **attribute value**

## B

### back-end

**backend**

1. the area of web technologies running on the server.
2. the internal part of the system server, involved in data processing.

### background

**background,** e.g. _background image_

- background-color — **background color**
- background-position — **background position**
- background-size — **background size**
- background-repeat — **background repetition**
- background-origin — **background limits**
- background-clip — **background crop**
- background-attachment — **background attachment**
- background-image — **background image**

### baseline

**baseline,** the imaginary line at the base of the characters in a line.

### bikeshed

**to pay excessive attention to minor details,** (see [the law of triviality](https://ru.wikipedia.org/wiki/Закон_тривиальности)). There is no Russian equivalent, so it is better to translate the general meaning, e.g. _avoid bikeshedding — not to argue about trivialities_.

### blending mode

**blending mode,** an algorithm for blending layers, used in graphical editors or directly in CSS, e.g. _overlay blending mode_

### block

1. **declarations block,** structural part of a [declaration](#statement). It consists of curly braces and contains property declarations (or, in the case of media queries, style blocks).
2. **block view,** see [view](#display)

### blockquote

**block quote,** HTML element to highlight the quoted _nonline_ area of the document. May contain the attribute `cite` with a link to the original source.

### border

**border,** The external visible part of a block, e.g. _border-left — border on the left._

- border-collapse — border fusion
- border-color — border color
- border-image — graphical border
- border-image-outset — indentation of the graphical border
- border-image-repeat — repetition of the graphical border
- border-image-slice — splitting of the graphical border
- border-image-source — image address for the graphical border
- border-image-width — thickness of the graphical border
- border-radius — rounding of the border
- border-style — border style
- border-width — border width

### border-radius

**rounding of the border,** e.g, _border-radius: 3px - rounding of the border by 3 pixels, border-top-left-radius - rounding of the top left corner,_ see also [rounded corners](#rounded-corners).

### bounding box

**bounding box**

### box model

**box model,** block dimension system, consisting of content, indentation, frame and outer indentation.

### box-shadow

**shadow (of the box),** e.g. _box-shadow is red_

### breadcrumbs

**breadcrumbs,** auxiliary navigation of a site, which reflects the structure or steps taken in sequence.

### breakpoint

1. **brakpoint,** — one of the widely used polysemantic translations, the exact meaning can be understood from the context.
2. **breakpoint,** a line in the code at which the script is paused to call the debugger.
3. **checkpoint,** the condition in which the layout of the site changes from one to the other. It is characteristic of media queries.

### browser

**browser**

### button

**button**

1. interface element that, when clicked, sends a form or performs another action
2. a form element `<button>` or `<input type="button">` (also `submit` and `image`).

## C

### callback

**callback,** the execution of a code after a function is completed, e.g. _pass value in a callback_

### candidate recommendation (CR)

**candidate recommendation,** status of the [W3C](#world-wide-web-consortium-w3c) specification. It is one of the possible options for [proposed recommendation](#proposed-recommendation-pr).

### cascade

### cascade

**cascade,** a description in the specification of the CSS scheme, which defines the order in which style blocks are applied to an element.

### cascade layer

**cascade layer,** a way of grouping and controlling the order in which styles are applied within a single [source](#cascade-origin), it is declared using the [directive](#at-rule) `@layer`. e.g. _rules within a cascade layer cascade together_

### cascade origin

**cascade origin,** built-in browser styles description area, the order of sources determines the application of styles or [cascade](#cascade): from browser styles to transitions-declarations. e.g. _there are eight cascade origings, including user styles_ — _есть восемь каскадных источников, включая пользовательские стили._

### cell

**cell**

1. the structural unit of a table.
2. the table element `<td>` or `<th>`.

### cellpadding

**indentation in the cells** of the table.

### cellspacing

**the distance between the cells** of the table.

### character reference

**character substitution,** e.g. `&nbsp;`. There is also a not quite accurate, but much more well-established meaning **special character.**

### checkbox

**checkbox**

1. interface element for selecting one or several options, e.g. _checkbox is disabled._
2. a form element `<input type="checkbox">`.

### child

1. noun. **child,** (plural.  **children**)
2. adj. **child,** e.g. _child process_

### classitis

**classitis,** a fictitious disease characterized by the excessive use of numerous classes: both in the design and for storing information.

### clear

**clear,** CSS property that prevents a block from wrapping around the preceding floating blocks.

- clear: left — **cleared on the left**
- clear: right — **cleared on the right**
- clear: both — **cleared on both sides**

### clearfix

**clearfix,** a method for preventing containers with floating blocks from collapsing. It consists in creating a special spacer, which is located after the floating blocks and clears them. A frequent solution to problems with floating blocks (see [summary table of all problems and solutions](http://css-live.ru/articles-css/clearfix-block-formatting-context-methods-cheatsheet.html)).

### click

**click,** to click on an object with the mouse cursor or a similar device, e.g. _double click is firing event._

### client-side

**client-side,** the technologies involved in making possible a web browser to work, often a synonym for [frontend](#front-end).

### clipping path

**clipping path**

### closure

**closure,** a function that contains in its body references to variables declared in the surrounding code.

### code

1. noun. **code,** non-countable. (like sugar), e.g. _error in code — _ not _error in the codes_ (wrong).
2. verb. **to code, to program,** e.g. _to code a site._

### colspan

**column merge,** HTML attribute for combining multiple table cells on one line.

### column

**column,** the vertical section in a table, layout, or text.

### color

**color**

### combinator

**combinator,** a special character used in a complex selector to precisely specify a combination of DOM elements, e.g. `>`, `+` etc. The space between selectors is also considered a combinator.

- descendant combinator — **descendant combinator,** `` (space).
- child combinator — **direct descendant combinator,** `>`. Also called **child**.
- adjacent sibling combinator — **adjacent sibling combinator** `+`.
- general sibling combinator — **neighbor combinator,** `~`.

### comment

**commentary,** an explanation of the code

### component

**component,** a constituent part of something. e.g. _app components_

### compositing

**compositing**

### composite layer

**composite layer**

### compositor

**compositor** (in the sense of "the compositing engine")

### container query

**container query,** the directive declaration `@container` with conditions, allows you to apply styles depending on the properties of the _parent_ container. e.g. _many container query cases can be solved with existing technology_

### containing block

**containing block** — block, to which dimensions and positions of the given block are calculated. To put it simply, the containing block is the parent of a given block, not by DOM, but by the document flow. e.g. _containing block isn’t always the content area of the parent_

### content

**content**

- metadata content — **metadata content**
- flow content — **flow content**
- sectioning content — **sectioning content**
- heading content — **heading content**
- phrasing content — **phrasing content**
- embedded content — **embedded content**
- interactive content — **interactive content**
- palpable content — **palpable content**
- script-supporting content — **script-supporting content**
- grouping content — **grouping content**

### continuous integration

**continuous integration,** the practice of assembling, testing and deployment of software in a frequent and automatized way

### cookie

**cookie,** a small piece of data that is sent from the server and stored in the browser.

- **access to cookies**
- **cookie banner**
- **authorization cookie**
- **first-party cookies**
- **third-party cookies**

### cross-browser

**cross-browser,** something that works on all browsers, combined.

### cross-platform

**cross-platform,** something that works on all platforms, combined.

### custom properties

**custom properties,** type of CSS properties `--my-property`, which developers can create by themselves and use further in the code as variables using the `var()` function. A common translation of **CSS variables,** e.g. _CSS variables, also known as CSS custom properties, are landing in Chrome 49._

### CSS Working Group (CSSWG)

**CSS Working group**

### custom

**custom** (also. **user**)

- **custom element**
- **custom attribute**.

## D

### data binding

**data binding,** automatic data synchronization between two entities, usually the model and the representation.

### declaration

**declaration,** property and value declaration.

### deep comparison

**deep comparison,** comparison of two objects, in which the structure of the objects is compared and the equality of the primitives contained within the objects is checked.

### deploy, deployment

**deploy, deployment,** publication of changes either directly to a public server (production) or through intermediate systems and automated build processes.

### deprecated

**deprecated,** status of a language feature that is not recommended to use because it has either _already_ been replaced, removed, or _is going to be_, in future versions, e.g. _this API is a replacement of the deprecated `React.addons.cloneWithProps()` _ или _`<applet>` is deprecated in favor of `<object>`.</p>

### design

1. noun. **design,** visual appearance of a website, may include the principles of interaction and architectural solutions, e.g. _new design for a site_.
2. verb. **develop,** to create or design the appearance and functionality.

### device pixel ratio

see. [pixel ratio](#pixel-ratio)

### dirty checking

**check for "dirty" object properties,** that is: a [deep comparison](#deep-comparison) of model properties, which leads to [ callback](#callback) if something has changed.

### disable

**disable**

### disabled

**disabled,** The state of a form element in which it is forbidden to modify it, e.g. _disabled button._

### display

1. **display,** css-property that defines how a block is displayed.

 - display: none — **not displayed**
 - display: block — **displayed as block**
 - display: inline — **displayed as inline element**
 - display: inline-block — **element displayed as inline-level block container**

- display: flex — **displayed as block-level flex container** (see. [flexbox](#flexbox))
- display: inline-flex — **displayed as an inline-level flex container** (see. [flexbox](#flexbox))

2. **screen,** e.g. _smartphone screen, screen resolution_.

### divitis

**divitis,** a fictitious disease characterized by the use of only `<div>` elements instead of [semantically](#semantics) appropriate ones.

### DOM

**Document Object Model, DOM**

### doctype

**doctype,** the `<DOCTYPE html>` construction type at the beginning of the document, which denotes the version of HTML used. Browsers use it to select a mode ([standard](#standards-mode-standards-compliance-mode), [almost-standard](#almost-standards-mode) or [compatibility](#quirks-mode)).

### dropdown

**drop-down menu,** interface element that reveals additional information when activated.

## E

### easing

**easing, a function of smoothness,** describes the changes in the animation speed using keywords or Bézier curves, e.g. _transition easing is linear._

### editor’s draft (ED)

**editor's draft,** early status of the [W3C](#world-wide-web-consortium-w3c) specification, suggested by one of the editors. The [working draft](#working-draft-wd) can be based on the editor's draft.

### element

**element**

- void elements — **empty elements**
- raw text elements — **elements with raw text**
- escapable raw text elements — **elements with escapable raw text**
- foreign elements — **foreign elements**
- normal elements — **normal elements**

### em

**em,** a measurement unit in CSS that depends on the size of the parent font, e.g. _font-size: 3em._

### enable

**to enable**

### enabled

**enabled,** The state of a form element in which it is allowed to be modified, e.g. _enabled button._

### engine

**engine,** e.g. _Safari is based on WebKit engine._

## F

### fallback

**fallback,** a backup, an additional implementation in case the browser does not have the necessary capabilities, such as enabled scripts or the necessary video codecs, e.g. _fallback to a link._

### favicon

**favicon,** site icon, usually 16×16 pixels in ICO format.

### feature query

**directive `@supports`,** a conditional structure that allows you to selectively apply styles depending on the browser's support for certain properties and values. There is no straightforward, well-established translation of the [media query](#media-query) example yet.

### fieldset

**fieldset,** element that combines several form fields, e.g. _green border on a fieldset._

### figure

**figure,** HTML5 element containing an image, video, table, graph or code fragment.

### figcaption

**figcaption,** title or caption to a figure.

### filter

**filter**

- filter: brightness — **brightness**
- filter: contrast — **contrast**
- filter: grayscale — **grayscale**
- filter: sepia — **sepia**
- filter: invert — **invert**
- filter: saturate — **saturation**
- filter: hue-rotate — **color rotation**
- filter: blur — **blurring**
- filter: opacity — **opacity**
- filter: drop-shadow — **shadow**

### flash of…

- flash of unstyled text, FOUT — displays the text in the system font before loading the web font.
- flash of invisible text, FOIT — absence of text on the page before the web font is loaded.
- flash of faux text, FOFT — displays the text in a modified basic font before loading the desired fonts

### flexbox

**flexbox,** [layout](#layout) mechanism.

- flex container — **flex container**
- flex item — **flex item**
- flex-direction — **main axis direction**
- flex-wrap — **Flex-elements transfer,** determines whether the container is a single-line or multiline container
- flex-basis — **base size** of the flex element along the main axis
- flex-grow — **expansion coefficient**
- flex-shrink — **contraction coefficient**
- main axis — **main axis,** the direction in which the flex elements are arranged one after the other in the container.
- cross axis — **cross axis,** direction, perpendicular to the main axis
- main size — **main size,** the size of the flex element along the main axis
- cross size — **cross size,** the size of the flex element along the transverse axis
- justify-content — **distribution of the flex elements** along the main axis
- align-items — **alignment of the flex elements** along the transverse axis
- align-self — **alignment of the flex element** along the transverse axis
- align-content — **alignment of the container lines** along the transverse axis
- order — **sequential number** of the flex element

### float

1. adj. **floating,** The property of a block that causes subsequent blocks to flow around it, e.g. _float layout — layout on floating blocks._
2. verb. **to float,** to follow closely the floating block, e.g. _text is floating to the right._
3. verb. **to squeeze,** to the right or left, usually through floating properties, e.g. _float block to the left._

### font

**font**

- font-weight — **saturation**

  - font-weight: normal — **normal**
  - font-weight: bold — **bold** or **half bolded**
  - font-weight: bolder — **bolder**
  - font-weight: lighter — **lighter**

- font-style — **font style**

  - font-style: normal — **normal**
  - font-style: italic — **italic**
  - font-style: oblique — **oblique**

- font-size — **font size, point**

- font-family — **font family, typeface**

  - font-family: serif — **serif**
  - font-family: sans-serif — **sans-serif**
  - font-family: monospace — **monospaced**

### footer

**footer**

1. the specific visual area at the end of a page.
2. element `<footer>` — a semantic part with meta-information.

### formatting context

**formatting context,** in CSS - the area in which the visual elements of the page (text fragments, blocks, cells, etc.) are lined up according to specific rules.

- block formatting context, BFC —  (e.g. _element with `overflow` establishes the new BFC)</li>
- grid formatting context — (see. [grid layout](#grid-layout))
- flexbox formatting context — (see. [flexbox](#flexbox))
- inline formatting context
- table formatting context</ul>

### forced color mode

**forced color mode,** in which the colors specified by the developer are forcibly replaced by system or user colors, most often to increase contrast and make the content more accessible to people with limited vision.

### fragment identifier

**fragment identifier,** the text after `#` in a URL, which allows you to refer to a specific part of the document. Used mainly in specifications and when working with SVG. HTML adopted a more familiar term [anchor](#anchor).

### framework

**framework,** a set of libraries and components to simplify development. Usually, it represents the basic structure of a product. _e.g., [Twitter Bootstrap](http://getbootstrap.com/)._

### front-end

**front-end**

1. the technical area for web interface development, includes supporting tools and technologies running in the browser or the [client-side](#client-side).
2. the external part of a server system, which is responsible for receiving data, sending responses and generating code for the browser. It is part of the [server-side](#server-side).

### full screen

**full screen mode,** the behavior of a program or a part of it, in which it occupies the whole screen.

### fullstack

**fullstack**

1. area of specialization, which includes [frontend](#front-end) and [backend](#back-end).
2. a specialist who can be responsible for all the aspects of a project: from the client side to the server side.

e.g., _Katerina has masted the databases, now she can replace "frontender" to "fullstack" on her resume._

### function

**function**

1. in programming - a program code fragment (subprogram) that can be addressed from elsewhere in the program.
2. in CSS — it may be present in the [declaration](#declaration), on the value position. e.g., `url(img/gradient.png)`.

## G

### generated content

**generated content,** part of the document created with CSS, [pseudo element](#pseudo-element) and `content` property.

### graceful degradation

**graceful degradation** — approach, in which the site interface is degraded for older browsers, in which some of the technology used is not supported. When this happens, the impact on the user is mitigated as much as possible. For example: a background color instead of a gradient, a bitmap graphic instead of a vector graphic, or playing a video with a plugin.

### gradient

**gradient,** a smooth transition from one color to another.

- linear gradient — **linear gradient**
- radial gradient — **radial gradient**
- conical gradient — **conical gradient**

### grid

1. **grid,** a way of ordering the arrangement of elements in a design by using a vertical or horizontal pattern, e.g. _module grid._
2. **grid,** a two-dimensional grid of rows and columns in a [grid layout](#grid-layout).

### **grid layout**

**grid layout,** a [layout](#layout) mechanism, which allows you to place the elements on a two-dimensional grid - [grid](#grid) (2).

- **grid container** — _grid container_
- **grid item** — _grid item_
- **grid track** — _grid track_, generic term for the rows and columns of a _grid_
- **grid cell** — _grid cell_
- **grid line** — _grid line_, virtual border between adjacent _grid tracks_, to which you can bind _grid items_
- **grid area** — _grid area_, space for placing _grid items_, restricted by four _grid lines_
- **grid gutter** — _grid gutter_, gap between adjacent _grid tracks_

## H

### header

**header**

1. the specific visual area at the beginning of the page.
2. element `<header>` — a semantic heading section.

### height

**height**

## I

### icon font

**icon font,** a synthetic font containing icons and other flat vector images for website design, e.g. _build an icon font._

### immutable

**immutable,** is a term most commonly applied to data (data types) in functional programming.

### implement

**to implement** e.g. _Firefox has implemented support of everything._

### inline

1. **inline,** having line properties.

 - inline block — **inline block**.
 - inline box — **line element** in line formatting: part of the body of the line container to which CSS rules are directly applied, e.g. _anonymous inline box_.
 - inline element — **inline element**.

2. **built-in,** located inside a line of code.

 - inline styles — **built-in styles**.
 - inline SVG — **built-in SVG**.
 - inline script — **built-in script**.

### input

**form element,** that allows the user to interact with the interface, for example: a text field, a button, a switch.

### intrinsic dimensions

**intrinsic dimensions,** width and height determined by the element itself, not by the environment. CSS cannot specify how its own dimensions are calculated. Only replaceable elements can have their own dimensions, for example: pictures, video, audio and other blocks, for which the representation does not depend on the developer.

### internationalization, i18n

**internationalization,** an interface design and development process that allows [localization](#localization-l10n) for different regions (different culture or language) without any technical changes, e.g. _`Intl.DateTimeFormat` - a class constructor that allows to format date and time taking into account the location._

### interoperability

**interoperability**

## K

### kerning

**kerning,** the distance between pairs of letters, taking into account their shape for a more uniform typing.

### keyframe

**keyframe,** one of the preset animation positions, from which changes occur automatically.

### keyframe animation

**keyframe animation,** the way to create animations in CSS using keyframes.

### keyword

**keyword**

## L

### label

**label,** establishes a connection between a specific element and a form element.

### last call (LC)

**final draft,** specification status [W3C](#world-wide-web-consortium-w3c) for the last corrections before the status [candidate to recommendation](#candidate-recommendation-cr) _(cancelled in 2014, found only in older specifications)_.

### layout

**layout,** the location of the main blocks on the page, e.g. _3 columns layout._

### legend

**legend,** title of a form element group, defined with [fields group](#fieldset)

### length

**length**

### letter-spacing

**letter spacing, tracking,** the total distance between the letters in a text, it is different from [kerning](#kerning).

### library

**library,** a set of ready-made solutions to simplify the development. Usually a library implements a specific function or a set of related functions, such as animation.

### line-box

**line-box**, in line formatting: a virtual container containing all elements of a single line.

### line-height

**line-height, interlineation,** the distance between the base lines of a text.

### list

**list,** the sequential listing of a group of elements.

- ordered list — sorted by a specific principle.
- unordered list — a list in which the order does not matter.

### list-style

**list style**

### localization, l10n

**localization,** the process of adapting the interface to the language and cultural connotation of a particular region (country, location), e.g. _`new Date().toLocaleDateString('en-US')` - converts the date to its string representation, according to the US location._

## M

### margin

**the external indentation,** e.g. _margin-bottom: -10px — bottom negative indent of 10 pixels._

### margin box

**outer margins of something.**

### matrix

**matrix (transformations),** description of the transformation of an object with the help of a matrix.

### media query

**media query,** the declaration of a directive `@media` with certain [conditions](#media-query-list), allows to apply styles depending on the capabilities of the device. The translation alternative "media queries" reflects the essence of the operation less accurately.

### media query list

**conditions to media queries,** a list of conditions defining in which cases the declarations within the `@media` directive will be applied. e.g., `only screen and (min-width: 35em)`.

### media type

**media type (device type),** can be a condition of a media query. Specifies for which output method the styles are intended (e.g. `screen` — on a screen, `print` — for printing, `speech` — for a speech synthesizer).

### media feature

**media feature (device feature),** can be a condition for a media query. Defines a device characteristic. E.g., `min-width`.

### mixin

**mixin,** a set of properties that extends the behavior of another entity, found in the CSS preprocessors and JavaScript patterns, e.g. _mixin is clearing — mixin cleans the flow._

### mobile first

**Mobile first,** a development approach in which the design of a service starts with a mobile version rather than a large-screen version. The term was introduced by Luke Wroblewski in his [book of the same title](https://abookapart.com/products/mobile-first).

### mock object

**mock object**

### mock-up

**mock-up,** the appearance or design of a site with varying degrees of detail, e.g. _designer has sent a page mock-up._

### modal

1. adj. **modal,** something that blocks the interface to perform an action, e.g. _modal dialog._
2. noun. **modal window (dialog),** interface element, see _modal._

### multiple

**multiple,** repeated two or more times, e.g. _multiple backgrounds._

### multiple columns

1. **multiple columns,** a mechanism from CSS that allows you to line up text in multiple columns, e.g. _multiple columns support in IE — _ Preferred over the bulky "many columns".
2. **multiple column,** consisting of several columns, e.g. _multiple columns layout._

## N

### nested

**nested,** to be within something, e.g. _double nesting._

### node

**node,** element of a structure, e.g. _child node_

### number

**number, numeric type**

## O

### opacity

**opacity,** the degree of opacity, e.g. _opacity: 0.1 — Opacity 10%._ Often mistakenly referred to as transparency.

### opaque

**opaque,** the degree of opacity, e.g. _opaque by 75%,_ means the transparency is 25%.

### outline

**outline,** external uniform contour of an element that is not involved in the block model.

## P

### package manager

**package manager,** less often ** package dispatcher,** auxiliary software to manage installing, configuring, upgrading and uninstalling software components.

### padding

**internal margin,** e.g. _padding-top: 10px — Top internal indent 10 pixels._

### pagination

1. **page navigation,** usually a list of links with page numbers into which the document is divided.
2. **pagination,** splitting the document into separate pages for easy reading, downloading, or other purposes.

### pattern

**pattern,** a standardized approach to code writing, e.g. _JavaScript patterns_

### parent

**parent**

### percentage

**percentage value, percent**

### performance

**performance,** a characteristic of the loading speed, rendering speed, etc., e.g. _CSS performance._

### performance budget

**performance budget,** the maximum allowable performance of a web application. Exceeding the budget means a drop in performance. e.g. _Performance Budget Metrics._

### persistent data structures

**persistent data structures**

### pinch

**to pinch,** gesture for controlling a touch screen interface: pinch-in (depending on the direction - pinch-out) on a touch screen.

### pixel

**pixel,** measurement unit for screen design, in plural. **pixels,** abbreviation. **px.**

- physical pixel — a cell on the pixel matrix, the resolution unit of the device's display.
- device independent pixel (dip) — **virtual pixel,** device-independent pixel, can be larger, smaller or equal to a physical pixel.
- bitmap pixel — **bitmap pixel**.

### pixel density

**pixel density,** the number of pixels that fit into a unit of the screen's linear size, e.g. _pixel density of the screen is 326 ppi (Pixels Per Inch)._

### pixel ratio

**pixel ratio,** the ratio of the physical pixel to the virtual pixel, e.g. _screen has pixel ratio of 2_

### placeholder

1. **placeholder,** a temporary substitute for a picture, text, etc. For example: _Instead of a portrait of the president, put a placeholder with kittens on it._.
2. **field hint,** attribute of a text field, designed to give hints about how to fill the field. The most common is an example of how to fill something out. e.g.: `placeholder="+7 (999) 123-12-13"`.

### ppi (pixel per inch)

**pixels per inch,** measurement unit for pixel density (see [pixel density](#pixel-density)).

### plugin

**TODO**

### polyfill

**polyfill,** a script that recreates a missing functionality, e.g. _new polyfill for IE6._

### progressive web metrics

**progressive web metrics,** a set of page metrics related to [performance](#performance).

- first paint — **first render**
- first contentful paint (FCP) — **first contentful render**
- first meaningful paint — **first meaningful rendering**
- visually ready — **visually ready**
- visually complete — **visual completeness**
- first interactive — **first interactivity**
- estimated input latency — **expected input latency**
- time to interactive (TTI) — **time to first interactivity**
- time to first consistently interactive — **time to stable interactivity**
- largest contentful paint (LCP) — **the largest significant rendering**
- cumulative layout shift (CLS) — **cumulative layout change**
- total blocking time (TBT) — **total blocking time**
- first input delay (FID) — **response time for the first interaction**

### prolyfill

**prolyfill,** one of the variants of [polyfil](#polyfill), which distinguishes itself by reproducing a _probable_ feature described in the specification, but not yet implemented in browsers.

### popup

** popup window, popup,** a separate window or interface element that appears on top of the current one, e.g. _annoying popup._

### position

**positioning**

- position: static — **static**
- position: absolute — **absolute**
- position: relative — **relative**
- position: fixed — **fixed**
- position: sticky — **pinned**

### preprocessor

**preprocessor,** a tool that converts code from one syntax to another, e.g. _Sass CSS preprocessor._

### progress bar

**Progress bar** or a progress indicator - an interface element that shows the progress of an operation.

### progressive enhancement

**progressive enhancement** - an approach in which all browsers get the same basic functionality, but in modern browsers this functionality is expanded to support new technologies. For example: gradients, vector graphics, video playback.

### Progressive Web App (PWA)

**progressive web application,** an approach to web application development that combines the advantages of conventional sites and native applications: fast loading, installation into the OS, offline work, push notifications, access to system APIs. The information for installation is described in the web manifest. The progressive approach consists in the fact that, for a normal browser - it is just a site, but for supporting browsers and operating systems - an application.

### promises

**promises,** a method for asynchronous script execution, in contrast to the use of callbacks.

### property

**property,** e.g. _CSS property_.

### proposed recommendation (PR)

**proposed recommendation,** status of the specification [W3C](#world-wide-web-consortium-w3c), a probable candidate for [recommendation](#recommendation-rec).

### pseudo-element

**pseudo element,** an additional internal element created with CSS and `::before` or `::after`.

### pseudo-class

**pseudo-class,** is used to bind a declaration to a certain state of a DOM element. Separated from the selector by a colon `:`. E.g., the rule block declaration with the `.item:hover` selector will be applied when `.item` is hovered over.

### pull request, pr

**pullrequest,** a request to accept changes to a repository branch, from a fork or another branch.

## Q

### quirks mode

**quirks mode,** a mode of interpreting and displaying the page by the browser, in which the browser deliberately avoids standards, in order to display documents created before the early 2000s and that relied on errors and features in the browsers of the time. Used for pages without [doctype](#doctype) and with obsolete doctypes (e.g. HTML 3.2).

## R

### radio button

**radio button,** a form element `<input type="radio">` for selecting one option among several ones, e.g. _radio button is checked._

### recalculate

**recalculation**

### recommendation (REC)

**recommendation,** final status of the [W3C](#world-wide-web-consortium-w3c) specification, recommended for implementation in browsers and for use by developers.

### registry

**registry,** a place to store packages, e.g. _GitHub Package Registry._ The "registry" term is an inaccurate translation, because it conflicts with the _character registry_ value used in the frontend.

### reflow

**reflow**

### rem

**rem,** a measurement unit in CSS that depends on the font size of the root element `<html>`, e.g. _font-size: 3rem — font size is 3 rem._

### render

**render**

### repaint

**repaint, rerender**

### reset

**reset,** usually, the resetting of default styles in CSS, e.g. _style reset file._

### resolution

**resolution,** the number of physical pixels on the screen of the device, e.g. _screen resolution is 1024×768 pixels._

### responsive design

**responsive design,** one of the technological methods for creating [adaptive design](#adaptive-design).

### Responsive Images Community Group (RICG)

**Responsive Images Community Group**

### rest parameters

**residual parameters,** (also _remaining parameters_, informal. _rest parameters_) syntax in JavaScript that allows unnamed function parameters to be represented as an array.

### root

**root**

### rounded corners

**rounded corners,** e.g. _rounded corners are out of fashion,_ see also. [rounded frames](#border-radius).

### row

**line, row**

- horizontal area in a table or layout.
- table element `<tr>`.

### rowspan

**row combination,** HTML attribute for combining multiple table cells into a single column.

### rule-set

**element styles block,** consists of a selector (or media query) and a declaration block.

## S

### shallow comparison

**superficial comparison,** a comparison that checks if two variables refer to the same object in the memory.

### scaffolding

**scaffolding,** automatic code generation from a description, a metaprogramming method.

### scale

1. noun. **scale**
2. verb. **to scale**

### scope

**scope,** the limited part of the program structure in which a declared variable is available or `<style scoped>` styles are applied.

### screen reader

**screen reader,** a program that reads aloud information from the device's screen, a kind of assistive technology. They are used by visually impaired people who find it easier to receive information by ear, by people with dyslexia, by blind or partially sighted people. e.g. _they use screen reader to navigate the web_, _screen reader will say “image cat”_.

### script

**script,** instructions that describe the behavior of the pages, e.g. _scripts are not loaded yet._

### scroll

1. **scroll,** interface element to move the hidden part of a page or block, it is an indication that the nested element is larger than the parent, e.g. _horizontal scroll is disabled._
2. **to scroll,** to move the hidden part of a page or block.

### scrollbar

**scrollbar,** the formal name is [scroll](#scroll), e.g. _system scrollbars._

### sectioning roots

**structural roots**

### semantics

**semantics,** the semantic content of HTML elements, e.g. _semantic coding._

### selector

**selector,** the necessary structural part of the [style block](#rule-set). Is responsible for linking declarations to DOM elements.

- simple selector — can be a [pseudo-class](#pseudo-class) or one of the following types:
  - type selector — addresses a tag, e.g. `ul`, `input` и др.
  - universal selector — **universal selector,** " asterisk ": `*`.
  - ID selector — **selector by identifier,** e.g. `#content`.
  - class selector — **class selector,** e.g. `.item`.
  - attribute selector — **attribute selector,** напр. `[type=submit]`.
- compound selector (other. sequence of simple selectors) — a sequence of simple selectors not separated by combinators, e.g. `input[type=submit]:focus`.
- complex selector — several simple and/or compound selectors separated by combinators:
  - descendant selector — **descendant selector,** e.g. `ul li`.
  - child selector — **direct descendant selector,** e.g. `#buttons > *`. Also often referred to as **child**.
  - adjacent sibling selector — **adjacent sibling selector,** e.g. `.item + .item`. Also often referred to as **sibling**.
  - general sibling selector — **general sibling selector,** e.g. `.item ~ .item`.

### server-side

**server-side,** area of technologies running on the server, often a synonym for [backend](#back-end).

### shadow DOM

**shadow DOM, shadow document model**

### shapes

**shapes, CSS shapes**

### shared

1. adj. **shared,** e.g. _shared memory_
2. adj. **shared,** e.g. _shared folder — public folder_, _shared access — public access_

### shim

**shim,** code that helps unifying the browser functionality, usually implements missing or normalizes existing support, e.g. _HTML5 shim for IE8._

### sibling

**sibling** (in the sense of "sibling element").

### sidebar

**sidebar,** the side part of a website, with secondary content, e.g. _sidebar is on the right side._

### skew

1. noun. **skew**
2. verb. **tilt**

### source maps

**source maps,** special markup to match source files and compiled code for debugging.

### specification, spec

**specification,** technology documentation for browser developers and manufacturers, usually in one of the following statuses: proposed or approved by the W3C, e.g. _specification draft._

### spread

**spread,** operator in JavaScript that spreads expressions to places where multiple arguments are expected when calling functions `doSomething(...array)`, multiple elements in arrays `[1, 2, ...array]`) are expected, and addition or overwrite of fields in `{ ...object, field: 'value' }` objects is expected.

### specificity

**specificity,** The [CSS selector ](#selector) characteristic that defines its priority [in the cascade](#cascade). It is composed by the weight of each [simple selector](#selector) in its composition.

### stacking context

**stacking content,** element of the visual page structure that limits the action of the `z-index` property of its descendants and is placed along the _z_ axis as a whole (either entirely on top of or entirely under any other element). e.g. _elements with opacity create new stacking context._

### staging server

**staging server,** server where a product is tested and debugged.

### standards mode, standards compliance mode

**standard mode,** interpretation and display mode of the page by the browser, in which the browser is required to follow the standards as closely as possible. Used for pages with more or less modern [doctypes](#doctype), e.g. doctype HTML5.

### statement

**statement,** CSS structural element. This can be an element style block, an import directive, a media query, etc.

### string

1. **string type,** in programming - a data type, which values are an arbitrary sequence (string) of alphabetic characters.
2. **string,** in CSS, it is the string value of a directive or property. e.g., in `content: "\201d"` the string is `"\201d"`.

### stub object

**placeholder**

### style

1. noun. **styles,** e.g. _apply styles to an element._ The plural is preferred: _element styles,_ not _element style_ (wrong).
2. verb. **to style,** e.g. _how to style selects,_ is preferable to the ambiguous "stylize".

### style guide

**style guide,** e.g. _project code style guide_.

### stylesheet

**stylesheet,** e.g. _document stylesheet_.

### swipe

**swipe,** gesture to control a touch screen interface: swiping your fingers across the touch screen.

### submit

**submit,** e.g. _form submission_.

## T

### tab

1. **tab,** one of the layers of a website or program interface, which is activated by selecting its label, e.g. _open in new tab._
2. **tab,** tab key, inserts the tab character, switches the focus to the next interface element, or completes a partially typed word, e.g. _press Ctrl Tab._
3. **tab,** tab character, has a configurable width and is used to indent code, e.g. _tabs are better than spaces._

### tag

1. **tag,** tags in HTML, there are opening, closing and single tags. e.g. _closing tag is missing._
 - tag name — **tag name**
 - start tag — **opening tag**
 - end tag — **closing tag**
2. **tag,** content marker, usually a short word.

### tap

**tap,** gesture to control a touch screen interface: tap once on the touch screen.

### text

**text**

### textarea

**text area,** form element for entering multiple lines of text.

### text-align

**alignment,** orientation of the text lines in a certain direction, or evenly across the width of the block.

- text-align: left — **to the left**
- text-align: right — **to the right**
- text-align: justify — **justify**

### text-shadow

**shadow (of the text),** e.g. _text-shadow is red._

### throttling

**throttling,** the introduction of artificial restrictions, for example, to reduce the frequency of calls to event handlers in JavaScript, or network speed and CPU power during tests.

### thumb

1. Abbreviation of [thumbnail](#thumbnail).
2. **slider,** element for controlling the [scrollbar](#scrollbar).

### thumbnail

**thumbnail,** a reduced copy of an image.

### title

1. **title,** if it is a `<title>` element, or the title of an element.
2. **hint,** when it comes to the attribute `title=""`.

### toggle

**toggle,** to toggle from one state to another, _toggle classes._

### tooltip

**tooltip,** auxiliary information that appears when you hover over an element or when it is activated, such as `title=""`.

### touch interface

**touch interface**

### transform

**transform,** e.g. _transform: scale(2) — transformation by scaling by a factor of 2._

### transition

**transition,** e.g. _transition: all 2s linear — a linear transition with a duration of 2 seconds._

### translate

**to relocate,** to move an object using CSS transformations, e.g. _translate(x, y) — move to X and Y._

### transpiler

**transpiler,** A compiler that converts source code in one programming language into source code in another programming  language.

### typography

**typography,** text formatting using font, line options, and more.

## U

### unit

**unit of measurement,** e.g. _rem unit — unit of measurement "rem"._

### unit testing

**unit testing**

### URI

**unified resource identifier,** a sequence of characters that identifies an abstract or physical resource.

### URL

1. _informal._ **address**. The recommended meaning for use when translating articles.

2. **unified resource index,** [URI](#uri), which also provides information about the location of this resource, e.g. _background: url("http://www.example.com/picture.png")_

### user experience (UX)

**user experience,** the sum of the sensations resulting from interaction with something (interface, device, product). In our context, it is recommended to use the abbreviation UX (e.g, _UX Specialist_).

### user interface (UI)

**user interface,** in a transparent context, it is recommended to use simply "interface".

### utility

**utility,** a program with a narrow purpose.

## V

### valid

**valid,** in accordance with a standard, specification, or other regulation, e.g. _valid markup_.

### validator

**validator,** a mean to verify compliance with a standard, specification, or other regulation (see [valid](#valid)), e.g. _W3C markup validator_.

### value

**value,** e.g. _CSS property value_.

### variable units

**variable units,** — custom properties that can be used as units of measurement in CSS. It is acceptable to use it in abbreviated form, without the word "measurement", e.g. _variable units make this easier to write._

### vendor prefix

**vendor prefix,** CSS property prefix `-webkit-` or `-moz-`, e.g. _add vendor prefixes._

### vendor files

**vendor files,** styles, scripts and other resources (dependencies) from other authors, used in the project, e.g. _tons of vendor scripts included in the code_

### vertical-align

**vertical align,** vertical arrangement of elements within a line of text or table.

### viewport

**viewport**

1. the visible area of a document within the screen.
2. `<meta name="viewport">` element controlling the adaptation of pages on mobile devices.

## W

### website, web site

**site,** combined under one page address, the translation "website" is redundant.

### worker

**worker,** an interface in JavaScript that allows a script to be executed in a non-primary thread.

- web worker — **web worker**
- service worker — **service worker**
- shared worker — **shared worker**

### working draft (WD)

**working draft,** early specification status [W3C](#world-wide-web-consortium-w3c).

### worklet

**worklet,** a class in JavaScript that has pre-defined methods with a specific signature, giving access to various browser APIs. [Project Houdini](https://github.com/w3c/css-houdini-drafts/wiki) provides for the following types of worklets:

- paint worklet — **rendering worklet**
- compositor worklet — **compositor worklet**
- layout worklet — **layout worklet**

### World Wide Web Consortium (W3C)

**World Wide Web Consortium,** the organization that develops web standards.

### web standards

**web standards**

### width

**width**

### word-spacing

**word spacing**

### workaround

**workaround,** a way of solving a problem under restricted conditions, e.g. _to figure out workaround._
