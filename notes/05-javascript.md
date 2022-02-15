# JavaScript

app.js will be the name of the file.

<script> can be the linking element for the js file.

primitive values are:
number: (1,2,3)
string: (Hello)
boolean: (true, false)

non-primitive values are:
let object = {thing: "it's a thing"}
let array = {1, 2, 3, 4, 5}
function example(){
    console.log('Hello, world!')
}

//number math and operators:
number++ means that it will add 1 to the number
number-- means that it will subtract 1 from the number
number += 5 //Note: will add 5 to the number (number = number + 5)
let sum = 2 + number will add 2 to the number

* = multiply
/ = divide
% = divides the number and then leaves the remainder (2%5= 1)

number == 5 //returns true or false
number === 5 //Forces a value  

> = greater than
< = less than
>= equal to or greater than
<= equal to or less than

//String Operators
string = '' "" ``
string += ' world' //Means string = string + ' world'
string = `Hello ${string2}` //this is interpolation


//bool operators
bool == true //are these equal?
bool != true //are these not equal?

&& = means "and" in a syntax
|| = means "or" in a syntax


objects are collections of data that are stored by a key or a value pair. 

//return means full stop

//within an array for ex:

= { 
    mick: (<- Mick right here is 'array item')
}

Notes 2/14/22:

Elivs Operator checks to see if a property is defined before it runs. 

-Class: is a blueprint of an object. 

-Method: is a function that exists on a class. 

-Entry Point: 

-MVC: Model View Controller (service)

Controller.js page works like a video game controller and is handled with the input of the user. 
The page will take a 'function' and then just passes it to another JS file. The page is very lazy. 
The reason why we have it in the first place is encapsulation. We use it so we have reusable code and group together similar code.

In the MCV there will typically be 5 pages that hold our data and make our code run.

Index, which holds the HTML code for us. Then the Controller.js page which holds the code that holds everything. The service page will then run the actual code and the model page holds the classes with the properties that make up the classes. Lastly, the proxyState, is the place where we hold all of our data. 