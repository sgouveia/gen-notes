
## Special Characters

Quotes and the back tick mark the beginning and end of a string, which means that everything between them will be made a string value by JavaScript. In fact almost anything. It would be hard to use a double quote as a character if we're using it to create a string. Or to use a single quote as an apostrophe.

To make this possible we use a backlash `\` inside the string, indicating that the character after it has a special meaning. This is called escaping the character.

```js
"This is a \"special\" sign" //outputs" This is a "special" sign
'I\'m sure you can\'t write proper English without escape characters'
// outputs: I'm sure you can't write proper English without escape characters
```

Another use for escape characters is to create new lines or tabs.

```js
"This line is not the same\nAs this"
// output:
// This line is not the same
// As this

"A list of items:\n\t-item1\n\t-item2"
//output:
//A list of items:
//	 -item1
//	 -item2
```