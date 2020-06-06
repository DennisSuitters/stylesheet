#Contributing
We welcome contributions, and hope that you follow the below guide when doing so.

###How to organize Declarations & Values.
The shorthand (first declaration in a block of declarations) for some follows with the longhand attribute in the order they are used in the shorthand version (WIP).

The declarations or ordered in a concentric pattern as linted by the [CSS declaration Sorter](https://github.com/Siilwyn/css-declaration-sorter-atom) plugin in Atom. We recommend using some sort of Linter to make cleaning up easier.

We've included where we can the values allowed as gleaned from [CSS Tricks](https://css-tricks.com/almanac/properties/)

  Inheritance
````
    @extend
    @include
    @mixin
````

  Class Attributes-
````
all: [initial|inherit|unset];
display: [inline|inlie-block|block|run-in|none|flex|flow-root|grid|table|table-cell|table-column|table-colgroup|table-header_group|table-row-group|table-footer-group|table-row|table-caption];
position: [static|relative|absolute|fixed|sticky|inherit];
top: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
right: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
bottom: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
left: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
offset-inline-start: ;
offset-inline-end: ;
offset-block-start: ;
offset-block-end: ;
grid: ;
grid-template-rows: [info](https://css-tricks.com/almanac/properties/g/grid-rows-columns/);
grid-template-columns: [info](https://css-tricks.com/almanac/properties/g/grid-rows-columns/);
grid-auto-rows: ;
grid-auto-columns: ;
grid-auto-flow: ;
grid-column-gap: ;
grid-row-gap: ;
grid-area: ;
grid-row-start: ;
grid-row-end: ;
grid-column: [info](https://css-tricks.com/almanac/properties/g/grid-row-column/);
grid-column-start: ;
grid-column-end: ;
grid-row: [info](https://css-tricks.com/almanac/properties/g/grid-row-column/);
grid-template: ;
grid-template-areas: ;
flex: [none|[<flex-grow> <flex-shrink> || <flex-basis]];
flex-basis: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
flex-direction: [row|row-reverse|column|column-reverse];
flex-flow: <flex-direction> || <flex-wrap>;
flex-grow: <num 1 or 2>;
flex-shrink: <num 1 or 2>;
flex-wrap: [nowrap|wrap|wrap-reverse];
box-decoration-break: [slice|clone]
place-content: ;
align-content: [flex-start|flex-end|center|space-between|space-around|stretch];
justify-content: [flex-start|flex-end|center|space-between|space-around|space-evenly];
place-items: [auto|normal|stretch|start|end|center|left|right|flex-start|flex-end|self-start|self-end|first baseline|last baseline];
align-items: [flex-start|flex-end|center|baseline|stretch];
justify-items: [stretch|center|start|end];
place-self: ;
align-self: [flex-start|flex-end|center|baseline|stretch];
justify-self: [stretch|center|start|end];
vertical-align: [baseline|top|bottom|middle|text-top|text-bottom|sub|super|length];
order: [order];
float: [none|left|right|inherit];
clear: [both|left|right];
shape-margin: ;
shape-outside: [circle()|ellipse()|inset()|polygon()|url()|initial|inherit]; [info](https://css-tricks.com/almanac/properties/s/shape-outside/)
shape-image-threshold: ;
orphans: ;
columns: <width> || <count>;
column-gap: [normal|px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
column-fill: [balance|auto];
column-rule: <width> <style> <color>;
column-rule-width: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
column-rule-style: [solid|dotted|dashed];
column-rule-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
column-width: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
column-span: [all|none];
column-count: [auto|x];
break-before: ;
break-after: ;
break-inside: ;
page-break-before: [auto|always|avoid|left|right];
page-break-after: [auto|always|avoid|left|right];
page-break-inside: [auto|avoid];
transform: [scale()|skewX()|skewY()|translate()|rotate()|matrix()|perspective()];
transform-box: ;
transform-origin: [info](https://css-tricks.com/almanac/properties/t/transform-origin/);
transform-style: [info](https://css-tricks.com/almanac/properties/t/transform-style/);
rotate: ;
scale: ;

perspective: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
perspective-origin: [info](https://css-tricks.com/almanac/properties/p/perspective-origin/);
visibility: [visible|hidden|collapse|inherit];
opacity: [0 - 1 in .01 increments];
z-index: [integer];
mix-blend-mode: [initial|inherit|unset|normal|multiply|screen|overlay|darken|lighten|color-dodge|color-burn|hard-light|soft-light|difference|exclusion|hue|saturation|color|luminosity];
backface-visibility: [visible|hidden|inherit|initial];
backdrop-filter: ;
clip-path: ;
mask: ;
mask-image: ;
mask-mode: ;
mask-position: ;
mask-size: ;
mask-repeat: ;
mask-origin: ;
mask-clip: ;
mask-composite: ;
mask-type: ;
filter: [blur()|brightness()|contrast()|drop-shadow()|grayscale()|hue-rotate()|invert()|opacity()|saturate()|sepia()|url()];
animation: <name> <duration> <timing function> <iteraction-count> <fill-mode> <play-state>;
animation-name: [none|"animation name"];
animation-duration: [0s|Xs|Xms];
animation-timing-function: [ease|ease-out|ease-in|ease-in-out|linear|cubic-bezier(x1, y1, x2, y2)];
animation-delay: [0s|Xs|Xms];
animation-iteration-count: [1|X];
animation-direction: [normal|alternate];
animation-fill-mode: [none|forwards|backwards|both];
animation-play-state: [running|paused|running];
transition: <transition-property> <transition-duration> <transition-timing-function> <transition-delay>;
transition-delay: [s/ms];
transition-duration: [s/ms];
transition-property: [property name];
transition-timing-function: [ease|linear|ease-in|ease-out|ease-in-out|step-start|step-end];
will-change: ;
counter-increment: ;
counter-reset: ;
cursor: [auto|default|none|context-menu|help|pointer|progress|wait|cell|crosshair|text|vertical-text|alias|copy|move|no-drop|not-allowed|all-scroll|col-resize|row-resize|n-resize|e-resize|s-resize|w-resize|ns-resize|ew-resize|ne-resize|nw-resize|se-resize|sw-resize|nesw-resize|nwse-resize];

box-sizing: [content-box|padding-box|border-box|inherit];
margin: <top> <right> <bottom> <left>;
margin-top: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
margin-right: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
margin-bottom: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
margin-left: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
margin-inline-start: ;
margin-inline-end: ;
margin-block-start: ;
margin-block-end: ;
outline: <width> <style> <color>;
outline-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
outline-style: [solid|none|hidden|dashed|dotted|double|groove|ridge|inset|outset];
outline-width: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
outline-offset: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
box-shadow: [horizontal offset] [vertical offset] [blur radius] [optional spread radius] [color];
border: <width> <style> <color>;
border-top: <width> <style> <color>;
border-right: <width> <style> <color>;
border-bottom: <width> <style> <color>;
border-left: <width> <style> <color>;
border-width: [[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]|thin(1px)|medium(3px)|thick(5px)];
border-top-width: [[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]|thin(1px)|medium(3px)|thick(5px)];
border-right-width: [[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]|thin(1px)|medium(3px)|thick(5px)];
border-bottom-width: [[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]|thin(1px)|medium(3px)|thick(5px)];
border-left-width: [[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]|thin(1px)|medium(3px)|thick(5px)];
border-style: [solid|none|hidden|dashed|dotted|double|groove|ridge|inset|outset];
border-top-style: [solid|none|hidden|dashed|dotted|double|groove|ridge|inset|outset];
border-right-style: [solid|none|hidden|dashed|dotted|double|groove|ridge|inset|outset];
border-bottom-style: [solid|none|hidden|dashed|dotted|double|groove|ridge|inset|outset];
border-left-style: [solid|none|hidden|dashed|dotted|double|groove|ridge|inset|outset];
border-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
border-top-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
border-right-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
border-bottom-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
border-left-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
border-radius: [all|horizontal/vertical|<top left> <top right> <bottom right> <bottom left>];
border-top-left-radius: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
border-top-right-radius: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
border-bottom-left-radius: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
border-bottom-right-radius: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
border-inline-start: ;
border-inline-start-width: ;
border-inline-start-style: ;
border-inline-start-color: ;
border-inline-end: ;
border-inline-end-width: ;
border-inline-end-style: ;
border-inline-end-color: ;
border-block-start: ;
border-block-start-width: ;
border-block-start-style: ;
border-block-start-color: ;
border-block-end: ;
border-block-end-width: ;
border-block-end-style: ;
border-block-end-color: ;
border-image: <source> <slice> <width>;
border-image-outset: [0|[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]];
border-image-repeat: [stretch|repeat|round|space];
border-image-slice: [100%|fill|[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]];
border-image-source: [none|url|data:image];
border-image-width: [auto|[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]];
border-collapse: [seperate|collapse];
border-spacing: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
background: <image> <position> <size> <repeat> <origin> <clip> <attachment> <color>;
background-image: [none|url|data:image];
background-position: [0% 0%|[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]|percentage|top|right|bottom|left];
background-size: [auto auto|[px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%]|auto|cover|contain];
background-repeat: [repeat|repeat-x|repeat-y|no-repeat|space|round];
background-origin: [padding-box|border-box|content-box|inherit];
background-clip: [border-box|padding-box|content-box|inherit];
background-attachment: [scroll|fixed|local];
background-color: [transparent|rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
background-blend-mode: ;
background-position-x: ;
background-position-y: ;
isolation: [isolate|auto];
padding: <top> <right> <bottom> <left>;
padding-top: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
padding-right: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
padding-bottom: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
padding-left: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
padding-inline-start: ;
padding-inline-end: ;
padding-block-start: ;
padding-block-end: ;
image-orientation: ;
image-rendering: ;

width: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
min-width: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
max-width: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
height: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
min-height: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
max-height: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
inline-size: ;
min-inline-size: ;
max-inline-size: ;
block-size: ;
min-block-size: ;
max-block-size: ;
table-layout: [auto|fixed|inherit];
caption-side: [top|bottom|inherit];
empty-cells: [show|hide|inherit|initial|unset];
overflow: [visible|hidden|scroll|auto|inherit];
overflow-x: [visible|hidden|scroll|auto|inherit];
overflow-y: [visible|hidden|scroll|auto|inherit];
resize: [none|both|horizontal|vertical|inherit];
object-fit: [fill|contain|cover|none];
object-position: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%] [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
scroll-behavior: [auto|smooth];
scroll-snap-coordinate: ;
scroll-snap-destination: ;
scroll-snap-type: ;
touch-action: [all|none|pan-x|pan-y|manipulation|pan-left|pan-right|pan-down|pan-up|pinch-zoom];
pointer-events: [none|auto|inherit];

ruby-align: ;
ruby-position: ;
color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
caret-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
font: ;
font-style: [normal|italic|oblique];
font-variant: [normal|small-caps|all-small-caps|petite-caps|all-petite-caps|titling-caps|unicase];
font-weight: [normal(400)|bold(700)|bolder(900)|lighter(100)];
font-stretch: [normal|ultra-condensed|extra-condensed|condensed|semi-condensed|semi-expanded|expanded|extra-expanded|ultra-expanded];
font-size: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
font-family: ;
line-height: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
font-feature-settings: ;
font-kerning: ;
font-language-override: ;
font-optical-sizing: ;
font-size-adjust: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
font-synthesis: :
font-variant-alternates: ;
font-variant-caps: ;
font-variant-east-asian: ;
font-variant-ligatures: ;
font-variant-numeric: ;
font-variant-position: ;
hyphens: ;
initial-letter: ;
initial-letter-align: ;
letter-spacing: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
line-break: ;
list-style: <list-style-type> || <list-style-position> || <list-style-image>;
list-style-type: [disc|circle|square|decimal|decimal-leading-zero|lower-roman|upper-roman|lower-greek|lower-latin|upper-latin|armenian|georgian|lower-alpha|upper-alpha|none];
list-style-image: <image-url>;
list-style-position: [inside|outside];
writing-mode: ;
direction: [ltr|rtl|inherit];
unicode-bidi: ;
unicode-range: ;
user-select: [all|none];
text-combine-upright: ;
text-align: [left|right|center|justify|inherit];
text-align-last: [left|right|center|justify|start|end|auto|inherit];
text-decoration: [none|underline|line-through|overline|inherit];
text-decoration-line: [none|underline|overline|line-through|inherit];
text-decoration-style: [solid|double|dotted|dashed|wavy];
text-decoration-color: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
text-decoration-thickness: ;
text-decoration-skip: [objects|none|spaces|ink|edges|box-decoration];
text-decoration-skip-ink: ;
text-emphasis: ;
text-emphasis-style: ;
text-emphasis-color: ;
text-emphasis-position: ;
text-indent: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
text-justify: [inter-word|inter-character|auto|none];
text-underline-position: [auto|inherit|under|left|right];
text-orientation: ;
text-overflow: [clip|ellipsis|ellipsis-word];
text-rendering: [auto|optimizeSpeed|optimizeLegibility|geometricPrecision];
text-shadow: <x> <y> <blur> <color>;
text-size-adjust: ;
text-transform: [lowercase|uppercase|capitalize|none|inherit];
white-space: [normal|pre|nowrap|pre-wrap|pre-line];
word-break: [normal|break-all|keep-all];
word-spacing: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
overflow-wrap: [normal|break-word|inherit];
quotes: ;
tab-size: [px|in|cm|mm|em|rem|pt|pc|ex|ch|vw|vh|vmin|vmax|%];
content: ["text"|counter(my-counter)|image-url|attr(data-visual-label)] / [alternate fallback];
widows: ;

grid-gap: ;
zoom: [<percentage>|<number>|normal];
block-overflow: [clip|ellipsis|<string>]
overflow-anchor: [auto|none];
overscroll-behavior: [contain|none];
text-underline-offset: [auto|<length>|<percentage>|initial|inherit|unset];
line-clamp: [none|<integer>];
word-wrap: [normal|break-word|initial|inherit];
fill: [rgb()|rgba()|<code>hsl()|hsla()|<hex-color>|<named-color>|currentcolor];
font-smoothing: ;
osx-font-smoothing: ;
font-display: [auto|block|swap|fallback|optional];
contain: [none|strict|content|[size || layout || style || paint]];
offset: ;
offset-position: ;
offset-path: [info](https://css-tricks.com/almanac/properties/o/offset-path/);
offset-distance: [length|<percentage>];
offset-anchor: [auto|position<percentage><length>];
offset-rotate: [info](https://css-tricks.com/almanac/properties/o/offset-rotate/);
````

#### Pseudo-classes & Pseudo-elements (nested rules)
We've tried to group these into some sort of logical grouping (WIP).

````
:root

:before / :after (Single for ie8 support)

:link
:active
:any-link
:focus
:focus-visible
:focus-within
:hover
:visited
:target

:blank
:default
:disabled
:empty
:enabled

:checked
:indeterminate
:invalid
::placeholder
:placeholder-shown
:read-write / :read-only
:required
:selection
:user-invalid
:valid

:dir()
:matches()
:is()
:not()
:in-range
:out-of-range

:lang()
:first-letter
:first-line
:first-child
:first-of-type
:last-child
:last-of-type
:nth-child
:nth-last-child
:nth-last-of-type
:nth-of-type
:only-child
:only-of-type

:marker
:optional
````
