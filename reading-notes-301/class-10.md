## What is a ‘call’?

- A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

[Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

## How many ‘calls’ can happen at once?

- It is single-threaded. Meaning it can only do one thing at a time.

[Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

## What does LIFO mean?

- *Last In, First Out*

[Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

- When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame. This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.

![image](https://github.com/LChanthabandith/LChanthabandith.github.io/assets/129714958/c350770e-75f3-4cd4-ad5d-040a10a5cfd6)

## What causes a Stack Overflow?

- A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

[Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

## What is a ‘reference error’?

- This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

```
console.log(foo) // Uncaught ReferenceError: foo is not defined
```

## What is a ‘syntax error’?

- This occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

```
JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1
```

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

## What is a ‘range error’?

- Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

```
var foo= []
foo.length = foo.length -1 // Uncaught RangeError: Invalid array length
```

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

## What is a ‘type error’?

- This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

```
var foo = {}
foo.bar // undefined
foo.bar.baz // Uncaught TypeError: Cannot read property 'baz' of undefined
```

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

## What is a breakpoint?

- A breakpoint is like a pause button you place in your code. When your program runs and reaches that point, it stops and lets you examine what's happening before continuing.

## What does the word ‘debugger’ do in your code?

- It is the ability to identify and fix errors within your code.
