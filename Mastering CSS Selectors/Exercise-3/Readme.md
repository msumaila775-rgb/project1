# About
I was presented with a HTML structure, instructed not to change the HTML and to write a single CSS rule for each description that targets only the requested elements, using the selectors from the lesson taught to me.

## To target only "Item 2" to make it gray, using a pseudo-class.
To isolate the second **li** element inside the list, use the **:nth-child()** pseudo-class.

## To target only the "Second paragraph in container" to give it a background color, using a pseudo-class.
Since the second **p** element shares the same parent **.container**, you can use the **:nth-of-type(2)** pseudo-class

## To target both paragraphs inside the .container to give them a line-height of 1.6, using a descendant selector.
A descendant selector uses a space to target any **p** tag inside an element with the class **.container**.

## Challenge
The selector **p:nth-child(1)** does not mean **find the first p element on the page.** Instead, it translate to **find an element that is a p tag AND is the absolute first child of its parent container.**