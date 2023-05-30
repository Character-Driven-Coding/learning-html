# Introduction to HTML and its Structure

HTML (Hypertext Markup Language) is the standard markup language used for creating web pages. It provides a structured way to define the content and layout of a webpage. In this beginner material, we will cover the basics of HTML and understand its structure.

## HTML Document Structure

An HTML document consists of several elements that define the structure and content of a webpage. Here is a basic HTML document structure:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>Heading 1</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

Let's break down the different parts of this structure:

- `<!DOCTYPE html>`: This declaration is placed at the beginning of the document to indicate that it is an HTML5 document.
- `<html>`: This is the root element of an HTML document. All other elements are contained within this element.
- `<head>`: This element contains meta-information about the document, such as the title of the page and links to external stylesheets.
- `<title>`: This element specifies the title of the webpage, which is displayed in the browser's title bar or tab.
- `<body>`: This element contains the visible content of the webpage, such as headings, paragraphs, images, and other elements.

## HTML Elements

HTML elements are used to define different parts of a webpage and provide structure to its content. Elements are represented by tags, which are enclosed in angle brackets. Here are some commonly used HTML elements:

- `<h1>`, `<h2>`, `<h3>`, ... `<h6>`: These elements represent headings of different levels, with `<h1>` being the highest level and `<h6>` the lowest.
- `<p>`: This element represents a paragraph of text.
- `<img>`: This element is used to insert an image into the webpage.
- `<a>`: This element creates a hyperlink to another webpage or a specific location within the same webpage.

## Tags and Attributes

HTML tags define the purpose and structure of an element. They are placed around the content they affect. Some tags, such as `<img>` and `<br>`, are self-closing and don't have a closing tag. Tags can also have attributes that provide additional information or settings for the element. Attributes are specified within the opening tag of an element.

For example, the `<img>` element can have attributes like `src` to specify the image source and `alt` to provide alternative text for screen readers:

```html
<img src="image.jpg" alt="Description of the image">
```

## Summary

HTML is the foundation of web development, allowing you to structure and define the content of a webpage. Understanding the basic structure of an HTML document and the purpose of different HTML elements is essential to creating well-formed web pages.

In the next sections, we will learn about [Creating a Basic HTML Document](day02-creating-a-basic-html-document.md).
