## anatomy of a variable

Consider the code snippet below and the dissection of each part:

```js
let myAge = 20 + 5;
```

#### let

JavaScript keyword used to declare a variable. It must be used *before* the variable's name, and only when declaring it. To declare a variable is to state that from that point on the word `myAge` will now be a variable that will store a value. Later on, when referring to the variable to check its value, or change it, you won't be using the keyword `let` any more.

#### myAge

The variable's name, which is yours to decide. Experimented programmers will tell you this is the single most difficult task in the job. But besides finding the perfect word, or words, that properly express what is being stored, there are a few rules you must follow, and some conventions you should respect.

A variable's name cannot be a JavaScript keyword. Some words, like `let` and others you will learn further on, are reserved by the programming language itself and not to be used as variable names.

You can use letters (uppercase or lowercase), numbers, and most special characters when naming a variable, but you must start with a letter, dollar sign (`$`), or underscore (`__`). You also can't use spaces anywhere, but it's not unusual to see a name comprised of more than one word (like our `myAge`);

Most programming languages define a convention on how to use more than one word to form a variable name, and JavaScript uses camel case: you write phrases such that each word in the middle of the phrase begins with a capital letter, but not the first (e.g. camelCaseEveryThingFromNowOn).

### =

This is the assignment operator. It assigns the value to the right of it to the variable to its left. In the case above, we don't have a value, we have an expression (`20 + 5`). So JavaScript will first reduce it to a value (`25`), and only then will the number be stored in the `myAge` variable. It's helpful to read assignment operations such as these from right to left (the value is assigned to the variable).
