## comments

Spaces, new lines, blank lines and tabs are great ways of organizing your code and making your intention clear to the next person who reads your code (most of the time they're yourself a week from now). And as the computer will ignore them, you're free to use them as you prefer.

Sometimes they're not enough though, and you'll feel the need to leave a comment with a brief explanation of what you're trying to achieve with your code. There are two ways of defining a comment.

#### Single line comment
```js
//this line is a comment
console.log('Hello world!');
console.log('This is a new line'); //this is also just a comment
```

The output of the previous block will be as follows:
```shell
Hello world!
This is a new line
```

The machine will ignore both comments.

#### Multi-line comment

If you feel the need for longer and multi-line comments, there's a better way than adding two forward slashes before every line. This is it:
```js
/*
Anything inside this multi-line comment
console.log('Hello');
console.log('World');
will be ignored and won't be executed
*/
`