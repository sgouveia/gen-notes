## whitespace

We've mentioned the semicolon marks the end of a statement in JavaScript, and how important it is we always use it. You're free to use (or not use) spaces, tabs, new lines, and blank lines, through your code. They won't have any effect on the program execution, but they're really useful to make your code more readable to you and everyone else who'll look at it. But the computer will ignore them, and check for semicolons to know when a statement ends and another begins.

Having this in mind know that all code blocks below will work, but you'll find that some of them are more readable (and understandable by a human) than others. The following output will be printed by both the code blocks that follow it:

```bash
I really hate this damn machine
I wish that they would sell it.
It never does quite what I want
But only what I tell it.
A PROGRAMMERS LAMENT, author unknown
```

A working but chaotic piece of code. Don't do this:
```javascript
console.log('I really hate this damn machine');console.log('I wish that they will sell it.');                         console.log('It never does quite what I want');



console.log      ('But only what I tell it.'); console.log('A PROGRAMMERS LAMENT, author unknown');
```

A working and organized piece of code. This is the way to go.
```js
console.log('I really hate this damn machine');
console.log('I wish that they will sell it.');                         console.log('It never does quite what I want');
console.log('But only what I tell it.');

console.log('A PROGRAMMERS LAMENT, author unknown');
`