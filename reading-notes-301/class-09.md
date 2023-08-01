[Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

## What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

## What is a pure function and how do we know if something is a pure function?

A pure function always produces the same output for the same input and doesn't have side effects like changing things outside of itself. To know if a function is pure, check if it always gives the same result with the same input and that it doesn't affect anything outside of it.

## What are the benefits of a pure function?

- Predictability
- Testability
- Parallelizable
- Reusability
- Immutability
- Performance Optimization
- Reduced Side Effects

## What is immutability?

The concept that an object or data value cannot be modified after it has been created.

## What is Referential transparency?

Referential transparency is a property of a function where its output is determined by its input values, allowing any call to the function to be replaced with its output without changing the behavior of the program.

[Node JS Tutorial for Beginners #6 - Modules and require](https://www.youtube.com/watch?v=xHLd36QoS4k)

## What is a module?

It's a separate file or group of files that contain related functions and data that you can use in other parts of your program.

## What does the word ‘require’ do?

It's used to import and use modules from other files into the current file.

## How do we bring another module into the file the we are working in?

Use the `require` function or the `import` statement.

## What do we have to do to make a module available?

Export its content using the `module.exports` or `exports` keyword in Node.js
