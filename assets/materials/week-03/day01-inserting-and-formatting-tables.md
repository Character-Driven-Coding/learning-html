# Crafting Structured Narratives: Inserting and Formatting Tables

Welcome back to Character-driven Code Organization, where storytelling meets programming. In this section, we will explore the art of creating tables in HTML. Tables serve as a powerful tool to organize and present data in a structured format, akin to the organized lines of a script or the neatly arranged props on a theater stage.

## Unveiling the Power of Tables

Tables provide a visually appealing way to display tabular data, creating a sense of structure and clarity. In HTML, tables are constructed using a combination of elements: `<table>`, `<tr>`, and `<td>`. Let's dive into each of these elements and their role in crafting a compelling narrative through tables.

### The `<table>` Element: Setting the Stage

The `<table>` element is used as the container for the entire table structure. It serves as the stage upon which your tabular data will be presented. Think of it as the framework that holds everything together.

To create a table, follow these steps:

1. Start with the `<table>` opening tag.
2. Within the `<table>` element, define the rows and cells of your table using the `<tr>` and `<td>` elements, respectively.
3. End with the `</table>` closing tag.

Here's an example of a basic table structure:

```html
<table>
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
  <tr>
    <td>Cell 3</td>
    <td>Cell 4</td>
  </tr>
</table>
```

This will create a 2x2 table with four cells:

| Cell 1 | Cell 2 |
|--------|--------|
| Cell 3 | Cell 4 |

### The `<tr>` Element: Defining Rows

The `<tr>` element represents a row in the table. It acts as a divider between different sets of data. Just as a scene break separates different acts in a play, the `<tr>` element separates rows in a table.

To create a row, place the `<tr>` opening and closing tags within the `<table>` element. Inside the `<tr>` element, define the cells using the `<td>` elements.

Here's an example of a table with two rows:

```html
<table>
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
  <tr>
    <td>Cell 3</td>
    <td>Cell 4</td>
  </tr>
</table>
```

### The `<td>` Element: Populating Cells

The `<td>` element represents a cell within a table. It holds the actual data or content that you want to display. Just as an actor breathes life into a character, the `<td>` element brings substance to your table.

To create a cell, place the `<td>` opening and closing tags within the `<tr>` element. Inside the `<td>` element, add your desired content.

Here's an example of a table with cells containing text:

```html
<table>
  <tr>
    <td>First Name</td>
    <td>Last Name</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
</table>
```

This will create a table with two columns and two rows, displaying names in the cells.

| First Name | Last Name |
|------------|-----------|
| John       | Doe       |

## Formatting Tables: Bringing Characters to Life

While HTML provides a basic structure for tables, you can enhance

 the visual appeal and storytelling impact by utilizing CSS. With CSS, you can style your tables, change colors, add borders, and make them visually engaging.

In the future section, we will explore how CSS can transform your tables into captivating visual elements that align with your narrative vision. Stay tuned!

Now, it's time for you to experiment with creating tables in HTML. Embrace the power of structured data presentation and bring your characters to life on the stage of a table and in the next section we will learn how to [Understanding the rows and columns in HTML tables](day02-understanding-the-rows-and-columns-in-html-tables.md).