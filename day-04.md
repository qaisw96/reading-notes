# Grid Layout
a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

![](https://www.w3schools.com/css/grid_columns.png)

![](https://www.w3schools.com/css/grid_rows.png)

```
display
Defines the element as a grid container and establishes a new grid formatting context for its contents.

Values:

grid – generates a block-level grid
inline-grid – generates an inline-level grid
.container {
  display: grid | inline-grid;
}

```
```
grid-template-columns
grid-template-rows
Defines the columns and rows of the grid with a space-separated list of values. The values represent the track size, and the space between them represents the grid line.

Values:

<track-size> – can be a length, a percentage, or a fraction of the free space in the grid (using the fr unit)
<line-name> – an arbitrary name of your choosing
.container {
  grid-template-columns:  ... |   ...;
  grid-template-rows:  ... |   ...;
}
```
