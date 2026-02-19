
## Template Literals

Single-quoted or double-quoted strings behave basically the same. But when you create a String with backtick quotes, you'll have a little more functionality.

With backtick quotes you won't need to use the escape character with `n` to span lines.

```js
// with single quotes
console.log('To be or not to be/nThat is the question');
/*
output:
To be or not to be
That is the question
*/

// with backticks
console.log(`To be or not to be
			That is the question`);
/*
output:
To be or not to be
That is the question
*/	
```

Another cool feature of backticks is to create new strings from embedding values instead of concatenating with the `+` operator.

```js
`I am ${2024 - 1994} years old`; //output: I am 30 years old

let first = `spider`;
let second = `man`;

console.log(`Peter Parker is ${first}-${second}`); //output: Peter Parker is spider-man
```

Everything you place inside `${}` in a template literal will be converted to a string and included in that position.
