# MVC

Main pages:

index.html
'var'Controller page
'var' Service page
Model page which will just stand for the variable you're working with
'AppState' which is the proxy state page

//NOTE: MCSMP (Main, Controller, Service, Model, Proxy State)


import other pages by simply typing out the other classes

-Interpolation: for the color value you would enter it in place of the value itself

2/17/22: How to start:

-Break it down (Make a plan):
-Data first (if you see fit)
-Code small
-Use conventions (Class definition upper camel/Lower every other variable/Plural collections)
-Look at your old code 
-Be a problem solver extraordinaire
-Take the solutions you went through from old code and apply it to your current situations



//NOTE: Lecture notes:
-Break down data
    -Pizza (id, name, sauce, size, price*)
    -Toppings
-Controllers & Services
    -PizzasControllers & PizzasService 
    -ToppingsController & ToppingsService
-AppState
    -Pizza: []
    -Toppings: []
-Make empty files with relevent classes

---------repeat per model

-Make fake data
    -Hardcode a pizza into AppState
-Render data to the page
    - _drawPizza() in controller
-Create new data
    -createPizza() in controller & service
-Delete Data
    -deletePizza(id) in controller & service


For the MCV:

-Start with the controllers for each parameter
-Then create the value sheets for each parameter (for example Pizza.js lives in Models)
-Then add those values to the appstate
-Then work on the value service sheets
-ProxyState = AppState (The AppState page does not get duplicated)

First things first inside a function:
-let template = '' (to make it easier to read)

-Helpful tip: Add ['PizzaController', createPizza] in your console log to see where the tool is functioning from. 

-Future checkpoints will have the "title" tag as a requirement for clickable icons.

2/21/22:
API: Application programming interface
'Acts like the menu of a restaurant'

Going forward all methods for our controllers need to have "try" and "catch". 

console.error(error) means if this error happens then throw it in the console. 

'async' tells js that at some point you will use that specified function

You should always try to throw an error message to anyone who is attempting to run a method but functions improperly. 

Download JSON.vue for Chrome 


2/22/22:
AxiosService contains the export class that holds the api. 

CRUD: Create, Read, Update, and Delete

BCW Serve 8081 to make a second 

2/23/22:
You cannot make a constructor asynchronus. It only functions in the traditional method that it's meant for. 

'ProxyState.on' is the event listener and will only apply when it gets the right response. 

'trycatch' auto fill-in


