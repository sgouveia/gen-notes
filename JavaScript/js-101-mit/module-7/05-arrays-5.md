
## traversing an array

The previous lessons give you pretty much everything you need to know about the structure and use of an array. Now it's time to bring previous knowledge and take your skills to the next level.

If there's the need to access and act (printing, for example) on every element of an array, you'll find yourself in a very repetitive task. A `for loop` is perfect for this kind of problem. You know you want to perform the same task a predetermined number of times. You'll see how `for loops` and `arrays` often walk hand in hand.

Let's go back to our bird catalog.

```js
let catalog = ['blackbird', 'bullfinch', 'bluejay', 'magpie', 'greenfinch'];

console.log('our catalog is comprised of the following birds:')

for (let i = 0; i < catalog.length; i++) {
	console.log(catalog[i]);
}

```

With each iteration we access the element of index i of the array and print it. As the value of i increments with each iteration (until it reaches the length of the array), every element of the array will be printed.