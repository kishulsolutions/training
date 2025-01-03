# JavaScript Callbacks and Promises Practice Questions

## Easy

### 1. Write a function `fetchData(callback)` that simulates fetching data after 2 seconds and calls the provided callback function with the data.
- **Task:** Use `setTimeout()` to simulate a delay.
- **Hint:** Pass a simple string as data to the callback.

### 2. Create a function `greetUser(name, callback)` where the callback logs a greeting message with the user's name.
- **Task:** Pass a function as the second argument.
- **Hint:** Use string interpolation to form the greeting.

### 3. Write a script that uses a callback to perform a basic arithmetic operation (add, subtract, multiply, or divide) on two numbers.
- **Task:** Define a function `calculate(a, b, operation)` that takes a callback as the `operation` parameter.
- **Hint:** Pass different functions for each operation.

---

## Medium

### 4. Write a function `readFileAsync(filename, callback)` that simulates reading a file after 3 seconds and then calls the callback with the file content.
- **Task:** Simulate file reading with `setTimeout()` and return a mock file content.
- **Hint:** Pass the filename to the callback.

### 5. Create a function `fetchUserDetails()` that returns a promise. Resolve it after 2 seconds with a user object `{ name: 'John', age: 25 }`.
- **Task:** Use `setTimeout()` to delay the promise resolution.
- **Hint:** Use `new Promise((resolve, reject) => {...})`.

### 6. Write a function `getWeather(city)` that returns a promise. Resolve the promise with a weather description if the city is "Mumbai" and reject it for other cities.
- **Task:** Handle both resolve and reject cases.
- **Hint:** Use `.then()` and `.catch()` to handle the promise.

### 7. Create a chain of promises that simulates making three API calls in sequence. Each promise should resolve with a message indicating the API number.
- **Task:** Chain three `.then()` calls.
- **Hint:** Use `Promise.resolve()` for simplicity.

### 8. Implement a script that uses `Promise.all()` to wait for multiple asynchronous operations (e.g., fetching data from three different endpoints).
- **Task:** Simulate each fetch with a delayed promise.
- **Hint:** Return an array of results when all promises resolve.

---

## Hard

### 9. Write a function `fetchDataWithRetry(url, retries)` that fetches data from a simulated API. If the fetch fails, retry up to `retries` times before rejecting the promise.
- **Task:** Simulate a fetch with random success/failure using `Math.random()`.
- **Hint:** Use recursion to handle retries.

### 10. Implement a script to fetch user details using a callback, but convert the same function to return a promise instead.
- **Task:** Refactor the callback-based function to use a promise.
- **Hint:** Return a promise that resolves with the user details.

### 11. Create a function `executeTasks(tasks)` where `tasks` is an array of functions returning promises. Execute them in sequence, ensuring each task waits for the previous one to complete.
- **Task:** Use `reduce()` to chain promises dynamically.
- **Hint:** Pass the result of each task to the next in the chain.

### 12. Write a script to simulate an API that fetches user data. Use both callbacks and promises in separate implementations to handle the response and errors.
- **Task:** Compare the readability of callbacks vs. promises.
- **Hint:** Simulate errors using `Math.random()` and handle them appropriately.

---

These questions will help you explore callbacks and promises in JavaScript, covering async handling, chaining, error handling, and practical use cases.
