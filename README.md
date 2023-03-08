# async_function_javascript


A JavaScript promise is an object representing the eventual completion or failure of an asynchronous operation and its resulting value. In other words, it is a way to handle asynchronous operations in JavaScript.

Promises have three states:
    Pending: The initial state of a promise, before it is resolved or rejected.
    Fulfilled: The state of a promise when it is successfully resolved.
    Rejected: The state of a promise when it fails to be resolved.
A promise is created using the Promise constructor, which takes a function as its argument. This function takes two arguments, resolve and reject, which are functions that are called when the promise is fulfilled or rejected, respectively.

Imagine you're ordering food from a restaurant. You place your order, but it's going to take some time to prepare and be delivered to you. While you're waiting, you can do other things, like read a book or check your email. When your food is ready, the restaurant will fulfill your order by delivering the food to you. However, there's a chance that your order might not be fulfilled, like if the restaurant is out of a certain ingredient. In this case, the restaurant will reject your order and give you an explanation why.

In this scenario, the order you placed is like a JavaScript promise. It represents an action that is going to be completed at some point in the future. The restaurant is like the code that will fulfill or reject the promise, depending on whether the order can be completed or not. And while you're waiting for your food, you can continue doing other things, just like you can continue running other code while waiting for a promise to be fulfilled.


This is an example of a JavaScript function that returns a Promise.

The addNumbers function takes in two parameters num1 and num2, checks if they are both numbers using typeof operator, and returns a Promise that resolves with the sum of the two numbers or rejects with an Error object if either of the parameters is not a number.

The addNumbers function is then called with arguments 5 and 7 and the returned Promise is handled using .then() and .catch() methods.

If the Promise is resolved, the .then() method is called with the sum value, which is then used to set the innerHTML of an element with id 'root' to display the result.

If the Promise is rejected, the .catch() method is called with an error object, which is then logged to the console using console.error().
