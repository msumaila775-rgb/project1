# Conceptual Deep Dive
If HTML is the walls and framework, and CSS is the paint and furniture, then trying to build a house using only CSS is like trying to decorate an empty place with paint and chairs. CSS cannot create the rooms, walls, doors, or the actual structure, it only styles the things that already exist. So no, it is not possible without HTML there is nothing for CSS to style.

A real problem with only inline CSS:

   Imagine a company website with 200 product pages and a marketing campaign that requires switching the brand color from blue to orange across the entire site.

   If every heading, button, and text block used inline CSS, you would need to edit each text on every page.

   That is a serious risk: inconsistent updates, missed pages, broken formatting, much higher development cost, and slower page loads because every page carries repeated style rules.

   With external CSS, you change one rule in one file and the new color affects every page immediately, avoiding those consequences.

If the HTML is **<p class="highlight">Text</p>**, the text will be green.

   Reason: **.highlight** is a class selector, and class selectors are more specific than plain element selectors like **p**.

   Even though both rules apply, the rule with higher specificity wins, so the class-based **color: green;` overrides** **p { color: blue; }**.

The lesson shows four different color formats because each format has a different practical strength:

   Hex: compact and widely used in design systems and CSS palettes; easy to copy from color pickers.

   RGB: lets you think in red/green/blue channels and is useful when adjusting individual channels or using transparency with **rgba()**.

   HSL: very intuitive for designers, because you can change hue, saturation, and lightness directly; great for creating tints, shades, and color families.

   Named colors: quick and readable for common colors like **gray**, **red**, or **white**; useful for simple cases and faster prototyping.
