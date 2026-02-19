## arithmetic operators

JavaScript provides not only the plus operator for adding but all the four basic arithmetic operators you already know. These operators always take two numeric values and produce a new one.

They are represented by
- `+` for adding,
- `-` for subtracting,
- `*` for multiplying, and
- `/` for dividing.

When in need to perform one of these, all you have to do is:

```js
12 + 10;
8 - 3;
2 * 4;
27 / 9;
```

Be aware that the order of the operations applies:

```js
2 + 5 * 10;
```

This expression produces the value 52: multiplication has precedence over addition. If you need to add 2 and 5 before multiplying its result by 10 you should use parenthesis:

```js
(2 + 5) * 10;
```
