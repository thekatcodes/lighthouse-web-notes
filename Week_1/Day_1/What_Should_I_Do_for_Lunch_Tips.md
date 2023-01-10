### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}
```
### Number(value) 
* When used as a function, Number(value) converts a string or other value to the Number type. If the value can't be converted, it returns NaN.

```javascript
Number("123"); // returns the number 123
Number("123") === 123; // true
```

### console.assert()
* The console.assert() method writes an error message to the console if the assertion is false. If the assertion is true, nothing happens.

```javascript
console.assert(1 === 1); // => nothing happens because true
console.assert(1 === 1.1); // => prints out "Assertion failed" to the terminal
```