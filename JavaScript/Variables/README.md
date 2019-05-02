### JavaScript Variables

A variable is a named reference that holds value of any data type.
You can assign a value to a variable using the equal to operator (=).

```js
var name = "Brian";
console.log(name);
```

The variable name now holds the value of "Brian";
Values of a variable can be changed we initialize a variable with the var keyword with a starting value of "Brian"
We can replace the value of the name variable by reasigning it to something new.

```js
name = "Tom";
console.log(name);
```

This code is read top down so whatever the last value of name is will be printed if we console.log()

## ES6+ Variables

```
ECMAScript is a scripting-language specification standardized by Ecma International in ECMA-262 
and ISO/IEC 16262. It was created to standardize JavaScript, so as to foster multiple independent implementations
```
ES6 implemented let and const 

### let 
 
If we initialize a variable with the let keyword this is a variable whose value can be altered.

```js
let amount = 9;
// amount can then be altered since it was initialized with let
amount = 10;
```

## const
If we initialize a variable with the const keyword this is a variable whose value must remain constant

```js
const name = "Brian";
// name cannot be altered since it was initialized with const
```

Using let and const is more organized and allows for less unpredictability than using the var keyword.

