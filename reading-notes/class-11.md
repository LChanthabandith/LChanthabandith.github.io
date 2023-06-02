# Readings: Audio, Video, Images

## Explain how the ability to use video and audio on the web has evolved since the early 2000s.

The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions `<video>` and `<audio>` elements and the availability of JavaScript APIs for controlling them. 

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

## Describe the use of the `src` and `controls` attributes in the `<video>` element.

`src`
> In the same way as for the <img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.

`controls`
> Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.

The `<video>` element allows you to embed a video very easily.

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)  

## Why is it important to have **fallback content** inside the `<video>` element?

The paragraph inside the `<video>` tags. This is called fallback content — this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content) 
  
## Write a very short story where `<audio>` and `<video>` are characters.
  
In a busy world of web coding, there were two stars: Audio and Video. Audio was a quiet genius, creating beautiful sounds, while Video was an outgoing storyteller, spinning tales in vibrant colors. They were often at odds, each feeling unappreciated by the other. So, they turned to their wise friend Body for advice. Body reminded them how they worked best when they teamed up, creating an exciting and interactive online world. Understanding this, Audio and Video stopped their rivalry and started appreciating how their unique talents worked magic together.
  
[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## How does Grid layout differ from Flex?
  
CSS *Grid* Layout (aka “Grid” or “CSS Grid”), is a two-dimensional grid-based layout system that, compared to any web layout system of the past, completely changes the way we design user interfaces. *Flexbox* is a one-directional flow has different use cases 

[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
 
## Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- *Grid Container* The element on which display: grid is applied. It’s the direct parent of all the grid items.
  
- *Grid Item* The children (i.e. direct descendants) of the grid container.
  
- *Grid Line* The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.
  
[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
  
To help improve preformance across different devices.
  
## Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.
  
`srcset` defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma.
  
`sizes` defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true
  
[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
  
## How is `srcset` more helpful for responsive images than CSS or JavaScript?

`srcset` allows the browser to automatically select and load the most suitable image based on the user's device characteristics, improving performance and saving bandwidth.
  
## Things I want to know more about
  
- Using the video element in my coding.
  
- Learning more about Grid terms.
