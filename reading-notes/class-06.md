# Readings: Problem Domain, Objects, and the DOM

[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

## How would you describe an object to a non-technical friend you grew up with?

A JavaScript **object** is like a container that can hold different types of information, labeled with names, or keys, for easy identification and retrieval.

## What are some advantages to creating object literals?

- It provides a shorter syntax for creating/initializing properties from variables (Property Shorthand).

- It provides a shorter syntax for defining function methods.

- It enables the ability to have computed property names in an object’s literal definition.

[Advantage of Object Literal](https://dotnettutorials.net/lesson/javascript-object-using-object-literal/)

## How do objects differ from arrays?

**Objects and arrays** are both useful for storing and manipulating data in JavaScript, but they have different structures, ways of accessing and manipulating elements, and use cases.

## Give an example for when you would need to use bracket notation to access an object's property instead of dot notation.

Bracket notation provides an alternative way to access object properties. Instead of using dot notation like this:

```
person.age;
person.name.first;
```

You can instead use brackets:

```
person["age"];
person["name"]["first"];
```
[Bracket Notation](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

## Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

```js
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

 `this` refers to the `dog` object. The advantage of using `this` is that it allows methods to access and use the properties of the current object, regardless of what the object is named.

## What is the DOM?

The **Document Object Model** _(DOM)_ is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

[Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

## Briefly describe the relationship between the DOM and JavaScript.

The **DOM** is not a programming language, but without it, the **JavaScript** language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the **DOM** and a scripting language like **JavaScript**.

[Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
