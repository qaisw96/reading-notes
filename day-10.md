# Call stack
mechanism for an interpreter (like the JavaScript interpreter in a web browser)
to keep track of its place in a script that calls multiple functions — what function is currently being run 
and what functions are called from within that function

## example :
```
function greeting() {
   // [1] Some code here
   sayHi();
   // [2] Some code here
}
function sayHi() {
   return "Hi!";
}

// Invoke the `greeting` function
greeting();

// [3] Some code here

```

## How that does

 ### first :
 ``Call stack list: ``
 - greeting

### second :
```Call stack list:```
- sayHi
- greeting

### third :
```Call stack list:```
- greeting

### last :
```Call stack list:```
-EMPTY
