## When should you use an `unordered list` in your HTML document?
The `<ul>` element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless.

[Usage Notes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)


## How do you change the `bullet style` of unordered list items?
The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property.

[Usage Notes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

## When should you use an `ordered list` vs an `unorder list` in your HTML document?
The `<ol>` and `<ul>` elements both represent a list of items. They differ in that, with the '<ol>' element, the order is meaningful. To determine which one to use, try changing the order of the list items; if the meaning is changed, the '<ol>' element should be used, otherwise you can use '<ul>'.

[Usage Notes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

## Describe two ways you can change the numbers on `list items` provided by an `ordered list`?

> `reversed`
This Boolean attribute specifies that the list's items are in reverse order. Items will be numbered from high to low.

> `start`
An integer to start counting from for the list items. Always an Arabic numeral (1, 2, 3, etc.), even when the numbering type is letters or Roman numerals. For example, to start numbering elements from the letter "d" or the Roman numeral "iv," use start="4".

[Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

## Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: "The Box Model"?

In the world of CSS, margin and padding are two characters that play a crucial role in the story of "The Box Model". Margin is like a guardian angel that surrounds a box and protects it from the outside world, while padding is the gentle cushioning that keeps the contents of the box safe and secure. Together, margin and padding form the box model, a system that allows boxes to travel long distances without getting damaged. Margin acts as a barrier that prevents unwanted elements from entering the box, while padding provides a soft, comfortable resting place for the items being transported. In the end, margin and padding are the unsung heroes of the box model, ensuring that boxes and their contents arrive at their destination in one piece.

## List and describe the **four** parts of an HTML elements box as referred to by the `box model`.

- **Content box**: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
- **Padding box**: The padding sits around the content as white space; size it using padding and related properties.
- **Border box**: The border box wraps the content and any padding; size it using border and related properties.
- **Margin box**: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.

[Parts of a box](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

## What `data types` can you store inside of an `Array`?

- Strings
- Numbers
- Objects
- Other arrays

## Is the `people` array a valid JavaScript array?  If so, how can I access the values stored? If not, why?

    ```javascript
    const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 
    'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
    ```
> Yes, the `people` variable is a valid JavaScript array. It is a two-dimensional array, also known as an array of arrays. To access the values stored in the array, you would use the index notation to access the elements of each subarray.

## List **five** shorthand operators for assignment in javascript and describe what they do.

- The **assignment** `(=)` operator is used to assign a value to a variable. The assignment operation evaluates to the assigned value. Chaining the assignment operator is possible in order to assign a single value to multiple variables.
- The **addition assignment** `(+=)` operator performs addition (which is either numeric addition or string concatenation) on the two operands and assigns the result to the left operand.
- The **subtraction assignment** `(-=)` operator performs subtraction on the two operands and assigns the result to the left operand.
- The **multiplication assignment** `(*=)` operator performs multiplication on the two operands and assigns the result to the left operand.
- The **division assignment** `(/=)` operator performs division on the two operands and assigns the result to the left operand.

[Assignment Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)


## Read the code below and evaluate the last `expression` and explain what the result would be and why.

    ```javascript
    let a = 10;
    let b = 'dog';
    let c = false;

    // evaluate this
    (a + c) + b;
    ```
> The result of the expression `(a + c) + b` is "10falsedog", because false is coerced to **0** when used with the **+** operator, and the resulting value is concatenated with the string "dog".

## Describe a real world example of when a conditional statement should be used in a JavaScript program.

Imagine a child being asked for help with a chore by their mother or father. The parent might say "Hey sweetheart! If you help me by going and doing the shopping, I'll give you some extra allowance so you can afford that toy you wanted." In JavaScript, we could represent this like so:

	```let shoppingDone = false;
	   let childsAllowance;

   	   if (shoppingDone === true) {
          childsAllowance = 10;
	   } else {
  	     childsAllowance = 5;
	   }
	   ```

This code as shown always results in the `shoppingDone` variable returning `false`, meaning disappointment for our poor child. It'd be up to us to provide a mechanism for the parent to set the `shoppingDone` variable to `true` if the child did the shopping.

[A Real Example](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

## Give an example of when a `Loop` is useful in JavaScript.

A **loop** is useful in JavaScript when you need to perform a repetitive task based on a certain condition or for a fixed number of times, such as iterating over an array to perform an operation on each element.


## Things I want to know more about

- Use all the different shorthand operators in JavaScript.

- Creating different conditional statements using complex, real world examples.

- Using a loop in JavaScript.