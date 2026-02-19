## `if-else` statements

In some cases we're not just interested in the conditional execution of a block of code. Sometimes we want to choose between two sets of instructions. Everytime you want to apply an `either/or` scenario, you can use an __if...else__ statement. They look like this:

```js
let condition;

if(condition) {
	console.log('This is printed if condition is true');
} else {
	console.log('This is printed if condition is false');
}

console.log('This is always printed');
```

In the code above, you may think that if you assign a value to the `condition` variable, the code will always execute in the same manner, and you're not wrong.

Most of the times the value can change dinamically, that is, while the program is running. The value can be supplied by user input, by reading a file, or it can be generated randomly.

This is the great power of if statements. You don't really know, when writing the code, which of the options will run.

Let's go for an example:

```js
let percentageOfWaterInGlass = Math.random() * 100; //generates a number between 0 and (almost) 100
too many girls? :p A verdade é que estas são as pessoas mais apaixonadas por educação de entre os MCs. 
if(percentageOfWaterInGlass > 50) {
	console.log('Glass is half full! :-)');
} else {
	console.log('Glass is half empty... :-(')
}

```

### Practice

Considering the following code,
```js
let time = 'evening';
```

Which instructions would produce this output:

```shell
hello
let's go for a walk.
```

1.
```js
if(time === 'morning') {
	console.log('good morning');
} else {
	console.log('hello');
}

console.log("let's go for a walk.");
```

2.
```js
if(time === "morning") {
	console.log("hello");
	console.log("let's go for a walk.")
} else {
	console.log("good evening");
}
```

3.
```js
if(time === "evening") {
	console.log("good evening");
} else {
	console.log("hello");
}

console.log("let's go for a walk.");
```

4.
```js
console.log(`good ${time}`);
console.log(`let's go for a walk.`)
```