
Here's the information you provided, formatted in Markdown for clarity:

---

## Getting Started with VS Code for Web Development

To streamline your web development workflow, follow these steps:

1.  **Install VS Code:** Download and install [Visual Studio Code](https://code.visualstudio.com/) on your operating system.
2.  **Install Live Server Plugin:** Open VS Code, go to the **Extensions** view (Ctrl+Shift+X or Cmd+Shift+X), search for "Live Server," and click **Install**. This extension provides a local development server with live reload capabilities.
3.  **View an HTML Page with Live Server:** Once Live Server is installed, open your HTML file in VS Code. In the bottom-right corner of the editor, you'll see a **"Go Live"** button. Click it to open your HTML page in your default browser with live reload enabled.
4.  **Access MDN Documentation:** While viewing your code in VS Code, you can **hover over any HTML element or CSS property** to see a quick summary. To open the full MDN Web Docs for that element, press **Alt + Click** (or Option + Click on Mac) on the element.
5.  **Toggle Word Wrap:** If your lines of code are extending horizontally and you want them to wrap within the editor's view, you can toggle word wrap.
    * **Select a line of code** (or just ensure your cursor is on it).
    * Go to **File > Preferences > Settings** (or Code > Preferences > Settings on Mac).
    * Alternatively, open the **Command Palette** (Ctrl+Shift+P or Cmd+Shift+P) and type "Toggle Word Wrap" then select the command.

---

Do you have any specific HTML elements or CSS properties you'd like to learn more about?
-----

## HTML Fundamentals

### 1\. HTML Tags & Structure

HTML tags act as containers for content or other HTML tags, forming the building blocks of a web page.

```html
<!DOCTYPE html> <html lang="en"> <head>
    <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction</title> </head>
<body>
    <h1>Hello world</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

-----

### 2\. Tag Structure: Opening and Closing

Most HTML elements have both an **opening tag** (e.g., `<p>`) and a **closing tag** (e.g., `</p>`). The content goes between these tags.

-----

### 3\. Self-Closing Tags

Some HTML tags are "self-closing" and do not require a separate closing tag.

  * **Example:** `<br>` (for a line break)

-----

### 4\. Heading Tags (`<h1>` to `<h6>`)

Heading tags define titles and subtitles, with `<h1>` being the most important and `<h6>` the least.

  * `<h1>`: Most important heading
  * `<h2>`
  * `<h3>`
  * `<h4>`
  * `<h5>`
  * `<h6>`

-----

### 5\. Paragraph Tag (`<p>`)

The `<p>` tag is used to define a paragraph of text.

  * `<p>This is a paragraph.</p>`

-----

### 6\. Anchor Tag (`<a>`)

The `<a>` tag creates hyperlinks to other web pages or locations within the same page.

  * **External Link:** `<a href="http://google.com">Google</a>`
  * **Local Link:** `<a href="/local.html">Local HTML Page</a>`

-----

### 7\. Line Break (`<br>`)

The `<br>` tag adds a single line break.

  * `This is line one.<br>This is line two.`

-----

### 8\. Image Tag (`<img>`)

The `<img>` tag embeds an image into the HTML document.

  * **Basic Usage:**
      * `<img src="./notebook.jpeg" alt="A notebook on a desk">` (Local image)
      * `<img src="https://www.worldone.in/cdn/shops/products/Mix_1024x1024.jpg?v=16788758" alt="Assorted notebooks">` (External image)
  * The `alt` attribute provides **alternative text** for the image, displayed if the image cannot be loaded or for screen readers.
  * **Controlling Dimensions:**
      * You can set `height` and `width` attributes, but generally, it's recommended to control image sizing using **CSS** to maintain aspect ratio and better responsiveness.
      * **Caution:** Do not set both `height` and `width` attributes directly on the `<img>` tag without careful consideration, as this can distort the image's aspect ratio.
      * Example with only height (letting browser calculate width to maintain aspect ratio): `<img src="./notebook.jpeg" alt="notebook" height="200">`

-----

### 9\. Text Formatting (Bold, Italic, Underline)

These tags apply basic text styling.

  * **Bold:** `<B>This text is bold</B>`
  * **Italic:** `<I>This text is italic</I>`
  * **Underline:** `<U>This text is underlined</U>`

-----

### 10\. Text Size (Big/Small)

These tags provide relative sizing for text.

  * **Big:** `<big>This is a big text</big>`
  * **Small:** `<small>This is a small text</small>`

-----

### 11\. Horizontal Rule (`<hr>`)

The `<hr>` tag creates a horizontal line, often used to separate content sections.

  * `<hr>`

-----

### 12\. Subscript (`<sub>`)

The `<sub>` tag renders text as a subscript.

  * **Example:** `H<sub>2</sub>O` (for chemical formulas like Water)

-----

### 13\. Superscript (`<sup>`)

The `<sup>` tag renders text as a superscript.

  * **Example:** `2<sup>2</sup>` (for mathematical exponents like 2 squared)

-----