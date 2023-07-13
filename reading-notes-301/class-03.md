# Readings: Passing Functions as Props

Reading

## What does .map() return?
We use the `map()` function to take an array of numbers and double their values. We assign the new array returned by `map()` to the variable doubled and log it.

[React Docs - lists and keys](https://legacy.reactjs.org/docs/lists-and-keys.html)

## If I want to loop through an array and display each value in JSX, how do I do that in React?

In React, you can use the map function to loop through an array and display each value in JSX.

## Each list item needs a unique ____.

Key

## What is the purpose of a key?

A “key” is a special string attribute you need to include when creating lists of elements. 

[React Docs - lists and keys](https://legacy.reactjs.org/docs/lists-and-keys.html)

## What is the spread operator?

The spread operator was added to JavaScript in ES6 (ES2015), just like the rest parameters, which have the same syntax: three magic dots ….

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## List 4 things that the spread operator can do.

- Copying an array
  
- Concatenating or combining arrays
  
- Using Math functions
  
- Using an array as arguments

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## Give an example of using the spread operator to combine two arrays.

Using the … spread operator is a convenient way to copy an array or combine arrays, and it can even add new items:

```
const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
```

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## Give an example of using the spread operator to add a new item to an array.

The spread operator can add an item to an another array with a natural, easy-to-understand syntax:

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## Give an example of using the spread operator to combine two objects into one.

The spread syntax is useful for combining the properties and methods on objects into a new object:

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

## In the video, what is the first step that the developer does to pass functions between components?

He defined the function in the parent component.

## In your own words, what does the increment function do?

The increment function increases the value of a variable by a specified amount.

## How can you pass a method from a parent component into a child component?

You can pass a method from a parent component to a child component as a prop.

## How does the child component invoke a method that was passed to it from a parent component?

The child component can use the method passed from the parent component by getting it through the props and calling it as a function.
