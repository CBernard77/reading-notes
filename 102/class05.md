## What is the purpose of CSS?

CSS (Cascading Style Sheets) allows you to create great-looking web page. Using CSS, you can control exactly how HTML elements look in the browser, presenting your markup using whatever design you like. CSS is a language for specifying how documents are presented to users

## What are the three ways to insert CSS into your project?

1. Inlining CSS involves directly adding CSS styles to individual HTML elements using the style attribute. While inline CSS can be useful for small styling tweaks, it's generally considered bad practice for larger stylesheets because it mixes content with presentation, making it harder to maintain and reuse styles.

2. Internal CSS involves placing CSS code within a <style> element in the <head> section of an HTML document. Internal CSS keeps the styling separate from the HTML content, making it easier to maintain compared to inline CSS. However, it still presents some challenges for larger projects, especially when trying to reuse styles across multiple pages.. Inline which provides styling directly in the HTML element.

3. External CSS: External CSS involves placing CSS code in an external file with a .css extension and linking it to the HTML document using the <link> element. 

    And the contents of styles.css:

    body {
        background-color: lightblue;
    }
    p {
        color: red;
    }

Using external CSS allows for separation of concerns, making it easier to manage and reuse styles across multiple HTML pages. It also enables better organization and maintenance of code, as styles are stored in a separate file. Additionally, browser caching can improve page loading times since the CSS file can be cached and reused across multiple pages.

## To give all elements red text using CSS, you would write this:
p {color: red;}






