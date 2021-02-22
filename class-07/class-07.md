# Domain Modeling

## Domain Modeling 

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

---

A domain model that’s articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

---

OOP in JavaScript at its most fundamental level.

- The new keyword instantiates (i.e. creates) an object.
The constructor function initializes properties inside that object using the this variable.


- The object is stored in a variable for later use.


- Domain modeling is the process of creating a conceptual model for a specific problem.

 - And a domain model that’s articulated well can verify and validate your understanding of that problem.

 ---

building your own domain models.


1. When modeling a single entity that’ll have many instances, build self-contained objects with the same attributes and behaviors.


2. Model its attributes with a constructor function that defines and initializes properties.


2. Model its behaviors with small methods that focus on doing one job well.


3. Create instances using the new keyword followed by a call to a constructor function.


2. Store the newly created object in a variable so you can access its properties and methods from outside.


4. Use the this variable within methods so you can access the object’s properties and methods from inside.

***

# HTML 

The `<table>` element is used to create a table. The contents of the table are written out row by row.

`<tr>`
You indicate the start of each row using the opening `<tr>` tag. followed by one or more `<td>` elements .

Each cell of a table is represented using a `<td>` element,  use a closing `</td>` tag.

At the end of the row you use a closing `</tr>` tag.

***

**Heading**

The `<th>` element is used just like the `<td>` element but its purpose is to represent the heading for either a column or a row.

***

The colspan attribute can be used on a `<th>` or `<td> `element and indicates how many columns that cell should run across.


```
<table>
<tr>
<th></th>
<th>9am</th>
<th>10am</th>
<th>11am</th>
<th>12am</th>
</tr>
<tr>
<th>Monday</th>
<td colspan="2">Geography</td>
<td>Math</td>
<td>Art</td>
</tr>
<tr>
<th>Tuesday</th>
<td colspan="3">Gym</td>
<td>Home Ec</td>
</tr>
</table>
```

The rowspan attribute can be used on a `<th>` or `<td>`element to indicate how many rows a cell should span down the table.


***

**Long Tables**

`<thead>`

The headings of the table should sit inside the `<thead>` element.

`<tbody>`

The body should sit inside the `<tbody>` element.


`<tfoot>`

The footer belongs inside the `<tfoot>` element.


```
<table>
<thead>
<tr>
<th>Date</th>
<th>Income</th>
<th>Expenditure</th>
</tr>
</thead>
<tbody>
<tr>
<th>1st January</th>
<td>250</td>
<td>36</td>
</tr>
<tr>
<th>2nd January</th>
<td>285</td>
<td>48</td>
</tr>
<!-- additional rows as above -->
<tr>
<th>31st January</th>
<td>129</td>
<td>64</td>
</tr>
</tbody>
<tfoot>
<tr>
<td></td>
<td>7824</td>
<td>1241</td>
</tr>
</tfoot>
</table>
```

***

# Function


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

*sources:*

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)


*ducket javascript |*


*ducket HTML CSS*

***

[HomePage](https://wafaankoush99.github.io/Reading-Notes/READMEcode201.html)  

***


contact wafadirawe@gmail.com




