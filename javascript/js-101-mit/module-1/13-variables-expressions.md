## variables and expressions

Let's dwell on some more scenarios.

```js
let myAge = 30;
let myOlderBrotherAge = 30 + 6;
```

As seen before, a variable never stores anything but values. In the second statement of the above code, it looks like we're assigning an expression to a variable, but JavaScrip will always resolve the expression first (in this case to the number `36`), and only after the assignment operator will *work*.

Variables don't *care* or *know* where their values came from. Their only purpose is to store values and return them on demand.

You could write that statement differently and more expressively, and it would do the exact same thing:

```js
myOlderBrotherAge = myAge + 6;
```

Look at the right of the assignment operator. It's nothing more than an expression, although JavaScript will have a little more work to do. First, it will replace `myAge` with the value stored in it (`30`), then it will add both numbers and finally, it will assign the new value to `myOlderBrotherAge`. After all this work, if you *ask* the variable what's inside, you'll obtain `36`, and nothing more. You won't have a way to know if that value came from a sum, a division, another variable, or the sum of two variables. And that's fine.

Knowing this, try and reason what happens with some code like the next one:

```js
let a = 5;
let b = a;
a = 7;
console.log(a);
console.log(b);
```