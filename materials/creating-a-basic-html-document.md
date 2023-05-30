# Creating a Basic HTML Document

In this section, we will learn how to create a basic HTML document from scratch. We will cover the essential elements and tags required to structure and define the content of a webpage.

## HTML Document Structure

An HTML document consists of the following structure:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

Let's break down the different parts of this structure:

- `<!DOCTYPE html>`: This declaration is placed at the beginning of the document to indicate that it is an HTML5 document.
- `<html>`: This is the root element of an HTML document. All other elements are contained within this element.
- `<head>`: This element contains meta-information about the document, such as the title of the page and links to external stylesheets.
- `<title>`: This element specifies the title of the webpage, which is displayed in the browser's title bar or tab.
- `<body>`: This element contains the visible content of the webpage.

## Adding Headings

Headings are used to structure the content of a webpage. HTML provides six levels of headings, ranging from `<h1>` to `<h6>`. The `<h1>` heading represents the main heading of the page, while `<h2>` to `<h6>` are used for subheadings.

```html
<body>
    <h1>Main Heading</h1>
    <h2>Subheading</h2>
</body>
```

## Adding Paragraphs

Paragraphs are used to group and present blocks of text. To create a paragraph, use the `<p>` element.

```html
<body>
    <p>This is a paragraph.</p>
</body>
```

## Adding Line Breaks

To insert a line break within a paragraph or other inline elements, use the `<br>` element. It doesn't require a closing tag.

```html
<body>
    <p>This is the first line.<br>
    This is the second line.</p>
</body>
```

## Formatting Text

HTML provides tags for formatting text, such as emphasis and strong emphasis. The `<em>` tag is used to emphasize text, while the `<strong>` tag is used to indicate strong emphasis.

```html
<body>
    <p>This is <em>emphasized</em> text.</p>
    <p>This is <strong>strongly emphasized</strong> text.</p>
</body>
```

## Adding Images

To insert an image into a webpage, use the `<img>` element. The `src` attribute specifies the image source (URL or file path), while the `alt` attribute provides alternative text for screen readers or when the image cannot be displayed.

```html
<body>
    <img src="image.jpg" alt="Description of the image">
</body>
```

## Summary

In this section, we have learned how to create a basic HTML document and use essential elements and tags to structure and define the content of a webpage. We covered headings, paragraphs, line breaks, text formatting, and image insertion. By understanding these fundamental concepts, you can start building simple web pages using HTML.

In the next sections, we will [Understanding tags and elements](materials/understanding-tags-and-elements.md).
