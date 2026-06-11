# Predicting The Output
For every scenario I was tasked to predict the result before testing it in a browser.

## Scenario A
From my understanding the text that will be displayed will have the color **red**, it will be **underlined**, the text will be aligned **center**.
Because, the inline style will overide the block style.  

## Scenario B
The font family that the paragraph will use is the **Arial, sans-serif**.
From my observation **#333333 and rgb(51, 51, 51)** are the same color.
If I remove the entire **p** rule, the font family the paragraph will use is **"Poppins", sans-serif**. The reason is that, the p rule had its own style so after it was removed, the paragraphs will take the styles from the body.

## Scenario C
The **<h1>** will display color **Bright Red**.
