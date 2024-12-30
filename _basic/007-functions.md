# JavaScript Functions Practice Questions

## Easy

### 1. Write a function that logs a greeting message to the console without returning anything.
- **Task:** Understand when a function does not need to return a value.
- **Example Function:**
  ```javascript
  function greet(name) {
    //  "Hello, <name>"
  }
  greet('Alice');
  ```

### 2. Write a function that returns the square of a number.
- **Task:** Learn when to return a value and how to use the return statement.
- **Example Function:**
  ```javascript
  function square(num) {
    // some code
  }
  console.log(square(4));
  ```

### 3. Write a function that takes two parameters and prints their sum without returning it.
- **Task:** Understand how parameters are passed and used in functions.
- **Example Function:**
  ```javascript
  function printSum(a, b) {
    // some code
  }
  printSum(3, 5);
  ```

### 4. Write a function that accepts an optional parameter and uses a default value if the parameter is not provided.
- **Task:** Practice using default parameters in functions.
- **Example Function:**
  ```javascript
  function greet(name = 'Guest') {
   //  "Welcome, <Guest>!"
  }
  console.log(greet());
  console.log(greet('Alice'));
  ```

---

## Medium

### 5. Write a function that takes another function as a parameter (callback) and calls it.
- **Task:** Understand how to use functions as first-class citizens in JavaScript.
- **Example Function:**
  ```javascript
  function executeCallback(callback) {
    // some code
  }
  executeCallback(() => console.log('Callback executed!'));
  ```

### 6. Write a function that calculates the factorial of a number recursively.
- **Task:** Learn about recursion and how functions can call themselves.
- **Example Function:**
  ```javascript
  function factorial(n) {
    // some code
  }
  console.log(factorial(5));
  ```

### 7. Write a function that accepts another function and a delay in milliseconds, then executes the function after the delay.
- **Task:** Learn how to use higher-order functions and setTimeout.
- **Example Function:**
  ```javascript
  function delayedExecution(callback, delay) {
    // some code
  }
  delayedExecution(() => console.log('Executed after delay'), 2000);
  ```

### 8. Write a function that accepts an array and a callback function, and returns a new array with the callback applied to each element.
- **Task:** Practice using callbacks to transform arrays.
- **Example Function:**
  ```javascript
  function mapArray(arr, callback) {
    // some code
  }
  console.log(mapArray([1, 2, 3], num => num * 2));
  ```

---

## Hard

### 9. Write a function that memoizes another function to cache its results and improve performance.
- **Task:** Understand closures and how functions can retain state.
- **Example Function:**
  ```javascript
  function memoize(fn) {
    // some code
  }
  const add = (a, b) => a + b;
  const memoizedAdd = memoize(add);
  console.log(memoizedAdd(1, 2));
  console.log(memoizedAdd(1, 2));
  ```

### 10. Write a function that implements a simple event emitter system with `on`, `off`, and `emit` methods.
- **Task:** Learn about custom function management and event handling concepts.
- **Example Function:**
  ```javascript
  function createEmitter() {
   // some code
  }
  const emitter = createEmitter();
  emitter.on('greet', name => console.log(`Hello, ${name}`));
  emitter.emit('greet', 'Alice');
  ```

### 11. Write a function that takes a string and a function as parameters, applies the function to each character in the string, and returns the new string.
- **Task:** Practice applying transformations to strings using callbacks.
- **Example Function:**
  ```javascript
  function transformString(str, transformFn) {
    // some code
  }
  console.log(transformString('abc', char => char.toUpperCase()));
  ```

### 12. Write a function that uses closures to create a counter with increment, decrement, and reset methods.
- **Task:** Understand closures and encapsulation in JavaScript.
- **Example Function:**
  ```javascript
  function createCounter() {
   // some code
  }
  const counter = createCounter();
  console.log(counter.increment());
  console.log(counter.decrement());
  console.log(counter.reset());
  ```

---

These questions are designed to cover fundamental and advanced JavaScript function concepts like parameters, return values, higher-order functions, callbacks, recursion, closures, and encapsulation.
