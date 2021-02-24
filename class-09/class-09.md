# Forms and Events

## FORMS

The term ‘form’ has referred to a printed document that contains spaces for you to fill in information.

A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.

`<input>`

Checkboxes allow users to select (and unselect) one or more options in answer to a question.


The name attribute is sent to the server with the value of the option(s) the user selects. When a question provides users with options for answers in the form of checkboxes, the value of the name attribute should be the same for all of the buttons that answer that question.


The value attribute indicates the value sent to the server if this checkbox is checked. checked The checked attribute indicates that this box should be checked when the page loads. If used, its value should be checked .

If you want to use an image for the submit button, you can give the type attribute a value of image . The src , width , height , and alt attributes work just like they do when used with the `<img>` element.


***


**Defention list**


The definition list is created withthe `<dl>` element and usuallyconsists of a series of terms andtheir definitions. Inside the `<dl>` element you willusually see pairs of `<dt>` and `<dd>` elements. This is used to contain the term being defined (the definition
term). & `<dd>` used to contain the definition.

***

# Lists, tabLes and Forms


Unordered Lists
For an unordered list you can use
the following values:
- none
- disc •
- circle ○
- square ◘



ordered Lists
For an ordered (numbered) list
you can use the following values:
decimal

- 1
- 2
- 3



decimal-leading-zero
- 01 
- 02 
- 03

lower-alpha
- a 
- b 
- c 

upper-alpha
- A
- B
- C

lower-roman
- i.
- ii. 
* iii.
upper-roman
- I 
* II 
- III

***
```
ul {
list-style-image: url("images/star.png");}
li {
margin: 10px 0px 0px 0px;}
```

## list style position

```css
ul {
width: 150px;}
li {
margin: 10px;}
ul.illuminations {
list-style-position: outside;}
ul.season {
list-style-position: inside;}
```


```css
ul {
list-style: inside circle;
width: 300px;}
li {
margin: 10px 0px 0px 0px;}
```

## Table properity
- width
- padding
- text-transform
- letter-spacing. fomt size 
- border-top & bottom
- text-align
- background-color
- hover


***

# empity celss in the table 

```
<td></td>
```

It can take one of three values:


**show**

This shows the borders of any
empty cells.


**hide**

This hides the borders of any
empty cells.


**inherit**

If you have one table nested
inside another, the inherit
value instructs the table cells to
obey the rules of the containing
table.

***

## collapse
Borders are collapsed into a
single border where possible.
(border-spacing will be
ignored and cells pushed
together, and empty-cells
properties will be ignored.)
## separate
Borders are detached from each
other. (border-spacing and
empty-cells will be obeyed.)

```
td {
background-color: #0088dd;
padding: 15px;
border: 2px solid #000000;}
table.one {
border-spacing: 5px 15px;}
table.two {
border-collapse: collapse;}
```

***

## EVENTS

avaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page.

When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.

**Types of events**

1. The user selects a certain element or hovers the cursor over a certain element.
2. The user chooses a key on the keyboard.
3. The user resizes or closes the browser window.
4. A web page finishes loading.
5. A form is submitted.
6. A video is played, paused, or finishes.
An error occurs.


oncchange | onclick | onmouseover | onmouseout | onkeydown | onload



****

*sources:*
*ducket javascript |*
*ducket HTML CSS*

[HomePage](https://wafaankoush99.github.io/Reading-Notes/READMEcode201.html)  


contact wafadirawe@gmail.com

