### Array Initialisation and Declaration
```javascript
var arry = [];
var numb = [1,2,3];
var ar = new Array("Ram","Rohan","Gokul");
var grid = [[1,2,3],[4,5,6]];
const mixed_arry = ["ant",1.2,{},[1,2,3]];
```
### Object declaration and Initialization
```javascript
const person = {name:'David', age:30};
const myobj = new Object();

Accessing properties:
person.name
person["age"]

Adding/Modifying properties
person.city = "New York";

Removing property:
delete person.age;
```
### DOM Finding and html elements changing
Document Object Model is a programming interface for web document.
```javascript
const inputText = document.getElementById("username").value;
const outputParagraph = document.getElementById("output");
outputParagraph.innerHtml = "You entered: " + inputText;
```
## ES6 UPDATES
### Arrow Function
```javascript
const sum = (a,b) => a+b;
```
### Classes
```javascript
class Person{
    constructor (name){ this.name = name;}
}
```
### Let and Const
```javascript
for( let i=0; i<3; i++){}
const PI = 3.14;
```
### Promises
```javascript
return new Promise((resolve,reject) => {
    resolve("File downloaded successfully");
    reject("Download Failed");
});
```
### New array method
```javascript
const numbers = [1,12,3,4,5];
const squares = numbers.map((number) => number*number);
```

