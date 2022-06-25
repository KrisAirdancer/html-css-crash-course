# html-css-crash-course
My code and notes from The Net Ninja's HTML &amp; CSS Crash Course: https://www.youtube.com/watch?v=hu-q2zYwEYs&amp;list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G


## Notes

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