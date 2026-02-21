## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
.getElementById returns a single element by its ID, getElementsByClassName returns a live HTMLCollection of elements by class, while querySelector returns the first matching element, and querySelectorAll returns all matching elements as a NodeList.


### 2. How do you create and insert a new element into the DOM?
Use document.createElement('div') to create a new element, then container.appendChild(card) to insert it into the DOM.


### 3. What is Event Bubbling? And how does it work?
Event bubbling is the process where an event propagates from the target element up to the root of the DOM. It allows parent elements to catch events from their children.


### 4. What is Event Delegation in JavaScript? Why is it useful?
Event delegation is handling events at a higher level in the DOM, allowing you to avoid adding event listeners to many individual elements. It's useful for dynamic content and optimizing performance.


### 5. What is the difference between preventDefault() and stopPropagation() methods?
preventDefault() prevents the default action of an event (like a form submission), while stopPropagation() prevents the event from bubbling up or capturing down the DOM.
