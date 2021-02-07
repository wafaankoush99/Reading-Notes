![](https://tekraze.com/wp-content/uploads/2018/05/javascript.jpg)

# PROGRAMMING WITH JAVASCRIPT

***

## WHAT IS A SCRIPT AND HOW DO I CREATE ONE?

A script is a series of instructions that a
computer can follow to achieve a goal.

***

```
- *Scripts are made up of instructions a computer can follow step by step.*
- *A browser may use different parts on the script depending on how the user interacts with the web page.*
- *Scripts can run different sections of the code in response to the situation around them.*
```

***

## WRITING A SCRIPT 
1: DEFINE THE GOAL 
2: DESIGN THE SCRIPT 
3: CODE EACH STEP 

## DEFINING A GOAL & DESIGNING THE SCRIPT

1. The script is triggered when the button is clicked.
2. It collects the name entered into the form field.
3. It checks that the user has entered a value.
4. If the user has not entered anything, a message
will appear telling them to enter a name.
5. If a name has been entered, calculate the cost of
the sign by multiplying the number of letters by
the cost per letter.
6. Show how much the plaque costs.  

***

## EXPRESSIONS & OPERATORS

**There are two types of expressions:**


EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE | EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
---------------------------------------------------------------------------------------------------------------------
`var color = 'beige';` | `var area = 3 * 2;`
The value of co 1 or is now beige | The value of area is now 6

## OPERATORS
They allow programmers to create a single value from one or more values. 

**Examples:**

### ASSIGNMENT OPERATORS

Assign a value to a variable
color = 'beige';
The value of co 1 or is now beige.

### ARITHMETIC OPERATORS
Perform basic math
area = 3 * 2;
The value of area is now 6.

### STRING OPERATORS
Combine two strings
greeting= 'Hi 1 + 'Mol ly';
The value of greeting is now Hi Molly. 

**There is just one string operator: the+ symbol. It is used to join the strings on either side of it.** 

```
var firstName = 'Ivy ' ;
var lastName = ' Stone' ;
var ful l Name = f irstName + l astName ; 
```

***

MIXING NUMBERS AND STRINGS TOGETHER

```
var costl = '7';
var cost2 = '9 ' ;
var total = costl + cost2; 
```

**You would end up with a string saying '79'.**

```
var number = 12;
var street= 'Ivy Road';
var add = number + street; 
```

**You would end up with a string saying '12Ivy Road'**

```
var scor e= ' seven ';
var score2 = ' nine';
var total = score * score2;
```

**You would end up with the value NaN.**

![](https://blog.eduguru.in/wp-content/uploads/2016/01/arithmetics-operation.png)

### COMPARISON OPERATORS
Compare two values and return true or fa 1 se
buy = 3 > 5;
The value of buy is fa 1 se.

### LOGICAL OPERATORS
Combine expressions and return true or fa 1 se
buy= (5 > 3) && (2 < 4);
The value of buy is now true

***

## A BASIC FUNCTION

*HTML*

```
<!DOCTYPE html>
<html>
<head> 
<ti t l e>Basic Function</title>
<l i nk rel ="stylesheet" href="css/ c03.css" />
</head>
<body>
<hl>TravelWorthy</ hl>
<div id="message">We lcome to our site! </ div>
<script src="js/ basic-function .js"></script>
</ body>
</ html> 
```

*JAVASCRIPT* 

```
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(}; 
```

**RESULT**

```
Sign up to receive our
newsletter for 10% offl 
```

***

## GETTING MULTIPLE VALUES OUT OF A FUNCTION

```
function getSize (width, height, depth) {
var area = width * height;
}
var volume = width * height * depth;
var sizes= [area , volume];
return sizes;
var areaOne = getSize (3, 2, 3)[0];
var volumeOne = getSize (3, 2, 3)[1]; 
```

*Explain:*

- First, a new function is created called get Size(). The area of the box is calculated and stored in a variable called area. 
- The volume is calculated and stored in a variable called vo 1 ume. Both are then placed into an array called shes. 
- This array is then returned to the code that called the getSize() function, allowing the values to be used. 
- The ar eaOne variable holds the area of a box that is 3 x 2. The area is the first value in the sizes array. 
- The vo 1 umeOne variable holds the volume of a box that is 3 x 2 x 3. The volume is the second value in the si zes array. 

***

[Home Page](https://wafaankoush99.github.io/Reading-Notes/)

*contact wafadirawe@gmail.com*