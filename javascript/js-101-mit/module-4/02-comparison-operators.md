
## Comparison Operators

We've seen how some operators produce numeric values, such as the arithmetic ones, or string values, like the concatenation operator. It's time to get acquainted with operators that will produce boolean values.

Let's start with comparison operators. Some questions are best answered with a simple yes or no, and this is what comparison operators are here for.

```js
// is less than; is greater than
3 < 9 // true
9 > 9 // false

// is equal to; is not equal to
9 === 5 // false
3.14 !== 4.13 // true

// is less than or equal to; is greater than or equal to
-2 <= -20 // false
5 >= 5 // true

```

Printing any of these expressions with `console.log`, JavaScript will output `true` or `false`, the boolean value of the expression. And of course you can (and most probably will) be using these operators with variables as operands and even combine them with arithmetic operators. An example:

```js
let benchmark = 9000;
let average = 5000;
let secondForm = 3500;
let bonus = 501;

let isOver9000 = (average + secondForm + bonus) > benchmark;

console.log(isOver9000); // outputs true
```

These boolean operators are mostly used with numbers, but JavaScript also allows you to compare strings, based on standard alphabetical ordering.

```js
'a' < 'b' // true 
'mario' > 'zelda' // false

//Beware of strings representing numbers
'2' > '12' // true: alphabetically the character '1' comes before '2'
```

Boolean variables in most languages also have a naming convention. Always try to use something like a question that could be answered with one of two possibilities: `isConnected`, `hasPowerUp`, `isMoving`.

### Practice

Given the following code, which value should be assigned to `b` in order for the `console.log` to print `false`?
```js
let a = 10;
let b;

console.log(a > b);
```

1. -10
2. 10
3. 8
4. 0