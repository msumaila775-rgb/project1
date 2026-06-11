# About Exercise-1

The color of the paragraph at first displays **Orange** but currently it displays **Green**. The CSS method that I used to overide the other styles is the CSS syntax **!important**.

I made the paragraph Green by creating an external **style.css** file, typed  **p{color: green !important}**. The !important css syntax gives the property the highest priority, even over inline styles, internal styles and others.

Also by removing that one line of code that I added and by changing one existing value in the **style** block will it be able to change the paragraph to blue? It is not possible because the paragraph has an **inline style:style="color: orange;"**.
So changing **p{color: red;}** to **p{color: blue}** will still leave the text **Orange**.