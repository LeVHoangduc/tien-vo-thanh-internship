# tien-vo-thanh-internship #open-questions

**1. Should we use table tags in HTML? Why?**
- It depends on the usage in web design. Firstly, tables in HTML are still useful elements displaying information in a structured grid-like format, organizing and 
  presenting tabular data. However, it's important to note that tables should not be used for general page layout purposes because there are some modern CSS 
  techniques more suitable and offer better responsiveness over the design such as flexbox or grid container.

**2. Which HTML tags have property display: inline, block, inline-block?**
- Inline tags: span, a, b, em, i, img, code, dfn, input, label...
- Block tags: div, h1 to h6, ul, ol, li, table...
- Inline-block tags: input, button, textarea, select, fieldset...

**3. When will we use section , article tag ?**
- section tag is used for dividing content into themed sections.
- article tag is used for standalone and distributable content pieces.

**4. How to use :before, :after CSS properties?**

  These are pseudo-elements in CSS allow you to insert content before or after an element's actual content.
  - ::before: inserts content before the element
  - ::after: inserts content after the element

**5. List all units in CSS.**
- Absolute units: px, in, cm, mm, pt, pc
- Relative Units: %, em, rem, ex...
- Viewport-percentage: vm, vi, vh, vw, vmin, vmax

  **5.1. When to use rem and when to use em?**
  - rem: is a unit that references the scale relative to the root element of the website, typically the tag, based on the value of the font-size property.
  - rem: is often used for global size values in CSS, such as font sizes, element widths, and heights.
  - em: is a unit that references the scale relative to the immediate parent element containing it or itself, based on the value of the font-size property.
  - em: is commonly used to set relative sizes for child elements inside a parent element, such as margins, paddings, and relative font sizes.

**6. What are the differences between position: absolute, relative, fixed?**
- relative: setting the top, right, bottom, and left properties of a relatively-positioned element.
- fixed: is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.
- absolute: is positioned relative to the nearest positioned ancestor

**7. How does the z-index property work?**
- If boxes do overlap, the elements that appear later in the HTML code sit on top of those
  that are earlier in the page. If you want to control which element sits on top, you can use the z-index.
- An element can have a positive or negative stack order
  
  **7.1. When two elements are stacked?**
  - Using the CSS "position"
  - Using the CSS "transform"
 
**8. How to add a google font to the CSS?**
![Image](https://github.com/thanhnguyen-agilityio/tien-vo-thanh-internship/assets/80720226/4fab7774-37f5-4027-88bf-0e1d20909fdb)

**9. What is the level of nesting CSS we should use? Why?**
- There is no rules for the limit of nesting CSS but excessive nesting can make the CSS code more complex and harder to understand. Generally recommended to keep 
  the level of nesting relatively low, typically within 2 or 3 levels
  
  **9.1. What is CSS nesting?**
  - CSS nesting refers to the ability to nest selectors and styles within each other directly in CSS. It allows you to write more organized and modular code by 
    visually representing the relationships between parent and child elements. With native CSS nesting, you can use the & character to reference the parent 
    selector within the nested selector and like sass.

**10. Should we use sprite-css? Why?**
- Yes, When a single image is used for several different parts of an interface. The advantage of using sprites is that the web browser only needs to request one 
  image rather than many images, which can make the web page load faster. However, their usage should be considered on a case-by-case basis, evaluating the 
  specific needs.
  
  **10.1. What is Sprite-image?**
  - Sprite image is a technique that combines multiple small images into a single large image. By using a sprite image, the individual images can be displayed by 
    specifying the position and size of each image within the sprite.

**11. List HTML validation tools you know.**
1. [W3C Markup Validation Servic](https://validator.w3.org/)
2. [HTML5 Validator](https://html5.validator.nu/)

**12. Why should refer to style by class name rather than style by id or the element tags?**
- Classes can be applied to multiple elements, allowing for the reuse of styles throughout the codebase. This promotes cleaner and more efficient CSS by avoiding 
   style duplication.

**13. Why should not use float and position: absolute? Now we prefer flexbox and do you know why?**
- We do not use float and position: absolute because they often require manual calculations and adjustments to achieve the desired positioning and alignment, 
  making the code more prone to errors and difficult to maintain.
- Flexbox is preferred over floats and position: absolute because it simplifies code, offers better control and responsiveness, improves browser compatibility, and 
  aligns with modern web development practices.
