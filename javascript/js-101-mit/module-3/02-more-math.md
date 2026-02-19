
## More Math methods

You now know how to produce a random value between 0 and almost 1, but this is not very practical if you need to generate numbers between 1 and 10. With some ingenuity and maybe using the remainder operator, you could get there, but let's check if the Math object can help us further with this.

```js
let randomToTen = Math.random() * 10;
console.log(randomInteger);
```

This is better, and it will give you some number between 0 and (almost, but never) 10. It's not quite what we wanted, but let's run this code several times to see what the output would be. Results could be something like:

```js
2.774648810228233
8.906213890852904
8.590881224178297
9.171499995731695
0.6783498845993341
3.0714913700441038
5.956765150233371
5.20555415940912
8.975706067767417
0.3139059643802944
```

We need integers. Another Math method could be an answer to this problem. 

```js
let randomInteger = Math.floor(randomToTen);
```

`Math.floor()` will produce the integer number less than a given number. In other words, it will round the number down. You could even combine these two Math operations and get what you need in just one statement.

```js
console.log(Math.floor(Math.random() * 10));
```

It's almost fine, but if you try it you'll notice that this will always give you a number between 0 and 9. We wanted numbers between 1 and 10.

`Math.ceil()` is another method that will produce the integer greater than a given number, that is, round the number up:

```js
console.log(Math.ceil(Math.random() * 10));
```
