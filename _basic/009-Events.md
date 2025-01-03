# JavaScript Events Practice Questions

## Easy

### 1. Write a script to display an alert when a button is clicked.
- **Task:** Use the `onclick` event or `addEventListener()`.
- **Hint:** Create a button and attach the alert to its click event.

### 2. Write a script to change the text of a heading when the mouse hovers over it.
- **Task:** Use `addEventListener('mouseover', ...)`.
- **Hint:** Update the `innerText` or `textContent` of the heading.

### 3. Write a script to disable a button after it is clicked.
- **Task:** Use the `click` event and set the button’s `disabled` property to `true`.
- **Hint:** Use `addEventListener('click', ...)` and `this.disabled`.

---

## Medium

### 4. Write a script to log the value of an input field to the console when the user types in it.
- **Task:** Use `addEventListener('input', ...)`.
- **Hint:** Use `.value` to fetch the input's content.

### 5. Write a script to change the background color of a `<div>` by selecting a color from an `<input type="color">`.
- **Task:** Use `addEventListener('input', ...)`.
- **Hint:** Use `.style.backgroundColor` and `.value`.

### 6. Write a script to stop the default action of a link and display a message instead.
- **Task:** Use `addEventListener('click', ...)` and `event.preventDefault()`.
- **Hint:** Select the `<a>` tag and bind the event.

### 7. Write a script to count the number of times a button is clicked and display the count in a `<span>`.
- **Task:** Use a variable to track clicks and update the span content.
- **Hint:** Use `addEventListener('click', ...)` to increment the count.

### 8. Write a script to trigger an alert when the user presses the "Enter" key inside an input field.
- **Task:** Use `addEventListener('keydown', ...)`.
- **Hint:** Check if `event.key === 'Enter'`.

---

## Hard

### 9. Write a script to implement drag-and-drop functionality for a `<div>`.
- **Task:** Use `dragstart`, `dragover`, and `drop` events.
- **Hint:** Enable the draggable attribute and use `event.preventDefault()` as needed.

### 10. Write a script to create a simple image carousel that changes images automatically every 3 seconds and also on button clicks.
- **Task:** Use `setInterval()` for auto-switching and `addEventListener()` for button controls.
- **Hint:** Use an array of image URLs and dynamically update the `src` attribute of an `<img>` element.

---

These questions will help you practice event handling in JavaScript, covering basic interactions to complex functionality.
