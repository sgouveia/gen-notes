## `switch` statement

Whenever you're faced with multiple choices, `else if` is great for a lot of branching possibilities. But when dealing with discrete values (that is, you're looking for a specific value, not an interval), JavaScript offers another tool: the `switch` statement.

The `switch` first evaluates an expression, then tries to match it to the value in one of the case clauses in the switch. If a match is found, it executes de block for that case.

```js
let expression = 'JavaScript';switch (expression) { case 'Python': console.log('This will only print if the value of expression is the string "Python".'); break; case 'JavaScript': console.log('This will only print if the value of the expression is the string "JavaScript".'); break; default: console.log('This will be printed if the value of the expression doesn\'t match the value in any of the case clauses.'); break; }
```

There's also, at the end, a default clause, which is executed if the expression evaluated in the switch statement does not match the value of any of the case clauses.

Also, you might be curious about the purpose of the break keyword at the end of each case. That break is a way of saying that as soon as we find a match we don't want anything else to run inside the switch. In the example above, if we didn't have the break, every string from "JavaScript" onwards, would be printed.