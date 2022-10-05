# CODE EXAMPLES

### border
```css
section {
border-block: 8px solid blue;
border-inline: 8px solid green;
}
```
### @container
```css
@container (min-width: 700px) {
.card {
    display: grid;
    grid-template-columns: 2fr 1fr;
  }
}
```
### object-view-box
```css
img {
    aspect-ratio: 1;
    width: 300px;
    object-view-box: inset(25% 20% 15% 0%);
}
```

### @media
```css
@media (400px < width < 1000px) {
/* ... */
}
.item2 {
    color: #000;
    mix-blend-mode: overlay;
}
```

### filter
```css
.image{
  filter: contrast(175%) blur(5px)
}
```
### backdrop
```css
.box {
backdrop-filter: blur(10px);
}
```
### color()
```css
.brightest-green {
background: color(display-p3 0 1 0);
}
```

### currentcolor
```css
.blue-text {
  color: blue;
}
.blue-text .blue-background {
background: currentColor;
}
```

### color-mix()

```css
.teal {
  background: color-mix(in lab, white 20%, #34c9eb);
}
```
### calc()
```css
.foo {
    --color: #4488dd;
    background-color: hsl(from var(--color) h s calc(l * 1.2))
}
```
### overscroll-behavior
```css
.foo {
    height: 200px;
    overflow: auto;
    overscroll-behavior-y: contain;
}
```
### scrollbar-gutter
```css
.container {
    scrollbar-gutter: stable;
}
```
### prefers-contrast
```css
@media (prefers-contrast: more) {
    .contrast {
      outline: 2px solid black;
    }
}
```
### forced-colors
```css
@media (forced-colors: active) {
    .button {
      border: 2px green solid;
    }
}
```
### :has()
/* Matching <a> elements that directly contain an <img> */
```css
a:has(> img)
```
### :where()
Selects any paragraph inside a header, main
or footer element that is being hovered 
```css
:where(header, main, footer) p:hover {
    color: red;
    cursor: pointer;
}
```
### will-change
CSS Comparison Functions min(), max(), clamp() 
```css
.element {
	width: clamp(100px, 50vw, 600px);
}
```
### Shadow DOM ::part()
```css
custom-element::part(foo) {
/* Styles to apply to the `foo` part */
}
```
### image-set()
```css
.box {
	background-image: image-set(
	url("small-balloons.jpg") 1x,
	url("large-balloons.jpg") 2x);
}
```
### image()
```css
.foo {
	background-image: image("myimage.webp#xywh=0,20,40,60");
}
```
	
# RANDOM PROPERTIES

* [content-visibility](https://www.google.com/search?q=content-visibility)
* Accent-color
* touch-action
* line-clamp
* prefers-reduced-motion
* prefers-color-scheme
* prefers-reduced-data
* color-contrast()
* color-scheme
* :focus-visible2022
* ::marker
* @layer layer-name {rules}

