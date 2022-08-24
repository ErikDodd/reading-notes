# Code 201 - Class 8 - Reading Notes

## Learn CSS - Flexbox

**1. Flexbox is designed for one-dimensional content. Explain what this means.**

- It is a layout that really helps with responsive design and it takes a bunch of different sized items and determines the best way to create the layout. This changes as the size of the viewport is adjusted. Items expand to fill the space or shrink to fit into smaller areas. For instance, the flexbox model is very helpful when creating a sidebar.

**2. Explain the difference between the main axis and cross axis.**

- The main axis is determined by using the 'flex-direction' property. This can be either columns or row depending on what you set it to. The cross axis runs in the other direction of your main axis. So if your main axis is row, running from left to right, then the cross axis would be column, running from top to bottom. With the cross axis you have the option of moving an individual item or moving the groups of items in order to keep them aligned with the flex container.

**3. What are some advantages of using flexbox over float?**

- It allows you to make all the children of a container take up an equal amount of available width and height regardless of the size of the viewport.
-It allows you to make standard the size of a column in a multiple column layout even if the content inside the columns is a different height.

**4. How does this topic connect with your long-term goals?**

- This will better allow me to control the layout of whatever I'm designing. In the past, there were some instances where I had 3 div elements and I wanted them to display inline and take up the same amount of space. I can do this really easily with the flexbox.

**5. How can using certain properties of flexbox negatively impact accessibility?**

- Using row reverse or column reverse. These both impact the visual order of the content but not the logical order of the content. The screenreader goes by the logical order, so if you use a screen reader it will read the content out of order which is not helpful for the user.
