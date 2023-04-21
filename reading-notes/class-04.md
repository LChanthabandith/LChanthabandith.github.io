# Readings: HTML Links, JS Functions, and Intro to CSS Layout

## To create a basic link, we wrap text or other content inside what element?

A basic link is created by wrapping the text or other content inside an `<a>` element and using the `href` attribute, also known as a **Hypertext Reference**, or **target**, that contains the web address.

[Anatomy of a link](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

## The `href` attribute contains what information?

The `<a>` HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address. Content within each `<a>` should indicate the link's destination. If the `href` attribute is present, pressing the enter key while focused on the <a> element will activate it.

[`<a>`: The Anchor element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#href)

## What are some ways we can ensure links on our pages are accessible to all readers?

- Don't repeat the URL as part of the link text — URLs look ugly, and sound even uglier when a screen reader reads them out letter by letter.

- Don't say "link" or "links to" in the link text — it's just noise. Screen readers tell people there's a link. Visual users will also know there's a link, because links are generally styled in a different color and underlined (this convention generally shouldn't be broken, as users are used to it).

- Keep your link text as short as possible — this is helpful because screen readers need to interpret the entire link text.

- Minimize instances where multiple copies of the same text are linked to different places. This can cause problems for screen reader users, if there's a list of links out of context that are labeled "click here", "click here", "click here".

[Active learning: creating a navigation menu](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)\

## What is meant by "normal flow"?
  
**Normal flow**, the way that webpage elements lay themselves out if you haven't changed their layout. Elements on a webpage lay out in **normal flow** if you haven't applied any CSS to change the way they behave. And, as we began to discover, you can change how elements behave either by adjusting their position in **normal flow** or by removing them from it altogether. Starting with a solid, well-structured document that's readable in normal flow is the best way to begin any webpage. It ensures that your content is readable even if the user's using a very limited browser or a device such as a screen reader that reads out the content of the page. In addition, since **normal flow** is designed to make a readable document, by starting in this way you're working with the document rather than struggling against it as you make changes to the layout.
  
[Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

## What are a few differences between `block-level` and `inline` elements?
  
> ### There are a couple of key differences between block-level elements and inline elements:

  > #### Content model
  - Generally, **_block-level elements_** may contain inline elements and (sometimes) other block-level elements. Inherent in this structural distinction is the idea that block elements create "larger" structures than inline elements.

  > #### Default formatting
  - By default, block-level elements begin on new lines, but **_inline elements_** can start anywhere in a line.

[Block-level vs. inline](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)

## _______ positioning is the default for every html element.
  
**Static** positioning is the default that every element gets. It just means "put the element into its normal position in the document flow — nothing special to see here."

[Static positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)
  
## Name a few advantages to using absolute positioning on an element.
  
- Precisely control the position of elements on a webpage.
  
- Allows elements to be positioned independently of their parent elements.

## What is a key difference between fixed positioning and absolute positioning?

With **absolute positioning**, you can place any page element exactly where you want it. In contrast, **fixed positioning** is placed to the viewport, the browser. **Fixed positioning** will stay in place when the page is scrolled.

## Describe the difference between a function declaration and a function invocation.

The difference between a **function declaration** and a **function invocation** is that a **declaration** _defines the function_, whereas an **invocation** _executes_ it.
  

## What is the difference between a parameter and an argument?

A **parameter** is a variable defined in the function's definition, while an **argument** is the value passed to a function when it is called.

## Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
  
Two benefits I have read about _pair programming_ are the ablilities to retain greater efficiency and having engaged collaboration. When working alone on code, I could be limiting myself on maximum efficiency. Having a fellow programmer with me will allow for better code efficiently, research code-related issues more swiftly, and retain knowledge from each others way of coding. In addition to the benefits regarding _pair programming_, **engaged collaboration** will help when my mind is steering off topic. For instance, there will be times that I may be working on a lengthly amount of coding and I may be distracted from completing the assignment from things such as social media. Having a fellow programmer will help keep me on task and become less likely to procrastinate. I beleive these two benefits correlate with each other as beneficial factors of _pair programming_ for myself. 
  
## Things I want to know more about
  
- Learning the disadvantages, if any, on absolute positioning.
  
- Understanding the varies types of functions that can be used.
  
- Try a pair programming exercise.
