## Math Methods

With the operators and data types you've seen so far you can do a lot. With the basic arithmetic operators and the possibility of concatenation, you can go through some more complex calculations, from simple powers to some basic trigonometry. But to start from zero every time you need to do some more complicated math would be cumbersome. JavaScript has some built-in functionalities through what we call methods, which will produce values you can use to create more interesting programs.

Let's start with one of the most useful ones: obtaining a random number. A lot of times you'll need some random value in your program, especially if you're creating a game. You would find it's really hard to create a random number from nothing if you were to do it yourself.

With JavaScript you just have to:

```js
let someRandomNumber = Math.random();
console.log(someRandomNumber); // outputs: ??
```

The `Math.random()` expression will produce a random decimal value between 0 (inclusive) and 1 (exclusive).