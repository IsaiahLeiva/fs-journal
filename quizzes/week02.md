# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var or const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is way to tell a webpage what to do through Javascript. It is a subprogram that performs a certain task
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
-S: Single-responsibility principle
-O: Open/Closed principle 
-L: Liskov Substitution principle
-I: Interface segregation principle
-D: Dependency inversion principle

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
"Pineapple" should be position number #2. This is because the index starts the itemization from 0, not 1. So it will be counted as 0, 1, 2 and so on.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push("them")
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if (hour < 1100){
  greeting = "Good Morning";
}
```

**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
What's missing is the update portion of the condition. so 'i++' belongs here.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model. It first accesses the HTML file.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Number, string, boolean, null, undefined, bigint, symbol, normal properties and object properties.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is used when defining a function, they essentially are the names created for the function definition. An argument is a value that a function receives from each parameter.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value is a value that cannot be changed. A reference value is a value that obtains its value from somewhere else, it references another value and uses that as its own.
```