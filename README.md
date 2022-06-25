# html-css-crash-course
My code and notes from The Net Ninja's HTML &amp; CSS Crash Course: https://www.youtube.com/watch?v=hu-q2zYwEYs&amp;list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G


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
        - <main>, <section>, <article>, <aside>, <header>, <footer>
