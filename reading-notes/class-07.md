# Readings: Object-Oriented Programming, HTML Tables

## Explain why we need domain modeling.

A **domain model** that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

## Why should tables not be used for page layouts?

- Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screen readers' output will be confusing to their users.

- Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.

- Tables are not automatically responsive: When you use proper layout containers (such as `<header>`, `<section>`, `<article>`, or `<div>`), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

 [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
  
## List and describe 3 different semantic HTML elements used in an HTML `<table>`.

- The `<thead>` HTML element defines a set of rows defining the head of the columns of the table.

[`<thead>`: The Table Head element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead)

- The `<tbody>` HTML element encapsulates a set of table rows (`<tr>` elements), indicating that they comprise the body of the table (`<table>`).

[`<tbody>`: The Table Body element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody)

- The `<tfoot>` HTML element defines a set of rows summarizing the columns of the table.

[`<tfoot>`: The Table Foot element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot)
  

## What is a constructor and what are some advantages to using it?

A **constructor** is just a function called using the new keyword. **Constructors** are an important feature of object-oriented programming that can help ensure that objects are properly initialized and used correctly, while also enabling encapsulation and flexibility in object creation.

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

## How does the term `this` differ when used in an object literal versus when used in a constructor?

When you only have to create a single object literal, it's not so useful. But if you create more than one, `this` enables you to use the same method definition for every object you create.

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

## Explain prototypes and inheritance via an analogy from your previous work experience.
   - *NOTE: This is a very common front end developer interview question*

Prototypes and inheritance are like using existing templates or structures as a starting point to create new objects or structures. Prototypes are like existing recipes that can be modified to create new dishes, while inheritance is adding on top of existing templates to create new, more specialized templates, like creating a Thai restaurant based on an existing Thai restaurant.

## Things I want to know more about

- Using constructors in JavaScript.

- Learning more semantic HTML elements.

- More information on Prototypes and Inheritance.
