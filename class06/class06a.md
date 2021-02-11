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

*** 

[Home Page](https://wafaankoush99.github.io/Reading-Notes/)

contact wafadirawe@gmail.com

