## The ternary operator

You've seen a lot of boolean operators and how to combine them. There's a special name for expressions that produce boolean values: conditions.

So far, we have not don much with the value produced by conditions. We've just printed it to the console or stored it in some variable. There's much more we can do do with conditions, such as making a decision between two choices.

This last boolean operator (boolean in the sense that it produces a boolean value) was built just for this. It doesn't take one, nor two, but three operands It's called the conditional operator, but most of the time just ternary operator, since there's no other quite like it in JavaScript.

```js
let speed = 100;
let whatNow = speed < 80 ? 'BOOM' : 'Keep driving';
console.log(whatNow); //if the speed is lower than 80, bus explodes; if not, you better keep driving.
```

This is a very elegant and expressive operator. As most boolean expressions it reads almost like an english sentence.

JavaScript first evaluates the condition before the `?` (it MUST be a condition, a boolean expression). If it's true the ternary will produce the value that is left to the `:` sign; if it's false, the one to the right.

### Practice

Considering the following code, what's the value of the `activity` variable?

```js
let isSunny = true;
let temperature = 32;
let activity = isSunny && temperature > 30 ? 'Go skating' : 'Go surfing';
```

1.
```js
true
```

2.
```js
'Go surfing'
```

3.
```js
'Go skating'
```

4.
```js
false
```