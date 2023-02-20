# Notes

## Things I want to know more about:

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

- The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete

2. Describe the use of the src and controls attributes in the video element.

- In the same way as for the img element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.

3. Why is it important to have fallback content inside the video element?

- So the user can at least access it some way regardless of what browser they are using.

4. Write a very short story where audio and video are characters.

- I am a video element. I allow people to watch a video on your webpage! My sibling is the audio element! He/she lets you listen to whatever is on your webpage! 

[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

1. How does Grid layout differ from Flex?

- Similarly to flexbox, the source order of the grid items doesn’t matter. Your CSS can place them in any order, which makes it super easy to rearrange your grid with media queries.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- Grid Container- The element on which display: grid is applied

- Grid Item- The children (i.e. direct descendants) of the grid container.

- Grid Line- The dividing lines that make up the structure of the grid.

[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

- It allows you to view them on a more narrow screen.

2. Define the following img attributes srcset and sizes. Write an example of how they are used.

- srcset defines the set of images we will allow the browser to choose between, and what size each image is

- sizes defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true 

![srcset-sizes](/img/srcset-sizes.jpeg)

3. How is srcset more helpful for responsive images than CSS or JavaScript?

- When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — hence the need to implement solutions like srcset

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
