## the `console.log`

A computer program is usually composed of an input from the user (data provided), some computation on that data, and an output (new data resulting from the said computation). A calculator does something of the kind. When you ask it to add two numbers, like `3 + 5` your input is the numbers `3` and `5`, but also the operation you need (the `+`). The calculator will perform (compute) the actual sum, produce the number `8`, and it will show it to you. `8` is the output of the operation. But a calculator is programmed to always show you the output on its screen. Not a computer. Every time you want to see an output, you must ask the computer to do it.

To ask for an output to be visible is very useful. You may want to test if the program is doing what you expect it to. You may want to inform the final user of what to do next. You may want to log what's happening during the program execution.

The medium where the output is sent may vary. Most of the time it will be your screen. In the early times of computer programming, it was a piece of paper (this was so common, that we still say we're *printing* an output, even if we're just showing it on the screen). Sometimes it's a file where we register some outputs for future reference. Sometimes it's even a distant computer on the internet.

During this tutorial, your outputs will be shown on a console, a special pane on your screen used solely for the purpose of showing them.

In JavaScript *printing* an output, or *logging it to the console* is done as follows:

```javascript
console.log('Hello World!');
```

This would show the words `Hello World!` in the console. It's one of the most useful tools when programming because it will allow you to check if what you want to happen and what in fact is happening is the same. 

Note: JavaScript, like most programming languages, is case-sensitive. This means it will process differently the words `console` and `Console`.

##### Which of the following will print 'Welcome to our world!'?

1
```js
Console.log('Welcome to our world!');
```
2
