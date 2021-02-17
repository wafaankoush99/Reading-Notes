# HTML Links, JS Functions, and Intro to CSS Layout

## LINKS

To link an element you should use this tag:

```
<a href="index.html">Home</a></li>
```

## Directory structure

On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.

- Structure : The diagram on the right shows the directory

- Relationships : The relationship between files and folders on a website is described using the same terminology as a family tree

- HomePage : The main homepage of a site written in HTML

## Relative URL

Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.


## Email link

```
<a href="mailto:jon@example.org">Email Jon</a>
```

## Open link in a new window

```
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> (opens in new window)
```


## Linking to a specific part in the same page

look at this code and try it in your VS

```
<h1 id="top">Film-Making Terms</h1>
<a href="#arc_shot">Arc Shot</a><br />
<a href="#interlude">Interlude</a><br />
<a href="#prologue">Prologue</a><br /><br />
<h2 id="arc_shot">Arc Shot</h2>
<p>A shot in which the subject is photographed by an
encircling or moving camera</p>
<h2 id="interlude">Interlude</h2>
<p>A brief, intervening film scene or sequence, not
specifically tied to the plot, that appears
within a film</p>
<h2 id="prologue">Prologue</h2>
<p>A speech, preface, introduction, or brief scene
preceding the the main action or plot of a film;
contrast to epilogue</p>
<p><a href="#top">Top</a></p>
```

***Note** : The `<h1>` element is used with an id attribute at the top of the page so that a link can be added to take readers from the bottom of the page to the top. 


***


## LAYOUT

The `<div>` element that contains this group of elements is then referred to as the containing element.

![](https://blogs.igalia.com/mrego/files/2014/03/grid-example.png)


## Relative position

```
p.example {
position: relative;
top: 10px;
left: 100px;}
```

![](https://th.bing.com/th/id/R0dcd78ae1c8d86746670fe067cca953e?rik=i0pmkVu873sniw&riu=http%3a%2f%2f1.bp.blogspot.com%2f-91qvY8qxSV0%2fUfpMd_yUo0I%2fAAAAAAAAAeg%2fwk-zyTVzZa8%2fs1600%2fimages.jpg&ehk=pnLD5xS0IDapEjxPedpXiPm1eJ%2fBgzS9OrLKJ30%2fjEY%3d&risl=&pid=ImgRaw)


## Absolute position

```
position: absolute;
```


![](https://cdn-images-1.medium.com/max/1200/1*pe9E2kzrX48Wwn_0wKklmw.png)

## Fixed position 

```
position: fixed;
```

![](https://th.bing.com/th/id/R9a10a9d10cd57247588354c1d4488f37?rik=1SO%2bXfiaLriP0Q&riu=http%3a%2f%2fwww.peachpit.com%2fcontent%2fimages%2fch21_0321703529%2felementLinks%2f21fig10.jpg&ehk=1eM9AOm8yP9pSe1NdmKriSLUtQj2BhLFiEMb%2fzS%2fWbA%3d&risl=&pid=ImgRaw)



**Notes**: When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. So If you want to control which element sits on top, you can use the **z-index** property


```
h1 {
position: fixed;
top: 0px;
left: 0px;
margin: 0px;
padding: 10px;
width: 100%;
background-color: #efefef;
z-index: 10;}
```

![](https://www.codingcreativo.it/wp-content/uploads/2020/05/z-index-css.jpg)



## Floating elements

```
floate: left;
```
```
floate: right;
```

## Clear floating

```
floate: clear;
```


## parents of fLoated eLements: soLution

ex:
```
border: 1px solid #665544;
overflow: auto;
width: 100%;}
```

## Create multi column using floate


```
.column1of2 {
float: left;
width: 620px;
margin: 10px;}
.column2of2 {
float: left;
width: 300px;
margin: 10px;}
```

![](https://i.ytimg.com/vi/Tmhwq_5Lwpc/maxresdefault.jpg)


## fixed width Layouts

Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

### Liquid Layouts

Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

## Functions, Methods, and Object


Function : consist of series statment that have been grouped together because they perform a spesefic task.


Method: same as function exept it is created inside an object.

Object: made up of properities and methods

## JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task, executed when "something" invokes it (calls it).

## Why we use it?

You can reuse code: Define the code once, and use it many times & use same code many times with different arguments, to produce different results.


![](https://www.frontamentals.com/static/function-breakdown-e46e54ec2e0de641547f63411acb1d84-bf43a.png)

**Function parameters** are the names of variables present in the function definition.
**Function arguments** are the real values that are passed to the function and received by them.

*** 


*exampel*

```
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(};
```

***These statements update the
message at the top of the page.
The function acts like a store; it
holds the statements that are
contained in the curly braces
until you are ready to use them.***

***

# Calling a function

Having declared the function. you can then execute all of the statement between its curly braces with just one line of code.

```

SayHello();

```

***


## Declaring function that need information
 
```

function getArea (width, height) {
return width * height ; 
}

```

**The parameters are used like variables within the function.**

***


## Gitting a single value out of a function

```

function calculateArea(width, height) {
  var area = width * height;
  return area;
}
var wallOne = calculateArea (3,5);
var wallTow = calculate(8,5);

```
***


## GETTING MULTIPLE VALUES
OUT OF A FUNCTION

function getSize (width, height, depth) {
var area = width * height;
}

```

var volume = width * height * depth;
var sizes= [area , volume];
return sizes;
var areaOne = getSize (3, 2, 3)[0];
var volumeOne = getSize (3, 2, 3)[1];

```

LOCAL VARIABLES: 
When a variable is created inside a function using the
var keyword, it can only be used in that function.

GLOBAL VARIABLES
If you create a variable outside of a function, then it
can be used anywhere within the script.

***

## 6 Reasons for Pair Programming

1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness


***



*sources:*
*ducket javascript |*
*ducket HTML CSS*

[HomePage](https://wafaankoush99.github.io/Reading-Notes/READMEcode201.html)  


contact wafadirawe@gmail.com
