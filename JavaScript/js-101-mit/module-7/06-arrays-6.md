
## Some array methods

During the strings section we went over some methods, or built-in functionalities, which allowed us to perform operations on strings. Arrays also have these built-in funcionalities, making it easy to carry out some common actions when dealing with arrays.

```js
let catalog = ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch'];

catalog.pop(); // removes the last element of the array
console.log(catalog); // prints: ['blackbird', 'bullfinch', 'bluejay', 'magpie']

```

By doing this operation you modify the original array, removing the last element. The `pop` method also returns the value of that last element before removing it. So it's possible to do something like:

```js
let catalog = ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch'];

let extinctBird = catalog.pop(); // removes the last element of the array
console.log(extinctBird); //pribts: greenfinch

console.log(catalog); // prints: ['blackbird', 'bullfinch', 'bluejay', 'magpie']

```

If you need to add an element to the original array, there's a method `push` for it:

```js
let catalog = ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch'];

catalog.push('kestrel');

console.log(catalog); // // prints: ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch', 'kestrel']


```