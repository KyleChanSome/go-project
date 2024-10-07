Why do all of this? For learning of course!

The Monkey Language supports features: 
integer, booleans, strings, arrays, hashes, prefix-, infix-, and index operators, conditionals, global and local bindings, first-class functions, return statements, closures.
in terminal in monkey folder- 
```
go run main.go
```
From simple outputs to closures! Here's some example code to try:
```
puts("Hello World!")

let newAdder = fn(x) { fn(y) { x + y } };
let addTwo = newAdder(2);
addTwo(3);

```
Expected output: 

```
Hello World!
null

5
```

TBD update this readme for more details on how to run the interpreter and more example codes to run
