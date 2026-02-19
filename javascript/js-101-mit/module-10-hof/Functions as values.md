Unlike some other languages, JavaScript allows us to deal with functions as values. This means you can store a function inside a variable just as you would do with any other data type like strings or numbers. After that it's possible to call the function throught the variable name.

Usually this is done without assigning a name to the function like we did before.


```js
let add = function(n1, n2) {
	return n1 + n2;
}

let result = add(3, 7);

add = 42;

result = add(2, 6); // error: the variable add does not contain a function anymore and as such can't be invoked
```

When storing functions in variables, it's essential to be mindful of variable reassignment and its implications. While this flexibility offers advantages in terms of code organization and readability, it can also lead to unexpected behavior if not used carefully.

One way of preventing such implications is to use the keyword `const` when assigning functions to a variable.
