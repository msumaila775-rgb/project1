# Predict The Output.
I was presented with different scenarios to predict the result before testing it.

## Scenario A
 The color the text displays inside the **p** is **Orange**.
 The universal selector * targets every single element directly,including the **p** element, and explicitly sets its color to **Orange**. On the other hand, the **div** selector sets the color of the **div** to blue, which the **p** would normally try to inherit.

 ## Scenario B
 The color the text displays inside the text is **Green**.
 The universal selector has  a low weight, while the class selector **.highlight** has a higher weight.
 This demonstrates the principle of CSS Specificity, where a more specific rule overrides a less specific one when they target the same element.