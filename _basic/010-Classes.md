# JavaScript Classes and Objects Practice Questions

## Easy

### 1. Create a class `Person` with properties `name` and `age`. Add a method `greet()` that returns a greeting message.
- **Task:** Instantiate the class and call the `greet()` method.
- **Hint:** Use the `constructor` to initialize properties.

### 2. Create an object `car` with properties `brand`, `model`, and `year`. Add a method `getCarInfo()` that returns a formatted string of the car details.
- **Task:** Access the properties and method of the object.
- **Hint:** Use object literal syntax.

### 3. Write a class `Rectangle` with properties `length` and `width`. Add a method `calculateArea()` that returns the area of the rectangle.
- **Task:** Create an instance and call the method to calculate the area.
- **Hint:** Use `this.length` and `this.width`.

---

## Medium

### 4. Create a class `Animal` with a method `makeSound()` that logs a generic sound. Extend the class to create `Dog` and `Cat` classes, each overriding `makeSound()`.
- **Task:** Use inheritance and method overriding.
- **Hint:** Use the `extends` keyword and `super()`.

### 5. Write a class `BankAccount` with properties `accountHolder`, `balance`, and a method `deposit(amount)`. Add another method `withdraw(amount)` that prevents overdrawing.
- **Task:** Test deposit and withdraw functionality.
- **Hint:** Use conditions inside `withdraw()` to check balance.

### 6. Create a class `Student` with a static method `compareMarks(student1, student2)` that returns the student with higher marks.
- **Task:** Create two students and compare their marks using the static method.
- **Hint:** Use the `static` keyword.

### 7. Write a script that uses a class `Product` to store product details. Add a method to calculate the total cost given the price and quantity.
- **Task:** Create instances and calculate the total cost for different products.
- **Hint:** Pass parameters to the constructor and use `this` to access them.

### 8. Create a `Shape` class with a method `getArea()`. Extend it to create `Circle` and `Square` classes, each implementing their version of `getArea()`.
- **Task:** Use polymorphism to calculate the area of different shapes.
- **Hint:** Implement specific area calculations in subclasses.

---

## Hard

### 9. Write a class `Order` that tracks the items in an order. Add methods to add items, remove items, and calculate the total price.
- **Task:** Use an array to store items and loop through them for calculations.
- **Hint:** Define each item as an object with `name`, `quantity`, and `price` properties.

### 10. Create a class `Library` to manage a collection of books. Add methods to add a book, remove a book by title, and search for books by author.
- **Task:** Use an array to store book objects and implement search functionality.
- **Hint:** Use array methods like `filter()` and `find()`.

### 11. Design a class `Flight` to manage passenger details. Add methods to add passengers, assign seats, and display passenger lists.
- **Task:** Use nested objects or arrays to handle passenger and seat data.
- **Hint:** Validate seat assignment to avoid duplication.

### 12. Write a class `EventEmitter` to mimic event handling. Add methods `on(event, callback)` to register callbacks and `emit(event)` to trigger them.
- **Task:** Implement a system to manage multiple events and callbacks.
- **Hint:** Use an object to store event names as keys and arrays of callbacks as values.

---

These questions cover various aspects of working with classes and objects in JavaScript, including inheritance, polymorphism, encapsulation, and static methods.
