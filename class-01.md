## How does HTTP sends data between computers?
**HTTP, _Hypertext Transfer Protocol_**, is an application protocol that defines a language for clients and servers to speak to each other. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client. This message, and all other data sent between the client and the server, is sent across your internet connection using _TCP/ IP_. [How The Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

## Describe how HTML, CSS, and JS files are “parsed” in the browser.
**HTML**  is the code that you use to structure your web content and give it meaning and purpose. [Getting Started with the Web.](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

**CSS**, _Cascading Style Sheets_, is the code that you use to style your website. [Getting Started with the Web.](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

**JS**, _JavaScript_, is the programming language that you use to add interactive features to your website. [Getting Started with the Web.](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

## How can you find images to add to a Website?
All images found through the web can be saved to an _images folder_. Images folder: This folder will contain all the images that you use on your site. Create a folder called images, inside your test-site folder. [Images](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

# How do you create a String vs a Number in JavaScript?
*String:* To signify that the value is a string, enclose it in single or double quote marks. _Example: let myVariable = 'Bob'_ [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

*Numbers:* Numbers don't have quotes around them. _Example: let myVariable = 10;_ [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

# What is a Variable and why are they important in JavaScript?
*Variables* are containers that store values. You start by declaring a variable with the _let_ keyword, followed by the _name_ you give to the variable. [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

# What is an HTML attribute?
Attributes contain extra information about the element that won't appear in the content.
An attribute should have:
- A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)

- The attribute name, followed by an equal sign.

- An attribute value, wrapped with opening and closing quote marks.

[Attributes](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

# Describe the Anatomy of an HTML element.
The anatomy of HTML are its elements. The HTML element consist of:
- *Doc Type* _<!DOCTYPE html>_

- *HTML* _<html></html>_

- *Head* _<head></head>_

- *Meta* _<meta charset="utf-8">_

- *Title* _<title></title>_

- *Body* _<body></body>_

# What is the Difference between <article> and <section> element tags?
*Article:* The _article_ HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable. [Article](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article)

*Section:* The _section_ HTML element represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it. [Section](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section)

# What Elements does a “typical” website include?
A typical website should include:
- Header

- Navigation Bar

- Main Content

- Side Bar

- Footer

# How does metadata influence Search Engine Optimization?
Your HTML document will be indexed more effectively by search engines if its language is set (allowing it to appear correctly in language-specific results, for example), and it is useful to people with visual impairments using screen readers. [META](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

# How is the <meta> HTML tag used when specifying metadata?
Many _<meta>_ elements include name and content attributes:
- _name_ specifies the type of meta element it is; what type of information it contains.

- _content_ specifies the actual meta content.

[META](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

# What is the first step to designing a Website?
Before creating a website, you want to ask yourself these questions:
- What exactly do I want to accomplish?
- How will a website help me reach my goals?
- What needs to be done, and in what order, to reach my goals?

All of this is called *_project ideation_* and is a necessary first step.

[Website Design](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)

# What is the most important question to answer when designing a Website?
  
*_What Exactly Do I Want To Accomplish?_* is the most important question to answer.

# Why should you use an <h1> element over a <span> element to display a top level heading?
The *_h1_* element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page.
A *_span_* element will render it to look like a top level heading, but it has no semantic value. It is therefore a good idea to use the right HTML element for the right job.
HTML should be coded to represent the data that will be populated and not based on its default presentation styling.
[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

# What are the benefits of using semantic tags in our HTML?
Some of the benefits from writing semantic markup are as follows:
- Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)

- Screen readers can use it as a signpost to help visually impaired users navigate a page

- Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes

- Suggests to the developer the type of data that will be populated

- Semantic naming mirrors proper custom element/component naming

[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

# Describe 2 things that require JavaScript in the Browser?
*_JavaScript_* is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, etc.

Some examples would be:
- The Twitter API allows you to do things like displaying your latest tweets on your website.

- The Google Maps API and OpenStreetMap API allows you to embed custom maps into your website, and other such functionality.
[JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

# How can you add JavaScript to an HTML document?
*_JavaScript_* is applied to your HTML page in a similar manner to CSS. Whereas CSS uses <link> elements to apply external stylesheets and <style> elements to apply internal stylesheets to HTML, JavaScript only needs one friend in the world of HTML — the <script> element.

Some different variations for adding *_JavaScript_* are:
- Internal JavaScript

- External JavaScript

[JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#internal_javascript)


## Things I want to know more about
- Deeper knowledge on the functions of *_CSS, HTML, and JavaScript_*.

- Understanding the benefits of *_S.E.O._* in relations to advertisements.

- More information on how we utilize *_meta_* elements.

- Learning more about *_JavaScript_* and its application for web development.
