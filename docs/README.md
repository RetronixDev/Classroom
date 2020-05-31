# Epoxy Development - Classroom

## JavaScript Variable
> Variable means anything that can vary. JavaScript includes variables which hold the data value and it can be changed anytime.

JavaScript uses reserved keyword var to declare a variable. A variable must have a unique name. You can assign a value to a variable using equal to (=) operator when you declare it or before using it.

### Syntax
```js
var <variable-name>;
var <variable-name> = <value>;
```

### Example: Variable Declaration & Initialization
```js
var one = 1; // variable stores numeric value

var two = 'two';  // variable stores string value

var three;  // declared a variable without assigning a value
```
In the above example, we have declared three variables using var keyword: one, two and three. We have assigned values to variables one and two at the same time when we declared it, whereas variable three is declared but does not hold any value yet, so it's value will be 'undefined'.

### Example: Multiple Variables in a Single Line
```js
var one = 1, two = 'two', three;
```

### Declare a Variable without var Keyword
JavaScript allows variable declaration without var keyword. You must assign a value when you declare a variable without var keyword.

```js
one = 1;

two = 'two';
```

### Points to Remember :
- Variable stores a single data value that can be changed later.
- Variables can be defined using var keyword. Variables defined without var keyword become global variables.
- Variables must be initialized before using.
- Multiple variables can be defined in a single line. e.g. var one = 1, two = 2, three = "three";
- Variables in JavaScript are loosely-typed variables. It can store value of any data type through out it's life time.
