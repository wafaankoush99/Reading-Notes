# Problem Domain, Objects, and the DOM


## OBJECTS


Objects group together a set of variables and functions to create a model of a something.

variables in objects become property

functions in objects become methods

keys are the names of properties and methods

NOTES: 
there can’t be two objects with the same key (name).

properties can take other objects as values

methods can only contain functions

***

# CREATE OBJECT

Literal notation way : it means the opject stored in a variable and the content in the curly braces .

We can accessan object using dot notation:
((object followed by properety or method))


```
var hotelName = hotel.name;
```

***

# DOCUMENT OBJECT MODE DOM

Dom tree is the model of a web page 

![](https://www.conceptdraw.com/solution-park/resource/images/solutions/dom-tree/SOFTWARE-DEVELOPMENT-DOM-Tree-Dom-Tree-Mindmap.png)


 It consists of four main types of nodes.
Each node is an object with methods and properties.

1- Document Node 
2- Element Node : html tags
3- Attribute Node : part of html tags
4- Text Node 

***

ACCESS THE ELEMENTS

1- Select an individual element node :
        - getEl ement Byld ()

        - querySe1ector()

        - select individual elements by traversing from one element to another within the DOM tree 

2- select Nodelists
        - getElementsByClassName()

        - getElementsByTagName()

        - querySelectorAll()

3- traversing between element
        - parentNode

        - previousSibl ing / nextSibl ing

        - firstChild / lastChild

***

## work with those elements:

1- Access text node : 

nodeValue

2- work with html content :

innerHtml

textContent

createElement()

createTextNode()

oppenedChild()

removeChild()

3- Access attribute values :

className / id

hasAttribute()

getAttribute()

setAttribute()

removeAttribute()

***

## caching dom queries:

if we want to work with an element more then once we should use a variable to store the result of the query. (queries method)


**DOM queries may return one element, or they may return a Nodelist**

METHODS THAT RETURN A SINGLE ELEMENT NODE:
getElementByld ('id') querySelector( 'css selector') search an entire document and return individual elements

METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):
Nodelists look like arrays and are numbered like arrays, but they are not actually arrays; they are a type of object called a collection. getElementsByClassName( 'class ') getEl ementsByTagName( 'tagName') querySelectorAll ('css selector')
In a live Nodelist, when your script updates the page, the Nodelist is updated at the same time.
In a static Nodelist when your script updates the page, the NodeList is not updated to reflect the changes made by the script.

***

SELECTING AN ELEMENT FROM A NODELIST

- the item() method
- array syntax [].(better)

***

you can repeat actopn for entire noodlist by looping

***

##white space node

some browsers add a text node whenever they come across whitespace between elements.

***

**To work with the content of elements you can:**

Navigate to the text nodes. This works best when the element contains only text, no other elements.
Work with the containing element. This allows you to access its text nodes and child elements.

***


The browser represents the page using a DOM tree.


DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.


You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.


Whenever a DOM query can return more than one
node, it will always return a Nadeli st.


From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.



An element node can contain multiple text nodes and
child elements that are siblings of each other.



In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).


Browsers offer tools for viewing the DOM tree.

***

ducket HTML CSS

HomePage

contact wafadirawe@gmail.com
