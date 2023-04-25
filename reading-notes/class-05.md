# Readings: Images, Color, Text

## What is a real world use case for the `alt` attribute being used in a website?

Using the `alt` attribute is a good practice for web developers to ensure _accessibility_, _improve SEO_, _enhance user experience_, and _comply with legal requirements_.

## How can you improve accessibility of images in an HTML document?

- Use descriptive `alt` text

- Use appropriate file formats, examples (jpeg, png, or gif).

- Provide alternative text for complex images.

## Provide an example of when the `figure` element would be useful in an HTML document.

> Let's say you have an article about a new product launch and you want to include an image of the product along with a caption describing its features. You could use the figure element to group the image and caption together, like this:
``` 
  <figure>
    <img src="product-launch.jpg" alt="Product Launch">
    <figcaption>Our new product features a sleek design, advanced technology, and intuitive user interface.</figcaption>
  </figure>
  ```
> These are created for exactly this purpose: to provide a semantic container for figures, and to clearly link the figure to the caption.

[Annotating images with figures and figure captions](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

## Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.

GIF images are great for creating animations and adding visual interest to websites and social media, while SVG images are great for logos, icons, and other graphics that need to be displayed at different sizes without losing quality.

## What image type would you use to display a screenshot on your website and why?

Unless you're willing to compromise on quality, you should use a lossless format for screenshots. This is particularly important if there's any text in your screenshot, as text easily becomes fuzzy and unclear under lossy compression. PNG is probably your best bet, but lossless WebP is arguably going to be better compressed.

[Screenshots](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)

## Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

**Foreground color** is the color of the text or content displayed on top of the background color, while **background color** is the color of the area behind the content. By using different combinations of foreground and background colors, you can create a visually appealing and easy-to-read webpage.

## Your friend asks you to give his colorless blog website a touch up.  How would you use color to give his blog some character?

I would choose a color palette, adding color to key areas, and using color for accents and highlights, to transform a colorless blog into a visually appealing and engaging website.


## What should you consider when choosing fonts for an HTML document?

- Readability

- Legibility

- Compatibility

- Contrast


## What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?

- The **font-size** CSS property sets the size of the font. Changing the font size also updates the sizes of the font size-relative `<length>` units, such as em, ex, and so forth.

[Font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size)

- The **font-weight** CSS property sets the weight (or boldness) of the font. The weights available depend on the font-family that is currently set.

[Font-weight](https://developer.mozilla.org/en-US/docs/Web/CSS/font-weight)

- The **font-style** CSS property sets whether a font should be styled with a normal, italic, or oblique face from its font-family.

[Font-style](https://developer.mozilla.org/en-US/docs/Web/CSS/font-style)

## Describe two ways you could add spacing around the characters displayed in an `h1` element.

The letter-spacing and word-spacing properties allow you to set the spacing between letters and words in your text. You won't use these very often, but might find a use for them to obtain a specific look, or to improve the legibility of a particularly dense font. They can take most length and size units.

```
html {
  font-size: 10px;
}

h1 {
  font-size: 5rem;
  text-transform: capitalize;
  text-shadow: 1px 1px 1px red, 2px 2px 1px red;
  text-align: center;
  letter-spacing: 2px;
}

h1 + p {
  font-weight: bold;
}

p {
  font-size: 1.5rem;
  color: red;
  font-family: Helvetica, Arial, sans-serif;
  line-height: 1.6;
  letter-spacing: 1px;
}
  ```
  
[Letter and word spacing](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)
