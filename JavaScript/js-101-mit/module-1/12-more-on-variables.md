## more on variables

As you learn you'll see lots of analogies for a variable. They'll ask you to look at variables like labeled boxes, parking spaces, containers, or truckloads. Analogies are helpful but they have limitations and can be harmful when constructing your mental model of important concepts. They may lead to misconceptions that won't let you construct new knowledge on top of it. 

It's okay to think of variables as a memory region in your computer that is given a name, so you can access it later.

Keeping this in mind, let's walk through some scenarios.

#### assigning a new name to a variable

```js
let myAge = 25;
myage = 26;
```

The first statement can be described as two operations:
- declaring a variable called `myAge`; and
- assigning a value (`25`) to it.

Within the second statement, we're assigning a new value to the same variable. It's still an assignment operation, so be sure to keep reading it from right to left (*the value 26 is assigned to the variable myAge*).

The computer memory is now storing the number `29`. Don't expect it to remember which value it had before. Memories don't keep that kind of history, and `25` is forever lost.

#### accessing a variable

Any time after its declaration you can access the variable and use the value stored in it. You can, for instance, print it to the console:

```js
console.log(myAge); // prints 26
```

We're using the name of the variable to pass a value to the console.log. JavaScript will replace the variable name with the value stored in it, in this case, the number 26.

Inside a variable there's **always** a value, never anything else. Variables don't store expressions or other variables, although at times it may look like they are.

```js
let myTwinBrotherAge = myAge;
```

With the knowledge from what happened with the previous example, when we printed `myAge`, try and guess what will JavaScript do.
