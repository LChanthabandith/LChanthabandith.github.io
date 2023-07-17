## What is a ‘Controlled Component’?

An input form element whose value is controlled by React in this way is called a *controlled component*.

[React Docs - Forms](https://legacy.reactjs.org/docs/forms.html)

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

If your app needs to give feedback or check answers as the user types, go for immediate updates. If your focus is more on saving resources and you only need the info when the user is done, wait to update until they submit the form.

## How do we target what the user is entering if we have an event handler on an input field?

use `event.target.value` in your event handler function. This gives you the current text the user has entered into that field.

## Why would we use a ternary operator?

A *ternary operator* is a quick and compact way to write an if-else statement. It's when you want to choose between two values based on a condition, especially within a single line of code.

## Rewrite the following statement using a ternary statement:

```
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

- ``` console.log(x === y ? true : false); ```
