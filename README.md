Why do all of this? For learning of course!

The Monkey Language supports features: 
integer, booleans, strings, arrays, hashes, prefix-, infix-, and index operators, conditionals, global and local bindings, first-class functions, return statements, closures.
in terminal in monkey folder- 
```
go run main.go
```
Some example code to try:
```
//puts built in function that outputs statements and expressions
puts("Hello World!")
// want to test out closures
let newAdder = fn(x) { fn(y) { x + y } };
let addTwo = newAdder(2);
addTwo(3);
//should output 5
```
