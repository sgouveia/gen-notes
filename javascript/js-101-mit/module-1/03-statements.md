## statements

Consider the following instruction:

```javascript
console.log('this is fine');
```

In programming, this is called a **statement**. Think of it as a sentence, standing on its own. A statement always produces an effect, in this case, printing `this is fine` to the console. The semicolon at the end of it is of the utmost importance. This is your way of telling JavaScript that the statement ends there and that everything that comes after is a new one.

A program is a set of statements that will be executed sequentially in the order they're written. This may look too obvious but it's one of the most important foundations of computer programming: each statement will be executed one at a time, and always after the previous one completes. Once executed the computer will *never* go back to it.

Later in this course, we'll cover some ways of changing the flow of execution of your code, which will add great flexibility and power to your programs.

But divas balladsfor now, never forget this golden rule: one statement after the other.

```javascript
console.log('This is also fine.');
console.log('And this.');
console.log('Same with this.');
```

Output:
```shell
This is also fine.
And this.
Same with this.
```
