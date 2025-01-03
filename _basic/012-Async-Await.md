# JavaScript Async/Await Practice Questions

## Easy

### 1. Write an async function `getGreeting()` that returns a greeting message after a 2-second delay.
- **Task:** Use `setTimeout` inside a promise and `await` its resolution.
- **Hint:** Use `Promise` to create the delay.

### 2. Write an async function `fetchName()` that waits for a resolved promise returning the name "John" and logs it to the console.
- **Task:** Create a promise that resolves with a name and use `await` to log it.
- **Hint:** Use `console.log()` after `await`.

---

## Medium

### 3. Create an async function `fetchUserData()` that makes two sequential API calls (simulated with `setTimeout`) to get a user's details and their posts. Log both responses to the console.
- **Task:** Use `await` to ensure the second call waits for the first.
- **Hint:** Use `Promise` to simulate the API calls.

### 4. Write an async function `getWeatherData()` that fetches weather information for multiple cities (e.g., "Mumbai", "Delhi") using `Promise.all` and logs the results.
- **Task:** Use `await` with `Promise.all` to handle multiple promises.
- **Hint:** Return an array of promises.

---

## Hard

### 5. Write an async function `retryOperation()` that attempts to fetch data from an API (simulated) and retries up to 3 times in case of failure before throwing an error.
- **Task:** Use `try...catch` and a loop to implement retries.
- **Hint:** Use `Math.random()` to simulate success/failure.

### 6. Create an async function `processTasks()` that takes an array of tasks (functions returning promises) and executes them in sequence. Log the result of each task after it completes.
- **Task:** Use a `for...of` loop with `await` to handle tasks sequentially.
- **Hint:** Pass the result of each task to the console.

---

These questions are designed to provide hands-on practice with `async`/`await`, covering scenarios from simple asynchronous handling to more complex retry mechanisms and sequential execution.
