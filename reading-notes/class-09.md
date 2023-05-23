# Readings: Forms and JS Events

## Why are forms so important in web development?

Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

[HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

## When designing a form, what are some key things to keep in mind when it comes to user experience?

From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

[Your first Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

## List 5 form elements and explain their importance.

- The `<form>` HTML element represents a document section containing interactive controls for submitting information.

- The `<label>` HTML element represents a caption for an item in a user interface.

- The `<input>` HTML element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The `<input>` element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes.

- The `<textarea>` HTML element represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text, for example a comment on a review or feedback form.

- The `<button>` HTML element is an interactive element activated by a user with a mouse, keyboard, finger, voice command, or other assistive technology. Once activated, it then performs an action, such as submitting a form or opening a dialog.

[Active learning: Implementing our form HTML](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

## How would you describe events to a non-technical friend?

Events are things that happen in the system you are programming — the system produces (or "fires") a signal of some kind when an event occurs, and provides a mechanism by which an action can be automatically taken (that is, some code running) when the event occurs. Events are fired inside the browser window, and tend to be attached to a specific item that resides in it. This might be a single element, a set of elements, the HTML document loaded in the current tab, or the entire browser window.

[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

## When using the `addEventListener()` method, what 2 arguments will you need to provide?

- the string "click", to indicate that we want to listen to the click event. Buttons can fire lots of other events, such as "mouseover" when the user moves their mouse over the button, or "keydown" when the user presses a key and the button is focused.

- a function to call when the event happens.

[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

## Describe the event object. Why is the target within the event object useful?

Sometimes, inside an event handler function, you'll see a parameter specified with a name such as `event`, `evt`, or `e`. This is called the event object, and it is automatically passed to event handlers to provide extra features and information.

The target property of the event object is always a reference to the element the event occurred upon. Setting a random background color on the button, not the page is possible with targetting event objects.

[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

## What is the difference between event bubbling and event capturing?

- Event bubbling describes how the browser handles events targeted at nested elements.

- An alternative form of event propagation is event capture. This is like event bubbling but the order is reversed: so instead of the event firing first on the innermost element targeted, and then on successively less nested elements, the event fires first on the least nested element, and then on successively more nested elements, until the target is reached.

[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
