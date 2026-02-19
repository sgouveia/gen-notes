## String methods

In the same way you've had built-in functionality to work with numbers through `Math`, JavaScript also provides some actions you can use with strings.

In this case, you won't use them through the `Math` word, but directly on the string value. Let's take a look at some of them.

```js
let mrKeating = 'Carpe diem. Seize the day, boys.';
let shouting = mrKeating.toUpperCase(); // we're creating a copy of mrKeating string with all characters in upper case, but we are not changing the original!
let whispering = mrKeating.toLowerCase(); // same, for lower case. Original remains untouched
```

This is useful when dealing with user input, where you want to ignore case sensitivity. Also when doing so, it's sometimes useful to ignore whitespace from both ends of a string.

There's a method for this:

```js
let carelessInput = '                        Good evening, Clarice.     ';
let trimmedInput = carelessInput.trim(); // this will also create a new string with all the unnecessary spaces removed, and assign it to the trimmedInput variable. The original? Not touched.
```
