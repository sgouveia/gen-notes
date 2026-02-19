## size of an array

During the string lesson we've seen how we could know the length of a string by accessing the value stored in its `length` property. Arrays also have this property, and we can check its value using dot notation.

```js
let catalogue = ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch'];
console.log('there are ' + catalogue.length + 'birds in our catalogue');
//prints 'there are 5 birds in our catalogue'
```

This means that regardless of its size, the last element of an array will have an index equal to the length of that array subtracted by one (because the first index is 0). This is useful to bear in mind, whenever we want to access elements counting from the end.

```js
console.log('the last bird in our catalogue is ' + catalogue[catalogue.length - 1]);

//prints 'the last bird in our catalogue is greenfinch'
```

You can use this pattern every time you need to access elements from the end of an array, but JavaScript provides a simpler notation to do the same:

```js
console.log(catalogue[-1]); //prints 'greenfinch'
console.log(catalogue[-2]); //prints 'magpie'
// and so on...
```