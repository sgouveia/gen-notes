
## Concatenation

When you're creating a new String you're producing a value (in memory that didn't exist before). A String is a JavaScript value, in the same way a Number is. Almost anything you'll put inside quotes will be a String.

This distinction between Numbers and Strings is important. Consider the following instructions:

```js
42; // a numeric value: a Number
'42'; // a text value: a String
```

If you go ahead and print both values, they will look the same in the console, but they represent two different values in your program.

You can't multiply or subtract two text values, but you can with two numbers as you've been doing extensively in previous lessons. There is one operator, though, you can use both with numbers and strings. The `+` operator.

Of course, you won't be adding strings (in the arithmetic sense, at least), but you'll be creating a new String comprised of the left and right operands together.

```js
console.log('bat' + 'man'); //output: batman
let first = 'spider';
let second = 'man';
console.log(first + '-' + second); //output: spider-man
```

This is called concatenation: we're creating a new string by joining two previous ones.