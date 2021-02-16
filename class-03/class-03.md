
# HTML Lists, Control Flow with JS, and the CSS Box Model

# LIST

**Numbered list**

The ordered list is created with the `<ol>` element

The unordered list is created with the `<ul>` element

Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag.

---

**Defention list**


The definition list is created withthe `<dl>` element and usuallyconsists of a series of terms andtheir definitions. Inside the `<dl>` element you willusually see pairs of `<dt>` and `<dd>` elements. This is used to contain the term being defined (the definition
term). & `<dd>` used to contain the definition.

***

**Nested list**

You can put a second list inside an `<li>` element to create a sublist or nested list


***

**Box Dimensions CSS**

html
```html
<div>
<p>The Moog company pioneered the commercial
manufacture of modular voltage-controlled
analog synthesizer systems in the early
1950s.</p>
</div>
```

css
```CSS
div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
p {
height: 75%;
width: 75%;
background-color: #0088dd;}
```

***

**limiting width** *or height*

html
```html
<tr>
<td><img src="images/rhodes.jpg" width="200"
height="100" alt="Fender Rhodes" /></td>
<td class="description">The Rhodes piano is an
electro-mechanical piano, invented by Harold
Rhodes during the fifties and later
manufactured in a number of models ...</td>
<td>$1400</td>
</tr>
```

css
```css
td.description {
min-width: 450px;
max-width: 650px;
text-align: left;
padding: 5px;
margin: 0px;}
```

***

**Overflow**

The overflow property tells the browser what to do if the content contained within a box is larger than the box itself.


html
```html
<h2>Fender Stratocaster</h2>
<p class="one">The Fender Stratocaster or "Strat"
is one of the most popular electric guitars of
all time, and its design has been copied by many
guitar makers. It was designed by Leo... </p>
<h2>Gibson Les Paul</h2>
<p class="two">The Gibson Les Paul is a solid body
electric guitar that was first sold in 1952.
The Les Paul was designed by Ted McCarty... </p>
```

css
```css
p.one {
overflow: hidden;}
p.two {
overflow: scroll;}
```

***

**Border, margin & padding**

![](https://i.ytimg.com/vi/RMNHZsDUZMo/maxresdefault.jpg)


```css
p.example {
padding: 10px;
margin: 20px;
}
```

***

**Centering content**

```
margin: 10px auto 10px auto;
text-align: left;
```

***

**Changing inline block**

html
```html
<ul>
<li>Home</li>
<li>Products</li>
<li class="coming-soon">Services</li>
<li>About</li>
<li>Contact</li>
</ul>
```

css
```css
li {
display: inline;
margin-right: 10px;}
li.coming-soon {
display: none;}
```
***

**Boeder img**


```
p.one {
-moz-border-image: url("images/dots.gif")
11 11 11 11 stretch;
-webkit-border-image: url("images/dots.gif")
11 11 11 11 stretch;
border-image: url("images/dots.gif")
11 11 11 11 stretch;}
p.two {
-moz-border-image: url("images/dots.gif")
11 11 11 11 round;
-webkit-border-image: url("images/dots.gif")
11 11 11 11 round;
border-image: url("images/dots.gif")
11 11 11 11 round;}
```

**hiding boxing visibility**


```css
li {
display: inline;
margin-right: 10px;}
li.coming-soon {
visibility: hidden;}
```

***

**border width**

html
```html
<p class="one">Hohner's "Clavinet" is essentially an
electric clavichord.</p>
<p class="two">Hohner's "Clavinet" is essentially an
electric clavichord.</p>
<p class="three">Hohner's "Clavinet" is essentially
an electric clavichord.</p>
```

css
```css
p.one {
border-width: 2px;}
p.two {
border-width: thick;}
p.three {
border-width: 1px 4px 12px 4px;}
```

And you can use another properety for borders like **border-style** and **boeder=color**.

***

**box shadows**

```css
p.one {
-moz-box-shadow: -5px -5px #777777;
-webkit-box-shadow: -5px -5px #777777;
box-shadow: -5px -5px #777777;}
```


***border corner**

```
border-radius: 10px;
```

**elliptical shapes**

```
-moz-border-radius: 100px;
-webkit-border-radius: 100px;}
```

***




# Basic JavaScript Instructions



**ARRAYS**


An array is a special type of variable. It doesn't just store one value; it stores a list of values.

*array literal*

```java
var colors;
colors ['white', 'black', 'custom '];
var el document.getElementByld('col ors');
el . textContent = col ors[O];
```


OR *array constructor*

```java
var colors
new Array('white ' ,
'black',
'custom ' );
var el = document.getElementByid( 'colors ' );
el.innerHTML = colors.item(O);
```


***

**ACCESSING & CHANG ING VALUES IN AN ARRAY**

```java
II Create the array
var colors = ['white',
'black' ,
'custom'];
II Update the third item in the array
colors[2] = 'beige ' ;
II Get the element with an id of col ors
var el = document .getElementByid(' colors') ;
II Replace with third item from the array
el .textContent = colors[2];
``` 

***
***


## if & eslse statment

![](https://www.kirupa.com/html5/images/if_else_72.png)

An if statement only runs a set of statements if the condition is true & An if... e1se statement runs one set of code if the condition is true or a different set if it is fa1se.

*try it in your VS*

```javascript
var pass =50;
var score = 75;
var msg;
II Pass mark
II Current score
II Message
II Select message to write based on score
if (score >= pass) {
msg = 'Congratulations, you passed!';
} else {
msg = 'Have another go!';
var el = document .getElementByld('answer');
el .textContent = msg;
```

**notes:** IF... ELSE


- There is no need to provide an el se option. (You can just use an if statement.)


- With a series of if statements, they are
all checked even if a match has been found
(so it performs more slowly than switch).



***

**SWITCH STATEMENTS**

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.


![](https://detriamelia.com/berkas/2020/01/PHP-Switch-Statement.jpg)


**notes:** 

SWITCH
* You have a default option that is run if none of the cases match.
* If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple i f
statements).


***


**TYPE COERCION & WEAK TYPING**

DataType | purpose
---------|---------
srting | text
number | number
boolean | true, false
null | empety value
undefined | Variable has been declared but not yet assigned a value


**notes**

* Data types can be coerced from one type to another.

* All values evaluate to either truthy or falsy.

* A unary operator returns a result with just one operand.

* Logical operators are processed left to right. They short-circuit (stop) as soon as they have a result - but they return the value that stopped the processing (not necessarily true or fa 1se).

***



 ![](https://i.ytimg.com/vi/wFB-ywsNPwg/maxresdefault.jpg)

 ***


## LOOPS


Loops are handy, if you want to run the same code over and over again, each time with a different value.

![](https://th.bing.com/th/id/R181d33980a4bd27fe021b8aec8ef94f9?rik=aQ%2bAGJ6n0TgiYw&riu=http%3a%2f%2fwww.w3resource.com%2fw3r_images%2ffor-loop.gif&ehk=035cg%2bza7mjMDeKsCvIKt0JH1lWz7pcJrHl35pURgJA%3d&risl=&pid=ImgRaw)

***


## THE MOST COMMON TYPES OF LOOPS:

***

###  **For loop** :
 Is used for iterating over a sequence.

*example*


```java
var sum = 0;
for (var i = 1; i <= 50; i++) {
   sum = sum + i;
}
alert("Sum = " + sum);    // => Sum = 1275
```
**Sum = 1275**

***

###  **While loop**
is used to repeat a section of code an unknown number of times until a specific condition is met.

*example*

```java
var sum = 0;
var number = 1;
while (number <= 50) {  // -- condition
  sum += number;        // -- body
  number++;             // -- updater
}
alert("Sum = " + sum);  
```
**Sum = 1275**


***

**Do while loop**

The key difference between a whi 1e loop and a do whi 1 e loop is that the statements in the code block come before the condition. This means that those statements are run once whether or not the condition is met.

```java
var i = l;
var msg : I I ••
II Set counter to 1
II Message
II Store 5 ti mes table in a variable
do {
msg += i + ' x 5 = ' + (i * 5) + '<br I>' ;s
i++;
} whil e ( i < 1) ;
II Note how this is already 1 and it still runs
document .getEl ementByld(' answer').innerHTML = msg;
```


***



*sources:*
*ducket javascript |*
*ducket HTML CSS*

[HomePage](https://wafaankoush99.github.io/Reading-Notes/READMEcode201.html)  


contact wafadirawe@gmail.com




