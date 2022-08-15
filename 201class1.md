# Code 201 - Class 1 - Reading Notes

## How the Web Works, Website Design & Proess, and Javascript Basics

**1. Compose a short poem describing how HTTP sends data between computer. **

- HTTP works so simply.The browser goes to the server and finds the address.Then the browser sends an HTTP request to ask the server, for a copy of the website and all the rest.What’s next is the server approves the request and sends a ‘200 OK’ message and sends the website through the browser in the form of data packets.These data packets and the rest of the website, which looks nice, travels across the internet connection and is delivered to your computer without a second suggestion.The browser receives the website and puts together all of the data packages into the full website, so you can be filled with joy and delight.

**2.Describe how HTML, CSS, and JS files are “parsed” in the browser.**

- The browser first parses through the HTML file first. Then it looks for <link> elements such as a connecting CSS style sheet or a <script> element for Javascript. Next the browser sends a request for the <link> element back to the server to send the related CSS file associated with the HTML doc. Finally, the browser sends over any Javascript files that are found using the <script> element.

**3.How can you find images to add to a Website?**

- Simply go to ‘Google Images’, search for whatever image you are looking for, select a specific image, and click on it to enlarge the image. Then either ‘save as’ or copy the image’s web address. Make sure to double check for copyrighted images by using Google’s license filter.

**4.How do you create a String vs a Number in JavaScript?**

- String is created by enclosing the value in single quotation marks. String deals with Text. Numbers deal with numbers. Numbers also don’t need to have quotation marks around the number.

**5.What is a Variable and why are they important in JavaScript?**

- Variables are containers that are used to store values. They are important because they allow us to do interesting things like send a customize a greeting to the user or make things more interactive on a webpage.

## Introduction to HTML

**1.What is an HTML attribute?**

- An HTML attribute contains additional information about an element that will not appear in the content. It For instance a class attribute can be located inside a <p> to target this specific tag to style it a certain way.

**2.Describe the Anatomy of an HTML element.**

- HTML Element = opening tag, content, closing tag. Ex. <p> Hello Code 201 Students </>

**3.What is the Difference between <article> and <section> element tags?**

- <Article> - encloses a single block of content that makes sense by itself on a page. An example of this is a blog.

- <Section> is similar to Article but this is for grouping together related parts of content on a page into a single section. So essentially you will have many <section> elements on a single page.

**4.What Elements does a “typical” website include?**

- <head>, <body>, <footer>, <main>, <nav>, <article>, <section>, <div>, <p>

**5.How does metadata influence Search Engine Optimization?**

- The ‘description’ listed in metadata is also used on the Search Engine Results page. When you search something like ‘Seattle Sounders’, the description listed in the metadata will show up as the description for the website.

**6.How is the <meta> HTML tag used when specifying metadata?**

- The <meta> tag is used describe the data included in the website. You can add <meta charset=“utf-8"> which specifies that the website will use utf-8 which is a universal character set that includes any character in the human language. The <meta> tag can also be used to describe the website, the author of the website and much more.

## How to Start to Design a Website

**1.What is the first step to designing a Website?**

- Determining what you want your website to do. Do you want to sell something or maybe provide information? What is your website about mainly is the first step.

2.What is the most important question to answer when designing a Website?

- What you want to accomplish with the website. What goals do you want to accomplish with your website. Everything else you do is dependent on answering that question.

## Semantics

**1.Why should you use an <h1> element over a <span> element to display a top level heading?**

-This is because the <h1> element has semantic meaning as a header and the <span> element doesn’t. The <h1> will by default will automatically be styled to be a larger font and make it look like a heading. With the <span> tag, you can essentially do the same thing but it takes more coding and has no semantic value as a header. So it is easier and more efficient to use the right semantic element.

**2.What are the benefits of using semantic tags in our HTML?**

- Search engines will consider the content as an important keyword which improves SEO.
- It helps with accessibility since screen readers will use it as a signpost when navigating the page to better serve the visually impaired.
- Looking for code is easier when using semantic tags as opposed to searching lots of <div> tags.
- This helps the developer with the type of data that will be used.  

## What is Javascript?

**1.Describe 2 things that require JavaScript in the Browser?**

- Interactive maps and animated 2D/3D graphics 

**2.How can you add JavaScript to an HTML document?**

- Javascript is added to HTML document by utilizing the <script> element. You can add the <script> tag in the HTML document like in the <head> element. Then you would add whatever Javascript inside the <script> element to make the page more interactive. You can add internal Javascript with the <script> tag or put it in an external Javascript file as well similar to CSS and the <style> tag.

## Things I Want to Know More About

1.Different ways to use Javascript to create more interactive websites
2.More in-depth information on Basics of Javascript and how to use in building simple websites
3.More info on Metadata