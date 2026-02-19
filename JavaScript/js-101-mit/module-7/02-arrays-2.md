## Accessing the elements of an array

By accessing the variable in which the array is stored, we get the entire list. If we want to access a specific element of the array we need to use the brackets and the corresponding index.

```js
let catalogue = ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch'];
console.log('the second bird on our catalogue is ' + catalogue[1]);
```

Maybe you noticed something off in the snippet above. We've talked about it before in the strings lesson. In most programming languages, indexes start on 0, not 1. That's why we would use `catalogue[0]` for 'blackbird', and `catalogue[1]` for 'bullfinch'.

Whenever you see this square brackets notation with an integer after a variable name, you'll probably be dealing with an array. But you can also use it to access a character in a string. Like this:

```js
let anotherBird 'crow';
console.log(anotherBird[3]); //prints 'w'
```

Be aware that if you try an index out of the bounds of the array (in ths case 5 or higher) you won't get any kind of error. JavaScript will instead return `undefined`.