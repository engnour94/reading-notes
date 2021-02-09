# Design web pages with CSS

## Color

### Foreground Color
The color property allows you to specify the color of text inside an element. You can specify any
color in CSS in one of three ways:

* rgb values
These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)

 * hex codes
These are six-digit codes that represent the amount of red, green and blue in a color,
preceded by a pound or hash #sign. For example: #ee3e80

* color names
There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

<br>
>/* color name */
h1 {
color: DarkCyan;}
/* hex code */
h2 {
color: #ee3e80;}
/* rgb value */
p {
color: rgb(100,100,90);}

### Background Color
CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.

>body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}

### Summery
Summary
COLOR
X Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
X There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
X Color pickers can help you find the color you want.
X It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
X CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
X CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.