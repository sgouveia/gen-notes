## `if` statements

In one of the first lessons we've told you what looked like a very obvious truths in JavaScript: code execution is done sequentially. This means that the execution of a program works much like reading a story. Statements are interpreted (and executed) from top to bottom in the order in which they were written.

However not all programs will have a straightforward execution. Frequentely we will want some statements to be executed depending on a condition (remember: a condition is an expression that produces a boolean value). Meaning that if a certain condition is met we will want a block of instructions to be executed, otherwise, skip them.

The simplest conditional statement you can use is called an __if statement__. The execution of the code inside an if statement is dependent on the evaluation of the boolean expresion on that if's conditional.

```js
let age = 15;

console.log("These are some of your rights:")

if (age >= 18) {
	console.log("having a driver's license");
	console.log("to vote");
	console.log("attend a casino");
}

console.log("freedom of speech");
console.log("freedom from discrimination");
```

The condition in the if statement (`age > 18`) is evaluated to `true` or `false` and each case produces a different output. If true, the three `console.log` inside the block will be executed and printed. If false, JavaScript will ignore them and jump to the `console.log` outside of it. (We call _a block_ to the code inside the curly brackets `{ }`).

Because we know that the `age` variable is already assigned with `15`, the output would always be:

```shell
These are some of your rights:
freedom of speech
freedom from discrimination
```

If we changed age to 30, then the following output would occur:

```shell
These are some of your rights:
having a driver's license
to vote
attend a casino
freedom of speech
freedom from discrimination
```

### Practice

Considering the following code, what value should the variable `hours` hold, so both strings are printed to the console?

```js
if(hours > 2 && hours < 8) {
	console.log('I should be sleeping');
}

console.log("it's now " + hours + "hours.");
```

1.
```js
true
```

2.
```js
8
```

3.
```js
4
```

4.
```js
20
```
