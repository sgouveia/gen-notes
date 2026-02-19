## lists of values

Until now we stored single values in variables, so we could access them later. This is great for storing one value, but if what if we need to store and access groups of values of the same nature?

Let's try it with what we already know. Suppose we want to create a catalogue for birdwatchers. How could we do that using only variables?

```js
let bird1 = 'blackbird';
let bird2 = 'bullfinch';
let bird3 = 'bluejay';
let bird4 - 'magpie';
```

Now, if we wanted to add another bird to our catalogue, and print all its names, we would do something like this"

```js
let bird5 = 'greenfinch';
console.log('Our catalogue is composed of: ' bird1 + ', ' + bird2 + ', ' + bird3 + ', ' + bird4 + ', ' + bird5);

// prints: Our cataloghe is composed of: blackbird, bullfinch, bluejay, magpie, greenfinch
```

Besides being cumbersome to access all the birds in our catalogue, we could never be sure to have included all of them, how many they are, or give them an order. 

There's an elegant and powerful solution to these situations, a data structure called an array. In the next lessons you'll add the array to your programmer's toolkit. 

In JavaScript we create arrays by using square brackets `[]`. Inside the square brackets we can insert multiple elements, separating them by a comma. The order of the elements will be the order they have when the array is created.

```js
let catalogue = ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch'];
console.log('Our catalogue is composed of: ' + catalogue);
```

