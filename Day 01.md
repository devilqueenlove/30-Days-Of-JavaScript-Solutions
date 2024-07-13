# 💻 Day 1: Exercises

1. Write a single line comment which says, _comments can make code readable_
```
# comments can make code readable
```

2. Write another single comment which says, _Welcome to 30DaysOfJavaScript_
```
# Welcome to 30DaysOfJavaScript
```

3. Write a multiline comment which says, _comments can make code readable, easy to reuse_
   _and informative_
```
/* comments can make code readable, easy to reuse 
and informative
*/
```

4. Create a variable.js file and declare variables and assign string, boolean, undefined and null data types
```
var name = "John Doe";    <!-- String -->
var isMarried = true;    <!-- Boolean  -->
var x;                    <!-- Undefined -->
var y = null;             <!-- Null -->
```
5. Create datatypes.js file and use the JavaScript **_typeof_** operator to check different data types. Check the data type of each variable
```
var name = "John Doe";    
var isMarried = true;    
var x;                    
var y = null;             

console.log(typeOf(name));          <!-- String -->
console.log(typeOf(isMarried));     <!-- Boolean  -->
console.log(typeOf(x));             <!-- Undefined -->
console.log(typeOf(y));             <!-- Null -->

```
6. Declare four variables without assigning values
```
let x,y;
cosnt a;
var z;
```
7. Declare four variables with assigned values
```
let a = "Alpha";
let b = `Bravo`;
const c = ' Charlie';
let d = true;

```
8. Declare variables to store your first name, last name, marital status, country and age in multiple lines
```
let firstName;
let lastName;
let martialStatus;
let country;
let age;
```
9. Declare variables to store your first name, last name, marital status, country and age in a single line
```
let firstName, lastName, martialStatus, country, age;
```
10. Declare two variables _myAge_ and _yourAge_ and assign them initial values and log to the browser console.

```sh
I am 25 years old.
You are 30 years old.
```

```
let myAge = 25;
let yourAge = 30;
console.log(`I am ${myAge} years old.`);
console.log(`You are ${yourAge} years old.`);
```