## values and expressions

The strings and numbers we've dealt with in previous lessons are simple values. There's no *work* to be done before using it. The only thing JavaScript did was print it to the console as given.

```js
console.log('string');
console.log(42);
```

The output will be exactly what's inside the parenthesis because what's inside are just values:

```shell
string
42
```

JavaScript provides some arithmetic operators which allow you to create an **expression**:

```js
2 + 9
```

An **expression** always produces a value, in this case, the number 11. JavaScript will evaluate the expression `2 + 9`, produce the value `11`, and just then store it in memory.

We don't use expressions by themselves, but we create statements with them. Remember **statements** from a previous lesson? We defined it as a kind of programming sentence, that ended with a semicolon, and that produced an effect.

This is an important distinction. An **expression** produces a value; like the `2 + 9` produced the value `11`. A **statement** produces an effect; like the `console.log('hello');` which has the effect of the string `hello` being printed to the console.

We can use expressions inside statements, and we'll do it a lot. In the following snippet, JavaScript will always resolve the expression to a value first, and only after that will the statement produce its effect (in this case, the console.log will print the value):

```js
console.log(2 + 9 + 3 + 8);
```

Output:
```shell
22
```
