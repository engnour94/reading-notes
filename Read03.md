#  Structure web pages with HTML

## What is HTML?
<br>

* HyperText Markup Language
* Tells the browser WHAT the content is
## HTML Tags
* There are opening tags
* There are closing tags
* And there are self-closing tags


## New Html5 Layout Elements
![image](sss.png)

### HTML elements
 Each HTML element tells the browser something about the information that sits between its opening and closing tags.

#### < head >

<br>

Before the < body > element you will often see a <head> element. This contains information
about the page . You will usually find a < title >
element inside the < head > element. The contents of the <br> < title > element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or
on the tab for that page
<br>
>`<head>`
 >` <title>Title of the document</title>`
> `</head>`
<br>

#### < body >
You met the < body > element Everything inside this element is shown inside the main browser window. you can insert this element to orgnize the body
> `<body>`
  `<h1>This is a heading</h1>`
  `<p>This is a paragraph.</p>`
>`</body>`


##### Headers & Footers

The < header > and < footer > elements can be used for:
* The main header or footer that appears at the top or bottom of every page on the
site.

* The < header > element used to contain the site
name and the main navigation.
* The < footer > element contains copyright information, along with links to the privacy policy and terms and conditions.

#### Other elements
* The < nav > element is used to contain the major navigational blocks on the site such as the
primary site navigation.

<br>
e.g

>nav {
 > display: block;
>}

<br>

*  < a > Linking Around Block-Level Elements allows you to turn an entire block into a link.If the `<a>` tag has no href attribute, it is only a placeholder for a hyperlink.

<br>

`<a href="https://engnour94.github.io/reading-note">Reading notes by Nour</a>`

<br>

## Extra Markup

### DOCTYPEs
Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using
DOCTYPES tell browsers which version of HTML you
are using.
for HTML5
`<!DOCTYPE html>`
### Comments
If you want to add a comment to your code that will not be visible in the user's browser, you
can add the text between these characters:
`<!-- -->`
### Block Elements

Some elements will always appear to start on a new line in the browser window. These are known as block level elements. 
Examples of block elements are
`<h1>, <p>, <ul>, and <li>`
<br>


### Inline Elements

Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.

<br>

`<a>, <b>, <em>, and <img>.` 

### Escape Characters
There are also special codes that can be used to show symbols such as copyright and trademark, currency symbols, mathematical characters, and
some punctuation marks
![img](111.png)
<br>
## Process & Design

* It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
* Site maps allow you to plan the structure of a site.
* Wireframes allow you to organize the information that will need to go on each page. ![imag](11.png)

* Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
* You can differentiate between pieces of information using size, color, and style.
* You can use grouping and similarity to help simplify the information you present.














