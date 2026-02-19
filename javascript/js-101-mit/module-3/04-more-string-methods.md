## More string methods

There's a lot more you can do with string methods. Let's go through some of them.

If you want to know how many characters a specific string has, all you have to do is:

```js
let bigWord = 'supercalifragilisticexpialidocious';
let characters = bigWord.length; // 34
```

What if you want to get a specific character from a given string? Simple, just tell JavaScript the position of the character you're looking for. There are two ways to achieve this:

```js
console.log(bigWord[1]); // outputs 'u'
console.log(bigWord.charAt(1)); // same
```

Were you expecting an `s`?

Actually in JavaScript, as in most programming languages, a sequence of values is numbered beginning from zero. Here, `s` would be 0. This positional number is called an index. It's an important concept in programming and we'll be dealing with it a lot (so get used to it).

Let's look yet at another useful string method:

```js
let person = 'homeowner';
let cuteSound = person.slice(2, 6); // 'meow'
```

With `slice` you use indexes to determine the starting and ending point of the new string you're creating. The first index corresponds to the first character to be included and it ends at - but does not include - the second index (and remember, indexes start at zero).

Finally, you can also use `slice` specifying the starting point, but omitting the second index completely. This will give a new string starting from that index until the end, like so:

```js
let pizza = 'margarita';
let name = pizza.slice(5); // 'rita'
```

