# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A subprogram designed to perform a particular task.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S - Single-responsibility Principle.
O - Open-closed Principle.
L - Liskov Substitution Principle.
I - Interface Segregation Principle.
D - Dependency Inversion Principle.

I had to google these, I don't recall them from the reading or lectures.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2. Arrays are base 0, so apple0 banana1 and pineapple2
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
Not entirely sure.

you.friends.push(them)

Best guess.
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
I don't know what this is. It sounds like an IF statement, and googling this shows discussions of Truthy and Falsy
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
Incrememter? i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. index.html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
I can only find MDN referencing 7, the primitive types.

null
undefined
boolean
number
bigint
string
symbol

maybe objects and arrays?
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are used when defining a function, they are the names created in the function definition. Arguments, on the other hand, are the values the function receives from each parameter when the function is executed (invoked).
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive variable's information is stored as the value of that variable, whereas a reference variable holds a reference to information related to that variable.

-google
```