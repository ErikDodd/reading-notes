# Code 201 - Class 5 - Reading Notes

## Learn HTML - HTML Media

**1. What is a real world use case for the alt attribute being used in a website?**

- It helps when users are visually impaired. The screen reader will read the 'alt' attribute out loud to them.

**2.How can you improve accessibility of images in an HTML document?**

- Be sure to use an alt attribute and title for the image.

**3.Provide an example of when the figure element would be useful in an HTML document.**

- When you want to utilize self-contained content that is independent of the main flow of the webpage.

**4.Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.**

- GIF and SVG are both images used online. The main difference is that GIF's look pixelated when they are made larger. SVG images are scalable and will look nice as the image changes size.

**5.What image type would you use to display a screenshot on your website and why?**

- PNG or Lossless WebP. The image can become fuzzy under lossy compression, so these two options don't have that.

## Learn CSS - Using Color & Styling HTML Text Elements

**1.Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.**

- Let's use text as an example. Foreground color would be the color of the font, while background color would be the color that is highlighted behind the font. Another example would be if you wrote notes in blue pen and highlighted them in yellow highlighter. The blue pen would be foreground color, and the yellow highlighter would be background color.

**2.Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?**

- I would want to figure out the base color of the website. Then find some other ways to incorporate color in the text like having heading tags be red or something similar. I would also color coordinate either the background color to the color of the headings. I would consider turning some of the elements into div tags and then adding some color to the borders as well.

**3.What should you consider when choosing fonts for an HTML document?**

- Whether or not it is a web safe font that is available across all systems. Example would be a sans-serif font like Helvetica or Arial. I'd also do a font stack, so that I could have some back up options as well just in case my preferred choice wasn't available. I'd also consider whether or not the font was being used for content in a p tag or if it was being used as an h1 or h2 and select a particular font to fit that need.

**4.What do font-size, font-weight, and font-style do to HTML text elements?**

- font-size allows you to adjust the size of the font in either pixels, em, or rem. Em is the same as the font size of parent element / the same size of font as the element you are currently applying style to. rem is similar but relates to the font being the same size as the root element in the document.

- font-weight relates to how bold you want the text to be. Examples include normal, bold, extrabold, black etc.

- font-style relates to the ability to turn italic text either on or off. Examples include normal, italic, oblique

**5.Describe two ways you could add spacing around the characters displayed in an h1 element.**

- letter-spacing property and word-spacing property
