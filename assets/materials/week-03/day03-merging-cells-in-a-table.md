# Merging Cells in HTML Tables

Welcome back to Character-driven Code Organization! In this section, we will learn how to merge cells in HTML tables. Merging cells allows you to combine multiple cells into a single cell, spanning across rows and columns. This feature is particularly useful when you need to create header cells or cells that contain more significant content.

To merge cells, we use the `colspan` and `rowspan` attributes on the `<td>` or `<th>` elements. The `colspan` attribute defines the number of columns a cell should span, while the `rowspan` attribute specifies the number of rows it should span.

Let's explore some examples to better understand how to merge cells in HTML tables:

## Merging Cells Horizontally

To merge cells horizontally, we use the `colspan` attribute. Here's an example:

```html
<table>
  <tr>
    <th colspan="2">Character</th>
    <th>Action</th>
  </tr>
  <tr>
    <td rowspan="2">Protagonist</td>
    <td>John</td>
    <td>Save the day</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Uncover the truth</td>
  </tr>
</table>
```

In this example, the first row contains a header cell that spans across two columns. The second row has a cell that spans two rows using the `rowspan` attribute. This creates a merged cell for the "Protagonist" label, allowing us to display the characters' names in separate cells.

## Merging Cells Vertically

To merge cells vertically, we use the `rowspan` attribute. Let's see an example:

```html
<table>
  <tr>
    <th>Character</th>
    <td rowspan="2">John</td>
    <td>Save the day</td>
  </tr>
  <tr>
    <th>Action</th>
    <td>Uncover the truth</td>
  </tr>
</table>
```

In this case, the first column in the first row spans two rows, thanks to the `rowspan` attribute. This creates a merged cell for the "Character" label, allowing us to display the character's name in a single cell across multiple rows.

## Combining Horizontal and Vertical Cell Merging

You can also combine both horizontal and vertical cell merging to create more complex table structures:

```html
<table>
  <tr>
    <th rowspan="2">Character</th>
    <th colspan="2">Actions</th>
  </tr>
  <tr>
    <td>Fight</td>
    <td>Save the day</td>
  </tr>
  <tr>
    <td>John</td>
    <td rowspan="2">Defeat the villain</td>
    <td>Rescue the princess</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Uncover the truth</td>
  </tr>
</table>
```

In this example, the first column is merged vertically using the `rowspan` attribute, while the second column is merged horizontally using the `colspan` attribute. This creates a complex table structure with merged cells that align with our character-driven storytelling.

Remember, merging cells in HTML tables allows you to create visually appealing and informative table layouts. Experiment with different combinations of `colspan` and `rowspan` attributes to achieve the desired structure for your storytelling needs.

In the next section, we will explore how to [create forms with input fields](day04-create-forms-with-input-fields.md), enabling user interaction and data collection.