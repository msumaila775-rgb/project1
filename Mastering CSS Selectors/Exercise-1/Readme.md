# About 
In this exercise I was given an **HTML and a CSS file**. I was ask to not change or remove any existing code, I should make the paragraph appear **Green**.

## Current Color.
The color displayed was red because the selector types carry differrent weight:
 p: has a very low weight.
 .highlight: has a medium weight.
 #main-text: has a high weight.
Because the ID selector has the highest specificity weight, the **#main-text** rule overrides both the class and element rules, making the text **Red**.

## Selector Used To Change The Paragraph Green.
Selector used: **P#main-text*
By combining the tag name **p** and the ID **#main-text**, the new selector has a weight of **1ID + 1 Element** which beats the original ID-only.

## How else I could make the Paragraph Green without using an ID or Inline by just adding one rule.
**p.highlight{color:green !important};**
The !important flag bypasses standard selector specificity weight entirely. It acts as a final override, making a simple class or element combination override even the strongest ID selectors.