### 1. What is a closure?
<p>
A closure is a function that has access to its external function by scope, even after the external function has stopped executing. This means that a closure can remember and access variables and arguments of its external function, even after the external function has stopped executing.
</p>

### 2. What are the differences between call, apply, and bind?
<p>call and apply immediately calls a function while bind creates a new function that can be invoked in the future. Arguments with call are passed in one by one, separated with a comma while apply expects an array as its argument.</p>

### 3. What is an event loop?
<p>An event loop is responsible for executing javascript code, collecting and processing events, and executing queued sub-tasks.</p>

### 4. What is currying function?
<p>A currying function is the process of taking a function with multiple arguments and turning it into a sequence of functions each with a single argument.</p>
<p>Curried functions are a great way to improve code reusability and functional composition</p>

### 5. What is prototype in javascript?
<p>Prototypes are the mechanism by which JavaScript objects inherit from another object.</p>

### 6. What is memoization?
<p>Memoization is an optimization technique by storing the result of expensive function calls and returning the cached results when the same inputs occur again.</p>

### 7. What is a higher-order function?
<p>a higher-order function is a function that accepts another function as an argument or returns a function as a return value or both of them.</p>
<p>Map, filter and reduce are some examples of higher-order functions that are already built-in to JavaScript.</p>

### 8. What is event delegation?
<p>Event delegation is a pattern of adding a single event listener to a parent element instead of multiple elements.</p>

### 9. Name some ways to handle asynchronous operation in javascript
<p><li>Callback is a function that is used to notify the calling instance</li></p>
<p><li>Promise is an object representing the eventual completion or failure of an asynchronous operation. A pending promise can either be fulfilled with a value or rejected with a reason.</li></p>
<p><li>Callbacks are attached to the returned promises that make handling of asynchronous code easier and more readable.</li></p>
<p><li>async/await is a new addition to ES2017 which is syntactic sugar on top of promises and make asynchronous code look synchronous code</li></p>

### 10. What is recursion?
<p>Recursion is a technique for iterating over an operation by having a function call itself repeatedly until it arrives at a result.</p>
<p>This is most effective for solving problems like sorting or traversing the nodes of complex or non-linear data structures</p>

### 11. What is a promise?
<p>is an object that may produce a single value sometime in the future with either a resolved value or a reason for not being resolved</p>

### 12. What is strict mode in JS?
<p>it is useful for writing secure JS code. It prevents some bugs from happening and throws more exceptions.</p>

### 13. What is the difference between null and undefined?
<p>null type is an object that is explicitly assigned to a variable.</p>
<p>undefined type is undefined where the variable has been declared but has no assigned value</p>

### 14. Explain the difference between synchronous and asynchronous.
<p>Synchronous is blocking operation while asynchronous is not. Synchronous complete the current code before the next code is executed while asynchronous continue on the next code without completing the current code</p>

### 15. What are the differences between var, let, and const
<p>var is scoped to a function. let and const are block-scoped. Accessible to nearest curly braces (function, if-else, for-loop)</p>
