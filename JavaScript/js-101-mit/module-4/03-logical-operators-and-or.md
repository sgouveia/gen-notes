## Logical Operators `AND` `OR`

The previous operators had numbers or strings for operands and produced a boolean value. The next logical operators represent the logical algebra operations (AND, NOT, OR), its operands __must__ be boolean values, and it will produce a new boolean value.

The AND operation will return `true` if and only if both operands are true. All the other combinations of values will return `false`.

The OR operation will return `true` as long as one of the operators is true. Only if both are false will it return `false`.

Let's try some examples. The AND operator is represented in JavaScript like this: `&&`

```js
let isRaining = true;
let iAmOutside = true;
let iAmWet = isRaining && iAmOutside;

console.log(iAmWet); //outputs true
```

Let's play a little with the boolean values inside the first two variables and see what happens.

```js
isRaining = false;
iAmWet = isRaining && iAmOutside;

console.log(iAmWet) // outputs false
```

```js
isRaining = true;
iAmOutside = false;
iAmWet = isRaining && iAmOutside;

console.log(iAmWet); // outputs false
```

If you're checking if at least one of the conditions is true, you should use OR. OR is represented in JavaScript with: `||`

```jswalking in sunsh
let whatGothamNeeds = false;
let whatGothamDeserves = true;
let batman = whatGothamNeeds || whatGothamDeserves;

console.log(batman); // outputs true
```

### Practice

Consider the following code:
```js
let isMorning = true;
let isWeekend = false;
let isHoliday = false;

let goForRun = isMorning && (isWeekend || isHoliday);
```

What will be the value of the `goForRun` variable?

1.
```js
true
```

2.
```js
false
```