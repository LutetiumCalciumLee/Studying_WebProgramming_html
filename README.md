# Chapter 7. JavaScript Core Objects and Arrays


### Object Concepts

- In JavaScript, an object is a collection of properties (data) and methods (functions).
- Objects represent real-world entities (e.g., a car, a person, a bank account) with unique attributes and behaviors.
- You can create objects using object literals or the `new Object()` constructor.
- Properties are accessed and modified using dot notation (e.g., `object.property`).

---

### Types of JavaScript Objects

- **Core Objects:**  
  Built-in objects available in any JavaScript environment, such as `Array`, `Date`, `String`, and `Math`.
- **HTML DOM Objects:**  
  Represent HTML elements in the document, allowing control over content and appearance.
- **Browser Objects:**  
  Provided by the browser for controlling browser features (e.g., `window`, `navigator`, `location`).

---

### Working with Core Objects

- **Date Object:**  
  Used to handle date and time information. Create with `new Date()`, and access components like year, month, day, hour, minute, and second using methods such as `getFullYear()`, `getMonth()`, and `getDate()`.

- **String Object:**  
  Represents and manipulates text. Strings are immutable. Common properties and methods include `length`, `charAt()`, `concat()`, `indexOf()`, `slice()`, `substr()`, `toUpperCase()`, `replace()`, `trim()`, and `split()`.

- **Math Object:**  
  Provides mathematical constants and functions. Methods include `Math.sqrt()`, `Math.random()`, `Math.floor()`, and others for calculations and generating random numbers.

---

### Arrays in JavaScript

- Arrays are used to store multiple values in a single variable.
- You can create arrays using array literals (`[]`) or the `new Array()` constructor.
- Arrays can contain elements of any type, and their size is dynamic—elements can be added or changed at any time.
- Access elements using zero-based indexing (e.g., `array`).
- The `length` property returns the number of elements in the array.
- Arrays have built-in methods such as `concat()`, `join()`, `reverse()`, `slice()`, `sort()`, and `toString()` for manipulation and processing.

---

### Creating and Using Custom Objects

- JavaScript allows you to define your own object types using either the `new Object()` syntax or object literals.
- You can add properties and methods to these objects to model real-world entities or application-specific data structures.
