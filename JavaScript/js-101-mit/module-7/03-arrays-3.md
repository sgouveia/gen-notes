## changing the value of a position

We can think of an array as a sequence of variables which can be accessed by their index in that array. If we can access the value in it by using the square brackets notation and its index, we can also replace its value with another one. Just as we would do with a stand-alone variable.

```js
let catalogue = ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch'];
catalogue[3] = 'crow';
console.log('our fourth bird is now ' + catalogue[3]);
//prints: our fourth bird is now crow
```

You should be aware that 