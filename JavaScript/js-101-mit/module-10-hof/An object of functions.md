Storing functions in variables doesn't add much value by itself. But if we can treat functions as values we can also store them in arrays or as properties of an object.

This is especially useful if we want to group functions that are similar in their purpose.

```js
const calculator = {
	add: function(n1, n2) {
			return n1 + n2;
		},
	subtract:function(n1, n2) {
			return n1 - n2;
		},
	multiply: function(n1, n2) {
			return n1 * n2;
		},
	divide: function(n1, n2) {
			return n1 / n2;
		}
}
```

By logically grouping all calculator related functions, we get more readibility, and your code is easier to mantain and understand. After the creation of this object, its use is very expressive.

```js
let sum = calculator.add(9,1);
let product = calculator.multiply(10, 6);
```