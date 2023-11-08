# prework-study-guide
study guide for learning

## Mussaddiq Mahmood
Hello, this is Mussaddiq Mahmood. I can help you write HTML notes in markdown format. Markdown is a simple way to format text using plain text syntax. You can use markdown to create headings, lists, tables, links, images, code blocks, and more. Here is an example of how you can write HTML notes in markdown format:

# HTML Notes

## Introduction

HTML stands for **HyperText Markup Language**. It is the standard language for creating web pages and web applications. HTML describes the structure and content of a web page using tags and attributes.

## Basic Syntax

An HTML document consists of two parts: a **head** and a **body**. The head contains information about the document, such as the title, meta data, and links to external resources. The body contains the actual content of the document, such as text, images, and links.

An HTML document starts with a **doctype declaration** that tells the browser what version of HTML the document is using. The doctype declaration for HTML5 is:

```html
<!DOCTYPE html>

After the doctype declaration, the HTML document has a root element called <html> that contains the head and body elements. The root element also has a lang attribute that specifies the language of the document. For example:

<html lang="en">
<head>
  <!-- head content goes here -->
</head>
<body>
  <!-- body content goes here -->
</body>
</html>

HTML elements are defined by tags that have a name and optionally some attributes. Tags are enclosed in angle brackets (< and >). Most HTML elements have a start tag and an end tag, with the content in between. For example:

<p>This is a paragraph.</p>

Some HTML elements are self-closing, which means they do not have an end tag. They are usually used for elements that do not have any content, such as images, line breaks, and input fields. For example:

<img src="logo.png" alt="Logo">
<br>
<input type="text" name="username">

HTML attributes provide additional information about an element, such as its id, class, style, or behavior. Attributes are specified in the start tag of an element, after the element name. Attributes have a name and a value, separated by an equal sign (=). The value is usually enclosed in double quotes ("). For example:

<a href="https://www.google.com" target="_blank">Visit google</a>

In this example, the <a> element has two attributes: href and target. The href attribute specifies the URL of the link, and the target attribute specifies how the link should be opened. The value _blank means the link should be opened in a new tab or window.
Common ElementsHere are some of the most common HTML elements and their uses:
- <h1> to <h6>: These elements are used to create headings of different levels. The <h1> element is the most important heading, and the <h6> element is the least important. For example:

<h1>HTML Notes</h1>
<h2>Introduction</h2>
<h3>Basic Syntax</h3>

- <p>: This element is used to create paragraphs of text. For example:

<p>HTML stands for HyperText Markup Language. It is the standard language for creating web pages and web applications.</p>

- <ul> and <ol>: These elements are used to create unordered and ordered lists, respectively. Each list item is enclosed in a <li> element. For example:

<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>

<ol>
  <li>First</li>
  <li>Second</li>
  <li>Third</li>
</ol>

- <table>: This element is used to create tables of data. A table consists of rows (<tr> elements) and columns (<td> elements). Optionally, a table can have a header (<th> elements) and a caption (<caption> element). For example:

<table>
  <caption>Student Grades</caption>
  <tr>
    <th>Name</th>
    <th>Math</th>
    <th>English</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>90</td>
    <td>85</td>
  </tr>
  <tr>
    <td>Bob</td>
    <td>80</td>
    <td>75</td>
  </tr>
</table>

- <div> and <span>: These elements are used to create generic containers for other elements. The <div> element is a block-level element, which means it occupies the entire width of its parent element and creates a new line before and after itself. The <span> element is an inline element, which means it occupies only the space needed for its content and does not create a new line. For example:

<div>
  <p>This is a paragraph inside a div.</p>
</div>
<span>This is a span inside a paragraph.</span>

- <img>: This element is used to insert images into a web page. The src attribute specifies the URL of the image, and the alt attribute specifies the alternative text for the image in case it cannot be displayed. For example:

<img src="logo.png" alt="Logo">

- <a>: This element is used to create hyperlinks to other web pages or resources. The href attribute specifies the URL of the link, and the target attribute specifies how the link should be opened. For example:

<a href="https://www.google.com" target="_blank">Visit google</a>

- <form>: This element is used to create forms for user input. A form consists of various input elements, such as text fields, checkboxes, radio buttons, and buttons. The action attribute specifies the URL where the form data should be sent, and the method attribute specifies the HTTP method to use (GET or POST). For example:

<form action="https://example.com/login" method="POST">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">
  <label for="password">Password:</label>
  <input type="password" id="password" name="password">
  <button type="submit">Login</button>
</form>

- <script>: This element is used to embed JavaScript code into a web page. The src attribute can be used to specify the URL of an external JavaScript file, or the code can be written directly between the <script> and </script> tags. For example:

<script src="script.js"></script>
<script>
  alert("Hello, world!");
</script>

- <style>: This element is used to embed CSS code into a web page. The type attribute specifies the MIME type of the style sheet, which is usually text/css. The CSS code can be written directly between the <style> and </style> tags. For example:

<style type="text/css">
  h1 {
    color: blue;
  }
  p {
    font-size: 16px;
  }
</style>

ConclusionThis is a brief overview of HTML and its basic syntax. To learn more about HTML, you can visit the following resources:
- HTML Tutorial: A comprehensive tutorial on HTML from W3Schools.
- HTML Reference: A complete reference of HTML elements and attributes from MDN Web Docs.
- HTML Validator: A tool to check the validity and quality of your HTML code.


I hope this helps you. If you have any questions or feedback, please let me know. 😊

