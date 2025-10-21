1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
Ans:
The difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll are:
getElementById is fastest but works only with IDs.
querySelector and querySelectorAll are more flexible accept full CSS selectors.
getElementsByClassName returns a live collection that updates automatically when the DOM changes.
2. How do you **create and insert a new element into the DOM**?
Ans:
To create a new element use document.createElement() and insert it using methods like append(),appendChild(),prepend() or insertBefore()
3. What is **Event Bubbling** and how does it work?
Ans:
Event Bubbling is a process in the DOM where an event starts from the innermost target element and then bubbles up to its parent elements.
It works by triggering an event on the target element first then passing it upward through its parent elements to the top of the DOM hierarchy.
4. What is **Event Delegation** in JavaScript? Why is it useful?
Ans:
Event Delegation is a technique where you attach a single event listener to a parent element which listens for events on its child elements via event bubbling.
It is useful because it improves performance.It handles dynamic elements created later.It simplifies code maintenance.
5. What is the difference between **preventDefault() and stopPropagation()** methods?
Ans:
The difference between preventDefault() and stopPropagation() are:
preventDefault() is prevents the default browser action and stopPropagation() is stop the event from bubbling up.

