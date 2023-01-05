<h1 align="center">Core_code_from_scratch_Javacript</h1>

<h1 align="center">Week-5</h1>

[**Go To Bottom**](#End-Of-Challenges)

# (Thursday)
## Javascript Intro
## If
```javascript
let age = prompt('How old are you?');
if (age < 18){
  console.log('Give this kid some milk')
} else{
  console.log('Offer this man a beer')
} 
```

## While
```javascript
let number = 1;
let table = prompt('Which multiplication table do you need?');
while(number <= 10){
    console.log(table * number);
    number = number + 1;
}
```

## For
```javascript
const weekDays = ['Monday','Tuesday','Wednesday','Thursday','Friday','Saturdar','Sunday']
let text = '';
for (let i = 0; i < weekDays.length; i ++) {
console.log(weekDays[i]);
} 
```

<h1 align="center">Week-6</h1>

# (Monday)

The assingment was to do the HTML course on EDPUZZLE.

# (Tuesday)

## Variables
```javascript
//Declare a variable firstname and initialize it with the value 'Lata'.

let firstname = 'Lata'
```
## What is X?
```javascript
//Which value does x have after execution of the following code?

let x = 'Geeta';

Answer: 'Geeta'
```
## Several Variables
```javascript
//Declare a variable flower and assign it the value 'rose'. Declare a second variable tree and assign it the value 'maple'.

let flower = 'rose';
let tree = 'maple';
```
## Reassignment
```javascript
//Which value does x have after execution of the following code?

let x = 'Tic';
x = 'Tac';
x = 'Toe';

Answer: 'Toe'
```
## Assign Variables

```javascript
//Which value does x have after execution of the following code?

let x = 'Laurel';
let y = 'Hardy';
let z = y;
y = x;
x = z;

Answer: 'Hardy'
```

# (Wednesday)

## Functions

```javascript
//Define a function hello that returns 'Hello world!'.

function hello(){
return 'Hello world!';
}
```
## Multiple functions

```javascript
//Define two functions. The first function a should return 'Hello a!' and the second function b should return 'Hello b!'.

function a(){
return 'Hello a!'
}

function b(){
return 'Hello b!'
}
```
## Function Calls

```javascript
//1. Define a function greet returning the value 'Haydo!'.
2. Declare a variable salutation. Call the function greet and assign the result of the call to the variable salutation.

function greet(){
return 'Haydo!'
}

let salutation = greet();
```
## What is X?

```javascript
//Which value does x have after execution of the following code? 

Answer: 'Hi!'
```
## Parameters

```javascript
//Write a function echo that also returns the passed parameter. echo('Greta')
should return 'Greta' and echo('CO2') should return 'CO2'

function echo(string) {
    return string;
}

console.log(echo('Greta'));
console.log(echo('CO2'));
```

# (Thursday)


   ## Strings
   ```javascript
   //Write a function greet having one parameter and returning 'Hello <parameter>!'.

Example: greet('Ada') should return 'Hello Ada!' and greet('Grace') should return 'Hello Grace!'.

function greet(name){
return 'Hello ' + name + '!';
}

console.log(greet('Ada!'));
   ```
   ## String: length
   ```javascript
   //Write a function length that takes a string and returns the number of characters of the string.

Example: length('sun') should return 3.

function length(string){
return string.length;
}
   ```
   ## String: toUpperCase()
   ```javascript
   //Write a function toCase that takes a string and returns that string in lowercase and uppercase with - as delimiter.

Example: toCase('Mthatha') should return 'mthatha-MTHATHA'.

function toCase(string){
return string.toLowerCase() +'-'+ string.toUpperCase();
}
   ```
   ## String: charAt()
   ```javascript
   //Write a function shortcut that takes two strings and returns the initial letters of theses strings.

//Example: shortcut('Amnesty', 'International') should return 'AI'.

function shortcut(string1, string2) {
  return string1.charAt(0) + string2.charAt(0);
}

   ```
   ## String: indexOf()
   ```javascript
   //Write a function indexOfIgnoreCase taking two strings and determining the first occurrence 
   of the second string in the first string. The function should be case insensitive.

//Example: indexOfIgnoreCase('bit','it') and indexOfIgnoreCase('bit','IT') should return

function indexOfIgnoreCase(st1, st2) {
  return st1.toLowerCase().indexOf(st2.toLowerCase());
}
   ```





### End Of Challenges

[**Go To Top**](#Core_code_from_scratch_Javacript)
