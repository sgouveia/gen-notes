## Logical Operators - `NOT`

Another operator you'll be using everyday in this journey will be the NOT. This is a unary operator: you use it on a single (boolean) operand and it will flip its boolean value. In JavaScript, NOT is represented by the `!` symbol.

Let's go through some examples.

```js
let intended = true;
let pun = !intended
console.log(pun); // outputs false
```
can
As with most operators, it's most useful when you combine it with others. You may mix boolean and numeric operators in your search for the truth of same statement.

Take some time to read the next example. It has a lot of expressions that will be resolved each at its time, until the final value is produced and assigned to the variable.

```js
let minAge = 4;
let maxAge = 99;
let myAge = 12;

let canPlayWithLegos = (myAge >= minAge) && !(myAge >= maxAge); // true if myAge is between 4 and 99
```

It takes a while to get used to the syntax of boolean operators. But try reading it aloud and you'll get something like an english sentence: _I can play with legos if my age __is higher than__ the minimum age __and__ it's __not__ __higher than__ the maximum age_.

We can even create more complex sentences like this, with yet another logical operator.

```js
let giveADamn = false;
canPlayWithLegos = ((myAge > minAge) && !(myAge > maxAge)) || !giveADamn; // always true

```

As with the arithmetic operators there are some rules for precedence with logical operators:

1. NOT: `!`
2. Comparison Operators: `===`, `>`, `<`, `>=`, `<=`
3. AND: `&&`
4. OR: `||`

This means that the expression above wouldn't need any parenthesis, but in most cases it's safer and easier to read if your intention is as clear as possible.

### Practice

Considering two variables `isRaining` and `hasUnbrella`, which JavaScript code best represents the following sentence: "It's raining and you don't have an umbrella"?

1.
```js
!isRaining && !hasUmbrella
```
2.
```js
isRaining
```
3.
```js
isRaining || !hasUmbrella
```
4.
```js
isRaining && !hasUmbrella
```