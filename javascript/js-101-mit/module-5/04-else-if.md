## `else if` statements

`if...else` statements branch the execution of code conditionally between only two options. If we have more than two possibilities, there's another way. It's like having a simple `if...else`, but in the middle you'll add several `else if` statements, each with its condition.

Conditions are verified sequentially, and if one is met the following block of code will execute, and none of the others will even be verified.

```js
var season = 'summer';

if (season === 'spring') {
    console.log('The trees might blossom, but winter is coming.');
} else if (season === 'summer') {
    console.log('It might be time to harvest, but winter is coming.');
} else if (season === 'autumn') {
    console.log('Leaves may fall, but winter is coming.');
} else if (season === 'winter') {
    console.log('Winter is here!');
} else {
    console.log('That is not a season...');
}

// prints 'It might be time to harvest, but winter is coming.'

```

In the example above the value stored in the variable `season` is the string "summer", which means that only the conditions in the `if` statement and in the first `else if` statement are checked. Once the condition is met, that block of code is executed, and the following clauses ignored.

If the value stored in the variable season was the string "potato" (or, in fact, any string outside "spring", "summer", "autumn", and "winter"), the boolean expressions on all `else if` statements would be checked, and found to evaluate to `false`. This would mean that the block of code that follows the `else` statement would be executed, just as we saw on the previous lesson.

### Practice

