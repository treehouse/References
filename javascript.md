# JavaScript Quick Syntax Reference


<!-- toc -->
- [array](#array)
- [arrow function](#arrow-function)
- [bracket notation](#bracket-notation)
- [class](#class)
- [const](#const)
- [dot notation](#dot-notation)
- [filter](#filter)
- [find](#find)
- [for](#for)
- [forEach](#foreach)
- [for...in](#forin)
- [for...of](#forof)
- [function](#function)
- [get](#get)
- [if](#if)
- [if...else](#ifelse)
- [if...else if](#ifelse-if)
- [instance](#instance)
- [let](#let)
- [loop](#loop)
- [object literal](#object-literal)
- [return](#return)
- [switch](#switch)
- [ternary](#ternary)
- [var](#var)
- [while](#while)

____
# array
```javascript
var myArray = [element1, element2, element3];
```

```javascript
var myArray = new Array();
```

### Learn on Treehouse
[JavaScript Loops, Arrays, and Objects - What is an Array?](https://teamtreehouse.com/library/what-is-an-array)


### Practice on Treehouse
[Practice Basic Arrays in JavaScript](https://teamtreehouse.com/library/practice-basic-arrays-in-javascript-2)


# arrow function

```javascript
const addNumToTen = num => 10 + num;
```

```javascript
const divideNumbers = (num1, num2) => num1/num2;
```

```javascript
const printMyName = () => {
    const myName = 'Ashley';
    console.log(myName);
}
```

### Learn on Treehouse
[Introducing Arrow Function Syntax](https://teamtreehouse.com/library/introducing-arrow-function-syntax)\
[Getting Started with ES2015 - Basic Arrow Syntax](https://teamtreehouse.com/library/basic-arrow-syntax)\
[Introducing ES2015 - Arrow Functions](https://teamtreehouse.com/library/arrow-functions)

### Practice on Treehouse
[Practice Arrow Functions in JavaScript on Treehouse](https://teamtreehouse.com/library/practice-arrow-functions-in-javascript)

##### See also
[function](#function)



# bracket notation

```javascript
object['propertyKey']
object['methodName']()
```

```javascript
var propertyKey = 'name'
object[propertyKey] 
```

```javascript
array[indexOfElement]
```

### Learn on Treehouse
[JavaScript Loops, Arrays, and Objects - Accessing Object Properties](https://teamtreehouse.com/library/accessing-object-properties)\
[Object-Oriented JavaScript - Dot Notation and Bracket Notation](https://teamtreehouse.com/library/dot-notation-bracket-notation)

##### See also
[dot notation](#dot-notation)



# class
```javascript
class Fruit {

}
```

### Learn on Treehouse
[Introducing ES2015 - Structure of Class](https://teamtreehouse.com/library/structure-of-class)\
[Object-Oriented JavaScript - Writing Your First Class](https://teamtreehouse.com/library/writing-your-first-class)

##### See also
[instance](#instance)



# const
```javascript
const myString = 'Hello World';
```

### Learn on Treehouse
[Defining Variables with Let and Const](https://teamtreehouse.com/library/defining-variables-with-let-and-const)\
[Introducing ES2015 - Let and Const](https://teamtreehouse.com/library/let-and-const)\
[Getting Started with ES2015 - Declaring Variables in JavaScript](https://teamtreehouse.com/library/declaring-variables-in-javascript-2)

### Practice on Treehouse
[Practice Let and Const in JavaScript on Treehouse](https://teamtreehouse.com/library/practice-let-and-const-in-javascript)

##### See also
[var](#var)\
[let](#let)



# dot notation
```javascript
object.propertyKey
object.methodName()
```

### Learn on Treehouse
[JavaScript Loops, Arrays, and Objects - Accessing Object Properties](https://teamtreehouse.com/library/accessing-object-properties)\
[Object-Oriented JavaScript - Dot Notation and Bracket Notation](https://teamtreehouse.com/library/dot-notation-bracket-notation)

##### See also
[bracket notation](#bracket-notation)


# filter
```javascript
array.filter(element => <condition>);
```

### Learn on Treehouse
[Array Iteration Methods - Remove Array Items with Filter](https://teamtreehouse.com/library/remove-array-items-with-filter)



# find
```javascript
array.find(element => <condition>);
```

# for
```javascript
for (let i = 0; i <= 10; i++){
    console.log(i);
}
```

### Learn on Treehouse
[JavaScript Loops, Arrays, and Objects - For Loops](https://teamtreehouse.com/library/for-loops-2)

##### See also
[forEach](#foreach)\
[for...in](#forin)\
[for...of](#forof)



# forEach

```javascript
myArray.forEach(function(elem){
    console.log(elem);
});
```

### Learn on Treehouse
[JavaScript Array Iteration - for vs forEach](https://teamtreehouse.com/library/for-vs-foreach)

### Practice on Treehouse
[Practice forEach in JavaScript](https://teamtreehouse.com/library/practice-foreach-in-javascript)


# for...in
```javascript
for (property in object) {
    console.log(`Key: ${prop}`); 
    console.log(`Value: ${object[prop]}`); 
}
```

##### See also
[for](#for)\
[for...of](#forof)



# for...of
```javascript
for (element of iterable) {
    console.log(element)
}
```

##### See also
[for...in](#forin)\
[for](#for)


# function

```javascript
function myFunc(param) {
    console.log(param);
}
```

### Learn on Treehouse
[JavaScript Basics - Introducing Functions](https://teamtreehouse.com/library/introducing-functions-5)

### Practice on Treehouse
[Practice Basic JavaScript Functions](https://teamtreehouse.com/library/practice-basic-javascript-functions)

##### See also
[arrow functions](#arrow-function)


# get

```javascript
get myDynamicProperty(){
	return dynamicProperty;
}
```

### Learn on Treehouse
[Object-Oriented JavaScript - Getters](https://teamtreehouse.com/library/getters)


# if
```javascript
if (x == y) {
    console.log(true);
}
```

### Learn on Treehouse
[JavaScript Basics - Introducing Conditional Statements](https://teamtreehouse.com/library/javascript-basics/making-decisions-with-conditional-statements/introducing-conditional-statements)

### Practice on Treehouse
[Practice If and Else If Statements in JavaScript](https://teamtreehouse.com/library/practice-if-and-else-if-statements-in-javascript)

##### See also
[conditional](#conditional)\
[if else](#ifelse)\
[if...else if](#ifelseif)\
[switch](#switch)\
[ternary](#ternary)



# if...else
```javascript
if (x == y) {
    console.log(true);
} else (
    console.log(false);
)
```

### Practice on Treehouse
[Practice If and Else If Statements in JavaScript](https://teamtreehouse.com/library/practice-if-and-else-if-statements-in-javascript)

##### See also
[conditional](#conditional)\
[if](#if)\
[if...else if](#ifelse-if)\
[switch](#switch)\
[ternary](#ternary)



# if...else if
```javascript
if (x == y) {
    console.log(true);
} else if (x == j) (
    console.log(true);
) else {
    console.log(false);
}
```

### Practice on Treehouse
[Practice If and Else If Statements in JavaScript](https://teamtreehouse.com/library/practice-if-and-else-if-statements-in-javascript)

##### See also
[conditional](#conditional)\
[if](#if)\
[if...else](#if-else)\
[switch](#switch)\
[ternary](#ternary)



# instance
```javascript
var banana = new Fruit();
```

### Learn on Treehouse
[Object Oriented JavaScript - Instantiating a Pet Object](https://teamtreehouse.com/library/instantiating-a-pet-object)

##### See also
[class](#class)


# let
```javascript
let myString = 'Hello World';
```

### Learn on Treehouse
[Defining Variables with Let and Const](https://teamtreehouse.com/library/defining-variables-with-let-and-const)
[Introducing ES2015 - Let and Const](https://teamtreehouse.com/library/let-and-const)
[Getting Started with ES2015 - Declaring Variables in JavaScript](https://teamtreehouse.com/library/declaring-variables-in-javascript-2)

### Practice on Treehouse
[Practice Let and Const in JavaScript on Treehouse](https://teamtreehouse.com/library/practice-let-and-const-in-javascript)

##### See also
[const](#const)\
[var](#var)



# loop

##### See also
[for](#for)\
[for...in](#forin)\
[for...of](#forof)\
[while](#while)

### Learn on Treehouse
[JavaScript Loops, Arrays, and Objects - What are loops?](https://teamtreehouse.com/library/what-are-loops)

### Practice on Treehouse
[Practice JavaScript Loops](https://teamtreehouse.com/library/practice-javascript-loops)



# object literal
```javascript
var object = {
    property1: "value1",
    property2: "value2",
    method1: function(){}
}
```

### Learn on Treehouse
[JavaScript Loops, Arrays, and Objects - The Object Literal](https://teamtreehouse.com/library/the-object-literal)\
[Object-Oriented JavaScript - Object Literals and Components of Objects](https://teamtreehouse.com/library/object-literals-and-components-of-objects)


### Practice on Treehouse
[Practice Object Literals in JavaScript on Treehouse](https://teamtreehouse.com/library/practice-object-literals-in-javascript)



# return
```javascript
return x;
```

# switch
```javascript
switch (x) {
    case 1:
        console.log(1);
        break;
    case 2:
        console.log(2);
        break;
    case 3: 
        console.log(3);
        break;
}
```

### Learn on Treehouse
[Exploring JavaScript Conditionals - Switch Statement](https://teamtreehouse.com/library/switch-statement)

##### See also
[conditional](#conditional)\
[if](#if)\
[if...else](#ifelse)\
[if...else if](#ifelseif)\
[ternary](#ternary)


# ternary
```javascript
<condition> ? <code if true> : <code if false>;
```

```javascript
x == y ? console.log('true') : console.log('false');
```

```javascript
var val = x == y ? true : false;
```

### Learn on Treehouse
[Exploring JavaScript Conditionals - Ternary Operator](https://teamtreehouse.com/library/ternary-operator)


##### See also
[conditional](#conditional)\
[if](#if)\
[if...else](#ifelse)\
[if...else if](#ifelseif)\
[switch](#switch)



# var
```javascript
var myString = 'Hello World';
```
### Learn on Treehouse
[JavaScript Basics - Introducing Variables](https://teamtreehouse.com/library/introducing-variables)

### Practice on Treehouse
[Practice Basic Variables, Input, and Output in JavaScript](https://teamtreehouse.com/library/practice-basic-variables-input-output-in-javascript)

##### See also
[const](#const)\
[let](#let)



# while
```javascript
while (i < 10) {
    i++;
}
```

### Learn on Treehouse
[Javascript Loops, Arrays, and Objects - What are Loops?](https://teamtreehouse.com/library/what-are-loops)

