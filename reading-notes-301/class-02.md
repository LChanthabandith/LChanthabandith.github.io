# Readings: State and Props

## Based off the diagram, what happens first, the `render` or the `componentDidMount`?
`Render` will happen first because `componentDidMount` is invoked immediately after a component is mounted.

## What is the very first thing to happen in the lifecycle of React?
The very first thing that happens is the creation of the component, which occurs when it is rendered for the first time.

[React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

## Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`.
constructor, render, componentDidMount, React Updates, componentWillUnmount

[React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

## What does `componentDidMount` do?
`componentDidMount` is a function in React that runs after the component is first added to the web page. This is usually where you'd set up things like data fetching or subscriptions, because by this point you know the component is properly set up and visible to the user.

## What types of things can you pass in the props?
In React, you can pass various types of data in props, including strings, numbers, booleans, objects, arrays, functions, and even other React components.

## What is the big difference between props and state?
Props in React are like parameters passed to a function. They come from outside the component and the component uses them but doesn't change them. State has data kept and managed within the component, and changes in state can influence what the component displays.

## When do we re-render our application?
In React, your application re-renders when there are changes to state or props, or when you call a method like `forceUpdate()`.


## What are some examples of things that we could store in state?
State in React can store data that may change or is interactive, like user input, API data, UI state (like open/closed modal), or form control values.

[React State Vs Props](https://youtu.be/IYvD9oBCuJI)
