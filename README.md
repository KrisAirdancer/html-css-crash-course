# html-css-crash-course
My code and notes from The Net Ninja's HTML &amp; CSS Crash Course: https://www.youtube.com/watch?v=hu-q2zYwEYs&amp;list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G

99% of the code in this project was provided by The Net Ninja. I only added comments and tweaked things a bit to learn from the material.


## Notes

*There was no coding portion in lesson 7. Thus, there are no branches or files for lesson 7.

- HTML provides the structure for a webpage while CSS provides the styling  (colors, etc.).
- You can view a local .html file (or any other file type for that matter) in a browser by pasting the local address into the browser URL bar.
- Pro Tip: Use the developer tools in a browser (inspect) to reverse engineer a website or elements on a website you want to replicate.
- The 'id' element:
    - Used to identify that specific element.
    - Can be used as a hook in JavaScript or CSS to modify that element.
    - Can be used to link the element to another element.
        - Such as linking a label to an input field.
- When an HTML form is submitted...
    - The form fields are checked for validity and the user notified if any fields are incorrect or incomplete (for fields where this applies).
    - The form fields are cleared.
    - The data from the fields is inserted into the URL (security issue I would think - there must be a better way to do this) and sent to the backend for processing.
        - It could also be processed by JavaScript on the frontend.
- Selectors
    - Used to target specific elements (tags, classes, etc.) on a webpage.
- Declarations
    - Key-value pairs that define attributes for a given element.
- Adding CSS to HTML
    - CSS can be added direclty to HTML pages, but that gets messy fast.
    - CSS can also be added to a separate file that is used in conjunction with the HTML files to generate the webpage.
- Inline Elements
    - Line up next to each other in the browser window.
    - Take up only as much room as the content they house needs.
    - ex. span, img, strong, em, a, etc.
- Block level elements
    - Take up the whole width of the page regardless of the size of the content they house.
    - ex. p, div, headers, li, etc.
- Padding & Margin
    - Margin controls the space around the element.
    - Padding controls the spacing insdie the element.
    - On inline elements, padding is added all the way around as expected. But margin is only added to the left and right sides of the element. Not to the top.
- Inline Block Elements
    - Mixes inline properties with block level properties.
    - Causes inline elements to behave like inline (sit next to each other and only take up as much space as their content needs), but causes padding and margin to behave as if it is a block level element (padding and margin are applied to all sides of the element).
- Default browser styles
    - If we don't provide styles via CSS, the browser will style elements using a default style (headers are bold and large, etc.).
    - "user agent" is the name (seen in the in-browser dev tools) of the default browser style sheet.
- Descendent Selectors
    - This allows us to target the child elements of parent elements.
- Cascade (as in C in CSS)
    - CSS properties can flow down from parent to child elements.
    - HTML elements can inherit CSS properties that are applied to their parents.
        - ex. A p tag inside a styled div tag would get the same style as the div tag.
    - Not all style rules are inherited.
    - Any style given to a child element directly will override the style inherited from the parent.
    - If you re-style the same element (and the same property), the declaration of style that comes farthest up the page will be used.
- HTML 5 Semantic Tags
    - Semantic tags tell the browser what the content on the site is.
    - Some common semantics tags
        - `<main>`, `<section>`, `<article>`, `<aside>`, `<header>`, and `<footer>`
- Position Properties
    - Static
        - The default positioning.
    - Relative
        - Positions the specified element a specified distance away from its original position. The original position being where it would be placed by default if no positioning was specified for that element.
        - Itis bounded by the specified distances.
    - Fixed
        - The element doesn't move from where it was placed.
        - Locks the element into a position relative to the browser window.
    - Absolute
        - Locks the element into a position relative to its parent element.
    - Sticky
        - Mixture of static and fixed.
- Normal Docuemnt Flow
    - The positioning used by default if no other positioning is set.
    - This arranges elements from top to bottom above and below each other. Just as they are coded in the HTML file.
- Z-Index
    - Positions items in front of and behind each ohter.
    - All elements have a z-index of 0 by default.
    - Positive values bring the element forward. Negative values push the elements backward.
- Pseudo Classes
    - Pseudo classes are used to style elements when they are in a specific state.
    - eg. :hover, :focus, :first-child, etc.
    - [List of pseudo classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) 
- Pseudo Elements
    - [List of pseudo elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements) 
- Responsive Design
    - Responsive design allows a webpage to style differently when viewed on different sized screens.
    - Media Queries
        - Media queries are a part of responsive design.
        - They tell the browser how to style an element based on the dimensions of the viewport.
        - Note: Viewport != screen size. eg. I can make a browser window (view port) super tiny on a gigantic monitor (screen size).
    - Viewport Meta Tag
        - A part of responsive design.
        - Tells the browser what width the viewport should be.
    - Responsive Images
        - A part of responsive design.
        - Only load smaller images for mobile devices.
    - Responsive design strategies
        - You should design a website based on a strategy for how you expect the site to be used.
        - One design strategy is "mobile-first."
            - This strategy aims to build a site so that it is optimized for mobile, but can be scaled up to work on larger screens.
            - This allows you to develop with just the essential content for the smaller screens, then add more content for larger screens.
        - This allows the developer to strategize about how to layout the site and what elements/images/text to include and how to style them.
        - The Viewport Method Tag (added to the HTML `<head>`) tells the browser what width the viewport should be.
            - This tag is necessary to make the responsive design work.
            - Here's an example from W3 Schools: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
        

















