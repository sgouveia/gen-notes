
## String and Number

Dealing with numbers and strings when using the `+` operator may lead to unexpected results if you're not sure which one is assigned to a variable:

```js
let someNumber = 2;
let someText = '2';

console.log(someNumber + someNumber); // what do you think the output will be?
console.log(someText + someText); // what about now?
```

This is a good demonstration of the importance of giving good names to variables. But if you want to be really sure, JavaScript allows you to find out what type of value is inside a variable before using it. This is the operator `typeof` (not all operators are symbols), and it produces a string value naming the type inside a variable.

```js
console.log(typeof someNumber); //output: number
console.log(typeof someText); // output: string
```

It's possible to concatenate strings and numbers with the `+` operator, which is very useful.

```js
let year = 2024;
let sentence = 'The year is ' + 2024; //output: The year is 2024
```

JavaScript will somehow assume that what you need is a new string, and it will convert the number 2024 to the string '2024' before performing the concatenation operation.

You can even perform an arithmetic operation before concatenation:

```js
let yearOfBirth = 1994;
let currentYear = 2024;
console.log('my age is ' + (currentYear - yearOfBirth));
//output: my age is 30
```

