We've stored functions as values inside variables and object properties. We can even create an array of functions. Knowing that a function can receive any value as an argument, or return any JavaScript value, it's also true that it's possible to pass a function as an argument, or return a function from a function call.

These functions that work on other functions are called Higher Order Functions, and its use provides programmers with great flexibility.

```js
// declare a function for later execution
const print = function(element) {
	console.log(element); 
}

// we might need this one as well
const addAndPrint = function(element) {
	console.log(element + 1); 
} 

// perform any type of action on each element of the array
const myForEach = function(array, action) {
	for (let i = 0; i < array.length; i++){
		action(array[i]); 
	} 
}

// execute some actions for each array element 
// notice how we're passing the function, not calling it (no parenthesis here) 

myForEach([1,2,3], print);
myForEach([1,2,3], addAndPrint);
```

As you can see, the `myForEach` function can perform any action on a given array. You can even declare the function directly on the arguments space:

```js
const numbers = [1, 2, 3, 4, 5];

// let's use our new Higher Order Function to print only even numbers
myForEach(odds, function(number) {
	if(number % 2 === 0) {
		console.log(number);
	}
});
```