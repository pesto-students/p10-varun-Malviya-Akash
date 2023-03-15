
# Browser Functionality: Requesting and Rendering Web Pages

When you enter a URL in your browser, the browser begins by sending a request to the server where the website is hosted. This request asks the server to send back the HTML, CSS, JavaScript, and any other resources required to display the page.

## Screenshots

![App Screenshot](https://static.javatpoint.com/blog/images/web-servers.png)

Once the browser receives the HTML code, it uses a parser to convert it into a Document Object Model (DOM) tree. This tree represents the structure of the web page, with each HTML tag represented as a node in the tree.

## Screenshot

![App Screenshot](https://www.w3schools.com/js/pic_htmltree.gif)

The browser then uses a rendering engine to apply CSS styles to each element in the tree and determine the final layout of the page.

## Screenshot

![App Screenshot](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works/rendering.svg)

As the rendering engine constructs the page, it may encounter JavaScript code that needs to be executed. The browser's JavaScript interpreter processes this code and may interact with the DOM tree and CSS styles, making further changes to the layout and appearance of the page.

Once the rendering engine has finished constructing the page, the browser uses a layout engine to calculate the size and position of each element in the DOM tree.

The browser then paints the final layout of the page on the screen, allowing you to view and interact with the content.

Overall, the browser's main functionality is to allow users to access and view content on the internet, and it does so by requesting and rendering web pages using a combination of parsing, rendering, and layout engines, as well as JavaScript processing and event handling

## Screenshot

![App Screenshot](https://i.stack.imgur.com/kBF3j.png)









