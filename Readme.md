# Assignment Answers

---

## Question 01

**What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?**

Answer:  
getElementById is used to select a single element by its unique ID, while getElementsByClassName selects all elements that share a specific class and returns a live HTMLCollection. On the other hand, querySelector and querySelectorAll allow selection using any CSS selector, with querySelector returning the first matching element and querySelectorAll returning all matches as a static NodeList. Overall, getElementById is best for unique elements, getElementsByClassName for multiple elements of the same class, and querySelector / querySelectorAll for more flexible selections.

---

## Question 02

**How do you create and insert a new element into the DOM?**

Answer:  
To create and insert a new element into the DOM, you first use document.createElement() to create the element and then set its content or attributes if needed. After that, you select the parent element where it should be added and use methods like appendChild(), prepend(), or insertBefore() to insert the new element into the DOM. This allows you to dynamically add content or structure to a webpage using JavaScript.

---

## Question 03

**What is Event Bubbling and how does it work?**

Answer:  
Event Bubbling is a mechanism in JavaScript where an event triggered on a child element propagates upward through its parent elements in the DOM hierarchy. When an event occurs, it first executes on the target element and then bubbles up to its ancestors unless explicitly stopped using methods like event.stopPropagation(). This allows multiple elements in the DOM to listen for the same event and respond accordingly.

---

## Question 04

**What is Event Delegation in JavaScript? Why is it useful?**

Answer:  
Event Delegation in JavaScript is a technique where a single event listener is added to a parent element to handle events on its child elements. Instead of attaching separate listeners to each child, the parent captures events bubbling up from its children and determines which element triggered the event. This approach is useful because it reduces memory usage, simplifies code, and works well for dynamically added elements.

---

## Question 05

**What is the difference between preventDefault() and stopPropagation() methods?**

Answer:  
The preventDefault() method in JavaScript is used to stop the browser’s default action for an event, such as preventing a form submission or a link from navigating. On the other hand, stopPropagation() prevents the event from bubbling or capturing further in the DOM hierarchy, stopping parent or ancestor elements from receiving the same event. While preventDefault() affects the default browser behavior, stopPropagation() controls how the event flows through the DOM.
