## What is the `single responsibility principle` and how does it apply to components?

The Single Responsibility Principle (SRP) states that a component should have only one purpose or task. By following this principle, components become more focused, easier to understand, and more simple to maintain.

## What does it mean to build a ‘static’ version of your application?

To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. 

[React Docs - Thinking in React](https://react.dev/learn/thinking-in-react)

## Once you have a static application, what do you need to add?

To make a static application interactive, you need to add event handlers, data fetching, state management, routing, dynamic rendering, form validation, error handling, and integration with APIs.

## What are the three questions you can ask to determine if something is state?

- Does it change over time?
- Can it be stored?
- Does it affect the behavior or output of the system?

## How can you identify where state needs to live?

- Often, you can put the state directly into their common parent.
- You can also put the state into some component above their common parent.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.

[React Docs - Thinking in React](https://react.dev/learn/thinking-in-react)

## What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

## Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?

Line 2, `return m => m > n;`, in the greaterThan function is creating and returning a new function. This new function accepts a parameter `m` and checks whether `m` is greater than `n`.

## Explain how either `map` or `reduce` operates, with regards to higher-order functions.

`map` transforms each element in a collection independently, while `reduce` combines all the elements into a single value.
