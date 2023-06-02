# What is JavaScript?

JavaScript is the most popular lightweight, interpreted compiled programming language. It can be used for both Client-side as well server-side **** developments. JavaScript also known as a scripting language for web pages.

## **Reason to Learn JavaScript**

JavaScript is used by many developers (65% of the total development community), and the number is increasing day by day. JavaScript is one such programming language that has more than 1444231 libraries and increasing rapidly. It is preferred over any other programming language by most developers. Also, major tech companies like Microsoft, Uber, Google, Netflix, and Meta use JavaScript in their projects.

## **Things that makes JavaScript demanding**

JavaScript is the most popular and hence the most loved language around the globe. Apart from this, there are abundant reasons to become the most demanding. Below are a listing of a few important points:

- **No need for compilers:** Since JavaScript is an interpreted language, therefore it does not need any compiler for compilation.
- **Used both Client and Server Side:** Earlier JavaScript was used to build client-side applications only, but with the evolution of its frameworks namely Node.js and Express.js, it is now widely used for building server-side applications too.
- **Helps to build a complete solution:** As we saw, JavaScript is widely used in both client and server-side applications, therefore it helps us to build an end-to-end solution to a given problem.
- **Used everywhere:** JavaScript is so loved because it can be used anywhere. It can be used to develop websites, games or mobile apps, etc.
- **Huge community support:** JavaScript has a huge community of users and mentors who love this language and take it’s legacy forward.

**JavaScript Versions**

JavaScript is a modern scripting language that is popular worldwide among developers. It is a lightweight, interpreted compiled language that can be used on both client-side as well as the server side. It was invented in the year 1995 by Brendan Eich. Over the years the language has improved a lot and a lot of new features have been added which make the coding process even easier. This language became an ECMA standard in the year 1997.

![Untitled](What%20is%20JavaScript%20464c83ccb5324370861f1d877d3dc139/Untitled.png)

# **JavaScript Where To**

## The <script> Tag

In HTML, JavaScript code is inserted between `<script>` and `</script>` tags.

## JavaScript in <head> or <body>

You can place any number of scripts in an HTML document.

Scripts can be placed in the `<body>`, or in the `<head>` section of an HTML page, or in both.

## **External JavaScript**

Scripts can also be placed in external files:

External scripts are practical when the same code is used in many different web pages.

JavaScript files have the file extension **.js**.

To use an external script, put the name of the script file in the `src` (source) attribute of a `<script>` tag:

```html
<script src="myScript.js"></script>
```

You can place an external script reference in `<head>` or `<body>` as you like.

The script will behave as if it was located exactly where the `<script>` tag is located.

External scripts cannot contain `<script>` tags.

# External JavaScript Advantages

Placing scripts in external files has some advantages:

- It separates HTML and code
- It makes HTML and JavaScript easier to read and maintain
- Cached JavaScript files can speed up page loads

To add several script files to one page  - use several script tags:

```html
<script src="myScript1.js"></script>
<script src="myScript2.js"></script>
```

## JavaScript Variables

v**ariables in JavaScript:** Variables in JavaScript are containers that hold reusable data. It is the basic unit of storage in a program.

The value stored in a variable can be changed during program execution.

A variable is only a name given to a memory location, all the operations done on the variable effects that memory location.

In JavaScript, all the variables must be declared before they can be used.

**Before ES2015**, JavaScript variables were solely declared using the *var* keyword followed by the name of the variable and semi-colon. Below is the syntax to create variables in JavaScript.

```html
var var_name;
var x;
```

The var_name is the name of the variable which should be defined by the user and should be unique. These types of names are also known as **identifiers**. The rules for creating an identifier in JavaScript are, the name of the identifier should not be any pre-defined word(known as keywords), the first character must be a letter, an underscore (_), or a dollar sign ($). Subsequent characters may be any letter or digit or an underscore or dollar sign.

**Below are some examples of declaring and initializing variables in JavaScript:**

// Declaring single variable
var name;

// Declaring multiple variables
var name, title, num;

// Initializing variables
var name = "Harsh";
name = "Rakesh";

JavaScript is also known as **untyped** language. This means, that once a variable is created in JavaScript using the keyword var, we can store any type of value in this variable supported by JavaScript.

**After ES2015**, we now have two new variable containers: let and const. Now we shall look at both of them one by one. The variable type **Let** shares lots of similarities with var but unlike var, it has scope constraints.

JavaScript **let** is a keyword used to declare variables in JavaScript that are block scoped. Two new keywords were added in the ES6 or ES2015 version of javascript. Generally, it is suggested that we must use the let keyword while working with JavaScript.

**Block Scope:** The variables which are declared inside the { } block are known as block-scoped variables. variables declared by the var keyword cannot be block-scoped.

### **JavaScript Const**

ES2015 (ES6) introduced the const keyword to define a new variable. The difference in const variable declaration to others is that it cannot be re-assigned.

**Properties:**

Cannot be reassigned.

It’s Block Scope

It can be assigned to the variable on the declaration line.

It’s a Primitive value.

The property of a const object can be changed but it cannot be changed to a reference to the new object

The values inside the const array can be changed, it can add new items to const arrays but it cannot reference a new array.

Re-declaring of a const variable inside different block scopes is allowed.

Cannot be Hoisted.

Creates only read-only references to value

## Data Types

   JavaScript is  a weakly typed language, which means it allows implicit type conversion when an operation involves mismatched types, instead of throwing type errors.

```
let foo = 42; // foo is now a number
foo = "bar"; // foo is now a string
foo = true; // foo is now a boolean
```

Data or values have data types. Data types describe the characteristics of data. Data types can be divided into two:

1. Primitive data types
2. Non-primitive data types(Object References)
3. 

### Primitive Data Types

All types except Object define  immutable  values represented directly at the lowest level of the language. We refer to values of these types as *primitive values*.

Primitive data types in JavaScript include:

1. Numbers - Integers, floats
2. Strings - Any data under single quote, double quote or backtick quote
3. Booleans - true or false value
4. Null - empty value or no value
5. Undefined - a declared variable without a value
6. Symbol - A unique value that can be generated by Symbol constructor

## number

```css
let n = 123;
n = 12.345;
```

The *number* type represents both integer and floating point numbers

NaN("**N**ot **a** **N**umber") is a special kind of number value that's typically encountered when the result of an arithmetic operation cannot be expressed as a number. It is also the only value in JavaScript that is not equal to itself.

# JavaScript Strings

A string (or a text string) is a series of characters like "John Doe".

Strings are written with quotes. You can use single or double quotes:

```css
// Using double quotes:
```

```css
let carName1 = "Volvo XC60";
```

```css
// Using single quotes:
```

```css
let carName2 = 'Volvo XC60';
```

**String Concatenation**

Connecting two or more strings together is called concatenation. Using the strings declared in the previous String section:

`let fullName = firstName + space + lastName; // concatenation, merging two string together.
console.log(fullName);`

```css
charAt(): Takes index and it returns the value at that index
string.charAt(index)
let webtech= 'JavaScript  '
console.log(string.charAt(0)) // J
```

charCodeAt(): Takes index and it returns char code(ASCII number) of the value at that index.

```css
 endsWith: it takes a substring as an argument and it checks if the string starts with that specified substring. It returns a boolean(true or false).
string.endsWith(substring)
let string = 'Love is the best to in this world'
console.log(string.endsWith('world')) // true
console.log(string.endsWith('love')) // false
```

```css
includes(): It takes a substring argument and it check if substring argument exists in the string. includes() returns a boolean. It checks if a substring exist in a string and it returns true if it exists and false if it doesn't exist.
let string = '30 Days Of JavaScript'
console.log(string.includes('Days'))     // true
console.log(string.includes('days'))     // false
console.log(string.includes('Script'))     // true
```

```css

// indexOf(): Takes takes a substring and if the substring exists in a string it returns the first position of the substring if does not exist it returns -1
```

```css
string.indexOf(substring)
let string = '30 Days Of JavaScript'
console.log(string.indexOf('D'))          // 3
console.log(string.indexOf('Days'))       // 3
```

```css
 lastIndexOf(): Takes takes a substring and if the substring exists in a string it returns the last position of the substring if it does not exist it returns -1
```

```css
let string = 'I love JavaScript. If you do not love JavaScript what else can you love.'
console.log(string.lastIndexOf('love'))       // 67
```

```css
length: The string length method returns the number of characters in a string included empty space. Example:
```

```css
let js = 'JavaScript'
console.log(js.length)        // 10
```

```css
repeat(): it takes a number argument and it returned the repeated version of the string.
 string.repeat(n)
let string = 'love'
console.log(string.repeat(10)) // lovelovelovelovelovelovelovelovelovelove
```

```css
 replace(): takes to parameter the old substring and new substring.
string.replace(oldsubstring, newsubstring)
```

```css
let string = '30 Days Of JavaScript'
console.log(string.replace('JavaScript', 'Python')) // 30 Days Of Python
```

```css
search: it takes a substring as an argument and it returns the index of the first match.
 string.search(substring)
let string = 'I love JavaScript. If you do not love JavaScript what else can you love.
```

```css
split(): The split method splits a string at a specified place.
let string = '30 Days Of JavaScript'
console.log(string.split())     // ["30 Days Of JavaScript"]
console.log(string.split(' '))  // ["30", "Days", "Of", "JavaScript"]
let firstName = 'Asabeneh'
console.log(firstName.split())  // ["Tibebe"]
console.log(firstName.split(''))  // ["T", "i", "b", "e", "b", "e"]
```

```css
 toLowerCase(): this method changes the string to lowercase letters.
let string = 'JavasCript'
console.log(string.toLowerCase())     // javascript
let firstName = 'TibEBE'
console.log(firstName.toLowerCase())  // tibebe
```

```css
 toUpperCase(): this method changes the string to uppercase letters.
```

```css
let string = 'JavaScript'
console.log(string.toUpperCase())      // JAVASCRIPT
let firstName = 'Tibebe'
console.log(firstName.toUpperCase())  // TIBEBE
```

# Exponential Notation

Extra large or extra small numbers can be written with scientific (exponential) notation:

```css
let y = 123e5;    // 12300000
```

```css
let z = 123e-5;   // 0.00123
```

# JavaScript Booleans

Booleans can only have two values: `true` or `false`.

```css
let x = 5;
```

```css
let y = 5;
```

```css
let z = 6;
```

```css
(x == y)       // Returns true
```

```css
(x == z)       // Returns false
```

Non-primitive data types in JavaScript includes:

1. Objects
2. Arrays

### Non-Primitive Data Types

*Non-primitive* data types are modifiable or mutable. We can modify the value of non-primitive data types after it gets created. Let us see by creating an array. An array is a list of data values in a square bracket. Arrays can contain the same or different data types. Array values are referenced by their index. In JavaScript array index starts at zero. I.e., the first element of an array is found at index zero, the second element at index one, and the third element at index two, etc.

**1. An object** in Javascript is an entity having properties and methods. Everything is an object in javascript.

```
// Creating object with the name person
let person = {
	firstName: "Luiza",
	lastName: "Shaikh",
};

// Print the value of object on console
console.log(person.firstName
	+ " " + person.lastName);

```

**2.  Array:** With the help of an array, we can store more than one element under a single name.

```css

var a = new Array();
var b = new Array(10);
var d = new Array(1, 2, 3, "Hello");
console.log("value of a=" + a);
console.log("value of b" + b);
console.log("value of d=" + d);

```

| Primitive | Non-Primitive |
| --- | --- |
| Primitive Data types are predefined. | Non-Primitive data types are created by the programmer |
| Primitive Data types will have certain values. | Non-Primitive data types can be NULL. |
| Size depends on the type of data structure. | Size is not fixed |
| Examples are numbers and strings. | Examples are Array and Linked List. |
| It can start with a lowercase. | It can start with uppercase. |

## JavaScript operators

JavaScript operators operate the operands, these are symbols that are used to manipulate a certain value or operand. Operators are used to performing specific mathematical and logical computations on operands. In other words, we can say that an operator operates the operands. In JavaScript, operators are used to compare values, perform arithmetic operations, etc.

**JavaScript Operators:** There are various operators supported by JavaScript.

**JS Arithmetic Operators**

**JS Assignment Operators**

**JS Comparison Operators**

**JS Logical Operators**

**JS Ternary Operators**

**JS Bitwise Operators**

**JS typeof Operator**

**JavaScript Arithmetic Operators:** These are the operators that operate upon the numerical values and return a numerical value.

Addition (+)**:** Addition ‘+’ operator performs addition on two operands. This ‘+’ operator can also be used to concatenate (add) strings.

Subtraction (-)**:** Subtraction ‘-‘ operator performs subtraction on two operands.

Multiplication (‘*’ ): Multiplication ‘*’ operator performs multiplication on two operands.

Division( ‘/’)**:** Division ‘/’ operator performs division on two operands (divide the numerator by the denominator).

Modulus (‘%’) **:** Modulus ‘%’ operator gives a remainder of an **integer** division.

Exponentiation (‘**’) **:** Exponentiation ‘**’ operator give the power of the first operator raised to the second operator.

Increment (‘+ +’)**:** Increment ‘+ +’ operator increases an integer value by one.

Decrement ‘- -‘: Decrement ‘- -‘ operator decreases an integer value by one.

Unary ‘+’: Unary ‘+’ is the fastest and preferred way of converting something into a number.

```html
Addition Operator
let a = 10 + 100
console.log(a);//110
```

```html
Subtraction Operator
let b = 50-35
console.log(b);//15
```

```html
Multiplication Operator
let c = 5* 5
console.log(c);//25
```

```html
Division Operator
let d = 3.0 / 2.0
console.log(d);//1.5
```

```html
Modulas Operator
let e = 9 % 5
console.log(e)//4
```

```html
Exponentian Operator
let f = 2 ** 5
console.log(f)//33
```

```html
Increment Operator
let g = 2;
g1 = g++;
console.log(g)//3
```

```html
Decrement Operator
let h = 2;
h1 = h--;
console.log(h)//1
```

```html
Unary plus Operator
let i = 3;
i1 = +i;
console.log(i1)//3
```

```html
Negation Operator
let j = 3;
j1 = -j;
console.log(j1)//-3
```

**Logical Operators**

The following symbols are the common logical operators: &&(ampersand) , ||(pipe) and !(negation). The && operator gets true only if the two operands are true. The || operator gets true either of the operand is true. The ! operator negates true to false and false to true.

```html
// && ampersand operator example

const check = 4 > 3 && 10 > 5         // true && true -> true
const check = 4 > 3 && 10 < 5         // true && false -> false
```

```html

const check = 4 > 3 || 10 > 5         // true  || true -> true
const check = 4 > 3 || 10 < 5         // true  || false -> true
```

```html

let check = 4 > 3                     // true
let check = !(4 > 3)                  //  false
```

**Ternary Operators**

Ternary operator allows to write a condition. Another way to write conditionals is using ternary operators. Look at the following examples:

```html
let isRaining = true
isRaining
  ? console.log('You need a rain coat.')
  : console.log('No need for a rain coat.')
isRaining = false
```

**Operator precedence in JavaScript**

Operator precedence refers to the priority given to operators while parsing a statement that has more than one operator performing operations in it. It is important to ensure the correct result and also to help the compiler understand what the order of operations should be. Operators with higher priorities are resolved first.

| Operator | Operation | Order of Precedence | Order of Evaluation |
| --- | --- | --- | --- |
| ++ | Increment | 1 | R -> L |
| — | Decrement | 1 | R -> L |
| — | Negation | 1 | R -> L |
| ! | NOT | 1 | R -> L |
| *, /, % | Multiplication, division, modulus | 2 | L -> R |
| +, — | Addition, subtraction | 3 | L -> R |
| + | Concatenation | 3 | L -> R |
| <, <= | Less than, less than, or equal | 4 | L -> R |
| >, >= | Greater than, greater than, or equal | 4 | L -> R |
| == | Equal | 5 | L -> R |
| != | Not equal | 5 | L -> R |
| === | Identity | 5 | L -> R |
| !== | Non-identity | 5 | L -> R |
| && | AND | 6 | L -> R |
| || | OR | 6 | L -> R |
| ?: | Ternary | 7 | R -> L |
| = | Assignment | 8 | R -> L |
| +=, -=, and so on. | Arithmetic assignment | 8 | R -> L |

**JavaScript Bitwise Operators**

| Operator | Name | Description |
| --- | --- | --- |
| & | AND | Sets each bit to 1 if both bits are 1 |
| | | OR | Sets each bit to 1 if one of two bits is 1 |
| ^ | XOR | Sets each bit to 1 if only one of two bits is 1 |
| ~ | NOT | Inverts all the bits |
| << | Zero fill left shift | Shifts left by pushing zeros in from the right and let the leftmost bits fall off |
| >> | Signed right shift | Shifts right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off |
| >>> | Zero fill right shift | Shifts right by pushing zeros in from the left, and let the rightmost bits fall off |

**Examples**

| Operation | Result | Same as | Result |
| --- | --- | --- | --- |
| 5 & 1 | 1 | 0101 & 0001 | 0001 |
| 5 | 1 | 5 | 0101 | 0001 | 0101 |
| ~ 5 | 10 | ~0101 | 1010 |
| 5 << 1 | 10 | 0101 << 1 | 1010 |
| 5 ^ 1 | 4 | 0101 ^ 0001 | 0100 |
| 5 >> 1 | 2 | 0101 >> 1 | 0010 |
| 5 >>> 1 | 2 | 0101 >>> 1 | 0010 |

**The typeof Operator**

You can use the typeof operator to find the data type of a JavaScript variable

**Example**

```html
typeof "John"                 // Returns "string"
```

```html
typeof 3.14                   // Returns "number"
```

```html
typeof NaN                    // Returns "number"
```

```html
typeof false                  // Returns "boolean"
```

```html
typeof [1,2,3,4]              // Returns "object"
```

```html
typeof {name:'John', age:34}  // Returns "object"
```

```html
typeof new Date()             // Returns "object"
```

```html
typeof function () {}         // Returns "function"
```

```html
typeof myCar                  // Returns "undefined" *
```

```html
typeof null                   // Returns "object"
```

## Conditional statements In JavaScript

Conditional statements are used for make decisions based on different conditions. By default , statements in JavaScript script executed sequentially from top to bottom. If the processing logic require so, the sequential flow of execution can be altered in two ways:

Conditional execution: a block of one or more statements will be executed if a certain expression is true

Repetitive execution: a block of one or more statements will be repetitively executed as long as a certain expression is true. In this section, we will cover *if*, *else* , *else if* statements. The comparison and logical operators we learned in the previous sections will be useful in here.

**JavaScript if-statement:** It is a conditional statement used to decide whether a certain statement or block of statements will be executed or not i.e if a certain condition is true then a block of statement is executed otherwise not.

```html
syntax 

if(condition)
{
   // Statements to execute if
   // condition is true
}
```

The if statement accepts boolean values – if the value is true then it will execute the block of statements under it. If we do not provide the curly braces ‘{‘ and ‘}’ after **if( condition )** then by default if statement considers the immediate one statement to be inside its block.

```html
JavaScript program to illustrate If statement
var age = 19;

if (age > 18)
console.log("Congratulations, You are eligible to drive");
```

**JavaScript if-else statement:** The if statement alone tells us that if a condition is true it will execute a block of statements and if the condition is false it won’t. But what if we want to do something else if the condition is false? Here comes the else statement. We can use the else statement with the if statement to execute a block of code when the condition is false.

```html
**Syntax:**
if (condition)
{
    // Executes this block if
    // condition is true
}
else
{
    // Executes this block if
    // condition is false
}
```

```html
// JavaScript program to illustrate If-else statement
var i = 10;

if (i < 15)
console.log("i is less than 15");
else
console.log("I am Not in if");

Output:

i is less than 15
```

**JavaScript nested-if statement:** JavaScript allows us to nest if statements within if statements. i.e, we can place an if statement inside another if statement. A nested if is an if statement that is the target of another if or else.

```html
**Syntax:**
if (condition1)
{
   // Executes when condition1 is true
   if (condition2)
   {
      // Executes when condition2 is true
   }
```

```html
// JavaScript program to illustrate nested-if statement
var i = 10;
if (i == 10) { // First if statement
	if (i < 15){
			console.log("i is smaller than 15");
			// Nested - if statement
			// Will only be executed if statement above
			// it is true
			if (i < 12)
			console.log("i is smaller than 12 too");
			else
			console.log("i is greater than 15");
		}
}
output
i is smaller than 15
i is smaller than 12 too
```

**JavaScript if-else-if ladder statement:** Here, a user can decide among multiple options.The if statements are executed from the top down. As soon as one of the conditions controlling the if is true, the statement associated with that if is executed, and the rest of the ladder is bypassed. If none of the conditions is true, then the final else statement will be executed.

```html
**Syntax:**

if (condition)
    statement;
else if (condition)
    statement;
.
.
else
    statement;
```

```html
JavaScript program to illustrate nested-if statement
var i = 20;

if (i == 10)
console.log("i is 10");
else if (i == 15)
console.log("i is 15");
else if (i == 20)
console.log("i is 20");
else
console.log("i is not present");

Output
i is 20
```

## **Switch Statement**

Switch is an alternative for **if else if else else**. The switch statement starts with a *switch* keyword followed by a parenthesis and code block. Inside the code block we will have different cases. Case block runs if the value in the switch statement parenthesis matches with the case value. The break statement is to terminate execution so the code execution does not go down after the condition is satisfied. The default block runs if all the cases don't satisfy the condition.

```html
switch(caseValue){
  case 1:
    // code
    break
  case 2:
   // code
   break
  case 3:
   // code
   break
  default:
   // code
}
```

## Example

```html
const expr = 'Papayas';
switch (expr) {
case 'Oranges':
console.log('Oranges are $0.59 a pound.');
break;
case 'Mangoes':
case 'Papayas':
console.log('Mangoes and papayas are $2.79 a pound.');
// Expected output: "Mangoes and papayas are $2.79 a pound."
break;
default:
console.log(Sorry, we are out of ${expr}.);
}
output
Mangoes and papayas are $2.79 a pound.
```

## Window Methods And Date Object

### Window alert() method

As you have seen at very beginning alert() method displays an alert box with a specified message and an OK button. It is a built-in method and it takes on argument.

```
alert(message)
```

```
alert('Welcome to Web_Tech')
```

Do not use too much alert because it is destructing and annoying, use it just to test.

### Window prompt() method

The window prompt methods display a prompt box with an input on your browser to take input values and the input data can be stored in a variable. The prompt() method takes two arguments. The second argument is optional.

```
prompt('required text', 'optional text')
```

```
let number = prompt('Enter number', 'number goes here')
console.log(number)
```

### Window confirm() method

The confirm() method displays a dialog box with a specified message, along with an OK and a Cancel button. A confirm box is often used to ask permission from a user to execute something. Window confirm() takes a string as an argument. Clicking the OK yields true value, whereas clicking the Cancel button yields false value.

```
const agree = confirm('Are you sure you like to delete? ')
console.log(agree) // result will be true or false based on what you click on the dialog box.
```

## Date Object

Time is an important thing. We like to know the time a certain activity or event. In JavaScript current time and date is created using JavaScript Date Object. The object we create using Date object provides many methods to work with date and time.The methods we use to get date and time information from a date object values are started with a word *get* because it provide the information. *getFullYear(), getMonth(), getDate(), getDay(), getHours(), getMinutes, getSeconds(), getMilliseconds(), getTime(), getDay().*

![Untitled](What%20is%20JavaScript%20464c83ccb5324370861f1d877d3dc139/Untitled%201.png)

# Arrays

In contrast to variables, an array can store *multiple values*. Each value in an array has an *index*, and each index has *a reference in a memory address*. Each value can be accessed by using their *indexes*. The index of an array starts from *zero*, and the index of the last element is less by one from the length of the array.

An array is a collection of different data types which are ordered and changeable(modifiable). An array allows storing duplicate elements and different data types. An array can be empty, or it may have different data type values.

**Declaration of an Array:**

```html
 let arrayName = [value1, value2, ...];

// Initializing while declaring
let house = ["1A", "2B", "3C", "4D"];
```

**Example:** An array in JavaScript can hold different elements that can store Numbers, Strings, and Boolean in a single array.

```html
// Storing number, boolean, strings in an Array
let house = ["1BHK", 25000, "2BHK", 50000, "Rent", true];
console.log(house)

```

**Example:** Accessing Array Elements of an Array in JavaScript are indexed from 0 so we can access array elements as follows.

```html
let house = ["1BHK", 25000, "2BHK", 50000, "Rent", true];
console.log(house[0]+" cost= "+house[1]);
let cost_1BHK = house[1];
let is_for_rent = house[5];
console.log("Cost of 1BHK = "+ cost_1BHK);
console.log("Is house for rent = ")+ is_for_rent;

Output:

"1BHK cost= 25000"
"Cost of 1BHK = 25000"
"Is house for rent = "
```

### Modifying array element

An array is mutable(modifiable). Once an array is created, we can modify the contents of the array elements.

```
const numbers = [1, 2, 3, 4, 5]
numbers[0] = 10      // changing 1 at index 0 to 10
numbers[1] = 20      // changing  2 at index 1 to 20

console.log(numbers) // [10, 20, 3, 4, 5]
```

## **JavaScript Basic Array Methods**

 **JavaScript Array.push() method:** Adding Element at the end of an Array. As arrays in JavaScript are mutable objects, we can easily add or remove elements from the Array. And it dynamically changes as we modify the elements from the array.

**Syntax :**

```
Array.push(item1, item2 …)
```

**Parameters:** Items to be added to an array.

**Example:** In this example, we will be adding new elements such as some numbers and some string values to the end of the array using **push()** method.

```html
// Adding elements at the end of an array
// Declaring and initializing arrays
let number_arr = [ 10, 20, 30, 40, 50 ];
number_arr.push(60);
number_arr contains [10, 20, 30, 40, 50, 60];

```

**JavaScript Array.unshift() method:** This method is used to add elements to the front of an Array

**Syntax :**

```
Array.unshift(item1, item2 …)
```

**Parameters:** Items to be added to the array

**Example:** In this example, we will be adding new elements to the beginning of the array using the **unshift()** method.

```html
// Adding element at the beginning of an array
    // Declaring and initializing arrays
let number_arr = [ 20, 30, 40 ];

number_arr.unshift(10, 20); 
// number_arr contains
    // [10, 20, 20, 30, 40]
```

 **JavaScript Array.pop() method:**This method is used to remove elements from the end of an array.

**Syntax:**

```
Array.pop()
```

**Parameters:** It takes no parameter

**Example:** In this example, we will be removing an element from the end of the array using the **pop()** method.

```html
// Removing elements from the end of an array
    // Declaring and initializing arrays

let number_arr = [ 20, 30, 40, 50 ];
number_arr.pop();
// number_arr contains
    // [ 20, 30, 40 ]

```

**JavaScript Array.shift() method:**ThisThis method is used to remove elements from the beginning of an array

**Syntax :**

```
Array.shift()
```

**Parameter:** it takes no parameter

**Example:** In this example, we will be removing an element from the beginning of the array using the **shift()** method.

```html
// Removing element from the beginning of an array
    // Declaring and initializing arrays

let number_arr = [ 20, 30, 40, 50, 60 ];
number_arr.shift();
// number_arr contains
    //  [30, 40, 50, 60];

```

 **JavaScript Array.splice() method:**This method is used for the Insertion and Removal of elements in between an Array.

```html
Array.splice (start, deleteCount, item 1, item 2….)
```

**Parameters:** 

- **Start:** Location at which to perform the operation.
- **deleteCount:** Number of elements to be deleted, if no element is to be deleted pass 0.
- **Item1, item2 …..:** this is an **optional** parameter.

These are the elements to be inserted from the location *start*

**Example:** In this example, we will be removing an element and adding new elements at the same time using the **splice()** method.

```html
// Removing an adding element at a particular location
    // in an array
    // Declaring and initializing arrays

let number_arr = [ 20, 30, 40, 50, 60 ];
number_arr.splice(1, 3);
// deletes 3 elements starting from 1
    // number array contains [20, 60]
```

## **Array Functions Summary:**

| Function | Usage |
| --- | --- |
| https://www.geeksforgeeks.org/javascript-array-push-method/ | Adds an element to the end of the array |
| https://www.geeksforgeeks.org/javascript-array-pop-method/ | Removes the last element of the array |
| https://www.geeksforgeeks.org/javascript-array-shift-method/ | Removes the first element of the array |
| https://www.geeksforgeeks.org/javascript-array-slice-method/(beginIndex, endIndex) | Returns a part of the array from beginIndex to endIndex |
| https://www.geeksforgeeks.org/javascript-array-splice-method/(beginIndex, endIndex) | Returns a part of the array from beginIndex to endIndexand modifies the original array by removing those elements |
| https://www.geeksforgeeks.org/javascript-string-concat-method/(arr) | Adds new elements (from arr) into the array at the end of the array |

### Array of arrays

Array can store different data types including an array itself. Let us create an array of arrays

```
const firstNums = [1, 2, 3]
const secondNums = [1, 4, 9]

const arrayOfArray =  [[1, 2, 3], [1, 2, 3]]
console.log(arrayOfArray[0]) // [1, 2, 3]

 const frontEnd = ['HTML', 'CSS', 'JS', 'React', 'Redux']
 const backEnd = ['Node','Express', 'MongoDB']
 const fullStack = [frontEnd, backEnd]
 console.log(fullStack)   // [["HTML", "CSS", "JS", "React", "Redux"], ["Node", "Express", "MongoDB"]]
```

# Loop in JavaScript

**Looping** in programming languages is a feature that facilitates the execution of a set of instructions/functions repeatedly while some condition evaluates to true. For example, suppose we want to print “Hello World” 10 times. 

- An operation is done, such as getting an item of data and changing it, and then some condition is checked such as whether a counter has reached a prescribed number.
- **Counter not Reached:** If the counter has not reached the desired number, the next instruction in the sequence returns to the first instruction in the sequence and repeats it.
- **Counter reached:** If the condition has been reached, the next instruction “falls through” to the next sequential instruction or branches outside the loop.

**There are mainly two types of loops:**

- **Entry Controlled Loop:** In these types of loops, the test condition is tested before entering the loop body. The **for Loop** and **while Loop** are entry-controlled loops.
- **Exit Controlled Loop:** In these types of loops the test condition is tested or evaluated at the end of the loop body. Therefore, the loop body will execute at least once, irrespective of whether the test condition is true or false. The **do-while loop** is exit controlled loop.

JavaScript mainly provides three ways for executing the loops. While all the ways provide similar basic functionality, they differ in their syntax and condition-checking time.

**while loop:** A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.

**Syntax :**

```
while (boolean condition) {
    loop statements...
}
```

![Untitled](What%20is%20JavaScript%20464c83ccb5324370861f1d877d3dc139/Untitled%202.png)

- While loop starts with checking the condition. If it is evaluated to be true, then the loop body statements are executed otherwise first statement following the loop is executed. For this reason, it is also called the **Entry control loop**
- Once the condition is evaluated to be true, the statements in the loop body are executed. Normally the statements contain an updated value for the variable being processed for the next iteration.
- When the condition becomes false, the loop terminates which marks the end of its life cycle

```
let i = 0
while (i <= 5) {
  console.log(i)
  i++
}

// 0 1 2 3 4 5
```

**for loop:** for loop provides a concise way of writing the loop structure. Unlike while loop, a for statement consumes the initialization, condition, and increment/decrement in one line thereby providing a shorter, easy-to-debug structure of looping.

**Syntax:**

```
for (initialization; testing condition; increment/decrement) {
    statement(s)
}
```

![Untitled](What%20is%20JavaScript%20464c83ccb5324370861f1d877d3dc139/Untitled%203.png)

- **Initialization condition:** Here, we initialize the variable in use. It marks the start of a for loop. An already declared variable can be used or a variable can be declared, local to loop only.
- **Testing Condition:** It is used for testing the exit condition for a loop. It must return a boolean value. It is also an **Entry Control Loop** as the condition is checked prior to the execution of the loop statements.
- **Statement execution:** Once the condition is evaluated to be true, the statements in the loop body are executed.
- **Increment/ Decrement:** It is used for updating the variable for the next iteration.
- **Loop termination:** When the condition becomes false, the loop terminates marking the end of its life cycle.

```
const countries = ['Finland', 'Sweden', 'Denmark', 'Norway', 'Iceland']
const newArr = []
for(let i = 0; i < countries.length; i++){
  newArr.push(countries[i].toUpperCase())
}

// ["FINLAND", "SWEDEN", "DENMARK", "NORWAY", "ICELAND"]
```

**do-while:** The do-while loop is similar to the while loop with the only difference is that it checks for the condition after executing the statements, and therefore is an example of an **Exit Control Loop.**

**Syntax:**

```
do {
    Statements..
}
while (condition);
```

![Untitled](What%20is%20JavaScript%20464c83ccb5324370861f1d877d3dc139/Untitled%204.png)

- The do-while loop starts with the execution of the statement(s). There is no checking of any condition for the first time.
- After the execution of the statements and update of the variable value, the condition is checked for a true or false value. If it is evaluated to be true, the next iteration of the loop starts.
- When the condition becomes false, the loop terminates which marks the end of its life cycle.
- It is important to note that the do-while loop will execute its statements at least once before any condition is checked and therefore is an example of the exit control loop.

**Infinite loop:** One of the most common mistakes while implementing any sort of looping is that it may not ever exit, i.e. the loop runs for infinite times. This happens when the condition fails for some reason.

```html
// JavaScript program to illustrate infinite loop

// Infinite loop because condition is not false
// condition should have been i>0.
for (let i = 5; i != 0; i -= 2) {
console.log(i);
}
let x = 5;
// Infinite loop because update statement
// is not provided
while (x == 5) {
console.log("In the loop");
}
```

```
let i = 0
do {
  console.log(i)
  i++
} while (i <= 5)

// 0 1 2 3 4 5
```

### for of loop

We use for of loop for arrays. It is very hand way to iterate through an array if we are not interested in the index of each element in the array.

```
const countries = ['Finland', 'Sweden', 'Norway', 'Denmark', 'Iceland']
const newArr = []
for(const country of countries){
  newArr.push(country.toUpperCase())
}

console.log(newArr)  // ["FINLAND", "SWEDEN", "NORWAY", "DENMARK", "ICELAND"]
```

## For-in loop

in JavaScript is used to iterate over the properties of an object. It can be a great debugging tool if we want to show the contents of an object. The for-in loop iterates only over those keys of an object which have their enumerable property set to “true”. The key values in an object have four attributes (value, writable, enumerable, and configurable). Enumerable when set to “true” means that we can iterate over that property.

```
for (let i in obj1) {
    // Prints all the keys in
    // obj1 on the console
    console.log(i);
    }
```

**Important Points:**

- Use the for-in loop to iterate over non-array objects. Even though we can use a for-in loop for an array, it is generally not recommended. Instead, use a for loop for looping over an array.
- The order in which properties are iterated may not match the properties that are defined in the object.

# Functions in JavaScript

A **function** is a set of statements that take inputs, do some specific computation, and produce output. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can call that function.

Function makes code:

- clean and easy to read
- reusable
- easy to test

A function can be declared or created in couple of ways:

- *Declaration function*
- *Expression function*
- *Anonymous function*
- *Arrow function*

**Function Declaration:** It declares a function with a function keyword. The function declaration must have a function name.

**Syntax**: The basic syntax to create a function in JavaScript is shown below.

```
function functionName(Parameter1, Parameter2, ...)
{
    // Function body
}
```

To create a function in JavaScript, we have to first use the keyword *function*, separated by the name of the function and parameters within parenthesis. The part of the function inside the curly braces {} is the body of the function.

**Function Definition:** Before, using a user-defined function in JavaScript we have to create one. We can use the above syntax to create a function in JavaScript. A function definition is sometimes also termed a function declaration or function statement. Below are the rules for creating a function in JavaScript:

- Every function should begin with the keyword *function* followed by,
- A user-defined function name that should be unique,
- A list of parameters enclosed within parentheses and separated by commas,
- A list of statements composing the body of the function enclosed within curly braces {}.

```html
function calcAddition(number1, number2) {
return number1 + number2;
}
console.log(calcAddition(6,9));

Output
15
```

**Function Expression:** It is similar to a function declaration without the function name. Function expressions can be stored in a variable assignment.

**Syntax:**

```
let Web-tech= function(paramA, paramB) {
    // Set of statements

```

```html
const square = function (number) {
return number * number;
};
const x = square(4); // x gets the value 16
console.log(x);
```

### Anonymous Function

Anonymous function or without name

```html
const anonymousFun = function() {
  console.log(
    'I am an anonymous function and my value is stored in anonymousFunction'
  )
}
```

 **Arrow Function:** It is one of the most used and efficient methods to create a function in JavaScript because of its comparatively easy implementation. It is a simplified as well as a more compact version of a regular or normal function expression or syntax.

**Syntax:**

```
let function_name = (argument1, argument2 ,..) => expression
const a = ["Hydrogen", "Helium", "Lithium", "Beryllium"];
const a2 = a.map(function (s) {
return s.length;
});
console.log("Normal way ", a2); // [8, 6, 7, 9]
const a3 = a.map((s) => s.length);
console.log("Using Arrow Function ", a3); // [8, 6, 7, 9]
```

**Function Parameters:** Till now, we have heard a lot about function parameters but haven’t discussed them in detail. Parameters are additional information passed to a function. For example, in the above example, the task of the function *calcAddition* is to calculate the addition of two numbers. These two numbers on which we want to perform the addition operation are passed to this function as parameters. The parameters are passed to the function within parentheses after the function name and separated by commas. A function in JavaScript can have any number of parameters and also at the same time, a function in JavaScript can not have a single parameter.

**Example :** In this example, we pass the argument to the function.

```html
function multiply(a, b) {
b = typeof b !== "undefined" ? b : 1;
return a * b;
}
console.log(multiply(69)); // 69
```

**Function with default parameters**

Sometimes we pass default values to parameters, when we invoke the function if we do not pass an argument the default value will be used. Both function declaration and arrow function can have a default value or values.

```
// syntax
// Declaring a function
function functionName(param = value) {
  //codes
}

// Calling function
functionName()
functionName(arg)
```

**Example:**

```html
function greetings(name = 'Betty') {
  let message = `${name}, welcome to Webb_tech!`
  return message
}

console.log(greetings())
console.log(greetings('Tibebe'))
```

**Calling Functions**: After defining a function, the next step is to call them to make use of the function. We can call a function by using the function name separated by the value of parameters enclosed between the parenthesis and a semicolon at the end. The below syntax shows how to call functions in JavaScript:

**Syntax:**

```
functionName( Value1, Value2, ..);
```

**Example :** Below is a sample program that illustrates the working of functions in JavaScript:

```html
function welcomeMsg(name) {
return ("Hello " + name + " welcome to Web_tech");
}
// creating a variable
let nameVal = "Students";
// calling the function
console.log(welcomeMsg(nameVal));

Output:

Hello Students welcome to Web_tech 
```

### Self Invoking Functions

Self invoking functions are anonymous functions which do not need to be called to return a value.

```
(function(n) {
  console.log(n * n)
})(2) // 4, but instead of just printing if we want to return and store the data, we do as shown below

let squaredNum = (function(n) {
  return n * n
})(10)

console.log(squaredNum)
```

**Return Statement**: There are some situations when we want to return some values from a function after performing some operations. In such cases, we can make use of the return statement in JavaScript. This is an optional statement and most of the time the last statement in a JavaScript function. Look at our first example with the function named as *calcAddition*. This function is calculating two numbers and then returns the result.

**Syntax:** The most basic syntax for using the return statement is:

```
return value;
```

The return statement begins with the keyword *return* separated by the value which we want to return from it. We can use an expression also instead of directly returning the value.