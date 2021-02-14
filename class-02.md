# HTML Text, CSS Introduction, and Basic JavaScript Instructions

## Text



### Headings and paragraphs
* **Headings**
HTML has six "levels" of headings
E.g:
`<h5>This is a Level 5 Heading</h5>`
<h5>This is a Level 5 Heading</h5>

* **Paragraphs**
To create a paragraph, surround the words that make up the paragraph with an opening `<p>` tag and closing `</p>` tag.


### Bold, italic, emphasis

* **Bold**

By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.
The `<b>` element also represents a section of text that would be presented in a visually different way (for example key words in a paragraph) although the use of the `<b> `element does not imply
any additional meaning.

* **Italic**
`<i>`
By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic.
The `<i>` element also represents a section of text that would be said in a different way from surrounding content — such as technical terms, names of ships, foreign words, thoughts, or other terms that would usually be italicized.

<br>

* **Superscript & Subscrip**

`<sup>`
The `<sup>` element is used to contain characters that
should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power 

`<sub>`

The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas .
E.g:
`<p>On the 4<sup>th</sup> of September you will learn about E=MC<sup>2</sup>.</p>`
`<p>The amount of CO<sub>2</sub> in the atmosphere grew by 2ppm in 2009<sub>1</sub>.</p>`

result:
<p>On the 4<sup>th</sup> of September you will learn
 about E=MC<sup>2</sup>.</p>
<p>The amount of CO<sub>2</sub> in the atmosphere
 grew by 2ppm in 2009<sub>1</sub>.</p>

 * **White Space**
 In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines. When the browser comes across
two or more spaces next to each other, it only displays one space.
Similarly if it comes across a line break, it treats that as a single space too. This is known as white space collapsing.


* **Line Breaks & Horizontal Rules**

`<br />`
As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can
use the line break tag `<br />`.

`<hr />`
To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the `<hr />` tag.



### Structural and semantic markup

* **Structural markup:** the elements that you can use to
describe both headings and paragraphs
* **Semantic markup:** which provides extra information; such
as where emphasis is placed in a sentence, that something
you have written is a quotation (and who said it), the
meaning of acronyms, and so on such as:
`<strong>` ,`<em>`, `<blockquote>`,`<q>`,`<abbr>`

### Summary TEXT

* HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).

* They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).


## Introducing CSS

CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.
* CSS Associates Style rules with HTML elements
CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

<br/>



### How to use css?

* **Using External CSS**
`<link>` 
The `<link>`element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does
not need a closing tag), and it lives inside the `<head>`element. It should use three attributes:

   * **href**
This specifies the path to the CSS file (which is often placed in a folder called css or styles).
   * **type**
This attribute specifies the type of document being linked to. The value should be text/css.
    * **rel**
This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

* **Using internal CSS**
`<style>`
You can also include CSS rules within an HTML page by placing them inside a `<style>` element, which usually sits inside the `<head>` element of the page.
The `<style>` element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/css.

* **CSS Selectors**

![selectors](https://codeandwork.github.io/courses/cs/media/css-selectors.jpg)

### Summary INTRODUCING CSS
* CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
* Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
* Different types of selectors allow you to target your
rules at different elements.
* Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
* CSS rules usually appear in a separate document,
although they may appear within an HTML page.


## Basic Javascript Instructions

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement. Statements should end with a semicolon.
  note that: 
  * JavaScript codeis green
* M ulti-line comments are pink
* Single-line comments are gray 

### COMMENTS 

You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code. 
MULTI-LINE COMM ENTS
To write a comment that stretches over more than
one line, you use a multi-line comment, starting with
the /* characters and ending with the */ characters.
Anything between these characters is not processed·
by the JavaScript interpreter.

*  SINGLE-LINE COMMENTS
In a single-line comment, anything that follows the
two forward slash characters // on that line will not
be processed by the JavaScript interpreter. Singleline comments are often used for short descriptions
of what the code is doing. 

### VARIABLES
JavaScript variables are containers for storing data values.
All JavaScript variables must be identified with unique names.

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

**The general rules for constructing names for variables (unique identifiers) are:**

* Names can contain letters, digits, underscores, and dollar signs.
* Names must begin with a letter
* Names can also begin with $ and _ (but we will not use it in this tutorial)
* Names are case sensitive (y and Y are different variables)
* Reserved words (like JavaScript keywords) cannot be used as names
>JavaScript identifiers are case-sensitive.

**The Assignment Operator**
In JavaScript, the equal sign (=) is an "assignment" operator, not an "equal to" operator.

This is different from algebra. The following does not make sense in algebra:

x = x + 5
In JavaScript, however, it makes perfect sense: it assigns the value of x + 5 to x.

(It calculates the value of x + 5 and puts the result into x. The value of x is incremented by 5.)

The "equal to" operator is written like == in JavaScript.

* **DATA TYPES**
JavaScript distinguishes between numbers, strings, and true or false values known as Booleans. 

JavaScript variables can hold numbers like 100 and text values like "John Doe".

In programming, text values are called text strings.

JavaScript can handle many types of data, but for now, just think of numbers and strings.

Strings are written inside double or single quotes. Numbers are written without quotes.

If you put a number in quotes, it will be treated as a text string.

**Declaring (Creating) JavaScript Variables**
Creating a variable in JavaScript is called "declaring" a variable.

You declare a JavaScript variable with the var keyword:

var carName;

After the declaration, the variable has no value (technically it has the value of undefined).

To assign a value to the variable, use the equal sign:

carName = "Volvo";


You can also assign a value to the variable when you declare it:

var carName = "Volvo";


### Arrays

JavaScript arrays are used to store multiple values in a single variable.
An array is a special variable, which can hold more than one value at a time.

If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

var car1 = "Saab";
var car2 = "Volvo";
var car3 = "BMW";

Creating an Array
Using an array literal is the easiest way to create a JavaScript Array.

Syntax:

var array_name = [item1, item2, ...];      

## DECISIONS AND LOOPS

EVALUATIONS
You can analyze values in
your scripts to determine
whether or note they
match expected results. 


DECISIONS
Using the results of
evaluations, you can
decide which path your
script should go down. 

LOOPS
There are also many
occasions where you will
want to perform the same
set of steps repeatedly. 

# OPERATORS AND LOOPS

## OPERATORS

### COMPARISON: OPERATORS (EVALUATING CONDITIONS)

**How they work?** Through evaluating a situation by comparing one value in the script to what you expect it might. The result will be a: Boolean **true or False**

* `==` is equal to
This operator compares two values : numbers strings Or Booleans to See if they are the same.

<br>

`let x =5`
<br>

`x == 8	     false`
 <br>

`x == 5	      true`
<br>

`x == "5"	  true`

<br>



<br>

* `!=` is not equal to
 This operator compares two values : numbers strings Booleans to if they are not the Same.

<br>

`let x =5`

<br>

 `x != 8	   true`

 <br>


 * `===` Strict  equal to
 This operator compares two  values to check that both value and equal type are the same
 
<br>

`let x =5`<br>
`x === 5	    true`<br>	
`x === "5"  	false` <br>

<br>

* `!==` Strict not equal to
This operator compares two  values to check that both value and equal type are not the same.

<br>

`let x =5`<br>
`x !== 5	   false`<br>	
`x !== "5"   	true`	<br>
`x !== 8	    true`<br>

<br>

* `>` Greater than

<br>

`let x =5`

 <br>

`x > 8	       false` 
<br>
<br>

* `< ` Less than

<br>

`let x =5`

<br>

`x < 8   	true`
<br>

 <br>

* `>=	` Greater than or equal to
<br>

`let x =5`
<br>

`x >= 8	    false`

<br>

<br>

* ` <=`	 less than or equal to
<br>

`let x =5`

<br>

`x <= 8	     true`
 <br>


### LOGICAL OPERATORS
Logical operators are used to determine the logic between variables or values.

Given that x = 6 and y = 3, the list below explains the logical operators:

* `&&`	and	(the result will be true only when the two values are true)

`(x < 10 && y > 1) is true`

* `||`	or (the result will be false only when the two values are false)

`(x == 5 || y == 5) is false`

* `!`	not 

`!(x == y) is true`

## LOOPS

Loops can execute a block of code a number of times.

### For loop
If you need to run code a specific number of ,times use a for loop  it is the most Common loop. 
In a for ,loop the condition is  usually a counter which is used  to tell how many times the loop should run

<br>

`for (init; condition; upadate) {statement;}`


### While loop

If you do not know how many times the code should,run you Can use a while loop. Here the condition be something other than a counter and the code will continue to loop for as long as the condition is true. 

`while (condition){statement; update;}`

### If Conditions

Conditional statements are used to perform different actions based on different conditions.

**Conditional Statements**

Very often when you write code, you want to perform different actions for different decisions.

You can use conditional statements in your code to do this.

In JavaScript we have the following conditional statements:

* Use if to specify a block of code to be executed, if a specified condition is true
* Use else to specify a block of code to be executed, if the same condition is false
* Use else if to specify a new condition to test, if the first condition is false
* Use switch to specify many alternative blocks of code to be executed
The if Statement
Use the if statement to specify a block of JavaScript code to be executed if a condition is true.

**Syntax**
if (condition) {
  //  block of code to be executed if the condition is true
}

**The else Statement**
Use the else statement to specify a block of code to be executed if the condition is false.

if (condition) {
  //  block of code to be executed if the condition is true
} else {
  //  block of code to be executed if the condition is false
}