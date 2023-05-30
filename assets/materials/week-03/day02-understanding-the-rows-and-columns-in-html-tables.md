# Understanding the Rows and Columns in HTML Tables

Welcome back to Character-driven Code Organization, where programming meets storytelling. In this section, we will dive deeper into the structure of HTML tables and explore how rows and columns play a crucial role in organizing and presenting data.

## Rows: Dividing and Structuring Data

In HTML tables, rows are used to organize data into horizontal segments. Just like the acts of a play, rows divide different sets of information, creating a clear and organized structure.

To create rows, we use the `<tr>` element. The `<tr>` element stands for "table row" and acts as a container for cells within a table.

Here's an example of a table with two rows:

```html
<table>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
</table>
```

This will create a table with two rows, each containing two cells. The content inside each cell represents the data you want to display.

## Columns: Organizing Data Vertically

Columns in HTML tables are responsible for organizing data vertically, aligning related information across multiple rows. Columns bring a sense of structure and make it easier for readers to interpret and compare data points.

In HTML, we don't have a specific element to represent columns. Instead, we achieve column organization by placing cells within the same index across different rows.

Here's an example of a table with three columns:

```html
<table>
  <tr>
    <td>Row 1, Column 1</td>
    <td>Row 1, Column 2</td>
    <td>Row 1, Column 3</td>
  </tr>
  <tr>
    <td>Row 2, Column 1</td>
    <td>Row 2, Column 2</td>
    <td>Row 2, Column 3</td>
  </tr>
</table>
```

This table has two rows and three columns. Each cell with the same index represents the corresponding column across the rows.

## Combining Rows and Columns

The true power of HTML tables lies in their ability to combine rows and columns to create complex structures. By strategically organizing cells, you can present intricate data sets, timelines, or any other form of tabular information.

Here's an example of a table combining rows and columns:

```html
<table>
  <tr>
    <td>Product</td>
    <td>Price</td>
  </tr>
  <tr>
    <td>Shirt</td>
    <td>$25</td>
  </tr>
  <tr>
    <td>Pants</td>
    <td>$40</td>
  </tr>
</table>
```

In this example, we have a simple product list with two columns: "Product" and "Price." Each row represents a different product and its corresponding price.

Experiment with different combinations of rows and columns to organize and present your data in a way that aligns with your storytelling goals.

Remember, tables serve as a powerful tool for structuring and visualizing data. Use them wisely to craft compelling narratives and convey information effectively.

In the next section, we will explore advanced table features and techniques like [merging cells in a table](day03-merging-cells-in-a-table.md) to further enhance your storytelling abilities.