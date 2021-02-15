# HTML Text, CSS Introduction, and Basic JavaScript Instructions


*** 
***



## TEXT 

When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

***


**Heading**


HTML has six "levels" of headings: from `<h1>` for main heading to `<h6>` for subheading.

![](https://blog.shareaholic.com/wp-content/uploads/2013/01/1-headings.jpg)

***

**Paragraph**

You can write a paragraph by using `<p>` tag

```
<p> I am a paragraph </p>
```


***

**Bold**

This tag make the text appear bold

```
<b> bold text </p>
```

***

**Italic**

This tag make a text italic

```
<i> italic text </i>
```

***

**`<sup>`** & `<sub>`

The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power 

The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas.

![](https://th.bing.com/th/id/R4db0734ab30d014da3dec1c10e1d9661?rik=22MQM7fNZqlnNQ&riu=http%3a%2f%2fwww.roseindia.net%2ftutorialfiles%2f26927.Sub%2526Sup_TagPick.gif&ehk=2ByvSiUQ%2b0NomqxOw0Qxfq7dWCejw4TRonpEnTiWXI4%3d&risl=&pid=ImgRaw)

***

**`<br />`**

If you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />`.

![](https://3.bp.blogspot.com/-I6ZYg9Vc1cU/XBEUw0vu7GI/AAAAAAAACy4/SOOGbLOmf6AjDd7nmc77_WCI9obSzEM1ACLcBGAs/s1600/html-br-tag.jpg)


***

**`<hr />`**


To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the `<hr />` tag.


![](https://1.bp.blogspot.com/-1s3Bd17saH0/XBEUaqoeTUI/AAAAAAAACyw/GZekd5CU1y0J6PUtgmxR266UB2FFIi5hQCEwYBhgL/s1600/html-hr-tag.jpg)

***

### **Semantic markup**

There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages.

**`<strong>`**


The use of the `<strong>` element indicates that its content has strong importance.

![](https://tutorialsplane.com/wp-content/uploads/2015/08/strong-tag-example.png)


***

**`<em>`**
The <em> element indicates emphasis that subtly changes the meaning of a sentence.

![](https://static.javatpoint.com/htmlpages/images/html-em-tag.png)


***

**`<blockquote>`**


The `<blockquote>` element is used for longer quotes that take up an entire paragraph. Note how the `<p>` element is still used inside the `<blockquote>` element.


And the `<q>` element is used for shorter quotes that sit within a paragraph.


try this in your visual code:

```

<blockquote cite="http://en.wikipedia.org/wiki/ Winnie-the-Pooh"> 
<p> Did you ever stop to think, and forget to start again? 
</p>
</blockquote>
<p> 
As A.A. Milne said, 
<q>
Some people talk to
animals. Not many listen though. That's the
problem.
</q>
</p>
```


***

**`<abbr>`**

If you use an abbreviation or an acronym, then the `<abbr>` element can be used. A title attribute on the opening tag is used to specify the full term.


***

NOTE: In HTML 4 there was a separate `<acronym>` element for acronyms. To spell out the full form of the acronym, the title attribute was used (as with the `<abbr>` element above). HTML5 just uses the `<abbr>` element for both abbreviations and acronyms.

```
<p> 
<abbr title="Professor">Prof</abbr>
 Stephen
Hawking is a theoretical physicist and
cosmologist.
</p>
<p>
<acronym title="National Aeronautics and Space
Administration">
NASA</acronym> do some crazy
space stuff.
</p>
```

***

**`<cite>`**

When you are referencing a piece of work such as a book, film or research paper, the `<cite>` element can be used to indicate where the citation is from.

***


**`<dfn>`**

The `<dfn>` element is used to
indicate the defining instance of
a new term.

***


**`<address>`**


The `<address>` element has quite a specific use: to contain contact details for the author of the page.

***

**`<ins>`** & **`<del>`**


The `<ins>` element can be used to show content that has been inserted into a document, while the `<del>` element can show text that has been deleted from it.

![](https://th.bing.com/th/id/R887f3c7217fb36cbaf58ad858216c475?rik=P8q67zkBNOJ4Rg&riu=http%3a%2f%2fcodelover.in%2fwp-content%2fuploads%2f2017%2f03%2fHTML-text-formating-del.jpg&ehk=zAMnJT2YWjIDf5n9U%2boWo7UfyDq3P%2ftQ%2f1f61KijpuM%3d&risl=&pid=ImgRaw)

***


**`<s>`**


The `<s>` element indicates something that is no longer accurate or relevant (but that should not be deleted).

Try it in your visual code:

```
<p>Laptop computer:</p>
<p><s>Was $995</s></p>
<p>Now only $375</p>
```

***
***

## INTRODUCING CSS

CSS allows you to create rules that specify how the content of an element should appear.

**BLock & InLine elements**

- *Block level elements* look like they start on a new line. Examples include the `<h1>`- `<h6>`, `<p>` and `<div>` elements.

- *Inline elements* flow within the text and do not start on a new line. Examples include `<b>`, `<i>`, `<img>`, `<em>` and `<span>`.

![](https://th.bing.com/th/id/R6f3ba711f381fa14c8e5bc0b7b9d63f6?rik=XpnZSbGnhuiBRQ&riu=http%3a%2f%2fnotesformsc.org%2fwp-content%2fuploads%2f2018%2f02%2fOutput-Inline-Element.png&ehk=SrjL7DLzhk7N8Bv%2fizeLz7B5CSvE9k1sO97sEO3N5UA%3d&risl=&pid=ImgRaw)


***

**ExampLe Styles**

- Boxes :

        - Width and height

        - Borders (color, width, and style)

        - Background color and images

        - Position in the browser window.

- Text :

        - Typeface
        - Size
        - Color
        - Italics, bold, uppercase, lowercase,     small-caps

- Specific : 

        -  lists
        - tables
        - forms



***

**CSS associate rules with HTML element**


CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.


![](https://th.bing.com/th/id/R70eed0a1c4bff8c7c80580da2eee0d21?rik=xTE3s7vjfAaGMw&riu=http%3a%2f%2fwww.lll.hawaii.edu%2fweb%2fworkshop%2fcss%2fimages%2fstyle-tag.jpg&ehk=lJT7KZe7DIw0anBAOZa8BDwdh0Ld7OUqeDE8onX9Xo0%3d&risl=&pid=ImgRaw)

```
*NOTE*: *in this example : selector is the { body }
     and the declaration inside the curly brackets { background-color:red; }*
```

***


**Values & Prpoereties**

 value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

 ![](https://th.bing.com/th/id/Ree4cac2ce08bd8b1a5800f8aed2b1823?rik=dQGrp2pUtg1MBQ&riu=http%3a%2f%2fcscie12.dce.harvard.edu%2flecture_notes%2f2014%2f20140224%2fimages%2fcss_property_value.png&ehk=A6iaLrMIzc9O1d8SFE5eVrozlIpg2IO9UMYdtrgGmME%3d&risl=&pid=ImgRaw)

 ***

 **Using externaL CSS**

 You can use external CSS As shown in the following example :

*index.html* :
```
<!DOCTYPE html>
<html>
<head>
<title>Using External CSS</title>
<link href="css/styles.css" type="text/css"
rel="stylesheet" />
</head>
<body>
<h1>Potatoes</h1>
<p>There are dozens of different potato
varieties. They are usually described as
early, second early and maincrop.</p>
</body>
</html>
```

*styles.css* :

```
body {
font-family: arial;
background-color: rgb(185,179,175);}
h1 {
color: rgb(255,255,255);}
```

Try it in your visual code and see the result.

***

**Using Internal CSS**

You can also include CSS rules within an HTML page by placing them inside a `<style>` element, which usually sits inside the `<head>` `element` of the page.


As shown in the following example :


*HTML & CSS*
```
<!DOCTYPE html>
<html>
<head>
<title>Using Internal CSS</title>
<style type="text/css">
body {
font-family: arial;
background-color: rgb(185,179,175);}
h1 {
color: rgb(255,255,255);}
</style>
</head>
<body>
<h1>Potatoes</h1>
<p>There are dozens of different potato
varieties. They are usually described as
early, second early and maincrop.</p>
</body>
</html>
```


**Note: When building a site with more than one page, you should use an external CSS style sheet.**

***

**CSS selectors**

There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.

![](https://th.bing.com/th/id/Rd26b821c1bf8d2b125a878296ceabd0b?rik=It3kzp4sDpIGyQ&riu=http%3a%2f%2ftutorial.techaltum.com%2fimages%2fcss-selectors.png&ehk=dCdC26dk9se3yM8DqTgJ3ChRtb8RV5WEbuYEcHMwico%3d&risl=&pid=ImgRaw)

*Note:* 

```
h1 is more specific than `*` p.*

*b is more specific than p*.

*p#intro is more specific than p.*
```


***

***



## BASIC JAVASCRIPT INSTRUCTION

A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.

```
var today= new Date{);
var hourNow =today.getHours{) ;
var greeting;
if (hourNow > 18) {
greeting= 'Good evening';
else if (hourNow > 12) {
greeting= 'Good afternoon';
else if (hourNow > O) {
greeting 'Good morning';
else {
greeting 'Welcome';
document.write(greeting) ;
```


~ **JAVASCRIPT IS CASE SENSITIVE** ~

♦ STATEMENTS ARE INSTRUCTIONS AND EACH ONE STARTS ON A NEW LINE.

♦ STATEMENTS CAN BE ORGANIZED INTO CODE BLOCKS.

♦ You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.


SINGLE LINE COMMENTS
```
// Create a ne1~ dat e object
```

MULTI-LINE COMMENTS

```
/* characters and ending with the * / 
```


***

**Variables**:

A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

![](https://cyberpointsolution.com/wp-content/uploads/2018/04/js-variables.jpg)

***

DATA TYPES

DataType | Example
--------|----
STRING  | 'Hi', Ivy! 1
NUMERIC  | 25
BOOLEAN | true

***

**CREATING VARIABLES**

1. Variables are declared and values assigned in the same statement.

```
var price = 5;
var quantity = 14;
var total =price * quantity;
```

2. Three variables are declared on the same line, then values assigned to each.

```
 var price, quantity, total ;
price = 5;
quanti ty = 14;
total = pr ice * quantity;
```

3. Two variables are declared and assigned values on the same line. Then one is declared and assigned a value on the next line.

```
var price
var total
5, quantity = 14;
price * quantity;
```

4. Here, a variable is used to hold a reference to an element in the HTML page. This allows you to work directly with the element stored in that variable. 

```
// Write total into the element with i d of cost
var el = document .getElementByld( ' cost');
el . textCont ent = '$' +total;
```

***

**RULES FOR NAMING VARIABLES**

![](https://image.slidesharecdn.com/datatypesinjava-150323065549-conversion-gate01/95/data-types-variables-expressions-arithmetic-operators-in-java-15-638.jpg?cb=1427093963)


***

**ARRAYS**


An array is a special type of variable. It doesn't just store one value; it stores a list of values.

*array literal*

```
var colors;
colors ['white', 'black', 'custom '];
var el document.getElementByld('col ors');
el . textContent = col ors[O];
```


OR *array constructor*

```
var colors
new Array('white ' ,
'black',
'custom ' );
var el = document.getElementByid( 'colors ' );
el.innerHTML = colors.item(O);
```


***

**ACCESSING & CHANG ING VALUES IN AN ARRAY**

```
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


**EXPRESSIONS**

An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.

1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE

```
var color = 'beige';
```

2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE

```
var area = 3 * 2;
```

***

**Operators**

Expressions rely on things called operators; they allow programmers to create a single value from one or more values.

Arrithmatic operator:

![](https://www.miltonmarketing.com/wp-content/uploads/2018/04/jsarithimage029.jpg)














