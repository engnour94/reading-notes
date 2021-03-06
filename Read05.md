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

