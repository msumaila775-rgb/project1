# About
My teammate wrote CSS to style a navigation bar and a content area, but the styles are bleeding into places they shouldn't. I was tasked to fix the errors based on the requirements.

# A selector that only targets links inside the nav.
To target an element that is inside another element, you use a **descendant selector** by separating the **parent element** and the **child element** with a spacce.

## Why the h2 h3 doesn't work.
Because there is only a space between them, **h2 h3** is looking for an **h3** element that is nested inside an **h2** element. Since HTML doesn't put headings inside other headings, this rule matches nothing.
To style multiple distinct element with the same rules, you use a **group selector** by separating the selectors with a **comma** **(h2, h3)**.

## Question 3
Yes, it fixes the issue. The original space selector **(ul.main-list li)** is a descendant selector. It targets every **li** nested anywhere inside that **ul**, including any sub-lists further down the tree. By switching to the child combinator **>**, CSS will only target **li** elements that are direct, immediate children of **ul.main-list**. If there is a second, nested list inside one of those list items, its sub-**li** elements will be safely ignored. 