# node-express

#### install node on machine
<p>sudo apt install nodejs</p>

### writing functions in index.js file
``` 
const {multiply, subtract, add }= require('./myModule');

let name = 'Amari James'
console.log(name);

function printName(person) {
    return `Wassup, ${person}`;
}

console.log(printName(name));

console.log(multiply(5, 5));
console.log(subtract(10, 77));
console.log(add(100, 342));
```

### calling on functions in myModule.js file
```
const introMe = () => "I go by Lil Red! What's your name?"

function multiply(num1, num2) {
    return num1 * num2;
}

function subtract(num1, num2) {
    return num2 - num1;
}

function add(num1, num2) {
    return num1 + num2;
}

module.exports = {
    introMe,
    multiply,
    subtract, 
    add
}
```

### print functions in terminal
<p>node index.js</p>
![print](1112readme.png)
